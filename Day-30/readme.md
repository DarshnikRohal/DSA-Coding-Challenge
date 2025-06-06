# 🚀 Day 30 – Tree Diameter & Duplicate Detection 🌲🔁

## 📚 What I Solved Today

Focused on finding the longest path in a binary tree and detecting duplicates using a clever cycle detection algorithm.

---

### 🧠 Problem 1: Diameter of a Binary Tree
- **Task:** Find the length of the longest path between any two nodes in a binary tree.
- **Approach:**  
  - Used **post-order DFS** to get height of left and right subtrees.  
  - At each node, updated global max as `leftHeight + rightHeight`.  
- **Complexity:** O(n) time, O(h) space (h = height of tree)

---

### 🧠 Problem 2: Find the Duplicate Number
- **Task:** Given `n + 1` integers in range `[1, n]`, find any duplicate (without modifying the array).
- **Approach:**  
  - Used **Floyd’s Cycle Detection Algorithm** (Tortoise and Hare).  
  - Treated values as next indices to simulate a linked list.  
  - Found cycle entry point as the duplicate.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- Tree problems like diameter often rely on bottom-up recursion with global tracking.
- Floyd’s algorithm is powerful even for non-traditional cycle detection (like arrays).

---
![Screenshot 2025-06-06 180544](https://github.com/user-attachments/assets/46aefa21-36f0-47ff-84b4-4e7215fcf33d)

---
![Screenshot 2025-06-06 174436](https://github.com/user-attachments/assets/7c5c08ad-243f-466b-9011-b614887f74a7)
