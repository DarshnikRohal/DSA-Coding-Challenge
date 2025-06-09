# 🚀 Day 33 – Right View of Tree & Palindrome Tweak 🌳🔤

## 📚 What I Solved Today

Worked on tree visibility logic and lexicographic string transformation with minimal changes.

---

### 🧠 Problem 1: Binary Tree Right Side View
- **Task:** Return the values of the nodes you can see from the right side of the binary tree.
- **Approach:**  
  - Used **BFS (level order traversal)**.  
  - At each level, captured the **last node’s value**.  
- **Complexity:** O(n) time, O(n) space

---

### 🧠 Problem 2: Lexicographically Smallest Palindrome
- **Task:** Convert a given string to the lexicographically smallest palindrome by changing **at most one character**.
- **Approach:**  
  - Used **two pointers** to compare characters from both ends.  
  - On mismatch, changed the **larger character** to match the smaller one.  
  - Ensured palindrome condition and minimal lexicographic order.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- **Right side view** problems rely on modified BFS logic.  
- Minimal-change string problems often require **greedy + two-pointer** techniques.

---
![Screenshot 2025-06-09 095555](https://github.com/user-attachments/assets/db324942-dc90-4846-830d-7ce5b7f9a377)

---
![Screenshot 2025-06-09 094954](https://github.com/user-attachments/assets/58f2baf4-711c-4664-85dc-b2bf05d90b3e)

