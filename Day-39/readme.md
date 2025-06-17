# 🚀 Day 39 – BST Insertion & String Deduplication 🌲🧹

## 📚 What I Solved Today

Practiced maintaining BST structure during insertion and used stack logic to clean up strings with adjacent duplicates.

---

### 🧠 Problem 1: Insert into a Binary Search Tree
- **Task:** Insert a given value into a BST such that the BST properties remain intact.
- **Approach:**  
  - Used **recursive insertion** strategy.  
  - Compared current node’s value with target:  
    - If less, insert into left subtree.  
    - If greater, insert into right subtree.  
  - Created and returned a new node when reaching a null child.
- **Complexity:** O(h) time, where h is the tree height

---

### 🧠 Problem 2: Remove All Adjacent Duplicates in String
- **Task:** Repeatedly remove adjacent duplicate characters from a string until no more can be removed.
- **Approach:**  
  - Utilized a **stack-like approach** with a result string.  
  - If the current character matched the last character in result, removed the last character.  
  - Else, added the character to the result.
- **Complexity:** O(n) time, O(n) space

---

## 🧠 Key Takeaways

- Recursive thinking is essential for clean and readable **tree operations**.  
- Stack-based solutions are intuitive and efficient for **string cleanup problems** involving reversals or undo operations.

---
![Screenshot 2025-06-17 112947](https://github.com/user-attachments/assets/63d4ae91-f473-47db-942a-9bbf0af88382)

---
![Screenshot 2025-06-17 113152](https://github.com/user-attachments/assets/b71c59eb-f7bb-4d26-8dcd-05dbf1b0f457)


