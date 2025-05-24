# 🚀 Day 2 – Middle of Linked List & Add Digits 🔁➕

## 📚 What I Solved Today

Focusing on pointer techniques and number manipulation problems on LeetCode.

---

### 🧠 Problem 1: Middle of the Linked List
- **Task:** Return the middle node of a singly linked list.
- **Approach:**  
  - Used the **two-pointer technique** (slow and fast).
  - When fast reaches the end, slow is at the middle.
- **Complexity:**  
  - Time: O(n), Space: O(1)

---

### 🧠 Problem 2: Add Digits
- **Task:** Repeatedly add digits until a single-digit result is obtained.
- **Approach:**  
  - Brute-force using loops and modulo.  
  - Then optimized using the **digital root formula**:  
    `result = 1 + (num - 1) % 9` for num > 0
- **Complexity:**  
  - Time: O(1), Space: O(1)

---


## 🧠 Key Takeaways

- The slow-fast pointer method is a recurring trick in linked list problems.
- Number theory (digital root) provides elegant constant-time solutions.
