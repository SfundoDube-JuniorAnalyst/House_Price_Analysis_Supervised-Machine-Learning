# House Price Prediction

A supervised learning project predicting residential property prices, pairing a regression approach with a classification approach on the same dataset.
Tasks:
Linear Regression → predicts continuous price
Logistic Regression → classifies homes as expensive vs affordable (split at median price)
Results: Linear Regression — RMSE ≈ 1,331,071 · Logistic Regression — 85.32% accuracy
Workflow: missing value handling → feature selection & encoding → train/test split → feature scaling → model training → evaluation → visualization (actual-vs-predicted, confusion matrix, feature importance)
Key insight: area and stories are the strongest price drivers, followed by air conditioning, preferred area, and bathroom count.
