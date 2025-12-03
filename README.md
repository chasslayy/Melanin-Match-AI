# Melanin Match AI  
**Machine Learning Final Project — Chastity Lewis**  
**Course:** CISC 550 — Fall 2025  

## 🎯 Project Overview  
Melanin Match AI is a supervised machine learning project that classifies images into five skin-tone categories.  
The goal is to explore classical ML algorithms and deep learning by building a model that can identify skin-tone ranges based on image color and tone.

This final version of the project uses a **safe synthetic dataset** consisting of color-swatch images representing the following categories:

- **Light**  
- **Tan**  
- **Medium**  
- **Deep**  
- **Dark**  

This approach allows for fair model evaluation without using real human photos.

---

## 📂 Dataset  
The dataset contains **50 images total** (10 per category).

**Structure:**


Each folder contains synthetic color patches that represent each skin tone category.

---

## 🧪 Methods  
Three models were trained and compared:

### **1. SVM (Support Vector Machine)**
- Baseline classical model  
- Uses flattened pixel values  
- Provides a benchmark for traditional ML performance  

### **2. kNN (K-Nearest Neighbors)**
- Another classical model  
- Simple distance-based classifier  
- Good comparison for non-deep approaches  

### **3. Convolutional Neural Network (CNN)**
- Deep learning model  
- Automatically learns image features  
- Highest-performing model  

---

## 📊 Evaluation  
The following evaluations were performed:

- Accuracy  
- Classification Report (Precision, Recall, F1-score)  
- Confusion Matrix  
- AUC (One-vs-Rest)  
- Model Comparison Table  

The **CNN achieved the strongest results**, followed by SVM and kNN.

---

## 🧠 Key Findings  
- Deep learning is more effective for image classification than classical models.  
- Even with a small dataset, the CNN learned clear distinctions between tone categories.  
- Synthetic color patches still allow for useful experimentation with ML pipelines.  

---

## 🚀 Future Work  
- Expand dataset with more color gradients  
- Add texture-based synthetic skin images  
- Experiment with transfer learning (EfficientNet/ResNet)  
- Deploy a simple web demo for shade prediction  

---

## 🔗 Notebook  
Click below to view the full working notebook:

👉 **[Melanin_Match_Project.ipynb](Melanin_Match_Project.ipynb)**  

