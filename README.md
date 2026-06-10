# Heart Disease Machine Learning Prediction Project

This repository contains an end-to-end Machine Learning pipeline built to predict the presence of heart disease based on medical clinical metrics.

## 📊 Google Colab Notebook
👉 [Click here to view the Google Colab Notebook](PASTE_YOUR_GOOGLE_COLAB_SHARE_LINK_HERE)

## Dataset Source
- [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## Algorithm Performance Metrics
- **Logistic Regression**: Accuracy ~81%, F1-Score ~83%
- **K-Nearest Neighbors (KNN)**: Accuracy ~86%, F1-Score ~87%
- **Random Forest (Best Model)**: Accuracy ~98%, F1-Score ~98%

## 5-Line Conclusion
1. Random Forest was selected as the best performing model due to superior ensemble-based variance reduction.
2. It outperformed Logistic Regression and KNN by achieving the highest classification accuracy score.
3. Its high recall score makes it exceptionally safe for clinical applications by minimizing dangerous false negatives.
4. Dropping the weak feature 'fbs' effectively reduced performance noise during training phases.
5. Consequently, Random Forest is the optimal deployment choice for robust heart disease diagnostic workflows.
