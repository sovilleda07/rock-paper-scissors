# 🪨📄✂️ Rock Paper Scissors  
*A simple browser-based Rock–Paper–Scissors game built with HTML, CSS, and JavaScript.*  
![Demo game](./img/demo.png)
---

## 🎮 Overview
This is a web-based **Rock Paper Scissors** game where the player competes against the computer. The app runs directly in the browser and uses JavaScript to generate the computer’s move and determine the winner. The score is stored using `localStorage`, so it persists even if you refresh the page.

---

## 🚀 Features
- Three selectable moves: **Rock**, **Paper**, and **Scissors**
- Random computer move generation
- Round result display
- Scoreboard saved in browser storage
- Reset score button
- Simple and clean UI

---

## 💻 Technologies Used

- **HTML5**: Structure of the game interface
- **CSS3**: Styling
- **JavaScript**: Game logic and DOM manipulation
- **LocalStorage**: For saving game progress

---

## 📂 Project Structure
```
/
├── index.html # Main game UI
├── css/
│ └── styles.css # Styling
├── scripts/
│ └── scripts.js # Game logic
└── img/ # Rock, paper, scissors emojis
```

---

## 🧠 How It Works
- The user clicks a move button.
- The JavaScript function `playGame()` compares:
  - The player's move  
  - The computer's randomly generated move
- The result elements update:
  - Result message  
  - Moves display  
  - Scoreboard (wins, losses, ties)

The score uses `localStorage` to persist after refresh.

---

## Live Demo

Experience the game live: [Rock, Paper, Scissors Game](https://sovilleda07.github.io/rock-paper-scissors/)

---

## ✂️ How to Play
1. Open the game in your web browser.
2. Click on your choice of Rock, Paper, or Scissors.
3. View the computer's choice and the result.
4. Play again!

---

## ▶️ How to Run

To run this project locally:

 1. Clone the repository: 

```bash
  git clone https://github.com/sovilleda07/rock-paper-scissors.git
```

 2. Navigate to the project directory: 

```bash
  cd rock-paper-scissors-game
```

 3. Open `index.html` in your preferred web browser 

---

## 📜 License
This project is free for personal or educational use.  

