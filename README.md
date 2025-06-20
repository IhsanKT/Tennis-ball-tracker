﻿# Tennis-ball-tracker
## Overview
This project focuses on analyzing tennis match videos to extract valuable performance metrics such as player speed, ball shot speed, and the total number of shots. The system uses advanced object detection and keypoint estimation techniques to track players and the ball in real time.

Leveraging the power of YOLO models and Convolutional Neural Networks (CNNs), the project not only detects tennis players and the ball but also identifies court keypoints for accurate localization and movement analysis. This is a comprehensive hands-on project designed to sharpen your skills in Machine Learning and Computer Vision.

## Sample Output
Here’s a snapshot from the processed output video:
![image](https://github.com/user-attachments/assets/a5e68762-e23c-41fd-a9eb-3a105fe834f6)

## Models Utilized

- **YOLOv8**: Used for real-time player detection.
- **Custom YOLO (fine-tuned)**: Trained specifically for high-precision **tennis ball detection**.
- **Court Keypoint Extraction CNN**: To identify reference points on the court for spatial awareness and tracking calibration.

---

## 🏋️‍♂️ Training Notebooks

- **YOLO-based Tennis Ball Detection**  
  `training/tennis_ball_detector_training.ipynb`

- **CNN-based Court Keypoint Detection (PyTorch)**  
  `training/tennis_court_keypoints_training.ipynb`

## ⚙️ Requirements

Make sure to have the following installed:

```bash
python==3.8
ultralytics
torch
opencv-python
pandas
numpy
