# TrafficViolationDetector 

**TrafficViolationDetector** is a real-time vehicle speed detection system that identifies and flags traffic violations using computer vision and object tracking.  
This project leverages **OpenCV**, **dlib**, and **Haar cascade classifiers** to detect moving vehicles, track their positions across frames, calculate their speeds, and highlight those exceeding a predefined speed limit.  

---

## Features  
- **Real-time vehicle detection** using a custom-trained Haar cascade model  
- **Object tracking** with **dlib correlation tracking** to monitor vehicles across frames  
- **Speed calculation** based on pixel movement and frame rate  
- **Violation detection** and alerting for speeding vehicles  
- **Video output** with annotated speed readings and violations  

---

## Technologies Used  
- **Python** 
- **OpenCV** (for image processing and vehicle detection)  
- **dlib** (for correlation tracking)  
- **Matplotlib** (for visualization)  

---

## How It Works  

1️⃣ The script processes a traffic video, detecting vehicles frame-by-frame.  
2️⃣ Each detected vehicle is assigned a **tracker** to monitor its movement.  
3️⃣ The **speed** of each vehicle is calculated based on pixel displacement and frame rate.  
4️⃣ Vehicles exceeding the speed limit are **marked as violators** with a red bounding box.  
5️⃣ A summary of detected cars and total violations is displayed on the output video.  

---

## Installation & Usage  

## **Install Dependencies**  
```bash
pip install opencv-python dlib matplotlib

python traffic_violation_detector.py
```

## **Demo**
<img width="561" alt="Screenshot 2025-04-01 at 1 43 24 PM" src="https://github.com/user-attachments/assets/22fe132f-08cf-419f-a441-b5f5bdd30a0f" />

Speeding vehicles are highlighted with a red bounding box and normal vehicles (within the speed limit) are marked with a green bounding box.


## License
This project is licensed under the **MIT** License.
