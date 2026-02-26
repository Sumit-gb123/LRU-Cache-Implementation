# LRU-Cache-Implementation
# LRU Cache Implementation in C++

## 📌 Overview
This project implements a **high-performance LRU (Least Recently Used) Cache** in C++ using a combination of **HashMap (unordered_map)** and a **Doubly Linked List** to achieve **O(1)** time complexity for both `get` and `put` operations.

The implementation focuses on **memory-efficient data structures**, **pointer-based design**, and concepts relevant to **system-level and platform software development**.

---

## ⚙️ Key Features
- O(1) time complexity for cache access and updates
- Efficient memory management using pointers
- STL-based implementation (`unordered_map`)
- Designed with scalability and performance in mind

---

## 🛠️ Technologies Used
- Language: **C++**
- Concepts:  
  - HashMap  
  - Doubly Linked List  
  - Pointers & Memory Management  
  - Cache Eviction Policies  
  - Time–Space Optimization  

---

## 🚀 Use Cases
- Operating Systems (Page Replacement Algorithms)
- Database Caching
- System & Platform Software
- Low-level Performance-Critical Applications

---

## 📄 Example
```cpp
LRUCache cache(2);
cache.put(1, 10);
cache.put(2, 20);
cache.get(1); // returns 10
cache.put(3, 30); // evicts key 2
