# ♟️ Minimax-Based Chess AI Engine

A fully functional Chess Game built using **Python** and **Pygame**, where a human player competes against an AI opponent powered by the **Minimax Algorithm**.

This project demonstrates adversarial search, heuristic evaluation, and decision-making in deterministic, perfect-information environments.

---

## 📖 Problem Statement

Traditional chess engines require intelligent decision-making to simulate human-like strategic thinking. The challenge is to design an AI that:

- Evaluates board states effectively
- Predicts future moves
- Minimizes opponent advantage
- Makes optimal decisions within limited computation depth

The goal of this project is to implement a functional Chess AI capable of strategic gameplay using classical game theory algorithms.

---

## 💡 Solution Approach

The AI is implemented using the **Minimax Algorithm**, a recursive adversarial search strategy.

### How it works:

1. Generate all possible legal moves
2. Simulate future board states (Game Tree)
3. Evaluate positions using a heuristic function
4. Choose the move that:
   - Maximizes AI advantage
   - Minimizes opponent gain

This simulates strategic foresight.

---

## 🧠 AI Logic

- Minimax Algorithm
- Depth-limited search
- Heuristic board evaluation
- Turn-based adversarial reasoning

The evaluation function considers:

- Material advantage
- Piece positioning
- Board control

---

## 🚀 Features

- ♟️ Complete chess rule implementation
- 🧠 AI opponent using Minimax
- 🎯 Heuristic board evaluation
- 🖱️ Interactive drag-and-drop GUI
- 🔄 Real-time move validation
- 🎨 Clean Pygame-based interface

---

## 🛠️ Technologies Used

- Python 3
- Pygame
- Object-Oriented Programming
- Game Tree Search

---

## 📂 Project Structure
Minimax-Based-Chess-AI-Engine/
│
├── ChessMain.py          # Main game loop and UI
├── ChessEngine.py        # Game logic and rules
├── ChienKoNgu.py         # Minimax AI implementation
├── images/               # Chess piece images
└── README.md

2️⃣ Install Dependencies
pip install pygame

3️⃣ Run the Game
python3 ChessMain.py
