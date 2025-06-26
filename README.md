# Task-3-Car Price Prediction using Linear Regression.
 🚗 Car Price Prediction using Linear Regression
Hey! 
This is a small project I did to understand **Linear Regression** using a car price dataset.
I used Python libraries like `pandas`, `sklearn`, and `matplotlib` for this. Below is what I did step-by-step .

==> Steps I Followed:

1. Imported libraries like pandas, matplotlib, seaborn, sklearn.
2. Loaded the dataset from a CarPrice  using `pd.read_csv().
3. Preprocessed the data:
   * Dropped the `Car_Name` column since it's not useful for regression
   * Handled categorical columns with one-hot encoding.
4. Split the datainto training and testing sets (`train_test_split`).
5. Trained a Linear Regression model using `sklearn.linear_model`.
6. Made predictions on the test set.
7. Evaluated the model using MAE, MSE, and R² score.
8. Plotted a graph of actual vs predicted prices.
9. Checked model coefficients to understand feature impact.
