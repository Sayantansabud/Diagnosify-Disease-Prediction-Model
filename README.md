# 🤖 Diagnosify - Disease Prediction Model

A **Symptom-Based Disease Diagnosis** web application built using **Flask** and **Machine Learning**.

## 🌟 Overview

In today’s digital age, timely access to healthcare insights is vital. Diagnosify is an intelligent, AI-powered web app that helps users get possible disease predictions by entering symptoms. Powered by a machine learning model, the system offers health recommendations, precautions, and more.

---

## 🚑 The Problem

Many individuals experience symptoms and seek immediate health guidance. However, overlapping symptoms across various diseases make self-diagnosis challenging and risky. Diagnosify bridges this gap with an ML-based solution for symptom-based disease prediction.

---

## 💡 The Solution

Diagnosify uses a **Decision Tree Classifier** trained on a dataset of diseases and symptoms. It predicts the most probable disease and also shares useful medical guidance.

### 🔧 How It Works

- 📝 **Symptom Input:** Users select symptoms via a clean interface.
- 🤖 **ML Prediction:** A trained Decision Tree Classifier processes inputs.
- 📋 **Result Output:** Displays the most probable disease with:
  - Description
  - Recommended medications
  - Precautions
  - Diet and workout suggestions

---

## 🔑 Key Features

✅ **Simple UI:** Beginner-friendly and mobile-responsive interface  
✅ **ML-Powered Predictions:** Trained Decision Tree Classifier  
✅ **Informative Output:** Offers disease summary, medications, diet & more  
✅ **Dark Mode:** Aesthetic modern UI with dark/light toggle  
✅ **Educational Blog:** Blog section for wellness and healthcare awareness  

---


## 🧠 Tech Stack

- **Frontend:** HTML, CSS (modern minimal UI), JavaScript  
- **Backend:** Python, Flask  
- **ML Model:** Decision Tree Classifier (scikit-learn)  
- **Others:** jQuery, Font Awesome  


---

##  Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/Diagnosify-Disease-Prediction-Model.git
cd Diagnosify-Disease-Prediction-Model

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py

