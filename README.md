# 🩺 Adaptive Diabetes Risk Analyser

A **machine learning-powered web application** that predicts the risk of diabetes using user-input health parameters. The system leverages **data preprocessing, feature engineering, and a trained ML model** to provide real-time predictions with **interactive visual insights**.

---

## 🚀 Features

* 🧠 **Machine Learning Model** (`diabetes_model.pkl`) trained on healthcare dataset
* 🌐 **Streamlit Web Application** (`diabetes_app.py`) for real-time risk prediction
* 📊 **Data Visualization** for interpreting health risk factors
* 🗂️ **Dataset Included** (`diabetes_risk_prediction_dataset.csv`)
* ⚡ Fast and lightweight with simple UI for end-users

---

## 🛠️ Tech Stack

* **Languages:** Python
* **Libraries/Frameworks:** Streamlit, scikit-learn, Pandas, NumPy, Matplotlib
* **Model:** Logistic Regression / SVM (based on your training)
* **Dataset:** CSV file with health attributes

---

## 📂 Project Structure

```
Adaptive-Diabetes-Risk-Analyser/
│── diabetes_app.py                  # Streamlit web app
│── diabetes_model.pkl               # Pre-trained ML model
│── diabetes_risk_prediction_dataset.csv  # Training dataset
│── csp/csp.py                       # Helper functions
│── README.md                        # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/SBhanu143/Adaptive-Diabetes-Risk-Analyser.git
cd Adaptive-Diabetes-Risk-Analyser
```

2. **Create Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

*(If `requirements.txt` is missing, install manually:)*

```bash
pip install streamlit scikit-learn pandas numpy matplotlib
```

---

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run diabetes_app.py
```

This will open the app in your browser (default: **[http://localhost:8501](http://localhost:8501)**).

---

## 📊 Example Workflow

1. User enters health details (e.g., Age, BMI, Glucose level, Blood Pressure).
2. The model predicts **risk of diabetes** (Yes/No).
3. The app displays **visual insights** to highlight risk factors.

---


## 🌟 Impact

This project demonstrates how **AI and ML can support early health risk detection**.
It empowers users to:

* Self-assess their diabetes risk
* Take preventive health actions
* Make informed decisions with clear visual feedback

---
