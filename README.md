# Wine-Classifier



Problem: Multiclass classification (3 wine cultivars) using chemical analysis (13 features).

Goal: Achieve >90% accuracy (met with SVM/RF).

Method: Train/validation via Stratified 5-fold CV; final evaluation on holdout test.

Models: Logistic Regression (baseline), SVM (RBF), Random Forest, (optional) XGBoost.

Metrics: Accuracy + classification report + confusion matrix.

Results: Report CV mean ± std and Test accuracy; include CM figure.

Insights: Which features matter (RF importances), any misclassification patterns.

Conclusion: Small, clean dataset; SVM/RF achieve >95–99% accuracy with minimal tuning.
