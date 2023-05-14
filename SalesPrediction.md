# Sales Prediction
This project uses a dataset of advertising spending across different channels to predict sales using a regression model. The project is implemented using Python and the following libraries: NumPy, Pandas, Seaborn, Scikit-learn, and Matplotlib.

## Dataset
The dataset used in this project is the Advertising.csv file, which contains data on advertising spending across three channels (TV, radio, and newspaper) and the resulting sales. The data is read into a Pandas dataframe and cleaned by dropping the Unnamed: 0 column. The resulting dataframe has 200 rows and 4 columns.

## Exploratory Data Analysis
The relationship between the advertising spending and sales is explored using a pair plot from Seaborn. The plot shows the relationships between the three channels and the sales, with TV advertising showing the strongest correlation with sales.

## Model Training and Evaluation
The dataset is split into training and testing sets using the train_test_split function from Scikit-learn. The data is then standardized using the StandardScaler function to improve the performance of the model. The Linear Regression model is trained on the standardized training data and used to predict sales on the standardized test data. The model achieved an R-squared score of 0.93, indicating a good fit between the model and the data.

Finally, a scatter plot is used to visualize the relationship between the predicted sales and the actual sales in the test set.

## Conclusion
This project demonstrates the use of regression models to predict sales based on advertising spending data. The results show that TV advertising spending is the most significant factor in predicting sales. This model can be used by businesses to optimize their advertising spending across different channels to maximize their sales.
