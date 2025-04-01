TrafficViolationDetector 🚗💨🚨
TrafficViolationDetector is a real-time vehicle speed detection system that identifies and flags traffic violations using computer vision and object tracking. This project leverages OpenCV, dlib, and Haar cascade classifiers to detect moving vehicles, track their positions across frames, calculate their speeds, and highlight those exceeding a predefined speed limit.

🔥 Features
✅ Real-time vehicle detection using a custom-trained Haar cascade model
✅ Object tracking with dlib correlation tracking to monitor vehicles across frames
✅ Speed calculation based on pixel movement and frame rate
✅ Violation detection and alerting for speeding vehicles
✅ Video output with annotated speed readings and violations

🛠️ Technologies Used
Python

OpenCV (for image processing and vehicle detection)

dlib (for correlation tracking)

Matplotlib (for visualization)

🚀 How It Works
The script processes a traffic video, detecting vehicles frame-by-frame.

Each detected vehicle is assigned a tracker to monitor its movement.

The speed of each vehicle is calculated based on pixel displacement and frame rate.

Vehicles exceeding the speed limit are marked as violators with a red bounding box.

A summary of detected cars and total violations is displayed on the output video.