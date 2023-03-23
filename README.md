# Linear Regression for Predicting Housing Prices

This project demonstrates the use of linear regression to predict housing prices in Location of Dataset using Python. The project uses a dataset of housing prices and splits the data into training and testing sets. A linear regression model is then trained on the training data, and the model's performance is evaluated on the testing data.

## Libraries Used
The project uses several Python libraries to achieve its objectives. These libraries include:

  1. Pandas: This library is used to load and manipulate the dataset.
  2. Matplotlib: This library is used for creating visualizations in Python.
  3. Seaborn: This library is used for creating more advanced visualizations in Python.
  4. Scikit-learn: This library is used for implementing machine learning models, including linear regression.

## Data Loading and Preparation
The first step in the project is to load the 
housing prices dataset using Pandas. The dataset is stored in a CSV file, which is loaded using the read_csv function. The dataset is then split into training and testing sets using the train_test_split function from the Scikit-learn library.

## Training and Testing the Model
The next step in the project is to train a linear regression model on the training data. The LinearRegression class from Scikit-learn is used to create the model, and the fit method is used to train the model on the training data. Once the model is trained, it is used to predict housing prices on the testing data using the predict method. The mean squared error and root mean squared error are calculated to evaluate the model's performance.

## Visualizing the Results
Finally, the results are visualized using the Seaborn library. The actual and predicted housing prices are compared using a dual graph of actual vs predicted, and the graph is plotted using the lmplot function.

## Conclusion
In conclusion, this project demonstrates the use of linear regression to predict housing prices using Python. The project shows how to load and manipulate data using Pandas, train and test a linear regression model using Scikit-learn, and visualize the results using Seaborn. The project provides a useful example for anyone interested in machine learning, data analysis, or data visualization in Python.
