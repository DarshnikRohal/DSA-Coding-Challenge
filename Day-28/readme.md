# 🚀 Day 28 – Binary Tree Problems & LCM-based Subarrays 🌳➗

## 📚 What I Solved Today

Worked on binary tree traversal and advanced subarray enumeration using LCM logic.

---

### 🧠 Problem 1: Minimum Depth of Binary Tree
- **Task:** Find the shortest distance from root to the nearest leaf.
- **Approach:**  
  - Used **BFS** to explore level-by-level and returned when first leaf was found.  
  - Also implemented DFS with base case checks for null children.
- **Complexity:** O(n) time, O(n) space

---

### 🧠 Problem 2: Number of Subarrays with LCM Equal to K
- **Task:** Count number of subarrays whose LCM equals `k`.
- **Approach:**  
  - Brute-force with nested loop for all subarrays.  
  - Used `__gcd` function to compute LCM efficiently.  
  - Broke early if LCM exceeded `k`.
- **Complexity:** Worst-case O(n²), optimized with pruning

---

## 🧠 Key Takeaways

- BFS provides optimal early exit for shortest paths in trees.
- LCM-based subarray problems require careful brute-force and math optimization.

---
![Screenshot 2025-06-05 184406](https://github.com/user-attachments/assets/5fae303e-d9ba-4c1b-9ee0-bc0e663d0de4)

---
![Screenshot 2025-06-05 184256](https://github.com/user-attachments/assets/0134d919-b4d0-4e6e-a5f0-d363c2df45f2)

