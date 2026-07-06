Explainable Machine Learning framework for lifestyle-based health outcome prediction using Gradient Boosting and SHAP.

# 🩺 Lifestyle-Based Health Outcome Prediction using Explainable AI (XAI)

An end-to-end Machine Learning project that predicts an individual's health risk based on lifestyle and physiological factors. The system integrates Explainable AI (SHAP) to provide transparent predictions by highlighting the factors influencing each prediction.

---

## 📌 Overview

Lifestyle-related diseases are becoming increasingly common due to unhealthy habits and changing lifestyles. This project leverages Machine Learning and Explainable AI to predict disease risk using user lifestyle data while providing interpretable explanations for each prediction.

The project evaluates multiple machine learning algorithms and selects the best-performing model based on classification metrics.

---

## 🚀 Features

- Predicts health risk using lifestyle and health parameters
- Compares multiple Machine Learning models
- Uses Gradient Boosting as the final prediction model
- SHAP-based Explainable AI for prediction transparency
- Feature importance visualization
- Exploratory Data Analysis (EDA)
- Model performance comparison
- Confusion Matrix and evaluation metrics

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP
- Pickle
- Google Colab
- Jupyter Notebook

---

## 📊 Dataset

Health Lifestyle Dataset

Approximately **100,000 records** containing:

- Age
- Gender
- BMI
- Daily Steps
- Sleep Hours
- Water Intake
- Calories Consumed
- Smoking Status
- Alcohol Consumption
- Resting Heart Rate
- Blood Pressure
- Cholesterol
- Family History
- Disease Risk

---

## 🤖 Machine Learning Models Evaluated

- Gradient Boosting ✅
- XGBoost
- CatBoost
- Random Forest
- Extra Trees Classifier
- Multi-Layer Perceptron (MLP)

---

## 📈 Best Model Performance

| Metric | Value |
|---------|------:|
| Accuracy | **75.18%** |
| Precision | 0.565 |
| Recall | 0.752 |
| F1 Score | 0.645 |

Gradient Boosting achieved the highest overall performance and was selected as the final model.

---

## 📊 Visualizations

- Disease Risk Distribution
- Gender Distribution
- Correlation Heatmap
- Model Accuracy Comparison
- Confusion Matrix
- Feature Importance Plot
- SHAP Summary Plot
- Global SHAP Feature Importance

---

## 📌 Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Explainable AI using SHAP
8. Model Saving
9. Prediction

---

## 📈 Results

- Compared six supervised Machine Learning algorithms.
- Gradient Boosting achieved the highest prediction accuracy.
- SHAP explanations improved model interpretability.
- Visualizations helped identify the most influential health-related features.

---

## 🔮 Future Improvements

- Web application deployment
- Cloud deployment
- User authentication
- PDF health reports
- Real-time prediction API
- Deep Learning models
- Personalized health recommendations

---

## 📄 License

This project is licensed under the MIT License.
