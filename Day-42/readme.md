# 🚀 Day 42 – Validating BSTs & Reversing Words 🌳✅📝

## 📚 What I Solved Today

Validated the integrity of a Binary Search Tree using recursion and performed space-aware string reversal.

---

### 🧠 Problem 1: Validate Binary Search Tree
- **Task:** Determine if a binary tree is a valid BST.
- **Approach:**  
  - Used **recursive bounds checking**:  
    - Passed down valid `min` and `max` range for each node.  
    - Ensured `node->val` was within bounds.  
  - Recurred for left and right subtrees with updated ranges.
- **Complexity:** O(n) time, O(h) space (due to recursion)

---

### 🧠 Problem 2: Reverse Words in a String
- **Task:** Reverse the order of words in a string while removing extra spaces.
- **Approach:**  
  - Trimmed leading/trailing/multiple spaces.  
  - Split the string into words.  
  - Reversed the list of words.  
  - Joined them back with a single space.
- **Complexity:** O(n) time, O(n) space

---

## 🧠 Key Takeaways

- Validating BSTs is best done with **min/max constraints**, not just in-order traversal.  
- Careful string manipulation involves both **structure cleanup** and **order reversal**.

---
![Screenshot 2025-06-23 181618](https://github.com/user-attachments/assets/36d79858-3f24-432e-9f97-5c3558b38cfb)

---
![Screenshot 2025-06-23 145446](https://github.com/user-attachments/assets/961e7ab9-fd16-4a3e-beaf-b6e9efc2a8ec)

