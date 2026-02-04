## Implement Queue Using Stack (C++)

### Problem Description

This program implements a **Queue data structure using two Stacks**. The objective is to demonstrate how queue operations can be simulated using stack operations.

---

### Approach

* Two stacks are used to maintain queue behavior.
* Enqueue operation inserts elements into the first stack.
* Dequeue operation transfers elements to the second stack when required to maintain FIFO order.

---

### Operations

* Enqueue
* Dequeue
* Display Front Element

---

### Complexity Analysis

* **Time Complexity**:

  * Enqueue: O(1)
  * Dequeue: O(n) (only during transfer)
* **Space Complexity**: O(n)

---

### Language

* C++ (STL Stack)

---

### Conclusion

This program provides a clear understanding of implementing one data structure using another and reinforces fundamental concepts of stacks and queues.

---

If you want it **even shorter** (for lab files or internal submission), tell me and I’ll condense it further.
