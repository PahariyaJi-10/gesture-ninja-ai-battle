# 🎮 Gesture Ninja: AI Battle 🤖

An interactive computer vision game inspired by Fruit Ninja, where players slice fruits using hand gestures — now enhanced with an intelligent AI opponent for competitive gameplay.

---

## 🚀 Features

* ✋ Real-time hand tracking using MediaPipe
* 🍎 Slice fruits using finger movement
* 💣 Avoid bombs (they reduce lives)
* 🤖 AI Opponent that competes with you
* ❤️ Life system (3 lives)
* 🔊 Sound effects using winsound
* 🎯 Real-time scoring system
* 🎮 Start / Restart controls
* 💥 Explosion effects on bomb hit

---

## 🧠 AI Opponent

* Tracks nearest fruit
* Moves dynamically toward targets
* Includes randomness for fair gameplay
* Competes against player score

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* NumPy
* Winsound

---

## 📁 Project Structure

gesture-ninja-ai-battle/
│
├── assets/        # fruit & bomb images
├── sounds/        # sound files (optional)
├── venv/          # virtual environment
├── main.py        # main game file
└── README.md

---

## ⚙️ Installation

```bash
git clone https://github.com/PahariyaJi-10/gesture-ninja-ai-battle.git
cd gesture-ninja-ai-battle
```

### 🧪 Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 📦 Install Dependencies

```bash
pip install opencv-python mediapipe numpy
```

---

## ▶️ Run the Game

```bash
python main.py
```

---

## 🎮 Controls

| Key | Action     |
| --- | ---------- |
| S   | Start Game |
| R   | Restart    |
| ESC | Exit       |

---

## 🧩 How It Works

1. Camera detects hand using MediaPipe
2. Index finger acts as blade
3. Speed + distance determines slicing
4. Apples increase score
5. Bombs reduce lives
6. AI competes by auto-slicing fruits

---

## 📌 Future Improvements

* 🔥 Combo system
* ⏱ Timer mode
* 🧑‍🤝‍🧑 Multiplayer
* 🎨 UI improvements
* 📊 Leaderboard

---

## 👨‍💻 Author
Divyansh Pahariya

---
