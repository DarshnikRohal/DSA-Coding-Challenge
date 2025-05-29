# 🚀 Day 11 – Remove Nth Node & Factorial Trailing Zeroes ✂️➕0️⃣

## 📚 What I Solved Today

Covered a classic linked list deletion problem and a math-based factorial trailing zeroes count.

---

### 🧠 Problem 1: Remove Nth Node From End of List
- **Task:** Remove the N-th node from the end of a singly linked list.
- **Approach:**  
  - Used a **dummy node** and **two-pointer** technique.
  - Advanced first pointer by `n` steps and then moved both together.
  - Removed node using `prev->next = curr->next`.
- **Complexity:** O(n) time, O(1) space

---

### 🧠 Problem 2: Factorial Trailing Zeroes
- **Task:** Count trailing zeroes in `n!`.
- **Approach:**  
  - Counted how many times 5 divides numbers from 1 to n.
  - Used `n/5 + n/25 + n/125 + ...`.
- **Complexity:** O(log n) time, O(1) space

---

## 🧠 Key Takeaways

- Dummy nodes are powerful for edge-case deletions.
- Trailing zeroes are all about powers of 5 in factorials!
