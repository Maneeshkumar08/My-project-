# Breast Cancer Detection using Deep Learning
This project detects **breast cancer (Benign vs Malignant)** from histopathological images using **deep learning and transfer learning**.The work is part of an **MSc Data Science final project**.

## 📂 Dataset
- **Name:** BreaKHis Dataset
- **Source:** https://www.kaggle.com/datasets/ambarish/breakhis
- **Classes:** Benign, Malignant
- **Images:** 7,909
- **Magnifications:** 40x, 100x, 200x, 400x

## 🧠 Approach
- Image preprocessing and resizing
- Exploratory Data Analysis (EDA)
- Train / Validation / Test split
- Class balancing (training set only)
- Data augmentation
- Transfer learning using **EfficientNetV2**

## ⚙️ Model
- **Architecture:** EfficientNetV2-B1
- **Pretrained:** ImageNet
- **Optimizer:** AdamW
- **Loss:** Binary Cross-Entropy

## 📊 Results
- **Test Accuracy:** ~93%
- **High recall for malignant cases**

## 🎓 Academic Note
This project was developed as part of the MSc Data Science Final Project
at the **University of Hertfordshire.**

## 👤 Author
- Maneesh Kumar Panduga
-MSc Data Science
-University of Hertfordshire

