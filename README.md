# Fine-Grained Sport Action Recognition with CNNs

## Overview
This project explains how convolutional neural networks (CNNs) can be used for video-based sports action recognition. The focus is on classifying table tennis strokes using a twin spatio-temporal CNN architecture.

## Key Idea
The model uses two input streams:
- RGB frames (appearance information)
- Optical flow (motion information)

These streams are combined before classification.

## Dataset
TTStroke-21 dataset  
129 videos  
675k frames  
120 FPS  
17 players

## Results
The twin CNN architecture achieved **91.4% classification accuracy**.

## Topics Covered
- CNN fundamentals
- 3D convolutions for video
- Spatio-temporal feature learning
- Confusion matrix evaluation
- Ethical issues in AI systems

## Files
Presentation-CNN.pdf
