# 🚀 Day 4 – Palindrome Number & Valid Perfect Square 🔢🧮

## 📚 What I Solved Today

Tackled two classic math-based problems that reinforce logic building and edge case handling.

---

### 🧠 Problem 1: Palindrome Number
- **Task:** Check if an integer is a palindrome (same forward and backward).
- **Approach:**  
  - Avoided converting number to a string.
  - Reversed half of the number and compared it to the other half.
  - Carefully handled edge cases like trailing zeros and negatives.
- **Complexity:**  
  - Time: O(log₁₀n), Space: O(1)

---

### 🧠 Problem 2: Valid Perfect Square
- **Task:** Determine if a number is a perfect square without using sqrt().
- **Approach:**  
  - Used **binary search** from 1 to num.
  - Checked if mid × mid == num.
- **Complexity:**  
  - Time: O(log n), Space: O(1)

---


## 🧠 Key Takeaways

- Efficient number manipulation avoids extra space.
- Binary search is a versatile tool beyond sorted arrays.
