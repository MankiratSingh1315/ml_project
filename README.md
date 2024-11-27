# Real-Time Emotion Recognition System

## Introduction
This project aims to develop a **Real-Time Emotion Recognition System** capable of detecting and categorizing multiple emotions simultaneously from live video data. The system has wide-ranging applications in **healthcare**, **psychology**, **law enforcement**, and **customer behavior analysis**.

## Features
- **Real-Time Emotion Detection:** Analyzes video frames to identify emotional states.
- **Multi-Emotion Representation:** Detects multiple emotions concurrently in real-time.
- **Overtime Metrics:** Tracks emotions over time for trend analysis in environments like shopping malls.

## Problem Statement
Current systems are limited to identifying a single dominant emotion and struggle with real-time efficiency, environmental variability, and overlapping emotions. This project aims to address these challenges by:
1. Detecting multiple emotions concurrently.
2. Displaying emotions intuitively on video feeds.
3. Ensuring robust performance across diverse conditions.

## Dataset
- **Name:** CK+ (Cohn-Kanade Extended)  
- **Categories:** Angry, Disgust, Fear, Happy, Sad, Surprise, and Contempt  
- **Size:** 981 image sequences from 123 subjects  
- **Advantages:**  
  - High-quality, labeled images for accurate training.  
  - Temporal sequences to aid in real-time emotion detection.

## Workflow
### Libraries and Tools
- **TensorFlow**, **Keras**: Neural network model development  
- **OpenCV**: Real-time video capture and processing  
- **Pandas**, **Matplotlib**: Data visualization and analysis  
- **Scikit-learn**: Data preprocessing and evaluation  

### Model Architecture
- **Base Model:** Convolutional Neural Network (CNN)  
- **Key Layers:**  
  - Convolutional layers for feature extraction  
  - Dense layers for emotion classification  
  - Softmax activation for output probabilities  

### Implementation Steps
1. **Data Preprocessing:** Convert frames to grayscale, resize, normalize.  
2. **Model Training:** Train on CK+ dataset with data augmentation techniques.  
3. **Real-Time Processing:** Detect and classify emotions on live video feeds.

### Evaluation Metrics
- **Accuracy:** Percentage of correct classifications.  
- **Precision & Recall:** Measure balance between false positives and negatives.  
- **Efficiency:** Real-time performance without lag.

## Results
The system accurately detects seven emotions (Surprise, Fear, Sad, Disgust, Contempt, Happy, Angry) with confidence scores. Performance is validated through accuracy, precision, and real-time testing.

## Future Scope
Enhancements may include:
- Incorporating additional datasets for better generalization.
- Extending to audio-visual emotion recognition.

---
For more information, refer to the [full project documentation](https://docs.google.com/document/d/1jYTd3KCe-QZJcUyXkPg87sTf2-1CMEJQwJ5c_USx-B4/edit?usp=sharing).
