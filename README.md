This project aims to develop a system to monitor driver alertness and detect alcohol consumption in real-time. Using machine learning and computer vision techniques, the system tracks driver behavior and provides alerts for potential drowsiness or alcohol impairment.

Features
Driver Drowsiness Detection and alcohol impairment detection: Monitors eye movements, facial expressions, and head position to detect signs of drowsiness,alcohol consumption levels through facial analysis .
Real-time Alerts: Provides real-time warnings when dangerous driving behavior is detected and takes the snapshot if alcohol consumption is detected
Installation
Prerequisites
Python 3.x
Required Python libraries (e.g., OpenCV, MediaPipe, TensorFlow)
Hardware: Camera (for capturing driver behavior), Alcohol detection sensor (optional)
Step 1: Clone the Repository
bash
Copy code
git clone https://github.com/Sejaldahal/Drowsiness-and-alcohol-detction-system.git
cd Drowsiness-and-alcohol-detction-system
Step 2: Install Dependencies
Install the required dependencies using pip:

bash
Copy code
pip install -r requirements.txt
Step 3: Set Up the Submodule (if applicable)
If your project includes submodules, initialize them:

bash
Copy code
git submodule update --init --recursive
Usage
Run the main Python script to start the driver monitoring system:
bash
Copy code
python main.py
Contributing
If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to your forked repository (git push origin feature/your-feature-name).
Create a pull request to the main repository.

