
### `Definition`

Queues are **linear data structures** that follow the **First-In, First-Out (FIFO)** principle, where elements are added at one end (**rear**) and removed from the other (**front**). They model ordered processing where items are handled in the order they arrive.

---
### `Key Ideas`

- Two distinct ends: **enqueue** at the rear, **dequeue** from the front.
    
- Preserves arrival order of elements.
    
- No direct access to arbitrary elements.
    
- Can be implemented using arrays, circular buffers, or linked lists.
    
- Common in scheduling, buffering, and task coordination.

---
### `Big-O Performance`

|Operation|Time Complexity|Notes|
|---|---|---|
|**Enqueue**|**O(1)**|Add element to the rear|
|**Dequeue**|**O(1)**|Remove element from the front|
|**Peek / Front**|**O(1)**|Read front element without removing|
|**Search**|**O(n)**|Must traverse elements|
|**Access (by index)**|**O(n)**|No random access|
|**Space Complexity**|**O(n)**|Stores n elements|

---
### `Connected Notes`

- [[Data Structures]]