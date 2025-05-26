# 🚀 Day 6 – Remove Linked List Elements & Happy Number 🔗😊

## 📚 What I Solved Today

Dived into problems involving pointer manipulation in linked lists and cycle detection in number transformations.

---

### 🧠 Problem 1: Remove Linked List Elements
- **Task:** Delete all nodes in a linked list that have a specific value.
- **Approach:**  
  - Introduced a **dummy node** before the head to handle deletions cleanly.
  - Iterated through the list, skipped nodes with the target value.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

### 🧠 Problem 2: Happy Number
- **Task:** Determine if a number eventually becomes 1 by summing squares of digits.
- **Approach:**  
  - Used a **set** to track previously seen numbers.
  - If a cycle occurs (number repeats), it's not a happy number.
  - Alternative: Used **Floyd's Cycle Detection Algorithm**.
- **Complexity:**  
  - Time: O(log n), Space: O(log n)

---

## 🧠 Key Takeaways

- Dummy nodes simplify edge case handling in linked lists.
- Using sets or slow-fast pointers can detect cycles in number operations.
