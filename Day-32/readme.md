# 🚀 Day 32 – Matrix Rotation & Binary Tree BFS 🌀🌲

## 📚 What I Solved Today

Practiced in-place matrix transformation and level-wise traversal of binary trees using queues.

---

### 🧠 Problem 1: Rotate Image (90° Clockwise)
- **Task:** Rotate an `n x n` matrix 90 degrees clockwise in-place.
- **Approach:**  
  - **Step 1:** Transpose the matrix (swap `matrix[i][j]` with `matrix[j][i]`)  
  - **Step 2:** Reverse each row.
- **Complexity:** O(n²) time, O(1) space (in-place)

---

### 🧠 Problem 2: Binary Tree Level Order Traversal
- **Task:** Return a 2D list representing level-wise traversal of a binary tree.
- **Approach:**  
  - Used **BFS** with a queue.  
  - Pushed all nodes of each level into a temporary vector.  
  - Enqueued left and right children accordingly.
- **Complexity:** O(n) time, O(n) space

---

## 🧠 Key Takeaways

- Matrix rotation is best done via **transpose + reverse** trick.  
- **Level order traversal** is a fundamental BFS template used in many tree problems.

---
![Screenshot 2025-06-08 190808](https://github.com/user-attachments/assets/4e26856a-963e-4545-94a7-5aa3b739facf)

---
![Screenshot 2025-06-08 185913](https://github.com/user-attachments/assets/8b3739da-c1eb-42f8-8ec2-4165fc78af40)

