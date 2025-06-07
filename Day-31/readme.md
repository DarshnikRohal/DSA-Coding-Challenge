# 🚀 Day 31 – Binary Tree Depth & Matrix Bit-Flipping 🌲🧩

## 📚 What I Solved Today

Practiced depth-first search recursion on binary trees and optimized bitwise operations on 2D arrays.

---

### 🧠 Problem 1: Maximum Depth of Binary Tree
- **Task:** Find the maximum depth (or height) of a binary tree.
- **Approach:**  
  - Applied **recursive DFS**:  
    ```cpp
    return 1 + max(depth(left), depth(right));
    ```
  - Base case: return 0 when node is null.
- **Complexity:** O(n) time, O(h) space (h = height of the tree)

---

### 🧠 Problem 2: Flipping an Image
- **Task:** Horizontally flip and then invert a binary matrix.
- **Approach:**  
  - Reversed each row using two-pointer swap.  
  - Flipped bits using XOR (`bit ^ 1`) during the same pass.  
- **Complexity:** O(n × m) time, in-place space

---

## 🧠 Key Takeaways

- Binary tree problems like depth are best solved via post-order DFS.  
- Matrix transformation problems can be optimized by merging passes and using XOR tricks.

---
![Screenshot 2025-06-07 134559](https://github.com/user-attachments/assets/573d3577-2b86-4ec9-847b-b2b88e2788a6)

---
![Screenshot 2025-06-07 133411](https://github.com/user-attachments/assets/b6119d56-9b02-4aad-8840-4356b10b92ab)
