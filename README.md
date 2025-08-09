# 🎯 Ultimate Tic-Tac-Toe Rules

Ultimate Tic-Tac-Toe takes the classic game to the next level by combining strategy across **nine mini tic-tac-toe boards**.

---

## 📌 Game Setup
- The game is played on a **3×3 grid of smaller tic-tac-toe boards**.
- Each small board contains **3×3 cells**, just like a normal tic-tac-toe game.
- Two players: **X** and **O**.

---

## 🕹 How to Play
1. **Your move determines your opponent’s board**  
   - When you play in a cell, it sends your opponent to the mini-board in the corresponding *position*.  
     Example: If you play in the **top-right** cell of a mini-board, your opponent must play in the **top-right** mini-board.

2. **If the target board is full or won**  
   - Your opponent may play **anywhere** on the board.

3. **Winning a mini-board**  
   - Play as normal tic-tac-toe inside a mini-board.
   - When you win, you **claim** that board for your symbol (**X** or **O**).

4. **Winning the game**  
   - The main goal is to win **three mini-boards in a row** (horizontal, vertical, or diagonal) on the **big board**.

---

## 📖 Example Flow
1. Player X starts in the **center** cell of the top-left mini-board.  
2. Player O must play in the **center mini-board**.  
3. This continues until one player wins.

---

## ⛔ Additional Rules & Clarifications
- No overwriting: You can only play in empty cells.
- Draws: If a mini-board is a draw, it still counts as “unclaimed.”
- Free move situations: If your move sends the opponent to a **won or full mini-board**, they can choose **any valid cell on any board**.

---

## 📷 Visual Layout
(*Photos will be added soon*)  
```text
