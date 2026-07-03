# curl_counter
counts curl
# 💪 AI Bicep Curl Counter

## Overview

AI Bicep Curl Counter is a computer vision project that detects and counts bicep curl repetitions in real time using a webcam. It uses MediaPipe Pose Estimation to track body landmarks and calculates the elbow angle to determine whether a complete curl has been performed.

---

## Features

* 🎥 Real-time webcam detection
* 💪 Automatic bicep curl repetition counting
* 📐 Elbow angle calculation
* 📊 Live repetition counter displayed on screen
* ⚡ Built using Python, OpenCV, and MediaPipe

---

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy

---

## Project Structure

```text
curl-counter/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/curl_counter.git
```

2. Move into the project directory

```bash
cd curl_counter
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

4. Run the project

```bash
python app.py
```

---

## How It Works

1. Opens the webcam.
2. Detects body landmarks using MediaPipe Pose.
3. Calculates the angle between the shoulder, elbow, and wrist.
4. Counts one repetition when a complete curl movement is detected.
5. Displays the current repetition count on the screen.

---

## Future Improvements

* Add voice feedback
* Support multiple exercises
* Workout history
* Calorie estimation
* Mobile application integration

---

## Author

**Manya Agrawal**

