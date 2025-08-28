## YOLOv8-object-detection-on-a-cat-dataset 🐱

### 📌 Overview

This repository is part of my Computer Vision learning journey.

I implemented YOLOv8 for object detection on a cat dataset, guided by the following excellent tutorial: <br />
[Train Yolov8 object detection on a custom dataset | Step by step guide | Computer vision tutorial](https://www.youtube.com/watch?v=m9fH9OWn8YM&list=PLb49csYFtO2HGELdc-RLRCNVNy0g2UMwc&index=3&ab_channel=Computervisionengineer)

Instead of just copy-pasting, I:
1. Rebuilt the project in my own way
2. Adapted it to a custom cat dataset
3. Added comments and explanations for clarity
4. Tweaked training parameters to experiment with performance

Documented the key steps so others (and my future self) can learn from it

### 🧑‍💻 What I Learned

- How YOLOv8 architecture works for object detection <br />
- Dataset preparation for training (annotation, augmentation, splitting) <br />
- Training & evaluating a custom object detector in PyTorch <br />
- Visualizing predictions and interpreting model performance

### 🔧 Tech Stack
- Python
- Ultralytics YOLOv8
- PyTorch
- OpenCV
- Matplotlib

### 📂 Repo Structure

```
├── data/               # Cat dataset (annotations + images)
├── notebooks/          # Jupyter notebooks for experiments
├── src/                # Training & evaluation scripts
├── outputs/            # Saved models and results
└── README.md           # Project documentation
```

## 🙏 Credits

This work was inspired by: [Train Yolov8 object detection on a custom dataset | Step by step guide | Computer vision tutorial](https://www.youtube.com/watch?v=m9fH9OWn8YM&list=PLb49csYFtO2HGELdc-RLRCNVNy0g2UMwc&index=3&ab_channel=Computervisionengineer)  <br />
Any changes, extensions, or mistakes here are my own.
