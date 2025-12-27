# 🖐️ American Sign Language Letter Detection (YOLOv8)

This project uses **YOLOv8** to detect **American Sign Language (ASL) hand gestures** and classify each one as a letter (A–Z).  
It was trained using a labeled dataset from Roboflow, where each hand sign is annotated with a bounding box and class label.

---

## 🎯 Project Goal

To build a computer vision model that can:

- Detect the hand in an image 📸  
- Draw a bounding box around it ⬛  
- Predict the corresponding ASL letter 🔤  

This type of system can support:

- assistive communication tools  
- sign-language education apps  
- gesture-based interfaces  

---

## 🧠 Model

We used:

- **Model:** YOLOv8 (Nano)  
- **Framework:** Ultralytics  
- **Training:** Transfer learning (fine-tuned on ASL dataset)

YOLO was chosen because it is:

✔ fast  
✔ accurate  
✔ easy to deploy  

---

## 📦 Dataset

Dataset source:

> **American Sign Language Letters — Object Detection**  
Provided by Roboflow Universe.

Each image contains:

- a hand showing a gesture  
- a bounding box  
- a label (A, B, C, …)

The dataset was automatically downloaded in Colab using the Roboflow API and exported in **YOLOv8 format**.

---

## 🚀 How to Train

Install dependencies:

```bash
pip install ultralytics roboflow
