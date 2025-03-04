# RealEmote - Realtime Facial Emotion Detection

## Overview
RealEmote is a real-time facial emotion detection system using Python, OpenCV, and DeepFace/FER. It detects emotions from live video feed or images and displays results in real-time.

## Features
- Real-time emotion detection using OpenCV and FER
- Supports multiple emotions: Happy, Sad, Angry, Surprised, Neutral, etc.
- Works with live webcam feed and image input
- Uses Deep Learning models for high accuracy

## Installation
### 1. Clone the Repository
```sh
 git clone https://github.com/akshanshthakur2/RealEmote.git
 cd RealEmote
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
 python -m venv .venv
 source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
 pip install -r requirements.txt
```

### 4. Run the Application
```sh
 python emotion_detection.py
```

## Troubleshooting
### Module Not Found Errors
If you encounter missing modules, try reinstalling them manually:
```sh
 pip install opencv-contrib-python moviepy tensorflow numpy
```
If `cv2` is not found, ensure OpenCV is installed correctly.

### DeepFace or FER Issues
If `DeepFace` or `FER` fails, reinstall with:
```sh
 pip install deepface fer
```

## Contributing
Feel free to fork and contribute to this project. Open a PR with your changes!

## License
MIT License

