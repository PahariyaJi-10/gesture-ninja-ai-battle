🎮 Gesture Ninja: AI Battle 🤖
An interactive computer vision game inspired by Fruit Ninja, where players slice fruits using hand gestures — now enhanced with an intelligent AI opponent for competitive gameplay.

🚀 Features
✋ Real-time hand tracking using MediaPipe
🍎 Slice fruits using finger movement
💣 Avoid bombs (they reduce lives)
🤖 AI Opponent that competes with you
❤️ Life system (3 lives)
🔊 Sound effects using winsound
🎯 Real-time scoring system
🎮 Start / Restart controls
💥 Explosion effects on bomb hit
🧠 AI Opponent
Tracks nearest fruit
Moves dynamically toward targets
Includes randomness for fair gameplay
Competes against player score
🛠️ Tech Stack
Python
OpenCV
MediaPipe
NumPy
Winsound
📁 Project Structure
gesture-ninja-ai-battle/ │ ├── assets/ # fruit & bomb images ├── sounds/ # sound files (optional) ├── venv/ # virtual environment ├── main.py # main game file └── README.md

⚙️ Installation
git clone https://github.com/PahariyaJi-10/gesture-ninja-ai-battle.git
cd gesture-ninja-ai-battle
🧪 Create Virtual Environment
python -m venv venv
venv\Scripts\activate
📦 Install Dependencies
pip install opencv-python mediapipe numpy
▶️ Run the Game
python main.py
🎮 Controls
Key	Action
S	Start Game
R	Restart
ESC	Exit
🧩 How It Works
Camera detects hand using MediaPipe
Index finger acts as blade
Speed + distance determines slicing
Apples increase score
Bombs reduce lives
AI competes by auto-slicing fruits
📌 Future Improvements
🔥 Combo system
⏱ Timer mode
🧑‍🤝‍🧑 Multiplayer
🎨 UI improvements
📊 Leaderboard
👨‍💻 Author
Divyansh Pahariya

