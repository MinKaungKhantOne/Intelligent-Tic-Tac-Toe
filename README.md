# MMDT Tic-Tac-Toe AI Visualizer

## Project Overview

MMDT Tic-Tac-Toe AI Visualizer is an interactive web-based application that demonstrates classical Artificial Intelligence (AI) game-playing strategies through the Tic-Tac-Toe game.

The application implements multiple AI agents using adversarial search algorithms and heuristic-based decision-making techniques. Users can play against AI agents, observe their decision-making processes, and compare different strategies through an interactive web interface.

Developed using Python and Flask, the project combines Game Theory, AI search algorithms, and full-stack web development in a single application.

## Key Features

### 1. Multiple AI Agents

The application implements different AI strategies:

- **Minimax with Alpha-Beta Pruning:** Uses adversarial search to find optimal moves while pruning unnecessary branches to improve search efficiency.
- **Heuristic-Based Agent:** Uses rule-based priority evaluation to select moves based on winning opportunities, blocking opponent moves, and strategic board positions.
- **Random Agent:** Selects available moves randomly as a baseline for comparing AI performance.

### 2. Minimax Algorithm

- Implements the Minimax decision-making algorithm for a two-player, zero-sum game.
- Evaluates possible game states to determine the best available move.
- Considers both the AI's objectives and the opponent's possible responses.
- Uses game-state evaluation to select optimal moves.

### 3. Alpha-Beta Pruning

- Optimizes Minimax search by eliminating branches that cannot affect the final decision.
- Reduces unnecessary game-state exploration.
- Maintains the optimal decision-making capability of Minimax.

### 4. Heuristic Priority Evaluation

- Implements rule-based priorities for move selection.
- Identifies immediate winning opportunities.
- Blocks potential opponent winning moves.
- Evaluates strategic board positions to improve gameplay decisions.

### 5. Interactive Web Visualization

- Provides an interactive Tic-Tac-Toe game interface.
- Allows users to play against different AI agents.
- Displays game progress and results.
- Visualizes candidate move scores to demonstrate AI decision-making.

### 6. AI Agent Benchmarking

- Compares different AI agents using their gameplay performance.
- Uses Random Agent as a baseline.
- Demonstrates differences between optimal search-based strategies and heuristic-based approaches.

## Technologies Used

| Category             | Technologies                |
| -------------------- | --------------------------- |
| Programming Language | Python                      |
| AI Algorithms        | Minimax, Alpha-Beta Pruning |
| Decision Making      | Heuristic Evaluation        |
| AI Baseline          | Random Agent                |
| Backend Framework    | Flask                       |
| Frontend             | HTML, CSS, JavaScript       |
| Web Communication    | REST API / HTTP             |
| Version Control      | Git, GitHub                 |
| Deployment           | Web Hosting Platform        |

## AI Algorithms

### Minimax with Alpha-Beta Pruning

The Minimax algorithm explores possible game states to determine the best move by considering the optimal decisions of both players.

Alpha-Beta Pruning improves search efficiency by skipping branches that cannot influence the final decision.

### Heuristic-Based Search

The heuristic agent evaluates available moves using predefined strategic priorities rather than exploring the entire game tree.

### Random Baseline Agent

The Random Agent selects a legal move randomly and serves as a baseline for comparing the performance of other AI strategies.

## How It Works

1. **Game Initialization:** The application initializes the Tic-Tac-Toe board.
2. **Player Interaction:** The user selects a cell to make a move.
3. **AI Decision Making:** The selected AI agent analyzes the current board state.
4. **Search and Evaluation:** The AI applies its search algorithm or heuristic rules to evaluate available moves.
5. **Move Execution:** The AI selects and executes its chosen move.
6. **Game State Update:** The application checks for winning conditions, draws, and remaining legal moves.
7. **Visualization:** The updated board and AI decision information are displayed through the web interface.

## Author

**Min Kaung Khant**

GitHub: [MinKaungKhantOne](https://github.com/MinKaungKhantOne)
