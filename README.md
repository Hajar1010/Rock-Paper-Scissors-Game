# 🎮 Rock Paper Scissors Game

A simple and fun **Rock Paper Scissors** game built using **HTML**, **CSS**, and **JavaScript**.  
The player competes against the computer — first to reach 3 points wins the game!

---

## 🧠 How It Works

1. The player selects **Rock**, **Paper**, or **Scissors**.
2. The computer randomly picks one of the three options.
3. The game determines the winner for that round:
   - Rock beats Scissors  
   - Scissors beats Paper  
   - Paper beats Rock  
4. The first to reach **3 points** wins the game.

---

## 🧩 Features

- 🎲 Random computer selection  
- 🧮 Score tracking for player and computer  
- 🏆 Winner announcement when someone reaches 3 points  
- 🔁 Reset button to start a new game  
- 🎨 Clean and responsive interface (using CSS)

---

## 💻 Technologies Used

- **HTML5** – for page structure  
- **CSS3** – for styling and layout  
- **JavaScript (ES6)** – for game logic and interactivity

---

## 🧱 Code Overview

### `getRandomComputerResult()`
Generates a random choice for the computer (`Rock`, `Paper`, or `Scissors`).

### `hasPlayerWonTheRound(player, computer)`
Checks if the player’s choice wins against the computer’s choice.

### `getRoundResults(userOption)`
Compares both choices, updates scores, and returns a message for the current round.

### `showResults(userOption)`
Updates the DOM to show round results, current scores, and declares a winner if someone reaches 3 points.

### `resetGame()`
(Placeholder function) – will reset scores, results, and UI for a new match.

---

## 🚀 How to Run the Game

1. Clone or download this repository.  
2. Open the `index.html` file in your browser.  
3. Click **Rock**, **Paper**, or **Scissors** to start playing.  
4. Try to beat the computer to 3 points! 😎  

---

## 🧠 Future Improvements

- Add animations and sound effects.  
- Let the player set a custom score limit (e.g., best of 5).  
- Improve mobile layout and accessibility.

---

## 🏅 Skills Demonstrated

- DOM manipulation  
- Event handling  
- Conditional logic  
- Randomization and functions  
- Basic game flow and UI feedback
