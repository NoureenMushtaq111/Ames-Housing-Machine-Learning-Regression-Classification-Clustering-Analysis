This Ames Housing Machine Learning Project provides a comprehensive analysis of 2,930 houses in Ames, Iowa using 82 features to predict sale prices and segment properties. The project implements three machine learning tasks:

Regression (price prediction): Tested 6 models including Linear, Ridge, Lasso, Decision Tree, Random Forest, and Gradient Boosting regression. Gradient Boosting achieved the best performance with R² = 0.918, MAE = $15,186, and RMSE = $25,576, explaining 91.8% of price variation.

Classification (high/low price categorization): Using median price ($160,000) as threshold, 5 models were evaluated. Logistic Regression, Random Forest, and SVM tied with 92.5% accuracy. Hyperparameter tuning improved Random Forest to 93.4% cross-validation accuracy.

Clustering (property segmentation): K-Means identified 3 meaningful clusters (older/lower-priced, mid-range family homes, large/premium houses) with silhouette score 0.074. DBSCAN detected 1 dominant cluster with outliers, effective for anomaly detection.

Key findings: Overall quality (r=0.799) is the strongest price predictor, followed by living area (r=0.707), garage capacity (r=0.648), and basement space (r=0.632). Newer houses and premium neighborhoods command higher prices. The project includes 33 comprehensive lab Q&A covering data preprocessing, model evaluation, ethical considerations, and practical real estate applications.
