# School Dropout Risk Prediction  
### Interpretable Machine Learning for Risk-Oriented Decision Support

## Business Context
School dropout represents a major societal and economic risk for educational
institutions and public organizations. Early identification of at-risk students
enables proactive interventions, optimized resource allocation, and measurable
impact on long-term outcomes.

From a broader perspective, this problem is analogous to **risk prediction
settings in finance and insurance**, where decisions must be both **accurate and
explainable** to support accountability and governance requirements.

## Project Objective
The objective of this project is to develop an **interpretable risk prediction
model** capable of identifying students with a high probability of dropout,
while ensuring transparency and trust in the decision-making process.

The project explicitly balances:
- Predictive performance  
- Model robustness  
- Interpretability for decision support  

## Modeling Strategy
Several classification models were evaluated to assess their suitability for
risk prediction:

- Logistic Regression  
- k-Nearest Neighbors (k-NN)  
- Support Vector Machine (SVM)  
- Neural Networks (MLP)

Models were compared using performance metrics adapted to imbalanced datasets
(precision, recall, macro F1-score), reflecting real-world risk management
constraints where false negatives and false positives carry different costs.

## Model Selection
Among the evaluated models, the **Support Vector Machine (SVM)** demonstrated the
best overall balance between predictive accuracy and stability, making it the
most appropriate candidate for deployment in a decision-support context.

## Model Interpretability (SHAP)
A strong emphasis is placed on **model interpretability**, a critical requirement
in regulated environments such as **finance, insurance, and public policy**.

To achieve this, **SHAP (SHapley Additive Explanations)** was used to:
- Explain individual risk predictions at the observation level
- Identify the key drivers contributing to elevated risk scores
- Provide transparent and auditable insights for stakeholders

This approach ensures that model outputs can be **understood, justified, and
communicated**, rather than treated as black-box decisions.

## Key Insights
- Academic performance indicators (validated credits, grades) are the strongest
  contributors to dropout risk
- Age at enrollment and academic engagement play a significant secondary role
- Interpretability enables targeted and explainable intervention strategies

## Business Value
This project demonstrates how **interpretable machine learning models** can be
used to support high-stakes decisions in risk-sensitive environments.

The methodology and interpretability framework are directly transferable to
applications such as:
- Credit risk assessment  
- Insurance underwriting  
- Customer churn and retention modeling  
- Compliance-driven predictive analytics  

## Data
The dataset used in this project is publicly available on Kaggle:  
https://www.kaggle.com/datasets/syedfaizanalii/predict-students-dropout-and-academic-success

## Technologies
**Python · Machine Learning · Risk Modeling · SVM · SHAP · Scikit-learn**
