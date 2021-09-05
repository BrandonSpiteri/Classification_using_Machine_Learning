# Classification using Machine Learning
A two class classification problem, approached using the following Machine Learning techniques:
1. knn
2. Perceptron
3. Naive Bayes
4. Logistic Regression
5. Linear and kernelised SVM

The dataset is 2D image. PCA is used for dimensionality reduction. 

Performance is reported using:
1. Accuracy
2. AUC-ROC
3. AUC-PR

Given the nature of the classification problem, the prediction is optimised using AUC-ROC metric. 

# Summarised Results:

| Model  | AUC-ROC |
| ------------- | ------------- | 
| k-Nearest Neighbour		  | 0.911	 | 
| Perceptron		| 0.778	 |
| Gaussian Naïve Bayes		| 0.742	  |
| Logistic Regression		| 0.804	 |
| Linear SVM		| 0.800	 |
| Kernelized SVM		| 0.932		 |

