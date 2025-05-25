# 🚀 Day 5 – Linked List Cycle & Palindrome Linked List 🔁🔄

## 📚 What I Solved Today

Focused on linked list pattern recognition – detecting cycles and checking for palindromes.

---

### 🧠 Problem 1: Linked List Cycle
- **Task:** Determine if a linked list has a cycle.
- **Approach:**  
  - Applied **Floyd’s Cycle Detection Algorithm** (slow and fast pointers).
  - Fast moves 2 steps, slow moves 1 step – if they meet, a cycle exists.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

### 🧠 Problem 2: Palindrome Linked List
- **Task:** Check if the elements of a linked list form a palindrome.
- **Approach:**  
  - Found the middle of the list.
  - Reversed the second half.
  - Compared first and second halves.
  - Restored the list to its original state (good practice!).
- **Complexity:**  
  - Time: O(n), Space: O(1) (excluding recursion stack if used)

---

## 🧠 Key Takeaways

- Cycle detection and half-list reversal are essential linked list techniques.
- Restoring modified data structures can demonstrate clean coding habits.
