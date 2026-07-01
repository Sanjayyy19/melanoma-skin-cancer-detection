# 🩺 Melanoma Skin Cancer Detection using EfficientNetB3 and Transfer Learning

## 📌 Project Overview

This project presents an AI-based deep learning system for the automated detection of melanoma skin cancer using dermoscopic images. The model is built using **EfficientNetB3** with **transfer learning** to classify skin lesions into two categories:

- 🟢 Benign (Non-Cancerous)
- 🔴 Malignant (Melanoma)

The objective is to assist in the early detection of melanoma by providing an accurate computer-aided diagnostic system.

---

## 🎯 Objectives

- Develop a deep learning model for melanoma classification.
- Improve diagnostic accuracy using transfer learning.
- Reduce manual effort in skin lesion screening.
- Evaluate the model using multiple performance metrics.
- Provide explainable predictions using LIME.

---

## 🧠 Model Architecture

- **Base Model:** EfficientNetB3 (ImageNet Pre-trained)
- **Transfer Learning**
- Global Average Pooling
- Batch Normalization
- Dropout Layer
- Dense Layer
- Sigmoid Output Layer

---

## 📂 Dataset

**Dataset Name:** Melanoma Cancer Image Dataset

The dataset contains dermoscopic images divided into two classes:

- Benign
- Malignant

### Dataset Split

- Training Set
- Validation Set
- Testing Set

> **Note:** The dataset is not included in this repository due to its size. It can be downloaded directly from Kaggle.

---

## 🔄 Project Workflow

```
Dataset
      │
      ▼
Data Loading
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Image Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
EfficientNetB3 Transfer Learning
      │
      ▼
Model Training
      │
      ▼
Fine-Tuning
      │
      ▼
Model Evaluation
      │
      ▼
LIME Explainability
```

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Training Accuracy | 90.59% |
| Validation Accuracy | 90.40% |
| Test Accuracy | **90.55%** |
| Precision | **94.61%** |
| Recall (Sensitivity) | **86.00%** |
| Specificity | **95.10%** |
| F1-Score | **90.10%** |
| ROC-AUC | **97.24%** |

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

---

## 🔍 Explainable AI

To improve model interpretability, **LIME (Local Interpretable Model-Agnostic Explanations)** was used.

LIME highlights the image regions that most influenced the model's prediction, making the classification process more transparent and interpretable.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- EfficientNetB3
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- LIME
- Kaggle Notebook

---

## 📁 Repository Structure

```
Melanoma-Skin-Cancer-Detection/
│
├── melanoma_detection.ipynb
├── best_model_finetuned.keras
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Future Enhancements

- Deploy the model as a Streamlit web application.
- Enable image upload for real-time prediction.
- Generate downloadable prediction reports.
- Extend the model for multi-class skin lesion classification.
- Improve performance using ensemble learning and Vision Transformers.

---

## 📌 Results

- Achieved over **90% classification accuracy** on unseen test images.
- Demonstrated strong discrimination capability with a **97.24% ROC-AUC**.
- Showed high precision, reducing false positive melanoma predictions.
- LIME-based explanations improved the transparency of model decisions.

---

## 👨‍💻 Author

**Sanjay Raj**

M.Sc. Data Science

SASTRA Deemed University

---

## 📄 License

This project is intended for educational and research purposes only.

It is **not a substitute for professional medical diagnosis**.
