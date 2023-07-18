# linear-regression
This code demonstrates how to perform linear regression using the scikit-learn library and visualize the results using Matplotlib.
![download (2)](https://github.com/ivias2000/linear-regression/assets/125237611/a0ed3b06-47ae-492e-bad9-b435bccfcc59)

Here's a step-by-step explanation of the code:

The code starts by importing necessary libraries: numpy (as np), pandas (as pd), LinearRegression from sklearn.linear_model, and matplotlib.pyplot (as plt).

It reads data from an Excel file named "linear_regression_data.xlsx" and stores it in a Pandas DataFrame called data.

The columns "input1", "input2", and "input3" are selected from the DataFrame data, and their values are combined to create a 2D NumPy array called vorudi. Similarly, the "output" column values are extracted to create a 1D NumPy array called khoroji.

The code selects only the values of the "input2" column from the DataFrame data and stores them in a 1D NumPy array called x.

A LinearRegression model is created and initialized as model.

The model is trained using the fit() method with vorudi as the input data and khoroji as the target data.

The model's predictions (y_prd) are calculated using the predict() method with vorudi as the input.

The code creates a plot using Matplotlib with two sets of data:

Points representing the predicted values (y_prd) against the "input2" values (x) are plotted as circles ('o').
Points representing the actual values (khoroji) against the "input2" values (x) are plotted as a line.
Finally, the plot is displayed using plt.show().

The code essentially fits a linear regression model to the data and visualizes the fitted line and actual data points. It allows you to understand how well the model fits the data and the relationship between the input feature "input2" and the output "output".
