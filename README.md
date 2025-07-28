# ANN
# 🧠 Heart Disease Prediction using Artificial Neural Network (ANN)

This project uses an **Artificial Neural Network (ANN)** to predict whether a patient is likely to have heart disease based on various medical attributes. It is built using Python and the Keras/TensorFlow framework inside a Jupyter Notebook.

---

## 📊 Dataset

The dataset includes clinical features such as:
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol
- Maximum heart rate
- Exercise-induced angina
- ST depression
- And more

**Target:**  
- `0` → No heart disease  
- `1` → Heart disease present

📁 Dataset Source: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## 🧠 Model Architecture

| Layer Type     | Details                          |
|----------------|----------------------------------|
| Input Layer    | 13 input features                |
| Hidden Layers  | Dense layers with ReLU activations |
| Output Layer   | 1 neuron (Sigmoid activation) for binary classification |

- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metrics:** Accuracy

---

## 📈 Performance

- ✅ **Training Accuracy:** ~98.26%
- ✅ **Testing Accuracy:** ~84.61%
- The model performs well, with slight overfitting observed.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- TensorFlow / Keras
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Files Included

- `Heart_ANN.ipynb` → Full notebook with:
  - Data preprocessing
  - ANN model building
  - Training & Evaluation
  - Visualizations

---

## 🖼️ Visual Outputs

- Accuracy and loss plots
- Confusion matrix
- Prediction examples

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/codesbysuraj/heart-disease-ann.git
   cd heart-disease-ann


This is my first Git Repository 
<br>
Author - Suraj Yadav (CSE-AIML)
