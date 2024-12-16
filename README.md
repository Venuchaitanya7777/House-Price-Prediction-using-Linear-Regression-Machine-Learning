# House-Price-Prediction-using-Linear-Regression-Machine-Learning
I have a strong interest in applying machine learning to solve real-world problems. For this project, I worked on predicting house prices using linear regression, inspired by the importance of accurate pricing in real estate.
The goal was to develop a machine learning model that predicts the selling price of houses based on various features, such as the size, location, and number of bedrooms.
Approach and Workflow
Dataset Selection:
I used the Kaggle House Prices dataset, which provides rich data with features like square footage, year built, and garage size, among others.
Data Preprocessing:

The dataset had missing values, so I handled them by filling numerical data with medians and dropping irrelevant columns like Alley and Fence which had too many null values.
feature scaling or encoding if applied.
Exploratory Data Analysis (EDA):

I visualized the relationships between features and the target variable (SalePrice) using correlation heatmaps and scatter plots. This helped identify the most important predictors, such as OverallQual and GrLivArea.
Model Building:

I implemented the model using Python’s scikit-learn library, splitting the data into training and testing sets to evaluate its performance.
choice of algorithm: I chose Linear Regression as it fits well with continuous target variables like house prices.
Model Evaluation:

To measure the model’s accuracy, I used metrics like Mean Squared Error (MSE) and R-squared. The model achieved an R-squared value of around 0.85, indicating a good fit.
