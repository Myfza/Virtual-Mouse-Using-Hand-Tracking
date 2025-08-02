# Virtual Mouse Using Hand Tracking

## Overview
This Python script utilizes OpenCV, MediaPipe, and PyAutoGUI to implement a virtual mouse that tracks hand movements via a webcam. It enables cursor movement and clicking using hand gestures.

🎥 [Preview Video](preview.mp4)

## Features
- Tracks hand movements in real-time using a webcam.
- Moves the cursor based on the index finger's position.
- Clicks when the thumb and index finger come close together.
- Uses OpenCV for video processing and MediaPipe for hand tracking.

## Prerequisites
- Python 3.x installed on your system.
- Required Python libraries:
  - `opencv-python`
  - `mediapipe`
  - `pyautogui`

## Installation
1. Ensure Python is installed by running:
   ```sh
   python --version
   ```
2. Install dependencies using:
   ```sh
   pip install opencv-python mediapipe pyautogui
   ```

## Usage
1. Run the script:
   ```sh
   python script.py
   ```
2. Ensure your webcam is on and positioned properly.
3. Move your index finger to control the cursor.
4. Bring your thumb close to your index finger to simulate a mouse click.
5. Adjust the sensitivity if needed by modifying the script.

## Instructions
1. Download or copy the script to your local system.
2. Ensure all dependencies are installed.
3. Open a command prompt or terminal.
4. Navigate to the script’s directory using:
   ```sh
   cd path/to/your/script
   ```
5. Run the script:
   ```sh
   python script.py
   ```
6. Move your hand in front of the webcam to control the cursor.
7. To click, bring your thumb and index finger close together.

## Script Explanation
- **Captures video feed using OpenCV.**
- **Processes frames using MediaPipe to detect hand landmarks.**
- **Moves the mouse based on the index finger’s position.**
- **Performs a click when the thumb and index finger are close together.**

## Example Output
```
Virtual Mouse Activated
Cursor Moving...
Click Detected!
```

## Notes
- Ensure your hand is visible to the webcam for optimal tracking.
- Adjust sensitivity by modifying the threshold values in the script.
- Works best in well-lit environments.

## 🤝 Contributions

Pull requests are welcome! Feel free to fork and help improve this project!

## 🧑‍💻 Developer

Made by **Muhammad Yusuf Aditiya (Myfza)**  
🔗 [GitHub](https://github.com/Myfza) | [LinkedIn](https://www.linkedin.com/in/myfza)

