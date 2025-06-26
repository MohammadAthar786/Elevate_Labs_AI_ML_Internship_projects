House Price Prediction

Regression problem

->Did Inspection of dataset to get initial insights about dataset using .shape(),info(),.describe() etc functions of Pandas check for missing value, duplicate Rows , constants value coloumns , identify categorical and numerical features
->Detect and Handle Outliers using box Plot and removed them from IQR Method
->check Distribution of Numerical Features using Histogram+KDE plots also draw mean and median line to get the idea of skewness , also find skewness using parameters, but didn't find Skewness much so that Transformation can be applied
->Make Correlation Matrix of numerical features and plot Heatmaps to identify correlation of features with target feature
->Did Extensive EDA , by plotting Histogram +KDE plots for numerical Features and count plot for Categorical Features
then encode categorical coloumns , used One hot Encoding , ordinal Encoding can also be done for furnished ,semi-furnished,not-furnished but that feature don't correlate much with Target
->After Encoding select relevant Features for Model training
->Make the Dataset into Dependent and independent Feature , X and y(Target)
->split the Dataset using test_train_split
->Applied Linear Regression Model
->Evaluate Metrics to check Model Performance
