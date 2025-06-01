# 🚀 Day 21 – Valid Parenthesis String & Pascal's Triangle II 🔁🔺

## 📚 What I Solved Today

Explored tricky parentheses validation with wildcards and built a row of Pascal’s triangle.

---

### 🧠 Problem 1: Valid Parenthesis String
- **Task:** Determine if string with `'('`, `')'`, and `'*'` is valid.
- **Approach:**  
  - Used **greedy strategy** with `low` and `high` bounds.  
  - `*` treated as `(`, `)` or empty to maintain valid balance range.  
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Pascal's Triangle II
- **Task:** Return k-th row of Pascal's Triangle.
- **Approach:**  
  - Used **1D DP array** and filled it backwards.  
  - Avoided recomputation with in-place updates.
- **Complexity:** O(k²) time, O(k) space

---


## 🧠 Key Takeaways

- Greedy logic can outperform backtracking in special cases.
- In-place DP updates make Pascal’s triangle memory-efficient.

---
![Screenshot 2025-06-01 185337](https://github.com/user-attachments/assets/d564a368-9b66-40af-9b1e-f6048245a720)

---
![Screenshot 2025-06-01 184332](https://github.com/user-attachments/assets/623293fb-7f9d-46db-bccc-0cb80d11f560)

