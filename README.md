# 🎮 AI Tic Tac Toe – Phaser 3

An interactive **Tic Tac Toe game with an AI-powered opponent**, developed using JavaScript and Phaser 3.

Challenge yourself against an AI opponent that uses the **Minimax algorithm** to evaluate possible moves and select the optimal strategy. The game features a modern dark-themed interface, smooth animations, interactive game cells, and instant game restart functionality.

## ✨ Features

- 🤖 **AI Opponent:** Play against an intelligent AI powered by the Minimax algorithm.
- 🧠 **Optimal Decision Making:** AI evaluates possible moves to maximize its chances of winning and avoid losing.
- 🎨 **Modern UI:** Dark-themed interface with gradient-like background effects and styled game panels.
- ⚡ **Smooth Animations:** Animated X and O symbols using Phaser tweens.
- 🖱️ **Interactive Gameplay:** Hover effects and clickable game cells.
- 🏆 **Win Detection:** Automatically detects human wins, AI wins, and draws.
- 🟢 **Winning Highlight:** Highlights the winning combination on the board.
- 🔄 **Play Again:** Restart the game instantly without refreshing the browser.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Game structure |
| CSS3 | Page styling |
| JavaScript | Game logic and interactions |
| Phaser 3 | 2D game rendering and animations |
| Minimax Algorithm | AI decision-making |

## 🧠 AI Algorithm – Minimax

The AI opponent uses the **Minimax algorithm**, a decision-making algorithm commonly used in two-player games.

The algorithm explores possible future moves and selects the move with the best possible outcome.

- **MAX Player (AI – X):** Tries to maximize the score.
- **MIN Player (Human – O):** Assumed to minimize the score.
- **AI Win:** Score = +10
- **Human Win:** Score = -10
- **Draw:** Score = 0

A depth factor is also included to prioritize faster wins and delay unavoidable losses.

This makes the AI extremely difficult to defeat when playing optimally.

## 🎮 How to Play

1. Open the game in your browser.
2. You play as **O (Human)**.
3. The computer plays as **X (AI)**.
4. Click any empty cell to make your move.
5. The AI automatically calculates and performs its move.
6. The game ends when either player wins or the board becomes full.
7. Click **PLAY AGAIN** to start a new match.

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.).
- Internet connection to load Phaser 3 from the CDN.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/tic-tac-toe-phaser.git
```

**2. Navigate to the project directory**

```bash
cd tic-tac-toe-phaser
```

**3. Run the game**

Open `tic_tac_toe.html` in your web browser.

Alternatively, use the VS Code Live Server extension and select **Open with Live Server**.

## 📂 Project Structure

```text
tic-tac-toe-phaser/
│
├── tic_tac_toe.html    # Main game implementation
├── README.md           # Project documentation
└── .gitignore          # Git ignored files
```

## 🔮 Future Improvements

- Add difficulty levels (Easy, Medium, Hard).
- Add two-player local multiplayer mode.
- Introduce sound effects and background music.
- Add score tracking and match statistics.
- Improve responsive support for mobile devices.
- Deploy the game using GitHub Pages.

## 👨‍💻 Author

**YOUR NAME**

GitHub: [@Gargi4-git](https://github.com/Gargi4-git)

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

⭐ If you like this project, consider giving it a star on GitHub!