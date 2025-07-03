Internship Report — Breast Cancer Detection Using SVM
Date: 3rd July 2025

Objective
To build a binary classification model for Breast Cancer Detection using the Support Vector Machine (SVM) algorithm, including complete preprocessing, exploratory analysis, model training, hyperparameter tuning, and evaluation.

Tasks Accomplished
Dataset Loading & Initial Analysis

Loaded the Breast Cancer dataset (569 rows × 31 columns).

Verified data integrity:

No missing values

No duplicate entries

Confirmed binary target (diagnosis: Benign vs Malignant)

Exploratory Data Analysis (EDA)

Visualized feature distributions using histograms.

Plotted boxplots of selected features (radius_mean, area_mean, etc.) against the diagnosis target.

Identified patterns between higher feature values and malignancy.

Feature Engineering

Applied Label Encoding to convert the diagnosis column to numerical (B=0, M=1).

Scaled all features using StandardScaler to prepare for SVM.

Applied PCA to reduce dimensionality for 2D visualization.

Model Training

Split data into train and test sets (80-20 split).

Trained two SVM models:

Linear Kernel

RBF Kernel

Model Evaluation

Evaluated both models using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Visualized decision boundaries using PCA-reduced 2D space.

Hyperparameter Tuning

Used GridSearchCV to tune C and gamma for RBF kernel.

Found the best combination: C=10, gamma=0.01.

Cross-Validation

Performed 5-fold cross-validation on the best model.

Achieved consistent accuracy with mean CV score > 96%.

Final Evaluation

Plotted heatmap of the confusion matrix.

Generated a complete classification report for test predictions.

Key Learnings
Understood the importance of feature scaling in SVM.

Learned how kernel choice (Linear vs RBF) affects decision boundaries.

Practiced model tuning using Grid Search and validation techniques.

Enhanced data visualization skills for both EDA and decision boundaries.
