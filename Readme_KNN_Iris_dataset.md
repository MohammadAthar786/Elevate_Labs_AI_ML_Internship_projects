🗓️ Work Summary – 1 July 2025
✅ KNN classification on Iris Dataset

1. Dataset Loading and Initial Exploration
   Loaded the Iris dataset using sklearn.datasets.

Converted it into a Pandas DataFrame and added human-readable labels.

Displayed sample rows and explored class distribution.

2. Exploratory Data Analysis (EDA)
   Visualized class distributions using sns.countplot.

Generated pairplot to examine feature relationships.

Created a heatmap to analyze feature correlations.

3. Feature Selection
   Selected Petal Length and Petal Width as they showed the best class separation from EDA.

Dropped less informative features for clearer decision boundaries.

4. Preprocessing
   Performed train-test split using stratified sampling.

Applied Standard Scaling to the features using StandardScaler.

5. KNN Model Training & Evaluation (K = 3)
   Trained KNeighborsClassifier from sklearn.

Evaluated the model using accuracy score on the test set.

Displayed the confusion matrix for class-wise performance.

6. Decision Boundary Visualization
   Visualized the decision boundary for 2 selected features.

Used meshgrid and color maps for a clear boundary representation.

7. Testing Different K Values
   Tested K from 1 to 15.

Plotted K vs Accuracy to find the best-performing K value.

Reported the highest accuracy and corresponding K.
