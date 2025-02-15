# Abnormal Behavior Detection Using LSTM

## Project Overview
This project focuses on detecting abnormal human behavior using a Long Short-Term Memory (LSTM) approach. It utilizes **MediaPipe for keypoint detection** and applies LSTM models to classify actions as **normal or abnormal** based on motion patterns.

## Objectives
- Understand **how to use LSTM for abnormal behavior detection**.
- Gain experience with **MediaPipe for keypoint extraction**.
- Learn **action recognition techniques** using deep learning.
- Experiment with **real-world data collection and annotation**.

## Dataset Information
- The dataset was **collected and labeled** by me and some of my friends.
- It consists of **two classes**:  
  - **Normal Behavior**
  - **Abnormal Behavior**
- Keypoint data was extracted from videos using **MediaPipe**.

## Methodology
1. **Keypoint Detection**:  
   - Extracts **pose landmarks** from video frames using **MediaPipe**.
   - Converts **keypoint sequences** into structured datasets.
   
2. **Feature Extraction & Preprocessing**:  
   - Normalizes keypoint coordinates.
   - Converts time-series data into input sequences for LSTM.

3. **Model Training & Evaluation**:  
   - Uses an **LSTM model** to analyze temporal patterns in movement.
   - Classifies actions as **normal or abnormal**.

## Technologies Used
- **MediaPipe** (for pose/keypoint detection)
- **TensorFlow/Keras** (for LSTM model implementation)
- **OpenCV** (for video processing)
- **Python & NumPy** (for data preprocessing)
- **Matplotlib** (for visualization)



*(Make sure to place these images inside a "screenshots" folder in your project directory.)*

## Key Learnings
- How to use **MediaPipe** for extracting **pose landmarks**.
- How **LSTM models** can be applied for **action recognition**.
- The process of **data collection and labeling** for behavior analysis.
- How to structure **time-series data** for deep learning models.

## Future Improvements
- Expand dataset with more diverse actions.
- Experiment with **Transformer-based** architectures for better accuracy.
- Improve real-time inference for deployment in **CCTV-based surveillance systems**.

---

Let me know if you need any modifications! 🚀  
