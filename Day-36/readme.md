# 🚀 Day 36 – Tree Path Sums & Vowel Reversal 🌳🔄🔡

## 📚 What I Solved Today

Worked on calculating path-based values in trees and used two-pointer logic for string manipulation.

---

### 🧠 Problem 1: Sum Root to Leaf Numbers
- **Task:** Each path from root to leaf forms a number. Return the **sum** of all such numbers.
- **Approach:**  
  - Used **recursive DFS** with a running sum.  
  - At each node: `currentSum = currentSum * 10 + node->val`  
  - On reaching a leaf, added `currentSum` to total.
- **Complexity:** O(n) time, O(h) space (due to recursion stack)

---

### 🧠 Problem 2: Reverse Vowels of a String
- **Task:** Reverse only the vowels in a string, keeping other characters unchanged.
- **Approach:**  
  - Implemented **two-pointer** approach.  
  - Moved pointers inward, swapping vowels found on both ends.  
  - Used a set of vowels for quick lookup.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- Recursive tree problems often involve carrying state through function parameters.  
- Two-pointer techniques can simplify **in-place transformations** significantly.

---
![Screenshot 2025-06-12 204544](https://github.com/user-attachments/assets/47217abd-4c46-4d80-b5e9-02e168211d66)

---
![Screenshot 2025-06-12 195549](https://github.com/user-attachments/assets/042e7522-6d67-411b-b692-785e3075e72e)
