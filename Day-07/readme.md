# 🚀 Day 7 – Rotate List & Plus One 🔄➕

## 📚 What I Solved Today

Practiced edge case handling and efficient list manipulation — from rotating linked lists to simulating digit-wise math operations.

---

### 🧠 Problem 1: Rotate List
- **Task:** Rotate a linked list to the right by k places.
- **Approach:**  
  - Counted the number of nodes.
  - Connected tail to head to form a circular list.
  - Broke the cycle at the (length - k % length) node.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

### 🧠 Problem 2: Plus One
- **Task:** Add one to a number represented as a list of digits.
- **Approach:**  
  - Iterated from the end, handled carry.
  - If overflow (e.g., 999), prepended `1` to the list.
- **Complexity:**  
  - Time: O(n), Space: O(1) or O(n) if new digit is added

---

## 🧠 Key Takeaways

- Converting a linked list into a cycle and breaking it at the right point is an elegant rotation trick.
- Always handle edge cases like overflow (e.g., 999 → 1000) in digit array problems.
