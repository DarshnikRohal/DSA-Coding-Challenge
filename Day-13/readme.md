# 🚀 Day 13 – Remove Duplicates II & Sign of Product 🧼✖️➕➖

## 📚 What I Solved Today

Today was about smart filtering in lists and analyzing the sign of a product without actual multiplication.

---

### 🧠 Problem 1: Remove Duplicates from Sorted List II
- **Task:** Remove all duplicates entirely from a sorted list.
- **Approach:**  
  - Used dummy head and scanned ahead to skip duplicate streaks.
  - Maintained unique nodes only.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Sign of the Product of an Array
- **Task:** Return the sign of the product of an array (1, -1, or 0).
- **Approach:**  
  - Counted number of negative elements.
  - Checked for zero early, then returned based on parity of negatives.
- **Complexity:** O(n) time, O(1) space

---

## 🧠 Key Takeaways

- Dummy node technique is essential for edge deletions in linked lists.
- Sign computation is a great way to avoid overflow in product calculations.
