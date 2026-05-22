## Alzheimer's Detection

### 🎯 Goal

The goal of this project is to develop a deep learning model capable of detecting **Alzheimer’s disease** from **brain MRI scans**.

Early detection can improve treatment planning and patient care by assisting healthcare professionals with accurate diagnosis.

---

### 🧵 Dataset

The dataset used in this project is sourced from **Kaggle**.

**Dataset Link:**  
https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images

#### About the dataset

The dataset contains **6400 MRI scan images** divided into four classes:

1. Mild Demented  
2. Moderate Demented  
3. Non Demented  
4. Very Mild Demented

---

### 🧾 Description

This project focuses on classifying brain MRI images into different stages of Alzheimer’s disease using deep learning.

The repository includes:

- Model training notebook
- Trained model (`model.h5`)
- MRI image samples
- Streamlit web application for live prediction

---

### 🧮 What I had done!

1. Collected MRI scan dataset from Kaggle.
2. Performed image preprocessing and normalization.
3. Built a deep learning classification model using TensorFlow/Keras.
4. Trained the model on MRI images.
5. Evaluated model performance using accuracy and loss.
6. Saved the trained model (`model.h5`).
7. Developed a Streamlit web application for predictions.

---

### 🚀 Models Implemented

#### Deep Neural Network (DNN)

The model architecture includes:

- Flatten Input Layer (`176 × 176 × 3`)
- Multiple Dense layers with ReLU activation
- Final Softmax output layer

**Why this model?**

- Effective for multi-class classification
- Learns useful image representations
- Efficient to train and deploy

---

### 📚 Libraries Needed

- numpy
- pandas
- matplotlib
- tensorflow
- keras
- imblearn
- os
- random
- warnings
- streamlit
- pillow

---

### 📊 Exploratory Data Analysis Results

#### Sample MRI Brain Scan

![Sample MRI Brain Scan](../Images/image.jpg)

The MRI dataset was visually inspected to understand class distributions and image patterns across different stages of Alzheimer's disease.

---

### 📈 Performance of the Models based on the Accuracy Scores

**Model:** Deep Neural Network (DNN)

- **Loss:** `0.5686`
- **Accuracy:** `93.64%`

The model achieved strong performance in classifying MRI scans into Alzheimer’s disease stages.

---

### 📢 Conclusion

This project demonstrates that deep learning can effectively assist in the early detection of Alzheimer’s disease using MRI scans.

With an accuracy of **93.64%**, the model shows promising potential as a clinical decision-support tool.

---
### ✒️ Contributor's Signature

**Rishi V**  
GitHub: https://github.com/kit29-25bad132  
LinkedIn: https://www.linkedin.com/in/rishivkit/  
Contributor - GSSoC 2026
