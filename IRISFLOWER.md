# IRIS FLOWER CLASSIFICATION
This is a Python project for Iris flower classification using machine learning. The Iris flower dataset contains three species: setosa, versicolor, and virginica, with different measurements. The goal of this project is to train a machine learning model to learn from the measurements of the iris species and classify them.

## Libraries Used
sklearn - for loading the Iris dataset and building machine learning models.
pandas - for data manipulation and analysis.
numpy - for numerical operations and array manipulation.
matplotlib - for data visualization.

## Dataset
The dataset used in this project is the Iris flower dataset, which is included in the sklearn library. The dataset consists of 150 samples, with each sample having four features: sepal length, sepal width, petal length, and petal width. The samples are labeled as one of the three species: setosa, versicolor, or virginica.

## Project Structure
iris_classification.ipynb - Jupyter notebook containing the Python code for this project.
README.md - This readme file.

## Exploring the Data
In the iris_classification.ipynb notebook, we first load the Iris dataset using the load_iris() function from sklearn. Then, we explore the dataset by printing the features and the target values. We also create a pandas DataFrame to store the dataset and visualize the data using various plotting techniques.

## Data Preprocessing
Before training our machine learning model, we preprocess the data by mapping the target values to their respective species names. We also split the data into training and testing sets using the train_test_split() function from sklearn.

## Building the Machine Learning Model
We train a logistic regression model using the training set and evaluate its performance on the testing set. We also visualize the decision boundary and the confusion matrix to gain insights into the model's performance.

## Conclusion
This project demonstrates how to build a machine learning model for Iris flower classification using logistic regression. We achieve an accuracy of around 95% on the testing set, indicating that the model is able to classify the flowers with a high degree of accuracy.
