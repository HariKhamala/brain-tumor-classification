# 🧠 Brain Tumor Classification from MRI Images using Deep Learning

This project focuses on building a robust deep learning-based pipeline to classify brain MRI images into four tumor categories: **Glioma**, **Meningioma**, **Pituitary**, and **No Tumor**. It includes both a **custom CNN model** and a **transfer learning approach** using MobileNetV2. The project is structured for future deployment via a Streamlit web app.

---

## 📌 Problem Statement

The goal is to develop an AI-powered solution to automate and improve the diagnosis of brain tumors from MRI scans. This can assist radiologists, reduce diagnostic turnaround time, and enable early detection in clinical settings.

---

## 🩺 Real-Time Business Use Cases

- **AI-Assisted Medical Diagnosis**  
  Provide radiologists with AI tools to classify brain tumors efficiently.

- **Early Detection and Patient Triage**  
  Automatically flag high-risk images for faster specialist review.

- **Research and Clinical Trials**  
  Use AI to pre-classify datasets by tumor type for research segmentation.

- **Second-Opinion AI Systems**  
  Assist remote telemedicine diagnosis in under-resourced areas.

---

## 🧪 Project Workflow

1. **Dataset Exploration**
   - 4 classes: Glioma, Meningioma, Pituitary, No Tumor
   - Dataset split into training and validation using `ImageDataGenerator`

2. **Preprocessing & Augmentation**
   - Normalized image pixel values
   - Augmentation: rotation, zoom, flip

3. **Model Building**
   - Custom CNN built from scratch
   - Transfer learning using pretrained MobileNetV2 (frozen base)

4. **Model Training**
   - Trained with early stopping and checkpoint saving best model

5. **Model Evaluation**
   - Accuracy, precision, recall, F1-score, and classification report

6. **Performance Comparison**
   - Accuracy curves plotted for visual comparison

---

## 📁 Dataset

**Source**:  
[Labeled MRI Brain Tumor Dataset](https://drive.google.com/drive/folders/1C9ww4JnZ2sh22I-hbt45OR16o4ljGxju)

Classes:
- `glioma_tumor`
- `meningioma_tumor`
- `no_tumor`
- `pituitary_tumor`

---
