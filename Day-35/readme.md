# 🚀 Day 35 – Binary Tree Ancestors & String Segments 🌳🧵

## 📚 What I Solved Today

Solved a fundamental recursive tree problem and a string parsing task focused on whitespace handling.

---

### 🧠 Problem 1: Lowest Common Ancestor of a Binary Tree
- **Task:** Find the lowest common ancestor (LCA) of two given nodes in a binary tree.
- **Approach:**  
  - Applied **recursive DFS traversal**.  
  - If both left and right subtrees return non-null, current node is LCA.  
  - If only one side is non-null, return that up the recursive chain.
- **Complexity:** O(n) time, O(h) space (recursion stack)

---

### 🧠 Problem 2: Number of Segments in a String
- **Task:** Count the number of non-empty words in a string separated by spaces.
- **Approach:**  
  - Iterated through the string.  
  - Counted a new segment when a **non-space character** follows a space or string start.  
  - Ignored multiple consecutive spaces.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- The LCA problem is a foundational example of **recursive tree analysis**.  
- String segmentation problems are easy to miscount without **careful condition checks**.

---
![image](https://github.com/user-attachments/assets/26721ee4-eaf6-4cc9-8a40-0c55e36e788f)
![image](https://github.com/user-attachments/assets/4df08fc2-72c2-47b9-9cfa-d3d693840ce2)

