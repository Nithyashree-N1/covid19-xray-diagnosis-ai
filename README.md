# COVID-19 Diagnosis from Chest X-Rays using Deep Learning and Machine Learning

An AI-driven medical imaging pipeline for detecting COVID-19 from chest X-ray images using Convolutional Neural Networks (CNNs), Multilayer Perceptron (MLP), Random Forest, and clustering techniques.

---

## Project Overview

This project focuses on multi-class chest X-ray image classification to identify:

- COVID-19
- Viral Pneumonia
- Normal

The workflow combines Deep Learning and Classical Machine Learning to evaluate the effectiveness of hybrid AI models in medical image analysis.

---

## Features

- Custom CNN architecture for image classification
- CNN-based feature extraction
- MLP and Random Forest classifiers using CNN embeddings
- Hyperparameter tuning with GridSearchCV
- K-Means clustering and PCA visualisation
- Data augmentation and class balancing
- Medical AI ethics and bias discussion

---

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV

---

## Dataset

The dataset used for this coursework was provided by the university and corresponds to the publicly available:

**COVID-19 Image Dataset** by Pranavraikokte on Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset

The dataset contains chest X-ray images organised into:
- COVID-19
- Viral Pneumonia
- Normal

---

## Dataset Setup

The dataset is not included in this repository due to GitHub storage limitations.

Download the dataset from Kaggle and place it inside:

```text
data/raw/Covid19-dataset/
```

---

## Repository Structure

```text
covid19-xray-diagnosis-ai/
│
├── data/
├── notebooks/
├── plots/
├── reports/
├── README.md
└── .gitignore
```

---

## Model Performance

| Model | Validation Accuracy |
|------|------|
| CNN | ~92% |
| MLP (CNN Features) | 100% |
| Random Forest (CNN Features) | 100% |
| K-Means (Raw Pixels) | 76% |
| K-Means (CNN Features) | 62% |

---

## Key Learning Outcomes

- Deep Learning for Medical Imaging
- CNN Feature Extraction
- Hybrid AI Pipelines
- Ensemble Learning
- Unsupervised Learning
- PCA Visualisation
- Hyperparameter Optimisation

---

## Future Improvements

- Transfer Learning (ResNet / EfficientNet)
- Explainable AI (Grad-CAM)
- Larger medical imaging datasets
- Real-time deployment

---

## Author

Nithyashree Nataraja

---

## Academic Note

This project was developed as part of university coursework for Applied AI and Data Mining.

---

