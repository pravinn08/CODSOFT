Task 2 – Movie Rating Prediction with Python

Objective: Predict IMDb ratings of Indian movies using features such as Year, Duration, Genre, and Votes.

Dataset: IMDb India Movies Dataset (Kaggle)

Steps Performed:

* Loaded the dataset using Pandas with `latin1` encoding.
* Cleaned and converted Year, Duration, Votes, and Rating into numeric format.
* Removed rows with missing values and handled categorical data using one-hot encoding for Genre.
* Split the dataset into training and testing sets (80/20).
* Applied the **Linear Regression** model to predict movie ratings.

Model Evaluation:

* Mean Squared Error (MSE): **1.641**
* Mean Absolute Error (MAE): **1.021**
* Root Mean Squared Error (RMSE): **1.281**
* R² Score: **0.117**

The model predicts movie ratings with an average error of approximately 1 rating point and explains about 11.7% of the variation in ratings.

Learning Outcomes:

* Learned to clean and preprocess real-world datasets.
* Converted text-based features into numerical values.
* Applied feature engineering using one-hot encoding.
* Built and evaluated a regression model using multiple performance metrics.

Tools & Libraries: Python, Pandas, NumPy, Matplotlib, Scikit-learn.
