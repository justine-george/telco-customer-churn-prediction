# 🔮 Telecommunications Churn Prediction


Predict customer churn in a telco using a dataset containing demographic and service data.

[Try the Live Colab Link!](https://colab.research.google.com/drive/179S9uSjffaUztRUuaNshgzbYXYcLCLeI?usp=sharing)

[Access the detailed report here](CustomerChurn_Report.pdf)

- Dataset Source: Kaggle
  - Size: 7043 customers
  - Features: 21
- Approach:
  - Conducted exploratory data analysis (EDA) to understand data distribution and characteristics.
  - Addressed class imbalance:
    - Used synthetic minority oversampling (SMOTE) for data augmentation.
    - Applied edited nearest neighbor (ENN) technique for noise reduction.
  - Employed and evaluated various machine learning algorithms:
    - XGBoost
    - KNN
    - SVM
    - Random Forest
    - And more...
  - Evaluation:
    - Utilized cross-validation techniques.
    - Metrics used:
      - Precision
      - Recall
      - F1 score
      - Area under the ROC curve (AUC-ROC)
