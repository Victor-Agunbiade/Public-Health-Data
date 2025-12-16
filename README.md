NY State Rabies Machine Learning Project

📌 Overview

This project applies machine learning techniques to the New York State rabies dataset to uncover insights and build predictive models. The primary goal is to classify infection risk based on county-level and sample-level features, enabling better understanding of rabies spread patterns.

🎯 Objectives

Clean and preprocess rabies dataset for analysis.

Engineer meaningful features (e.g., positivity rate, seasonality, species type).

Build classification models to predict infection presence.

Evaluate performance using accuracy, precision, recall, F1-score, and ROC-AUC.

Visualize results with confusion matrix heatmaps and ROC curves.

📂 Dataset

Source: New York State rabies surveillance data.

Key Columns:

County

Species

Positive Samples

Total Samples

Date (converted into Year, Month, Season)

🛠️ Features

Numeric Features: Positive Samples, Total Samples, Positivity Rate, Month, Year, DayOfWeek.

Categorical Features: County, Species, Season.

Derived Features: Infection presence (binary target), rolling averages, seasonal indicators.

⚙️ Pipeline

Data Preprocessing

Handle missing values.

Convert datetime into numeric/categorical features.

Scale numeric features.

One-hot encode categorical features.

Model Training

Logistic Regression, Random Forest, or other classifiers.

Train/test split with cross-validation.

Evaluation

Confusion matrix, classification report.

ROC curve and AUC score.

Precision, recall, F1-score.

Visualization

Heatmap of confusion matrix.


Feature importance charts.

📊 Example Results

Accuracy: ~99%

Confusion Matrix: [[5924, 3], [7, 1018]]

Precision: 0.997, Recall: 0.993, F1-score: 0.995

ROC-AUC: ~0.99

🚀 Next Steps

Expand dataset with environmental and demographic features.

Explore advanced models (XGBoost, Neural Networks).

Perform threshold tuning to minimize false negatives.

Deploy model for real-time rabies risk monitoring.

📜 License

This project is for research and educational purposes. Please cite appropriately if used in publications.
### Click here to see it live! https://public.tableau.com/views/Rabies_Visualization/RabiesinNY?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
