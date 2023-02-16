# Supervised Learning using Random Forest Classifier Ensemble Method for Processing MNIST Dataset
This project involves using the Random Forest Classifier ensemble method to perform supervised learning on the MNIST dataset. The goal is to optimise the performance of the classifier by testing various parameters and evaluating the accuracy using the silhouette score.

The code is written in Python 3.11 and run on a Jupyter Notebook in Visual Studio Code.

# Required Libraries
The following libraries are required to run the code:

Numpy
Pandas
Scikit-learn
Matplotlib

# Data Preprocessing
Before the analysis is conducted, the data must be preprocessed to ensure it is in the correct format. This includes dividing the dataset into training, development, and test sets. The following techniques are used for data preprocessing:

Train-Test Split

# Random Forest Classifier
The Random Forest Classifier is implemented using the RandomForestClassifier class from the scikit-learn library. The performance of the classifier is evaluated using the silhouette score.

# Model Tuning
The performance of the classifier is optimized by testing various parameters such as the number of estimators, max depth, and min samples split. The best parameters are determined using the development dataset.

# Evaluation
In order to assess the performance of the classifier, the silhouette score was used to evaluate its accuracy on the test dataset. Additionally, a confusion matrix was generated to identify which digits were most challenging to classify accurately.

# Visualization
Visualization is performed using the Matplotlib library to assess the performance of the classifier and visualize the results.
