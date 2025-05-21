# 🎮 Tic Tac Toe - React Game

This is a simple **Tic Tac Toe** game (also known as "Three in a Row") built with **React**. It allows two players to take turns playing on a 3x3 grid until one wins or the game ends in a draw.

---

## 🚀 Features

- Built with functional React components
- Uses `useState` hook for managing game state
- Win detection logic included
- Basic game status display (next player / winner)
- Responsive to player interaction

---

## 📸 Demo

![tic-tac-toe-screenshot](https://via.placeholder.com/500x300.png?text=Game+Screenshot)  
<!-- Optional: Replace with your own image or GIF demo -->

---

## 🧠 How It Works

- The board is a 3x3 grid of buttons (`<Square />`) rendered by the `<Board />` component.
- Player X starts first.
- After each click, the board updates and checks for a winner using the `calculateWinner()` function.
- If a player wins, the game displays the winner.
- If all squares are filled with no winner, the game ends in a draw.

---

## 📦 Technologies Used

- React (with `useState`)
- JavaScript
- CSS (for layout and button styling)

---

## 🛠 How to Run Locally

