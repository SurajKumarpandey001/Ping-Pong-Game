# 🕹️ Hand Gesture Controlled Ping Pong Game

A fun and interactive ping pong game controlled entirely using your hands, built with **OpenCV**, **cvzone**, and **MediaPipe**. Play against yourself or a friend — no keyboard or mouse needed!

## 🎮 How It Works

- Your webcam detects your **left and right hands**.
- Bats are controlled by moving your hands up and down.
- The ball bounces across the screen — block it with your virtual bat to score points.
- If the ball crosses either player's boundary, the game is over.

## ✨ Features

- Real-time hand tracking with cvzone
- Gesture-based gameplay
- Score tracking for both players
- Game Over screen
- Option to restart the game with a key press (`r`)

## 🛠️ Technologies Used

- Python
- OpenCV
- cvzone
- MediaPipe
- NumPy

## 🖼️ Gameplay Preview

> 📸 Add screenshots or a short gameplay GIF here to make your README pop!

## 📁 Folder Structure
project-folder/ │ ├── Resources/ │ ├── Background.png │ ├── gameOver.png │ ├── Ball.png │ ├── bat1.png │ └── bat2.png ├── main.py └── README.md



## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/SurajKumarpandey001/Ping-Pong-Game
cd hand-gesture-ping-pong

2. Install Dependencies
Make sure you have Python installed. Then install the required libraries:
pip install opencv-python cvzone numpy
✅ Note: cvzone internally uses mediapipe for hand detection.

3. Run the Game
python main.py

4. Controls
Move your left hand to control the left bat.
Move your right hand to control the right bat.
Press r to restart the game after "Game Over".

📌 Notes
For best performance, ensure your camera is facing you with good lighting.
Adjust your camera resolution or hand detection confidence if needed.

👨‍💻 Author
Suraj Kumar


---

Let me know if you'd like to include a GIF or YouTube video link of your gameplay demo — that makes a big difference on GitHub. Also, I can add license and `.gitignore` files if needed!
