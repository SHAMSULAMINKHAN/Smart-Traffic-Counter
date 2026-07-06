# Smart-Traffic-Counter

## Overview

Smart Traffic Counter is a university project that uses computer vision and deep learning to automatically detect and count vehicles from CCTV footage. The system analyzes video streams, detects vehicles using YOLOv11, and counts the number of vehicles crossing predefined counting lines to estimate traffic flow.

The project aims to support intelligent traffic management by providing real-time vehicle counting and visual traffic statistics through an interactive dashboard.

---

## Project Objectives

* Detect vehicles from CCTV video.
* Count vehicles crossing predefined counting lines.
* Display the number of vehicles passing each line.
* Display the total number of vehicles detected.
* Provide a real-time visualization of traffic flow.
* Demonstrate the application of computer vision in intelligent transportation systems.

---

## Features

* Real-time vehicle detection using **YOLOv11**
* Support for CCTV video input
* Configurable counting lines
* Per-line vehicle counting
* Total vehicle count
* Live video visualization
* Dashboard displaying traffic statistics
* Modular Python implementation for future extensions

---

## Input

The system accepts video input from CCTV cameras. Video files can be processed to detect and count vehicles moving through the monitored area.

---

## Output

The system provides a dashboard that includes:

* Live video with vehicle detections
* Vehicle count for each predefined counting line
* Total number of vehicles that have passed
* Real-time traffic monitoring information

---

## Technology Stack

* **Programming Language**

  * Python

* **Deep Learning**

  * YOLOv11
  * PyTorch

* **Libraries**

  * Ultralytics
  * OpenCV
  * NumPy
  * Matplotlib

---

## System Workflow

```text
CCTV Video
      │
      ▼
Frame Extraction
      │
      ▼
Vehicle Detection (YOLOv11)
      │
      ▼
Vehicle Tracking
      │
      ▼
Line Crossing Detection
      │
      ▼
Vehicle Counting
      │
      ▼
Traffic Dashboard
```

---

## Dashboard

The dashboard displays:

* Live processed video
* Vehicle detection results
* Count for each counting line
* Total number of vehicles detected
* Real-time traffic monitoring information

---

## Project Structure

```text
smart-traffic-counter/
│
├── data/
├── models/
├── src/
├── scripts/
├── outputs/
├── docs/
├── assets/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Applications

* Intelligent Traffic Management
* Traffic Flow Analysis
* Smart City Monitoring
* Transportation Research
* Academic Computer Vision Projects

---

## Future Improvements

* Vehicle classification
* Speed estimation
* Traffic density analysis
* Multi-camera support
* Traffic congestion detection
* Automatic report generation
* Cloud deployment
* Web-based monitoring dashboard

---

## Author

This project was developed as part of a university project to demonstrate the use of computer vision and deep learning techniques for intelligent traffic management.
