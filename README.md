# 🎮 Advanced Tic Tac Toe Arena

A feature-rich Tic Tac Toe game developed using **Python**, **Tkinter**, and **Object-Oriented Programming (OOP)**. This project extends the traditional Tic Tac Toe game by incorporating Artificial Intelligence, modern GUI design, sound effects, timers, match scoring, themes, and advanced gameplay features.

---

# 📌 Project Overview

Advanced Tic Tac Toe Arena is a desktop-based game that allows users to play either against another player or against a computer-controlled AI. The game includes multiple difficulty levels, score tracking, timer support, sound effects, and theme customization.

The project demonstrates the practical implementation of:

- Python Programming
- Object-Oriented Programming
- GUI Development using Tkinter
- Event Handling
- Artificial Intelligence (Minimax Algorithm)

---

# ✨ Features

## 🎮 Game Modes

### Player vs Player (PvP)
Two human players can play on the same computer.

### Player vs Computer (PvC)
Play against the computer with different AI difficulty levels.

---

## 🤖 AI Difficulty Levels

### Easy Mode
- Random move selection.
- Easy to defeat.

### Medium Mode
- Blocks opponent's winning moves.
- Attempts winning moves when available.
- Uses simple strategic decision making.

### Hard Mode
- Uses the Minimax Algorithm.
- Evaluates all possible game states.
- Unbeatable AI.

---

## 🏆 Match System

Players can choose:

- Best of 3
- Best of 5

The first player to reach the required number of wins becomes the match winner.

---

## ⏱ Turn Timer

Available options:

- 10 Seconds
- 15 Seconds
- 20 Seconds

If a player fails to make a move before the timer expires:

- A random move is automatically selected.

---

## 🎨 Theme Support

### Dark Theme
Modern gaming-style interface.

### Light Theme
Clean and professional interface.

Themes can be switched at any time.

---

## 🔊 Sound Effects

The game includes sounds for:

- Button Click
- Winning a Round
- Draw Match
- Timeout

---

## 📊 Scoreboard System

Displays:

- Player X Score
- Player O Score
- Draw Count
- Current Round

---

## 🏅 Winner Highlight

When a player wins:

- Winning cells are highlighted in green.
- Winner notification is displayed.

---

## 📜 Scrollable Interface

The application uses a scrollable layout to ensure all controls remain accessible regardless of screen size.

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core Programming Language |
| Tkinter | GUI Development |
| OOP | Code Organization |
| Random Module | AI and Timer Logic |
| Math Module | Minimax Algorithm |
| Winsound | Sound Effects |

---

# 📚 OOP Concepts Used

## 1. Classes

### SoundManager Class

Responsible for:

- Click Sound
- Win Sound
- Draw Sound
- Error Sound

### TicTacToeApp Class

Responsible for:

- GUI
- Game Logic
- Match Handling
- Timer System
- AI Integration
- Scoreboard Management

---

## 2. Encapsulation

All game-related data is stored inside classes.

Examples:

```python
self.board
self.score_x
self.score_o
self.current
```

---

## 3. Abstraction

Complex operations are hidden behind functions.

Example:

```python
best_move_hard()
```

The user simply sees the computer making an intelligent move.

---

## 4. Modularity

The code is divided into independent modules:

- Sound Management
- AI Logic
- Game Logic
- Theme Management
- GUI Components

---

# 🧠 Artificial Intelligence

## Easy AI

Uses:

```python
random.choice()
```

Chooses any available cell randomly.

---

## Medium AI

Strategy:

1. Check for winning move.
2. Block opponent winning move.
3. Prefer center and corners.
4. Otherwise choose random move.

---

## Hard AI

Uses:

```python
Minimax Algorithm
```

The Minimax Algorithm:

- Explores all possible future game states.
- Maximizes AI score.
- Minimizes player score.
- Guarantees the best possible move.

Result:

✅ Impossible to beat.

---

# 🎨 Theme System

The project contains a predefined THEMES dictionary.

### Dark Theme

- Dark Background
- Neon Accent Colors
- Gaming Appearance

### Light Theme

- Light Background
- Professional Look
- Better Daytime Visibility

---

# ⏱ Timer System

Each player gets a limited amount of time.

Available values:

- 10 Seconds
- 15 Seconds
- 20 Seconds

If time reaches zero:

1. Timeout sound plays.
2. Random move is generated.
3. Game continues.

---

# 🏆 Match Flow

```text
Start Game
     ↓
Choose Settings
     ↓
Begin Round
     ↓
Player Move
     ↓
Check Winner
     ↓
Update Score
     ↓
Next Round
     ↓
Match Winner
```

---

# 📂 Project Structure

```text
Advanced_TicTacToe.py

│
├── SoundManager Class
│
├── Theme Dictionary
│
├── Game Logic Functions
│   ├── get_winner()
│   ├── is_draw()
│   ├── best_move_easy()
│   ├── best_move_medium()
│   ├── best_move_hard()
│   └── _minimax()
│
├── TicTacToeApp Class
│   ├── Menu Screen
│   ├── Game Screen
│   ├── Theme Handling
│   ├── Timer Handling
│   ├── Scoreboard
│   ├── Match Handling
│   └── Event Handling
│
└── Main Function
```

---

# ▶️ Installation

## Step 1

Install Python 3.

Verify installation:

```bash
python --version
```

---

## Step 2

Download or clone the project.

---

## Step 3

Open terminal in project directory.

Run:

```bash
python advanced_tictactoe.py
```

---

# 🎮 How To Play

1. Launch the application.
2. Enter player names.
3. Select game mode.
4. Choose AI difficulty.
5. Select match length.
6. Configure timer settings.
7. Click Start Game.
8. Take turns placing X and O.
9. Win rounds to win the match.

---

# 📸 User Interface

## Menu Screen

Contains:

- Game Mode Selection
- Player Name Entry
- AI Difficulty Selection
- Match Length Selection
- Timer Configuration
- Theme Toggle
- Sound Toggle
- Start Game Button

---

## Game Screen

Contains:

- Live Scoreboard
- Round Counter
- Turn Indicator
- Timer Display
- Game Board
- New Game Button
- Reset Match Button

---

# 🔮 Future Enhancements

Possible improvements:

- Online Multiplayer
- Database Integration
- User Accounts
- Leaderboard System
- Game Statistics
- Save and Load Games
- Network Multiplayer
- Machine Learning Based AI
- 4×4 and 5×5 Boards

---

# 🎯 Learning Outcomes

This project helped in understanding:

- Object-Oriented Programming
- GUI Design using Tkinter
- Event Driven Programming
- Artificial Intelligence
- Minimax Algorithm
- Software Design Principles
- Python Application Development

---

# 👨‍💻 Author

**Ananya **

B.Tech Student

Project:
**Advanced Tic Tac Toe Arena**

Developed using Python, Tkinter, OOP, and Minimax Algorithm.

---

# 📄 License

This project is developed for educational and learning purposes.

© 2026 Ananya . All Rights Reserved.
