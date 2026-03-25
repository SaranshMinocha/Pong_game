# 🏓 Pong Game

A classic two-player Pong game built with **Python** and **Turtle Graphics**, featuring object-oriented design and progressive difficulty.

---

## 📁 Project Structure

```
pong/
│
├── main.py          # Game loop, window setup, event bindings
├── ball.py          # Ball class – movement, collision, speed scaling
├── paddle.py        # Paddle class – player-controlled movement
└── scoreboard.py    # Scoreboard class – score tracking and display
```

---

## 🎮 Gameplay

- **2 players** compete on the same keyboard
- Each player controls a paddle to deflect the ball
- The ball **speeds up after every hit** — the longer the rally, the more intense it gets
- First player to miss concedes a point

---

## 🕹️ Controls

| Player | Move Up | Move Down |
|--------|---------|-----------|
| Player 1 (Left) | `W` | `S` |
| Player 2 (Right) | `↑` | `↓` |

---

## ⚙️ Features

- **Progressive speed** — ball accelerates with each paddle hit using the `time` library
- **Score tracking** — live scoreboard displayed on screen
- **OOP architecture** — clean separation of concerns across 4 classes
- **Collision detection** — wall and paddle bounce logic

---

## 🚀 How to Run

**Requirements:** Python 3.x (Turtle is built into the standard library — no installs needed)

```bash
python main.py
```

---

## 🛠️ Built With

- Python 3
- `turtle` — graphics and game rendering
- `time` — ball speed progression

---

## 💡 How It Works

| Class | Responsibility |
|-------|----------------|
| `Ball` | Handles movement direction, bouncing off walls/paddles, and speed increase on each hit |
| `Paddle` | Manages paddle position and responds to keyboard input |
| `Scoreboard` | Tracks and renders the score for both players |
| `main.py` | Sets up the screen, binds keys, runs the game loop |
