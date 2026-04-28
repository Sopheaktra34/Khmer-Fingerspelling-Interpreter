# Khmer Fingerspelling Interpreter 🤚🇰🇭

## 📌 Project Overview

The **Khmer Fingerspelling Interpreter** is a real‑time hand gesture recognition system that translates **Khmer fingerspelling consonants** into text.  
This project is developed to help **bridge the communication gap between deaf individuals and non‑signers in Cambodia** using Machine Learning and Deep Learning techniques.

***

## 🎯 Project Objectives

*   Develop a **real-time Khmer fingerspelling recognition system**
*   Recognize **33 Khmer consonant hand signs**
*   Provide a practical tool to support accessibility and inclusion
*   Contribute resources for **Khmer Sign Language (KSL)** research

***

## ✋ Fingerspelling Actions

*   This project focuses on **33 Khmer consonant fingerspelling gestures**
*   Each consonant is treated as **one action (class)**
*   Fingerspelling is mainly used for:
    *   Names
    *   Places
    *   Technical or uncommon words without standard signs

📂 **Detailed descriptions of each action and class labeling are available in the Google Drive link below.**

***

## 📦 Dataset Description

### 📸 Data Collection

*   Dataset obtained from previous researchers: **7,862 images**
*   Images collected by our team using **DroidCam**: **23,700 images**
*   **Total collected images:** 31,562

### 🧹 Data Cleaning

To improve dataset quality, we removed:

*   Blurry images
*   Images without visible hands
*   Duplicate images

✅ **Final cleaned dataset:** **13,945 images** across 33 consonant classes

### 🔍 Preprocessing

*   Hand landmarks extracted using **MediaPipe**
*   Image resizing applied for Deep Learning models

***

## 🧠 Models Implemented

### Machine Learning Models

*   Random Forest (RF)
*   K‑Nearest Neighbors (KNN)
*   Logistic Regression (LR)
*   Support Vector Machine (SVM)

### Deep Learning Models

*   Convolutional Neural Network (CNN)
*   ResNet50

***

## 🧪 Experiment Setup

*   **Data split:** 80% training / 20% testing
*   **Hand detection:** MediaPipe
*   **Video processing:** OpenCV
*   **User Interface:** Streamlit
*   **Evaluation metrics:**
    *   Accuracy
    *   Precision
    *   Recall
    *   F1‑Score

***

## 📊 Results Summary

| Model               | Accuracy (%) |
| ------------------- | ------------ |
| **Random Forest**   | **97.94** ✅  |
| KNN                 | 94.56        |
| SVM                 | 94.78        |
| Logistic Regression | 93.51        |
| CNN                 | 88.56        |
| ResNet50            | 89.68        |

### 🔍 Key Findings

*   Random Forest achieved the **highest accuracy**
*   RF recognized all consonants except **“ha” (ហ)**
*   Deep Learning models require **larger datasets** for improved performance

***

## 🛠️ Technologies Used

*   Python
*   OpenCV
*   MediaPipe
*   Scikit‑learn
*   TensorFlow / Keras
*   Streamlit
*   Google Colab
*   VS Code
*   DroidCam

***

## 📂 Dataset & Trained Models

🔗 **Google Drive (Dataset, Actions & Models):**  
<https://drive.google.com/drive/folders/1T4zcJSrvotoHw67zshY4zEsvXTNeuulE>

You can open the Google Drive link to explore:

*   Fingerspelling action images
*   Dataset structure
*   Trained ML and DL models
*   Supporting project resources

***

## ▶️ How to Run the Project

```bash
git clone https://github.com/Sopheaktra34/Khmer-Fingerspelling-Interpreter.git
cd Khmer-Fingerspelling-Interpreter
pip install -r requirements.txt
streamlit run app.py
```

***

## 🚀 Future Improvements

*   Expand dataset to include:
    *   Sub‑consonants
    *   Vowels and independent vowels
    *   Numbers
*   Improve Deep Learning accuracy
*   Deploy as a mobile or production‑ready web application

Just say the word 👍
