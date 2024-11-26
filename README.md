~""Drowsiness and alcohol impairement detection system""~



This project aims to develop a system to monitor driver alertness and detect alcohol consumption in real-time. Using machine learning and computer vision techniques, the system tracks facial landmarks and hence traces driver behavior and provides alerts for potential drowsiness or alcohol impairment.

Features
Driver Drowsiness Detection and alcohol impairment detection: Monitors eye movements, facial expressions, and head position,analyzes gaze deviation, mouth aspect ratio (MAR)  to detect signs of drowsiness,alcohol consumption levels through facial analysis .
Real-time Alerts: Provides real-time warnings when dangerous driving behavior is detected and takes the snapshot if alcohol consumption is suspected and Saves the snapshot with a timestamp in a designated folder.

Installation
Prerequisites
Python 3.x
Required Python libraries (e.g., OpenCV, MediaPipe,scipy)
```bash
pip install opencv-python mediapipe scipy
```
procedure:
 step1: Run the program:
```powershell
streamlit run streamlit.py
```


step2:
```powershell
python snapshot.py
```
The system will start processing the webcam feed, detecting drowsiness and alcohol impairment.

Press 'q' to quit the application.

Alert System
Primary Alert: Played when the driver shows signs of drowsiness.
Secondary Alert: Played after several drowsy detections.
Alcohol Alert: Played when alcohol impairment is detected.
