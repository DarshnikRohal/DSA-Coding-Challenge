# 🚀 Day 45 – Town Judge & GCD of Strings 🏛️🔠

## 📚 What I Solved Today

Solved a logic-based identification problem involving trust relationships and explored how math concepts like GCD can apply to string patterns.

---

### 🧠 Problem 1: Find the Town Judge
- **Task:** Identify the person in the town who is trusted by everyone but trusts no one.
- **Approach:**  
  - Used a **trust score array** of size `n+1`.  
  - For each pair `(a, b)` in `trust`, did:
    - `score[a]--` (a trusts someone)  
    - `score[b]++` (b is trusted)  
  - The judge is the one with a score of `n-1`.
- **Complexity:** O(n + t), where t = size of trust array

---

### 🧠 Problem 2: Greatest Common Divisor of Strings
- **Task:** Return the largest string `x` that divides both `str1` and `str2` (i.e., both can be formed by repeating `x`).
- **Approach:**  
  - Checked if `str1 + str2 == str2 + str1`.  
  - If true, returned `str1.substr(0, gcd(len1, len2))`.  
  - Used built-in `__gcd` function.
- **Complexity:** O(n), where n = length of shorter string

---

## 🧠 Key Takeaways

- Trust-based graph problems can be solved with **count tracking**.  
- String divisibility problems sometimes boil down to elegant **mathematical insights** like GCD.

---
![Screenshot 2025-07-06 215447](https://github.com/user-attachments/assets/a98a102a-3e5b-4729-92fe-1391f4546adf)

---
![Screenshot 2025-07-06 221315](https://github.com/user-attachments/assets/066df0b7-5cdc-4169-a6ae-a7cc8e889d1d)


