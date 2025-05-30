# 🚀 Day 14 – Partition List & Reverse Integer 🔁🔢

## 📚 What I Solved Today

Worked on a key linked list rearrangement and a digit-based integer reversal with overflow handling.

---

### 🧠 Problem 1: Partition List
- **Task:** Reorder a linked list so all nodes with values < x come before nodes ≥ x.
- **Approach:**  
  - Created two dummy heads: `before` and `after`.  
  - Populated both lists while traversing.  
  - Linked them in the end.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Reverse Integer
- **Task:** Reverse the digits of a 32-bit signed integer.
- **Approach:**  
  - Used modulo and division to reverse digits.
  - Checked for overflow before appending each digit.
- **Complexity:** O(log n) time, O(1) space

---

## 🧠 Key Takeaways

- Two-list dummy pointer pattern is very effective.
- Watch for 32-bit overflows during arithmetic operations!
