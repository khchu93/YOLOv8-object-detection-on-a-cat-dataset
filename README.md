## Object Detection with YOLOv8 🐱 <br />
Object Detection / Ultralytics YOLOv8 / Label Studio(annotation)

### 💻 Description
Self-learning journey 1: Computer vision, object detection with YOLOv8

### 📌 Overview

I implemented YOLOv8 for object detection on a custom dataset, guided by the following excellent tutorial: <br />
[How to Train YOLO Object Detection Models in Google Colab (YOLO11, YOLOv8, YOLOv5)](https://www.youtube.com/watch?v=r0RspiLG260&ab_channel=EdjeElectronics)

Instead of just copy-pasting, I:
1. Rebuilt the project in my own way
2. Adapted it to a custom cat dataset
3. Added comments and explanations for clarity
4. Tweaked training parameters to experiment with performance

Documented the key steps so others (and my future self) can learn from it

### ✨ What I Learned

- How YOLOv8 architecture works for object detection <br />
- Dataset preparation for training (annotation, augmentation, splitting) <br />
- Training & evaluating a custom object detector in PyTorch <br />
- Visualizing predictions and interpreting model performance

### 📂 Repo Structure

```
├── data/               # Cat dataset (annotations + images)
├── notebooks/          # Jupyter notebooks for experiments
├── src/                # Training & evaluation scripts
├── outputs/            # Saved models and results
└── README.md           # Project documentation
```

### 🙏 Credits

This work was inspired by: [How to Train YOLO Object Detection Models in Google Colab (YOLO11, YOLOv8, YOLOv5)](https://www.youtube.com/watch?v=r0RspiLG260&ab_channel=EdjeElectronics)  <br />
