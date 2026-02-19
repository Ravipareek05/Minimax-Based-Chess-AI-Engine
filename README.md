# ♟️ Minimax-Based Chess AI Engine

A fully functional Chess game built using **Python** and **Pygame**, where a human player competes against an AI opponent powered by the **Minimax Algorithm**.

---

## 📖 Problem Statement

Design an intelligent Chess AI capable of:

- Evaluating board states effectively  
- Predicting future opponent moves  
- Minimizing opponent advantage  
- Making optimal decisions within limited search depth  

The challenge is to simulate strategic thinking in a deterministic, perfect-information game environment.

---

## 💡 Solution Approach

The AI uses the **Minimax Algorithm**, a recursive adversarial search technique.

### Working Principle:

1. Generate all possible legal moves  
2. Construct a game tree of future states  
3. Evaluate each board position using a heuristic function  
4. Choose the move that maximizes AI advantage and minimizes opponent gain  

This simulates strategic foresight and intelligent decision-making.

---

## 🚀 Features

- Complete chess rule implementation  
- AI opponent using Minimax  
- Heuristic board evaluation  
- Interactive drag-and-drop GUI  
- Real-time move validation  
- Clean Pygame-based interface  

---

## 🛠️ Technologies Used

- Python 3  
- Pygame  
- Object-Oriented Programming  
- Game Tree Search  

---

## 📂 Project Structure

```
Minimax-Based-Chess-AI-Engine/
│
├── ChessMain.py      # Main game loop and UI
├── ChessEngine.py    # Game logic and rules
├── ChienKoNgu.py     # Minimax AI implementation
├── images/           # Chess piece images
└── README.md
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ravipareek05/Minimax-Based-Chess-AI-Engine.git
cd Minimax-Based-Chess-AI-Engine
```

### 2️⃣ Install Dependencies

```bash
pip install pygame
```

### 3️⃣ Run the Game

```bash
python3 ChessMain.py
```

The game window will open and you can start playing against the AI.

---

## 🎓 Educational Value

This project demonstrates:

- Adversarial search algorithms  
- Heuristic evaluation design  
- Recursive decision-making  
- AI behavior in perfect-information games  

These concepts extend to robotics planning, financial modeling, and strategic optimization systems.

---

## 🏆 Author

Ravi Pareek  
B.Tech Computer Engineering  
Thapar Institute of Engineering & Technology  
