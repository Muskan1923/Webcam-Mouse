# Webcam_mouse
# 🖐️ Webcam Mouse using Hand Gestures

This project allows you to control your computer mouse using hand gestures through your webcam.
It uses MediaPipe for real-time hand tracking, OpenCV for video capture and visualization, and PyAutoGUI & Pynput for controlling mouse actions such as movement, clicks, and screenshots.


# 🧠 Features

1.🖱️ Move Cursor — Move your index finger to control the mouse pointer.
2.👆 Left Click — Perform a left click using a specific hand gesture.
3.👉 Right Click — Perform a right click using a different gesture.
4.✌️ Double Click — Execute a double click gesture.
5.📸 Screenshot — Take a screenshot gesture and save it automatically.


# ⚙️ Requirements

Install the following dependencies before running the code:
      pip install opencv-python mediapipe pyautogui pynput


# 🖥️ How It Works

1.The webcam captures your hand in real time.
2.MediaPipe Hands detects hand landmarks (like fingertips, joints, etc.).
3.The program measures angles and distances between key landmarks to recognize gestures.
4.Depending on the detected gesture, it performs actions like mouse movement or clicks.

# 🧩 Gesture Mapping

| Gesture                        | Description  | Action              |
| ------------------------------ | ------------ | ------------------- |
| Index finger open, thumb close | Move mouse   | 🖱️ Cursor moves    |
| Index bent (<50°)              | Left Click   | 🖱️ Left click      |
| Middle bent (<50°)             | Right Click  | 🖱️ Right click     |
| Both index & middle bent       | Double Click | 👆 Double click     |
| Both fingers close together    | Screenshot   | 📸 Screenshot saved |


# 🧰 Usage

1.Clone or download the repository.
2.Make sure your webcam is connected.

Run the script:
      python main.py

# 🧾 Notes

1.Adjust gesture sensitivity in the angle/distance thresholds if detection feels inaccurate.
2.Lighting conditions affect detection performance.
3.Works best with a single hand in front of the camera.


# 🧑‍💻 Author
Muskan Jhala
📧 [jhalamuskan71@gmail.com]
💡 Project inspired by computer vision and gesture control experiments.


