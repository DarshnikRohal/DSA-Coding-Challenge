# 🚀 Day 8 – Odd Even Linked List & Excel Sheet Column Number 🔁📊

## 📚 What I Solved Today

Today’s mix featured pointer restructuring and base conversion logic. One from linked lists, the other from spreadsheet-style math!

---

### 🧠 Problem 1: Odd Even Linked List
- **Task:** Rearrange nodes in a linked list so that all odd-indexed nodes come before even-indexed ones.
- **Approach:**  
  - Used two pointers `odd` and `even` to collect nodes separately.  
  - Linked odd list to even list at the end.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

### 🧠 Problem 2: Excel Sheet Column Number
- **Task:** Convert a column title (like "AB") to its corresponding number.
- **Approach:**  
  - Treated the string as a base-26 number (A=1, ..., Z=26).
  - Used ASCII arithmetic to compute total.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

## 🧠 Key Takeaways

- Pointer separation and re-linking is a handy skill for linked list reordering.
- Problems involving letter-based math are best approached like base conversions.
