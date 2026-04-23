# Real-Time Emotion Risk Screening System (YOLOv8)

## Overview
This project is a real-time facial emotion detection system using YOLOv8 and OpenCV.

It detects emotions from webcam video and calculates a simple risk score based on emotion trends.

## Features
- Real-time webcam emotion detection
- YOLOv8 custom-trained model
- GPU acceleration (CUDA)
- Emotion trend scoring
- Excel logging
- Visualization support

## Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- PyTorch
- Pandas

## Demo
![Demo](demo_screenshot.png)

## How to Run

1. Install dependencies:
```bash
pip install ultralytics opencv-python pandas openpyxl matplotlib
Open Webcam detection.ipynb
Update the model path to your trained YOLOv8 weights
Run all cells to start webcam emotion detection
```markdown
## Notes
This project is a prototype system for emotion-based risk screening and is not intended as a medical diagnosis tool.
