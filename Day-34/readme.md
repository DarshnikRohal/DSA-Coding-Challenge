# 🚀 Day 34 – Flattening Trees & Word Length Logic 🌲✂️📝

## 📚 What I Solved Today

Worked on transforming a binary tree into a linked list structure and handled string parsing edge cases.

---

### 🧠 Problem 1: Flatten Binary Tree to Linked List
- **Task:** Flatten a binary tree into a right-skewed linked list **in-place**.
- **Approach:**  
  - Used **reverse post-order traversal** (right → left → root).  
  - Maintained a `prev` pointer to rewire nodes during backtracking.  
  - Set `node->right = prev`, `node->left = NULL`, then `prev = node`.
- **Complexity:** O(n) time, O(h) space (due to recursion stack)

---

### 🧠 Problem 2: Length of Last Word
- **Task:** Find the length of the last word in a given string.
- **Approach:**  
  - Started traversal from the end.  
  - Skipped trailing spaces, then counted characters until a space.  
  - Handled edge cases like strings with trailing spaces.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- **Flattening trees** in-place requires understanding traversal order and pointer rewiring.  
- Even simple string problems demand **edge case awareness** and clean logic.

---
![Screenshot 2025-06-10 114242](https://github.com/user-attachments/assets/9265451d-5a5e-44a2-9db4-49417e60a0cf)

---
![Screenshot 2025-06-10 113316](https://github.com/user-attachments/assets/9e1d11a3-f229-479e-9158-efd8bb98e77e)

