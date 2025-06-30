# 🚀 Day 44 – Sorted List to BST & Max Vowels in Substring 🌳🔠📊

## 📚 What I Solved Today

Practiced recursive tree construction from linked lists and used the sliding window technique to optimize vowel counting in substrings.

---

### 🧠 Problem 1: Convert Sorted List to Binary Search Tree
- **Task:** Convert a **sorted singly linked list** into a **height-balanced BST**.
- **Approach:**  
  - Used **slow and fast pointer technique** to find the middle of the list (root node).  
  - Recursively applied the same logic to left and right halves of the list to build subtrees.  
  - Ensured balance by always picking the middle node as root.
- **Complexity:** O(n log n) time, O(log n) space (due to recursion)

---

### 🧠 Problem 2: Maximum Number of Vowels in a Substring of Given Length
- **Task:** Return the maximum number of vowels found in any substring of length `k`.
- **Approach:**  
  - Implemented a **sliding window** of size `k`.  
  - Kept a count of vowels within the current window.  
  - Moved the window forward by updating the count efficiently.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- Using **slow/fast pointers** allows efficient middle detection in linked lists for recursive tree construction.  
- **Sliding window** techniques offer linear-time solutions to many substring-related problems.

---
![Screenshot 2025-06-30 175221](https://github.com/user-attachments/assets/4f88367a-5dc0-4bb9-8478-28b30ce9c3ec)

---
![Screenshot 2025-06-30 175930](https://github.com/user-attachments/assets/aecc337b-8afb-440a-b45b-5a6eb61de5bd)

