# Autonomous-Obstacle-Avoidance-Drone
This project implements an autonomous navigation system using the DJI Tello drone. The drone uses onboard sensors and a downward-facing camera to maintain height, avoid obstacles, and perform precision landing using computer vision.
⚙️ Features
📏 Altitude Control
Maintains a target height by detecting distance from the ground.
🚧 Obstacle Avoidance
Automatically:
Moves forward
Turns 90° right when obstacle is detected
Adjusts height to avoid collision
🎯 Precision Landing (Computer Vision)
Uses a mask detection system (Flask + OpenCV) to:
Detect landing pad
Validate landing conditions
Execute safe landing
