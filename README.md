# UnsupervisedLearning_PCA_Analysis
Exploration of the differences between US States by 1973 Crime and Urban Population Stats using unsupervised learning methods such as Principal Component Analysis (PCA) and various clustering techniques. The results of the analysis are presented using various visualizations, which allow for an in-depth understanding of the data.

The code is written in Python 3.11 and run on a Jupyter Notebook in Visual Studio Code.

# Required Libraries
The following libraries are required to run the code:

Numpy
Pandas
Missingno
Scikit-learn
Matplotlib
Seaborn

# Data Preprocessing
Before the analysis is conducted, the data must be preprocessed to ensure it is in the correct format. This includes dealing with any missing values and scaling the data. The following techniques are used for data preprocessing:

MinMaxScaler
LabelEncoder
StandardScaler

# PCA Analysis
The PCA analysis is conducted using the PCA class from the scikit-learn library. This allows us to visualize the data and identify any patterns or redundancies in the data. Biplots are produced to visualize the patterns between objects in the data.

# Clustering
Clustering is performed using the KMeans and Agglomerative Clustering algorithms from the scikit-learn library. The evaluation metrics used to assess the performance of the clustering algorithms include:

Confusion Matrix
Silhouette Score

# Visualization
Visualization is performed using the Matplotlib and Seaborn libraries. This includes producing plots to visualize the data and assess the performance of the clustering algorithms.
