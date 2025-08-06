# CodeAlpha_Heart-Disease-Prediction-from-Medical-Data-


##  Project Overview
This machine learning project predicts the presence of heart disease using patient clinical data. Features were selected using Random Forest importance, and a classification model was built using XGBoost. The dataset includes attributes like chest pain type, cholesterol, maximum heart rate, and ST depression.

Key steps:
- Feature selection using `RandomForestClassifier`
- Data scaling with `StandardScaler`
- Model training using `XGBClassifier`
- Evaluation using classification metrics and visualizations

##  Results

- **Top Features Used**:
  `['cp', 'thalach', 'ca', 'oldpeak', 'thal', 'age', 'chol', 'trestbps']`

- ✅ **Model Performance**:
  - **Accuracy**: *0.94*  
  - **ROC AUC Score**: *0.98*  
  - Confusion Matrix and ROC Curve plotted for visual evaluation

The model demonstrated strong classification performance and is well-suited for early detection of heart disease.
