
### `Definition`

**Big-O notation** is a mathematical notation used to **describe how an algorithm’s resource usage grows** as the size of its input increases. It focuses on **growth trends**, not exact execution time.

---
### `Key Ideas`

- **Measures Scalability, Not Speed**  
    Big-O describes how performance changes with input size, not how fast code runs on a specific machine.
    
- **Time and Space Complexity**  
    Most commonly used to describe:
    
    - **Time complexity** → how runtime grows
    - **Space complexity** → how memory usage grows
    
- **Worst-Case Focus**  
    By convention, Big-O usually represents the **upper bound** (worst case) of growth.
    
- **Ignores Constants and Lower Terms**  
    Implementation details and constant factors are abstracted away to focus on dominant growth.
    
- **Common Complexity Classes**
    
    - **O(1)** — constant
        
    - **O(log n)** — logarithmic
        
    - **O(n)** — linear
        
    - **O(n log n)** — linearithmic
        
    - **O(n²)** — quadratic
        
    - **O(2ⁿ)** — exponential
    
- **Comparison Tool**  
    Allows algorithms to be compared independent of language or hardware.

---
### `Connected Notes`

- [[Algorithms]]
- [[Time Complexity]]
- [[Space Complexity]]