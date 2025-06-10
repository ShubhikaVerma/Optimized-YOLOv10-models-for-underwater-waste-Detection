
# 🌊 Underwater Garbage Detection using YOLOv10

This project focuses on real-time underwater garbage detection using the latest YOLOv10 object detection models. It aligns with **UN Sustainable Development Goals (SDGs)** — specifically:
- **Goal 6**: Clean Water and Sanitation
- **Goal 14**: Life Below Water



---

## 🚀 Project Highlights

🧮 YOLOv10 Training Hyperparameters

| **Hyperparameters** | **Values**      |
| ------------------- | --------------- |
| Learning Rate       | 0.001           |
| Batch Sizes         | 32, 64          |
| Optimizers          | Adam, AdamW     |
| Epoch Sizes         | 60, 70, 80, 100 |


- 🎯 **Best Model**: YOLOv10s + AdamW + 32 batch size + 100 epochs  
  - **Precision**: 84.2%  
  - **Recall**: 73.5%  
  - **mAP@50**: 78.9%  

---

## 📁 Dataset

- **Dataset Name**: `underwater_garbage`
- A curated collection of images depicting marine litter across different underwater scenes.
- Includes occluded, small-scale, and cluttered object instances.

---

## 🧪 Experiments & Results

- Conducted extensive comparison between YOLOv10n and YOLOv10s.
- Evaluated performance at varying epochs and batch sizes.
- Included multiple optimizers to tune model behavior.
- Best model selected based on mAP and F1-Confidence curve analysis.



---

## 🎥 Live Detection Modes

- 📸 **Image Inference** — Classifies static input images.
- 🎞️ **Video Detection** — Processes pre-recorded videos to detect objects.
- 📹 **Live Camera Stream** — Performs real-time garbage detection using webcam feed.



---

## 🛠️ Requirements

- Python 3.8+
- PyTorch
- Ultralytics YOLOv10 repository (latest version)
- OpenCV
- matplotlib, seaborn


