# 🚀 Day 41 – Deleting in BST & Longest Common Prefix 🌳✂️🔠

## 📚 What I Solved Today

Handled dynamic structural changes in a BST and implemented an efficient solution to a common string pattern problem.

---

### 🧠 Problem 1: Delete Node in a Binary Search Tree
- **Task:** Delete a node with a given value from a BST and maintain the BST property.
- **Approach:**  
  - Used **recursive traversal** to locate the node.  
  - Three deletion cases handled:
    - No children → return `nullptr`
    - One child → return the child
    - Two children → find **inorder successor** (leftmost node in right subtree), replace value, delete successor recursively.
- **Complexity:** O(h) time, where h = height of tree

---

### 🧠 Problem 2: Longest Common Prefix
- **Task:** Find the longest common prefix among an array of strings.
- **Approach:**  
  - **Sorted** the array to bring similar prefixes closer.  
  - Compared only the **first and last strings**, since they are the most different post-sorting.  
  - Stopped comparison at first mismatch.
- **Complexity:** O(n log n + m) time, where m = length of shortest string

---

## 🧠 Key Takeaways

- Deleting in a BST requires careful case analysis and **recursive updates**.  
- Sorting simplifies common prefix problems by limiting the comparison scope.

---

![Screenshot 2025-06-21 135912](https://github.com/user-attachments/assets/065499f3-fb98-4c4c-93d9-f2c1a9b09784)

---
![Screenshot 2025-06-21 135456](https://github.com/user-attachments/assets/78753b3a-48ae-47c4-bdec-95332930a3ab)


