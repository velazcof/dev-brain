
Azure Functions is a **serverless compute service** provided by Microsoft Azure that allows developers to run **event-driven code without managing infrastructure**.

It implements the **Function as a Service (FaaS)** model, automatically scaling functions in response to events such as HTTP requests, timers, or service triggers while charging based on execution and resource usage.

---
### `Key Capabilities`

- Event-driven execution model
- Automatic scaling based on demand
- Fully managed serverless infrastructure
- Multiple language runtimes (C#, JavaScript, Python, Java, PowerShell, TypeScript)
- Deep integration with Azure ecosystem services
- Stateless function execution model
- Multiple hosting plans (Consumption, Premium, Dedicated)
- Built-in triggers and bindings for cloud services

---
### `Usage Basics`

Typical workflow:

1. Create a function project using the Azure Functions runtime
    
2. Define a function with a **trigger** (HTTP, timer, queue, etc.)
    
3. Deploy the function to Azure
    
4. Azure automatically executes the function when the trigger fires

**Example HTTP-triggered function (JavaScript):**

```javascript
module.exports = async function (context, req) {  
  const name = req.query.name || "world";  
  context.res = {  
    body: `Hello ${name}`  
  };  
};
```

**Deployment example using Azure CLI:**

```bash
az functionapp create \  
  --resource-group myResourceGroup \  
  --consumption-plan-location eastus \  
  --runtime node \  
  --functions-version 4 \  
  --name my-function-app \  
  --storage-account mystorageaccount
```

---
### `Challenges`

- Cold start latency in the Consumption plan
- Execution time limits depending on hosting plan
- Debugging distributed serverless workflows can be difficult
- Stateful workflows require additional services
- Azure ecosystem complexity can increase configuration overhead
- Vendor lock-in when tightly integrated with Azure services

---
### `Connected Notes`

- [[Function-as-a-Service (FaaS)]]