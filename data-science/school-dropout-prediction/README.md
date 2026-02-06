# School Dropout Risk Prediction  
### Model Selection and Interpretability with SHAP

## Overview
This project focuses on predicting student dropout risk using machine learning models.
Beyond predictive performance, the project emphasizes **model selection** and
**interpretability**, relying on **SHAP values** to understand and justify model predictions.

## Objectives
- Predict student dropout risk using supervised learning models
- Compare multiple classifiers and select a robust model
- Emphasize interpretability to support transparent decision-making
- Ensure full reproducibility using a public dataset

## Models Evaluated
- Logistic Regression  
- k-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Neural Network (MLP)

## Model Selection
Models were compared using standard classification metrics:
- Accuracy
- Precision
- Recall
- F1-score

Among the evaluated models, the **SVM** achieved the best overall balance between
performance and robustness, and was selected as the final model.

## Interpretability with SHAP
To move beyond black-box predictions, **SHAP (SHapley Additive exPlanations)** was used to:
- Quantify feature contributions at both global and local levels
- Identify the most influential variables associated with dropout risk
- Improve transparency and trust in model predictions

This interpretability step is essential for real-world deployment, especially in decision-support and policy-driven environments.

## Dataset
The dataset used in this project is **publicly available on Kaggle** and is included
in this repository for full reproducibility:

🔗 https://www.kaggle.com/datasets/syedfaizanalii/predict-students-dropout-and-academic-success

**Source:**  
Syed Faizan Alii – Kaggle

## Repository Structure

```text
school-dropout-prediction/
├── notebooks/
│   └── Projet_de_session.ipynb
├── report/
│   └── Rapport_Projet_TOUYEM_BATIONO.pdf
├── data/
│   ├── Dropout_Data.csv
│   └── README.md
├── results/
│   └── README.md
└── README.md
```
## How to Reproduce
1. Open the notebook located in `notebooks/`
2. Ensure required Python libraries are installed
3. Run all cells sequentially
4. Review model evaluation and SHAP interpretability outputs

## Key Takeaways
- Model performance alone is insufficient without interpretability
- SHAP provides actionable insights into dropout risk factors
- Interpretable machine learning supports transparent and responsible decision-making

## Author
**Hilaire Touyem**  
Data Science & Optimization


