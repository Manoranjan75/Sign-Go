# Real-Time Sign Language Detection

This project implements a real-time sign language detection system using **MediaPipe** for keypoint extraction and a **Long Short-Term Memory (LSTM)** neural network for classification.  
The system is designed to recognize a predefined set of sign language gestures from live video input.

---


## Project Overview
The goal of this project is to create a system that can detect sign language gestures in real-time.  
It leverages the power of **MediaPipe's Holistic model** to extract key facial, pose, and hand landmarks, which are then used as input to a trained **LSTM model** for classification.

---

## Features
- Real-time keypoint extraction using **MediaPipe Holistic**.  
- **LSTM model** for classifying sign language gestures.  
- Data collection pipeline for creating a custom dataset.  
- Training and evaluation of the LSTM model.  
- Real-time sign language detection with probability visualization.  

---

## Prerequisites
Before running this project, ensure you have the following installed:

- Python **3.7+**  
- **OpenCV**  
- **MediaPipe**  
- **TensorFlow**  
- **Scikit-learn**  
- **Matplotlib**  
- **NumPy**  
