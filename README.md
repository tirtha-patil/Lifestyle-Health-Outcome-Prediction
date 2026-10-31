Explainable Machine Learning framework for lifestyle-based health outcome prediction using Gradient Boosting and SHAP.

# 🩺 Lifestyle-Based Health Outcome Prediction using Explainable AI (XAI)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn%20%7C%20Gradient%20Boosting-orange)
![Explainable AI](https://img.shields.io/badge/XAI-SHAP-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success)

An end-to-end Machine Learning project that predicts an individual's health risk based on lifestyle and physiological factors. The system integrates Explainable AI (SHAP) to provide transparent predictions by highlighting the factors influencing each prediction.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Repository Structure](#-repository-structure)
- [Dataset](#-dataset)
- [Machine Learning Models & Benchmark Comparison](#-machine-learning-models--benchmark-comparison)
- [Best Model Performance](#-best-model-performance)
- [Visualizations](#-visualizations)
- [Workflow](#-workflow)
- [Results](#-results)
- [Future Improvements](#-future-improvements)
- [License](#-license)

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

## 📂 Repository Structure

```text
Lifestyle-Health-Outcome-Prediction/
├── Dataset/                                # Raw and processed health & lifestyle datasets
│   ├── health_lifestyle_dataset.csv
│   ├── health_processed.csv
│   ├── Obesity prediction.csv
│   ├── obesity_processed.csv
│   ├── Sleep_health_and_lifestyle_dataset.csv
│   ├── sleep_processed.csv
│   └── world_health_data.csv
├── Images/                                 # Visualizations, EDA charts & SHAP plots
│   ├── img 1.png - img 13.png
├── Notebook/                               # Jupyter notebook with complete ML & XAI pipeline
│   └── An Explainable AI Framework for Interpreting Lifestyle Behaviors and Health Outcomes.ipynb
├── Results/                                # Exported models and benchmark evaluations
│   ├── best_model.pkl                      # Trained Gradient Boosting model artifact
│   ├── gender_encoder.pkl                  # Fitted LabelEncoder for gender
│   ├── target_encoder.pkl                  # Fitted LabelEncoder for target risk classes
│   └── model_comparison.csv                # Comparative performance metrics across models
├── .gitattributes                          # Git attributes and line ending configuration
├── .gitignore                              # Git ignore rules for Python/Jupyter
├── LICENSE                                 # MIT License
├── README.md                               # Project documentation
└── requirements.txt                        # Python dependencies
```

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

## 🤖 Machine Learning Models & Benchmark Comparison

Six supervised classification algorithms were trained and evaluated on test datasets:

| Model | Accuracy | Precision | Recall | F1 Score | Status |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Gradient Boosting** | **75.18%** | **0.5652** | **0.7518** | **0.6453** | **Selected Best Model** 🏆 |
| Random Forest | 75.17% | 0.5652 | 0.7517 | 0.6452 | Evaluated |
| Extra Trees | 75.17% | 0.6273 | 0.7517 | 0.6453 | Evaluated |
| CatBoost | 75.15% | 0.6480 | 0.7515 | 0.6458 | Evaluated |
| Multi-Layer Perceptron (MLP) | 75.11% | 0.5797 | 0.7511 | 0.6450 | Evaluated |
| XGBoost | 74.70% | 0.6227 | 0.7470 | 0.6467 | Evaluated |

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
