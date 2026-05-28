
AWS Lambda is a **serverless compute service** provided by Amazon Web Services that allows developers to run **event-driven code without provisioning or managing servers**.

It implements the **Function as a Service (FaaS)** model, automatically executing functions in response to events from AWS services or HTTP requests while scaling automatically and charging only for the compute time used.

---
### `Key Capabilities`

- Event-driven function execution
- Automatic scaling based on incoming events
- Fully managed infrastructure
- Support for multiple runtimes (Node.js, Python, Java, Go, .NET, Ruby, custom runtimes)
- Deep integration with AWS ecosystem services
- Stateless execution model
- Pay-per-execution pricing model
- Can be triggered by many AWS services (S3, API Gateway, DynamoDB, SNS, SQS, etc.)

---
### `Usage Basics`

Typical workflow:

1. Write a function that handles an **event**
	
2. Deploy the function to AWS Lambda
	
3. Configure an **event source or trigger**
	
4. Lambda automatically runs the function when the event occurs

**Example Lambda function (Node.js):**

```javascript
exports.handler = async (event) => {  
  return {  
    statusCode: 200,  
    body: JSON.stringify("Hello from AWS Lambda!")  
  };  
};
```

**Deployment example using AWS CLI:**

```bash
aws lambda create-function \  
  --function-name my-function \  
  --runtime nodejs20.x \  
  --handler index.handler \  
  --zip-file fileb://function.zip \  
  --role arn:aws:iam::123456789012:role/lambda-role
```

---
### `Challenges`

- Cold start latency for infrequently used functions
- Execution time limits for functions
- Stateless execution requires external services for persistence
- Complex event pipelines can be difficult to debug
- Vendor lock-in when tightly integrated with AWS services
- Cost can increase with high invocation frequency

---
### `Connected Notes`

- [[Function-as-a-Service (FaaS)]]