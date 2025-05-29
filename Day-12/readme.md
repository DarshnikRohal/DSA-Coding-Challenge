# 🚀 Day 12 – Insert GCD in List & Count Odds 🧮🧠

## 📚 What I Solved Today

A GCD-based linked list problem and a quick math puzzle to count odd numbers in a range.

---

### 🧠 Problem 1: Insert GCD Between Nodes
- **Task:** For each adjacent pair in a linked list, insert a node with the GCD of the two values.
- **Approach:**  
  - Iterated through the list, calculated GCD for current and next nodes.
  - Inserted a new node in between using pointer manipulation.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Count Odd Numbers in an Interval Range
- **Task:** Count how many odd numbers lie in the range `[low, high]`.
- **Approach:**  
  - Used arithmetic trick to compute count directly:
    `((high - low) / 2) + 1 if low % 2 != 0 or high % 2 != 0`
- **Complexity:** O(1) time, O(1) space

---

## 🧠 Key Takeaways

- GCD + pointer operations = great hybrid problem.
- Some problems are just smart math in disguise.
