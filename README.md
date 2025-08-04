# 🧠 Heart Disease Prediction using Artificial Neural Network (ANN)

This project uses an **Artificial Neural Network (ANN)** to predict whether a patient is likely to have heart disease based on various medical attributes. It includes both a **Jupyter Notebook** for training and a **Streamlit Web App** for real-time prediction.

---

## 🌐 Live App

👉 [Click here to try the app](https://ai-heart-risk-checker.streamlit.app/)

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

📁 **Dataset Source:**  
[Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## 🧠 Model Architecture

| Layer Type     | Details                            |
|----------------|------------------------------------|
| Input Layer    | 13 input features                  |
| Hidden Layers  | Dense layers with ReLU activations |
| Output Layer   | 1 neuron with Sigmoid activation   |

- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metrics:** Accuracy

---

## 📈 Model Performance

- ✅ **Training Accuracy:** ~98.26%  
- ✅ **Testing Accuracy:** ~84.61%  
- 🧪 Slight overfitting observed

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Files Included

| File                      | Description                                   |
|---------------------------|-----------------------------------------------|
| `Heart_ANN.ipynb`         | Notebook: training, evaluation, visualization |
| `heart_disease_app_py.py` | Streamlit web interface                       |
| `heart_ann_model.h5`      | Trained ANN model (Keras H5 format)           |
| `requirements.txt`        | Project dependencies                          |

---

## 🚀 How to Run the App Locally

```bash
# Clone the repository
git clone https://github.com/codesbysuraj/heart-disease-detect-ann.git
cd heart-disease-detect-ann

# Install dependencies
pip install -r requirements.txt

# Launch the Streamlit app
streamlit run heart_disease_app_py.py


👨‍💻 **Author**  
**Suraj Yadav**  
- GitHub: [@codesbysuraj](https://github.com/codesbysuraj)  
- Email: [surajy.tech@gmail.com](mailto:surajy.tech@gmail.com)

