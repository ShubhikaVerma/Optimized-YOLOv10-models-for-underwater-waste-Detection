
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

 # YOLOv10s + AdamW + 32 batch size + 100 epochs  
![image](https://github.com/user-attachments/assets/e36842fb-f71b-4754-86ba-e5c5757022ad)
![image](https://github.com/user-attachments/assets/79eaa5ae-d126-4fd1-842b-24858a97cd59) ![image](https://github.com/user-attachments/assets/feff3aeb-0aac-4f01-83a9-28008c6f7a9a)
![image](https://github.com/user-attachments/assets/2d4a3bb5-4c8d-475f-adf5-c5315736ea65)
![image](https://github.com/user-attachments/assets/aa41bf8f-39c2-4910-ac08-7f2751bfdf77)





---

## 🎥 Live Detection Modes

- 📸 **Image Inference** — Classifies static input images.
- 🎞️ **Video Detection** — Processes pre-recorded videos to detect objects.
- 📹 **Live Camera Stream** — Performs real-time garbage detection using webcam feed.

![image](https://github.com/user-attachments/assets/39e16f84-4714-49d1-ab02-bcfeb703764f)


---

## 🛠️ Requirements

- Python 3.8+
- PyTorch
- Ultralytics YOLOv10 repository (latest version)
- OpenCV
- matplotlib, seaborn


