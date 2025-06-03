# 🚀 Day 22 – Majority Element & Valid Parentheses Cleanup 🗳️🔧

## 📚 What I Solved Today

Solved two key problems: one on finding dominant elements and the other on cleaning up invalid parentheses in strings.

---

### 🧠 Problem 1: Majority Element
- **Task:** Find the element that appears more than ⌊n / 2⌋ times.
- **Approach:**  
  - Applied **Boyer-Moore Voting Algorithm**.  
  - Maintained a counter that resets when encountering a new element.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Minimum Remove to Make Valid Parentheses
- **Task:** Remove the minimum number of parentheses to make the input valid.
- **Approach:**  
  - First pass: push unmatched `)` onto a stack.  
  - Second pass: mark unmatched `(` and rebuild the string.
- **Complexity:** O(n) time and space

---

## 🧠 Key Takeaways

- The Boyer-Moore algorithm is incredibly space-efficient.
- Stack-based string validation helps maintain expression integrity.

---

![Screenshot 2025-06-03 194153](https://github.com/user-attachments/assets/b5ab6f30-9878-4b60-b5a3-c01a52683d42)

---
![Screenshot 2025-06-03 193057](https://github.com/user-attachments/assets/5fe20d97-a655-4cfe-a7e0-3974cfdfc451)
