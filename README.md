# Lung and Colon Histopathology Image Classification

## 📌 Overview

This project focuses on the classification of lung and colon histopathological images using image processing techniques and transfer learning-based deep learning models.

The project was developed as part of a Computer Vision course assignment.

The workflow includes image enhancement, image quality evaluation, transfer learning model exploration, ablation study, and comprehensive model evaluation.

---

## 🎯 Objectives

- Enhance histopathological images to emphasize important cellular and nuclear structures.
- Evaluate the quality of enhanced images using MSE, RMSE, SSIM, and PSNR.
- Explore the performance of five different transfer learning models.
- Conduct an ablation study to analyze the impact of image processing and model selection.
- Evaluate the best-performing model using accuracy and loss curves, confusion matrix, precision, recall, and F1-score.

---

## 📂 Dataset

The dataset contains five classes of lung and colon histopathological images:

- `colon_aca` — Colon Adenocarcinoma
- `colon_n` — Normal Colon Tissue
- `lung_aca` — Lung Adenocarcinoma
- `lung_n` — Normal Lung Tissue
- `lung_scc` — Lung Squamous Cell Carcinoma

The dataset was provided for the Computer Vision course.

---

## 🔬 Project Workflow

```text
Original Histopathological Images
              │
              ▼
      Image Preprocessing
              │
              ▼
      Image Enhancement
              │
              ▼
   Quality Evaluation
  MSE | RMSE | SSIM | PSNR
              │
              ▼
     Enhanced Dataset
              │
              ▼
     Transfer Learning
              │
      ┌───────┼────────┐
      ▼       ▼        ▼
    VGG16  ResNet50  MobileNetV2
      │       │        │
      └───────┼────────┘
              │
      DenseNet121
              │
      EfficientNetB0
              │
              ▼
       Model Comparison
              │
              ▼
        Best Model
              │
              ▼
       Ablation Study
              │
              ▼
     Model Evaluation
              │
       ┌──────┼──────┐
       ▼      ▼      ▼
    Curves  Confusion  Metrics
             Matrix
