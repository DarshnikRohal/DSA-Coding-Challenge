# 🚀 Day 18 – Queue Using Stacks & Contains Duplicate 🔁🔍

## 📚 What I Solved Today

Worked on implementing a queue using stacks and detecting duplicates in an array.

---

### 🧠 Problem 1: Implement Queue using Stacks
- **Task:** Implement a queue using two stacks.
- **Approach:**  
  - `Stack1` for enqueue, `Stack2` for dequeue.  
  - Transferred elements from `Stack1` to `Stack2` during dequeue.
- **Complexity:**  
  - Amortized O(1) for push, O(1) for pop/peek

---

### 🧠 Problem 2: Contains Duplicate
- **Task:** Determine if any value appears at least twice.
- **Approach:**  
  - Used a hash set to store seen values.  
  - If value is already present, return true.
- **Complexity:** O(n) time, O(n) space

---

## 🧠 Key Takeaways

- Two stacks can mimic queue behavior with some clever data transfer.
- Sets are ideal for constant-time uniqueness checks.

---
![Screenshot 2025-05-31 220752](https://github.com/user-attachments/assets/cd2b0500-557d-43df-acb8-b740337aeaaf)

---

![Screenshot 2025-05-31 220534](https://github.com/user-attachments/assets/76945fd9-459b-46d3-8455-395f7621bf9e)

