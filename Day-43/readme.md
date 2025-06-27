# 🚀 Day 43 – Kth Smallest in BST & Zigzag Conversion 🌳↕️✍️

## 📚 What I Solved Today

Practiced an in-order traversal selection problem on BSTs and implemented a pattern-based transformation on strings.

---

### 🧠 Problem 1: Kth Smallest Element in a BST
- **Task:** Return the k-th smallest element in a Binary Search Tree.
- **Approach:**  
  - Used **in-order traversal** to get nodes in sorted order.  
  - Maintained a `count` to track how many nodes have been visited.  
  - When `count == k`, stored the current node’s value.
- **Complexity:** O(h + k) time, O(h) space (h = tree height)

---

### 🧠 Problem 2: Zigzag Conversion
- **Task:** Convert a given string into a zigzag pattern on a given number of rows and read it line by line.
- **Approach:**  
  - Created a list of strings for each row.  
  - Used a **`currentRow` pointer** and a **direction flag** to simulate writing characters row by row.  
  - Concatenated all rows at the end.
- **Complexity:** O(n) time, O(n) space

---

## 🧠 Key Takeaways

- BST + in-order traversal makes for efficient and clean rank-based queries.  
- Simulation-based approaches are often ideal for **pattern-structured string problems**.

---
![Screenshot 2025-06-27 233251](https://github.com/user-attachments/assets/7d1acf3a-c9c4-466c-98ca-3d4db066061a)

---

![Screenshot 2025-06-27 191958](https://github.com/user-attachments/assets/9f3926ca-9d39-46e5-b8e1-62ee3bc4f64f)
