# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. This hands-on project is perfect for polishing your machine learning and computer vision skills.

## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)

## Models Used
* YOLO v8 for player detection
* Fine-tuned YOLO for tennis ball detection
* Court keypoint extraction

* Trained YOLOv5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court keypoint model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

## Training
* Tennis ball detector with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoints with PyTorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python 3.8
* ultralytics
* pytorch
* pandas
* numpy
* opencv
