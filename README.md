# 🐺 Wolf & Sheep (Pawns vs. Knight)

A sleek, single-file strategy board game where four Pawns (Sheep) attempt to trap a single Knight (Wolf). Built with **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript**, featuring a custom **Minimax AI** with three levels of difficulty.

![Game UI Preview](https://img.shields.io/badge/UI-Tailwind--CSS-38B2AC?style=flat-square)
![Logic-JS](https://img.shields.io/badge/Logic-Vanilla--JS-F7DF1E?style=flat-square)
![AI-Minimax](https://img.shields.io/badge/AI-Minimax--Alpha--Beta-blue?style=flat-square)

## 🎮 How to Play

### The Goal
*   **As the Pawns (White):** Your goal is to surround the Knight so that it has no legal moves remaining.
*   **As the Knight (Black):** Your goal is to slip past the line of Pawns and reach the final row on the opposite side of the board.

### Movement Rules
*   **The Pawns:** Can only move **one square diagonally forward**. They cannot move backward.
*   **The Knight:** Moves like a "King" in checkers—it can move **one square in any of the four diagonal directions** (forward or backward).
*   **Perspective:** The game automatically flips the board so that your pieces always start at the bottom of the screen.

## 🤖 The AI (Minimax Engine)

The game features a strategic AI that uses the **Minimax Algorithm** enhanced by **Alpha-Beta Pruning**.

*   **Heuristic Evaluation:** The AI evaluates board states based on the Knight's vertical progress, the cohesion of the Pawn "wall," and the remaining mobility of the Knight.
*   **Difficulty Levels:**
    *   **Level 1 (Novice):** Lookahead of 4 moves. Makes occasional tactical blunders.
    *   **Level 2 (Expert):** Lookahead of 6 moves. Very difficult to bypass as the Knight.
    *   **Level 3 (Master):** Lookahead of 9 moves. Analyzes thousands of potential board states per turn to find the optimal "trap" configuration.

## 🚀 Installation & Running

This game is entirely self-contained in a single HTML file.

1.  **Download** the `.html` file provided in the previous response.
2.  **Open** the file in any modern web browser (Chrome, Firefox, Safari, or Edge).
3.  **No dependencies** or local servers are required—all CSS and JS are loaded inline or via high-speed CDNs.

## 🛠️ Built With

*   **Tailwind CSS:** For the modern, responsive "Glassmorphism" UI.
*   **Vanilla JavaScript:** For the game engine, board state management, and AI logic.
*   **HTML5 Canvas-less Grid:** Utilizes a DOM-based grid for accessibility and ease of styling.
