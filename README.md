<div align="center">

# 🐍 Snake Clash

**An arcade-style Snake game built with Python and Pygame**

[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pygame](https://img.shields.io/badge/Pygame-2.x-00B140?style=for-the-badge&logo=python&logoColor=white)](https://www.pygame.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Mac%20%7C%20Linux-lightgrey?style=for-the-badge)](https://github.com/)

*Guide your snake through the arena, hunt rare food, and beat the high score — one bite at a time.*

[Report Bug](https://github.com/yourusername/snake-clash/issues) · [Request Feature](https://github.com/yourusername/snake-clash/issues)

</div>

---

## 🎮 See It In Action

#### 🏠 Welcome Screen

<img width="1328" height="900" alt="Screenshot 2026-06-11 123217" src="https://github.com/user-attachments/assets/9259c8e3-a1f1-49d1-b6a0-79f03835e458" />

#### 🕹️ Gameplay

<img width="1329" height="900" alt="Screenshot 2026-06-11 123304" src="https://github.com/user-attachments/assets/7ee451cf-2991-4fd1-b530-278dfe1a074d" />


---

## ✨ Features

- 🟢 Classic Snake gameplay with a **smooth, arcade feel**
- 🍱 **Three food types** with unique effects and point values
- 💾 **Persistent high score** saved across sessions
- ⏸️ **Pause & resume** support mid-game
- 🔊 **Sound effects** for eating and game over
- 🎨 Snake skin **textured background** with rounded snake segments

---

## 🍱 Food Types

| Food | Color | Points | Effect |
|------|-------|:------:|--------|
| Normal Food | ⚫ Black | +10 | Snake grows |
| Bonus Food | 🔴 Red | +50 | Snake grows (rare spawn) |
| Slow Food | 🔵 Blue | +10 | Reduces game speed temporarily |

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `SPACE` | Start game |
| `↑ ↓ ← →` | Steer the snake |
| `P` | Pause / Resume |
| `ENTER` | Restart after game over |

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| Python 3.7+ | Core game logic & loop |
| Pygame 2.x | Rendering, input & audio |

---

## 📁 Project Structure

```
snake-clash/
├── snakes.py         # Main game script
├── snake_bg.jpg      # Background texture image
├── eat.mp3           # Eat sound effect
├── game_over.mp3     # Game over sound effect
└── hiscore.txt       # Auto-generated high score file
```

> `hiscore.txt` is created automatically on first run. The three asset files must sit in the same folder as `snakes.py`.

---

## ⚙️ Installation & Setup

### Prerequisites

- Python `3.7+`
- Pygame library

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/snake-clash.git
cd snake-clash
```

### 2️⃣ Install Dependencies

```bash
pip install pygame
```

### 3️⃣ Add Assets

Place the following files in the project root alongside `snakes.py`:

- `snake_bg.jpg` — background image
- `eat.mp3` — eating sound
- `game_over.mp3` — game over sound

### 4️⃣ Run the Game

```bash
python snakes.py
```

---

## 🧠 Game Logic

- The snake moves continuously in the last pressed direction
- Eating any food grows the snake by **5 segments**
- **Bonus Food** is rare — grab it fast for 50 points
- **Slow Food** drops the speed temporarily, giving breathing room
- Hitting a **wall** or your **own body** ends the game
- High score is saved to `hiscore.txt` and loaded on the next run

---

## ⭐ Support

If you enjoyed this project, consider giving it a **⭐ star** on GitHub!
