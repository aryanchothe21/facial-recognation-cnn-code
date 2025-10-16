# Facial Emotion Recognition (FER) using CNN

This repository contains the implementation of a **Convolutional Neural Network (CNN)** for recognizing human facial emotions using the **FER2013 dataset**.

---

## 📘 About the Project
Facial Emotion Recognition (FER) identifies seven emotion classes:
**Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral**.

This project uses a custom CNN model trained on the FER2013 dataset to classify emotions efficiently with reduced parameters.

---

## 📂 Files Included
- `sc.ipynb` → Jupyter Notebook containing CNN training and evaluation  
- `Ai plagiarism report.pdf` → AI plagiarism detection report  
- `facial recognation grammerly report.docx` → Grammarly grammar analysis report  

---

## 🧠 Model Details
- Architecture: Sequential CNN  
- Regularization: Dropout & Batch Normalization  
- Validation Accuracy: **63.93%**
- Dataset: **FER2013 (Grayscale 48x48 Images)**  

---

## ⚙️ Requirements
To run this project, install the following libraries:
```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn
