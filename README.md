# Airborn_optical_character_recognization
A computer vision application that enables users to write and draw characters in the air using hand gestures. The system tracks hand movements through a webcam and converts them into digital drawings in real time using MediaPipe and OpenCV.

## 🚀 Features
* Real-time hand and finger tracking
* Draw letters, shapes, and symbols in the air
* Gesture-based color switching
* Virtual eraser functionality
* Live webcam interaction
* No physical mouse, pen, or touch device required

## 🛠️ Tech Stack
* Python
* OpenCV
* MediaPipe
* NumPy

## 🎮 Gestures

**Index Finger Up** → Draw on virtual canvas
**All Fingers Up** → Erase drawing
**Thumb + Index Pinch** → Change brush color
**C Key** → Clear canvas
**Q Key** → Quit application

## ▶️ Run Project

```bash
pip install opencv-python mediapipe numpy
python main.py
```

## 💡 How It Works
1. Captures video through webcam.
2. Detects hand landmarks using MediaPipe.
3. Tracks index finger movement.
4. Converts finger motion into drawing strokes.
5. Supports color switching and erasing through hand gestures.
6. Displays drawings on a virtual canvas in real time.

## 📸 Output
* Hand landmark detection
* Air writing of letters and symbols
* Dynamic color changes using gestures
* Gesture-based erasing

## 🔮 Future Enhancements
* Save drawings as images
* Handwritten character recognition
* Multi-user support
* Shape and gesture shortcuts

## 📜 License
Educational and learning purpose project.
