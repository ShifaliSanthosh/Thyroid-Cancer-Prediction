# Thyroid-Cancer-Prediction

This project presents a comprehensive evaluation and comparison of multiple machine learning models for predicting thyroid cancer, building upon initial accuracy findings from our base reference paper.

Dataset Collection and Pre-processing: 

This project predicts thyroid cancer using machine learning techniques, integrating multiple datasets: China Medical University Clinical Data (724 patients, 17 attributes), UCI Machine Learning Repository Health Data (383 patients, attributes for predicting thyroid cancer recurrence), Nodule Dataset from GitHub (177 thyroid nodules, 9 features), and DDTI Dataset from Kaggle (480 ultrasound images, converted to CSV format). 
The dataset used in this project is stored in "done_dataset_significant_features.csv". The dataset contains significant features selected through the p-value feature selection method.


Exploratory Data Analysis (EDA):

The correlation matrix of the dataset is visualized using a heatmap, showing the correlation between features. The distribution of each feature is plotted using histograms, showing the distribution of features by result.

Machine Learning Model Evaluation:

The performance of multiple machine learning models is evaluated using accuracy as the metric. The results are:

GBM: 0.8112
Logistic Regression: 0.8089
LDA: 0.7879
SVM (Radial): 0.7622
SVM (Linear): 0.7972
Random Forest (LOOCV): 0.8929
Random Forest (Stratified K-Fold): 0.8065

The Random Forest model showed significant enhancement in performance, particularly with Leave-One-Out Cross-Validation achieving an accuracy of 0.8929.
