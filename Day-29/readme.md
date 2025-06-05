# 🚀 Day 29 – Sum of Left Leaves & Kth Largest Element 🍃🔢

## 📚 What I Solved Today

Solved problems involving binary tree leaf tracking and selection problems using heaps.

---

### 🧠 Problem 1: Sum of Left Leaves
- **Task:** Compute the sum of all left leaf nodes in a binary tree.
- **Approach:**  
  - DFS traversal with an `isLeft` flag.  
  - If node is a leaf and marked `isLeft`, add its value.
- **Complexity:** O(n) time

---

### 🧠 Problem 2: Kth Largest Element in Array
- **Task:** Find the k-th largest element in an unsorted array.
- **Approach:**  
  - Maintained a **min-heap** of size `k`.  
  - Replaced root when a larger element was found.
- **Complexity:** O(n log k) time, O(k) space

---

## 🧠 Key Takeaways

- DFS flags can help capture contextual node properties (left/right).
- Min-heaps are efficient for tracking top-k elements in a stream of values.

---

![Screenshot 2025-06-05 185855](https://github.com/user-attachments/assets/0eb2fee5-5a9a-4487-ab19-e90c1a5fe258)

---
![Screenshot 2025-06-05 185119](https://github.com/user-attachments/assets/f5a1f4d7-65f5-4d01-a331-94b64e9dfa47)
