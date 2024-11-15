# Anomaly Detection in Video Streams

## Overview

This project implements an anomaly detection system for video streams, utilizing a combination of Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM) models, and Diffusion Models. The goal is to identify abnormal events or activities in videos, providing an automated solution for real-time anomaly detection.

## Key Features

- **Video Frame Extraction:** Extracts frames from a video and resizes them for further analysis.
- **Diffusion Model for Frame Reconstruction:** Uses a diffusion model to reconstruct frames and calculates reconstruction errors to help identify anomalies.
- **CNN + LSTM Architecture:** Combines CNNs for spatial feature extraction and LSTMs for sequential temporal analysis to detect anomalies across video frames.
- **Binary Classification:** Classifies videos as either normal or anomalous based on the model’s predictions.
  
## Technologies Used

- **Python**
- **TensorFlow (Keras)**
- **OpenCV**
- **NumPy**
- **Matplotlib**
  

## Usage

### Step 1: Prepare the Video
Make sure you have a video file ready for anomaly detection. The system will extract frames from the video and process them.

### Step 2: Frame Extraction
Run the script to extract frames from your video.

