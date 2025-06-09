# 🐣 ChickEgg - Real-Time Chicken and Egg Detection

**ChickEgg** is a real-time object detection system built using **YOLOv11**, designed to accurately identify chickens and eggs in farm environments from live video streams.

## 📌 Key Features

- ⚡ Real-time detection with **YOLOv11**
- 🎯 High performance on a custom farm dataset:
  - **Precision (B):** 0.93  
  - **Recall (B):** 0.92  
  - **mAP@0.5 (B):** 0.945  
  - **mAP@0.5:0.95 (B):** 0.735  
- 📸 Custom data collection and annotation using [Roboflow](https://roboflow.com/)
- 🐔 Trained specifically on farm-related scenes for detecting:
  - `chicken`
  - `egg`

## 📁 Dataset

- Total annotated images: **6,715**
  - **Training set:** 5,524 images  
  - **Validation set:** 792 images  
  - **Test set:** 399 images  
- Collected from various farm camera feeds
- Annotated using **Roboflow** for high-quality bounding boxes and labels
- Balanced to ensure robust generalization across unseen farm environments

---

Feel free to contribute, raise issues, or fork this project to extend its capabilities!
