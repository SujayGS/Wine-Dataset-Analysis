# Wine-Dataset-Analysis

This project focuses on the application of clustering and classification techniques to uncover patterns and predict outcomes from the provided dataset.

## Clustering Methods

The following clustering algorithms were used to group the data into meaningful clusters:

- **KMeans**: A widely-used partitioning method that minimizes variance within clusters.
- **Agglomerative Clustering**: A hierarchical approach that builds nested clusters by merging pairs of clusters.
- **DBSCAN**: A density-based method that finds core samples of high density and expands clusters from them.
- **BIRCH**: An efficient clustering method that handles large datasets by building a hierarchical tree structure.
- **Affinity Propagation**: A method that identifies exemplars among data points and forms clusters based on message passing.
- **Mean-Shift**: A non-parametric clustering technique that finds clusters by shifting points towards the mode.

## Classification Methods

After clustering, various classification algorithms were implemented to predict categorical outcomes:

- **Logistic Regression**: A statistical model for binary classification.
- **Gaussian Naive Bayes**: A probabilistic classifier based on Bayes' theorem.
- **Decision Trees**: A flowchart-like structure for making decisions based on feature values.
- **Random Forest**: An ensemble learning method that builds multiple decision trees for improved accuracy.
- **Support Vector Machines (SVM)**: A robust classifier that finds the optimal hyperplane for separating classes.
- **K Nearest Neighbours (KNN)**: A simple, instance-based learning algorithm that classifies data based on the nearest training samples.
- **Ada Boost Classifier**: An ensemble method that combines weak classifiers to create a strong classifier.
