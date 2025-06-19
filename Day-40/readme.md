# 🚀 Day 40 – LCA in BST & String Rotation Check 🌳🔁

## 📚 What I Solved Today

Focused on optimizing Lowest Common Ancestor (LCA) search in a BST and implemented a clever trick for detecting string rotations.

---

### 🧠 Problem 1: Lowest Common Ancestor of a Binary Search Tree
- **Task:** Given the root of a BST and two nodes, return their **lowest common ancestor**.
- **Approach:**  
  - Used BST properties to guide the search:  
    - If both `p` and `q` are less than the current node, recurse left.  
    - If both are greater, recurse right.  
    - If one is on the left and the other on the right (or equal), current node is LCA.
- **Complexity:** O(h) time, where h = height of the tree

---

### 🧠 Problem 2: Rotate String
- **Task:** Check if one string is a rotation of another.
- **Approach:**  
  - Concatenated original string with itself: `s + s`  
  - Checked if the goal string exists as a substring within that.  
- **Complexity:** O(n) time for substring check, O(n) space for concatenation

---

## 🧠 Key Takeaways

- BSTs allow for faster, cleaner implementations of problems like **LCA** due to their sorted structure.  
- Rotation problems can often be reduced to **substring search** using clever transformations.

---
![Screenshot 2025-06-19 103953](https://github.com/user-attachments/assets/e4f6f65d-0806-4fdb-bc15-96edcd1931b1)

---
![Screenshot 2025-06-19 103044](https://github.com/user-attachments/assets/ebd7d242-c465-4d60-8502-309b92478d27)

