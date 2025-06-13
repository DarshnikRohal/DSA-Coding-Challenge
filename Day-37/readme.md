# 🚀 Day 37 – Zigzag Tree Traversal & Palindrome Search 🌲🔄🔍

## 📚 What I Solved Today

Explored a twist on binary tree traversal and a straightforward search for palindromes in strings.

---

### 🧠 Problem 1: Binary Tree Zigzag Level Order Traversal
- **Task:** Traverse a binary tree in a zigzag (alternating left-right) level order pattern.
- **Approach:**  
  - Used a **queue for BFS** and a boolean flag `leftToRight` to control insertion order.  
  - At each level, collected node values in a temporary array.  
  - Reversed the array if the direction was right-to-left.
- **Complexity:** O(n) time, O(n) space

---

### 🧠 Problem 2: Find First Palindromic String in the Array
- **Task:** From a list of strings, return the first one that is a palindrome.
- **Approach:**  
  - Iterated through the array.  
  - Compared each string to its reverse (`s == reverse(s)`).  
  - Returned the first match immediately.
- **Complexity:** O(n * m) time, where m is average word length

---

## 🧠 Key Takeaways

- Zigzag traversal can be easily implemented with **BFS + order control logic**.  
- Palindrome detection is simple yet useful for filtering or early exits in string processing.

---
![Screenshot 2025-06-13 184026](https://github.com/user-attachments/assets/fd837ee3-870f-4c12-b06c-09fc7b33a8f5)
![Screenshot 2025-06-13 183900](https://github.com/user-attachments/assets/143c4927-60b1-497c-99d0-a16c9b4155cd)
