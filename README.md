# Introduction
In this project, we perform binary classification of cardiovascular disease using two machine learning algorithms: Support Vector Machine (SVM) and K-Nearest Neighbors (KNN). These are popular and powerful algorithms in the field of machine learning, especially for classification problems.
To optimize the processing and analysis of large datasets, the SVM and KNN models are deployed on the Apache Spark platform. Apache Spark is a distributed data processing system designed to process large-scale data at high speeds. Spark allows for distributed and parallel computations across clusters of computers, helping to speed up processing and improve system performance.
In this project, the main objective is to compare the performance of the two algorithms, SVM and KNN, in predicting cardiovascular disease, thereby determining the most effective method. The research process begins with collecting and preparing cardiovascular disease data. This data includes multiple attributes related to patients' health and lifestyle habits, such as age, gender, BMI, blood pressure, blood glucose levels, and other risk factors.

# Illustration of parallelization of the algorithm
## SVM

SVM (Support Vector Machine) is a supervised learning algorithm capable of being used for both classification and regression tasks, but it is primarily applied to classification problems. In this algorithm, data is represented as points in an n-dimensional space (where n is the number of features). The value of each feature corresponds to a coordinate in that space. The task of SVM is to find a "hyperplane" that separates the classes. Simply put, a hyperplane is a straight line that can divide the data into two distinct parts, corresponding to different classes.
![image](https://github.com/user-attachments/assets/ece310d5-0a5d-4c75-b31e-3f60d2e84fcc)

![image](https://github.com/user-attachments/assets/2cdd43f0-7958-4d13-9f17-d8c124c32221)

## KNN
K-Nearest Neighbors (KNN) is a simple, supervised machine learning algorithm used for classification and regression tasks. It works by finding the k closest data points (neighbors) to a query point and making predictions based on the majority class (for classification) or the average value (for regression) of these neighbors. KNN is non-parametric and instance-based, meaning it makes decisions based on the entire dataset rather than a model. It is easy to implement and understand but can be computationally expensive and sensitive to the choice of k and the distance metric used.
![image](https://github.com/user-attachments/assets/adece265-58c2-4312-b2a3-7e9dbf3e396c)
![image](https://github.com/user-attachments/assets/7cdf21e1-b85b-4d5e-a8a1-307e491055e1)


# Report link
https://docs.google.com/document/d/1nRPd8dUugEjP1wcMZ34qaQsoASRyR3W8xHZWsuTsBIQ/edit?usp=sharing
