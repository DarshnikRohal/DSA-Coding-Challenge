# 🚀 Day 38 – Palindrome Validation & BST Search 🔡🌳

## 📚 What I Solved Today

Focused on sanitizing input for palindrome checking and leveraged binary search tree properties for efficient lookup.

---

### 🧠 Problem 1: Valid Palindrome
- **Task:** Determine if a given string is a valid palindrome, considering only alphanumeric characters and ignoring case.
- **Approach:**  
  - Used **two-pointer technique**: one from the start, one from the end.  
  - Skipped non-alphanumeric characters using `isalnum()`.  
  - Converted characters to lowercase for case-insensitive comparison.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Search in a Binary Search Tree
- **Task:** Given the root of a BST and a value, return the subtree rooted at the node with that value (or `nullptr` if not found).
- **Approach:**  
  - Used **recursion** to compare value at current node with the target:  
    - If equal, return node.  
    - If less, search left subtree.  
    - If greater, search right subtree.
- **Complexity:** O(h) time, where h = height of tree

---

## 🧠 Key Takeaways

- Always sanitize and preprocess input when validating strings.  
- Binary Search Tree (BST) logic helps in **logarithmic time lookups**, improving performance over linear search.

---
![Screenshot 2025-06-15 133618](https://github.com/user-attachments/assets/fbf86b25-333e-4ece-ad1b-e89c64a79d97)

---
![Screenshot 2025-06-15 133211](https://github.com/user-attachments/assets/c51f5091-4040-4c31-8eb0-375faecb5920)
