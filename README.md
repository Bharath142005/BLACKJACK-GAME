# Blackjack 🎴  

A simple **Blackjack card game** built with **HTML, CSS, and JavaScript**.  
This project was created as a learning exercise to practice DOM manipulation and game logic.  

![Blackjack Table](images/table.png)

## 🚀 Features  
- Start a new game and draw cards  
- Random card generation (Ace = 11, Face cards = 10)  
- Display of cards, sum, and player chips  
- Win/Lose logic:  
  - **Blackjack** if sum = 21  
  - **Bust** if sum > 21  
  - Option to draw new cards until the game ends  

## 🛠️ Tech Stack  
- **HTML** – Structure  
- **CSS** – Styling and background table image  
- **JavaScript** – Game logic and interactivity  
- **Vite** – Development server & bundler  

## 📂 Project Structure  
```
├── index.html       # Main HTML page
├── index.css        # Styles (background, buttons, text)
├── index.js         # Blackjack game logic
├── vite.config.js   # Vite config
├── package.json     # Dependencies & scripts
└── images/
    └── table.png    # Background table image
```

## ▶️ Run Locally  

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/blackjack-game.git
   cd blackjack-game
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```
4. Open in browser:
   ```
   http://localhost:5173
   ```

## 🎮 How to Play  
1. Click **Start Game** to begin with two random cards.  
2. Click **New Card** to draw another card.  
3. Try to reach **21** without going over.  
4. The game will display messages for win/loss conditions.  

## 📖 Credits  
- Inspired by [Scrimba JavaScript course](https://scrimba.com/learn-javascript-c0v/~034/s0uua76l8t/head)  
