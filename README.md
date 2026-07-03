# 🏥 Predicting health insurance costs

A simple Machine Learning project that predicts a person's health insurance cost based on their personal and medical information.

---

## 📌 Project Overview

The goal of this project is to build a regression model that can estimate health insurance charges using features such as:

- Age
- Gender
- Body Mass Index (BMI)
- Number of Children
- Smoking Status
- Diabetic Status
- Region

The project follows a complete Machine Learning workflow, from data preprocessing to model training and evaluation.

---

## 📂 Project Structure

```
Predictinghealthinsurancecosts.ipynb    # Main notebook
insurance.csv                           # Dataset
best_model.pkl                          # Trained model
scaler.pkl                              # Feature scaler
label_encoder_gender.pkl                # Gender encoder
label_encoder_smoker.pkl                # Smoker encoder
label_encoder_diabetic.pkl              # Diabetic encoder
app.py                                  # Streamlit application
README.md                               # Project documentation
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib
- Streamlit
- Matplotlib
- Seaborn

---

## 📊 Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Preprocess the data
5. Perform Feature Engineering
6. Train multiple regression models
7. Evaluate model performance
8. Save the best model and preprocessing artifacts
9. Deploy the model using Streamlit

---

## 📈 Model Evaluation

The models were evaluated using common regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was saved for deployment.

---

## 🚀 Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Predicting-Health-Insurance-Costs.git
cd Predicting-Health-Insurance-Costs
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📸 Application

The Streamlit application allows users to:

- Enter personal information
- Predict estimated health insurance costs instantly
- Get predictions using the trained machine learning model

---

## 📁 Dataset

The project uses the **Insurance Cost Prediction** dataset containing demographic and health-related information.

Typical features include:

- Age
- Gender
- BMI
- Children
- Smoker
- Diabetic
- Region
- Insurance Charges (Target)

---

## 🎯 Future Improvements

- Improve model accuracy with additional feature engineering
- Hyperparameter tuning
- Add more visualization to the dashboard
- Deploy the application online (Streamlit Cloud, Render, or Hugging Face Spaces)

---

## ⭐ If you found this project helpful, consider giving it a star!
