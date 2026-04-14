♟️ Minimax-Based Chess AI Engine
A fully functional Chess game built using Python and Pygame, where a human player competes against an AI opponent powered by the Minimax Algorithm.

📖 Problem Statement
Design an intelligent Chess AI capable of:

Evaluating board states effectively
Predicting future opponent moves
Minimizing opponent advantage
Making optimal decisions within limited search depth

The challenge is to simulate strategic thinking in a deterministic, perfect-information game environment.

💡 Solution Approach
The AI uses the Minimax Algorithm, a recursive adversarial search technique.
Working Principle:

Generate all possible legal moves
Construct a game tree of future states
Evaluate each board position using a heuristic function
Choose the move that maximizes AI advantage and minimizes opponent gain

This simulates strategic foresight and intelligent decision-making.

🚀 Features

Complete chess rule implementation
AI opponent using Minimax with Alpha-Beta Pruning
Heuristic board evaluation
Interactive GUI with move highlighting
Real-time move validation
Castling, En Passant, and Pawn Promotion support
Clean Pygame-based interface


🛠️ Technologies Used

Python 3
Pygame
Object-Oriented Programming
Game Tree Search (Minimax + Alpha-Beta Pruning)


📂 Project Structure
Minimax-Based-Chess-AI-Engine/
│
├── ChessMain.py                    # Main game loop and UI
├── ChessEngine.py                  # Game logic and rules
├── ChessAI.py                      # Minimax AI implementation
├── ChessEngine_naive_algorithm.py  # Naive algorithm (reference)
├── images/                         # Chess piece images
└── README.md

⚙️ How to Run the Project
1️⃣ Clone the Repository
bashgit clone https://github.com/Ravipareek05/Minimax-Based-Chess-AI-Engine.git
cd Minimax-Based-Chess-AI-Engine
2️⃣ Install Dependencies
bashpip install pygame
3️⃣ Run the Game
bashpython3 ChessMain.py
The game window will open and you can start playing against the AI.

🎮 Controls
KeyActionZUndo last moveRReset the gameQSwitch to AI vs AI modeESwitch to Human vs AI mode

🎓 Educational Value
This project demonstrates:

Adversarial search algorithms
Heuristic evaluation design
Recursive decision-making
AI behavior in perfect-information games

These concepts extend to robotics planning, financial modeling, and strategic optimization systems.

🏆 Author
Ravi Pareek
B.Tech Computer Engineering
Thapar Institute of Engineering & Technology