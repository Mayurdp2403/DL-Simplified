# 🐾 Animal Detection using Advanced DL Models

## 📌 Project Overview

| | |
|---|---|
| **Project** | Animal Detection using Advanced Deep Learning Models |
| **Issue** | [#1034](https://github.com/abhisheks008/DL-Simplified/issues/1034) |
| **Author** | [@Yugal0708](https://github.com/Yugal0708) |
| **Dataset** | [Animals-10 — Kaggle](https://www.kaggle.com/datasets/alessiocorrado99/animals10) |
| **Program** | GSSoC 2026 |
| **Level** | Advanced |

Wildlife animal detection is a critical application in forest monitoring, conservation systems, and smart camera traps. This project builds a **multi-model deep learning pipeline** combining **object detection** (YOLOv8) and **image classification** (4 CNN architectures) with a comprehensive performance comparison.

---

## 🎯 Goal

Detect and classify 10 animal species using 5 different deep learning models and compare them on **accuracy**, **inference speed**, and **model efficiency**.

---



## 🤖 Models Implemented

| # | Model | Task | Accuracy | Inference | Params |
|---|---|---|---|---|---|
| 1 | **YOLOv8n** | Object Detection | mAP@0.5: 37.3% | ~12 ms | 3.2M |
| 2 | **InceptionV3** | Classification | ~88–92% | ~18 ms | 23.9M |
| 3 | **ResNet50** | Classification | ~85–89% | ~22 ms | 25.6M |
| 4 | **MobileNetV2** | Classification | ~83–87% | ~9 ms | 3.4M |
| 5 | **VGG16** | Classification | ~81–85% | ~35 ms | 138.4M |

---

## 📊 Dataset

- **Name:** Animals-10
- **Source:** [Kaggle](https://www.kaggle.com/datasets/alessiocorrado99/animals10)
- **Total Images:** ~26,000
- **Classes:** dog, horse, elephant, butterfly, chicken, cat, cow, sheep, spider, squirrel
- **Split:** 80% Train / 10% Val / 10% Test

---

## 🛠️ Tech Stack

```
Python 3.10       TensorFlow 2.x    Keras
PyTorch           Ultralytics YOLOv8
OpenCV            NumPy             Pandas
Matplotlib        Seaborn           scikit-learn
```

---

## 🚀 How to Run

### Option 1: Kaggle (Recommended)
1. Open `Model/animal_detection_using_DL.ipynb` on Kaggle
2. Add dataset: **alessiocorrado99/animals10**
3. Enable **GPU P100**
4. **Run All**

### Option 2: Google Colab
1. Upload notebook to Colab
2. Enable **T4 GPU**
3. Run the Kaggle download cell in Section 3
4. **Run All**

---

## 📈 Key Results

- **Best Accuracy** → InceptionV3 (~88–92%)
- **Fastest Inference** → MobileNetV2 (~9ms/img) — best for real-time
- **Most Lightweight** → MobileNetV2 (3.4M params)
- **Best for Production** → YOLOv8 (Stage 1) + InceptionV3 (Stage 2)

---

## 📌 Use Cases

- 🌿 Forest & wildlife monitoring systems
- 🚗 Road animal crossing detection alerts
- 🏕️ Smart camera traps for conservation
- 🔬 Biodiversity research & population counting
- 🛡️ Intrusion detection near human settlements

---

## 📚 References

1. Jocher et al. (2023). *Ultralytics YOLOv8*
2. Szegedy et al. (2016). *Rethinking the Inception Architecture*. CVPR.
3. He et al. (2016). *Deep Residual Learning for Image Recognition*. CVPR.
4. Sandler et al. (2018). *MobileNetV2*. CVPR.
5. Simonyan & Zisserman (2014). *VGGNet*. ICLR.

---

 [@Yugal0708](https://github.com/Yugal0708)*