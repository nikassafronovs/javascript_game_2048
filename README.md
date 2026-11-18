# 2048 Game

2048 is a feature-rich web version of the popular sliding tile puzzle game. Designed with a clean UI and smooth interactions, it provides an engaging puzzle-solving experience across all screen sizes with local high-score persistence.

## 🔗 Live Demo

Check out the live version of the game:
👉 [Play 2048 Online](https://nikassafronovs.github.io/javascript_game_2048/)

## 🛠️ Built With

* **HTML5** – Markup and structural layout of the game board.
* **SCSS** – Styling, responsive design (Flexbox/Grid), and animations.
* **JavaScript** – Core game mechanics, state management, matrix algorithms, and DOM manipulation.
* **Web APIs** – `LocalStorage` for persisting high scores.
* **Git & GitHub Pages** – Version control and hosting the live version.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

1. **Clone the repository:**
git clone https://github.com/nikassafronovs/javascript_game_2048.git
cd javascript_game_2048

2. **Install dependencies:** `npm install` or `yarn install`

3. **Run the project locally:** `npm start` or `yarn start`

## Features

* **Core Game Engine:** Implements a 4x4 matrix grid with robust movement, tile shifting, and merging algorithms for all four directions (Left, Right, Up, Down).
* **Keyboard Controls:** Fully interactive gameplay listening to keyboard arrow events (`ArrowLeft`, `ArrowRight`, `ArrowUp`, `ArrowDown`) to control board moves.
* **Dynamic Tile Generation:** Automatically spawns new random tiles (value 2 with 90% probability and 4 with 10% probability) in empty cells after every valid move.
* **Real-Time Score Tracking:** Dynamically calculates and updates the player's score as matching tiles combine.
* **Game Lifecycle & States:** Manages distinct game states (`idle`, `playing`, `win`, `lose`) with fully functional Start and Restart buttons.
* **Win & Lose Detection:** Automated checks that detect when the 2048 tile is reached (win condition) or when no valid moves remain (game over).
* **Dynamic DOM Rendering:** Efficiently syncs the internal matrix state with the DOM, updating cell values, scores, and toggling win/lose message overlays.


