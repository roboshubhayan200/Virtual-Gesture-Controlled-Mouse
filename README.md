🖱️ Gesture Controlled Mouse Using Hand Tracking

📌 Overview

The Gesture Controlled Mouse project allows you to control your computer’s cursor and click operations using hand gestures, without touching a physical mouse.
Built with Python, OpenCV, MediaPipe, and CVZone, this project uses real-time hand-tracking through your webcam to interpret gestures for cursor movement, clicks, and actions — making it an interactive and futuristic way to interact with your system.

🚀 Features

✅ Real-time Hand Tracking using OpenCV and MediaPipe
✅ Cursor Movement based on the index finger position
✅ Left and Right Clicks using hand gestures (index + middle finger)
✅ Smooth and Accurate Cursor Control with gesture smoothing
✅ Lightweight & Fast – works on most systems with a standard webcam
✅ Modular Codebase – easy to extend for gesture keyboard or volume control

🧠 Tech Stack

Python 3.8+

OpenCV – for camera input and image processing

MediaPipe – for hand landmark detection

CVZone – simplifies interaction with MediaPipe

AutoPy – to control mouse actions

NumPy – for coordinate and distance calculations

📂 Project Structure
Gesture-Controlled-Mouse/
│
├── main.py                # Main program file
├── requirements.txt       # Project dependencies
├── README.md              # Documentation

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/<your-username>/Gesture-Controlled-Mouse.git
cd Gesture-Controlled-Mouse

2️⃣ Install all dependencies
pip install -r requirements.txt

3️⃣ Run the project
python main.py

🖐️ How to Use

Run the script — your webcam window will open.

Show your hand in front of the camera.

Move the cursor using your index finger (landmark 8).

Perform a click by bringing your index and middle finger tips together.

Keep your hand steady to ensure smoother control.

🧩 Core Logic Summary

The index finger tip (ID 8) controls the cursor position.

The distance between index (ID 8) and middle (ID 12) determines click actions.

Uses cvzone.HandTrackingModule to get real-time landmark positions.

The AutoPy library performs system-level mouse actions.

🎥 Demo

https://github.com//Gesture-Controlled-Mouse
(Check out my video of this project in my linkedin profile provided below..)

👨‍💻 Author

Shubhayan Dutta
🎓 Engineering Student | AI & Cloud Computing | Robotics & Quantum Enthusiast
🌐 www.linkedin.com/in/shubhayan-dutta

🪄 Acknowledgements

MediaPipe
 – for robust hand tracking

CVZone
 – simplified OpenCV utilities

AutoPy
 – for seamless OS-level mouse control
