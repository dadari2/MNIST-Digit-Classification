# MNIST-Digit-Classification

This repository contains the results of a classification task on the MNIST dataset using different machine learning algorithms.

Trained  four different algorithms on the MNIST dataset and evaluated their performance. The results are summarized below.

Algorithm	Validation Error	
KNN	- 0.0303,
Naive Bayes	- 0.1632,
Logistic Regression	- 0.073,
MLP - 0.0221

Additionally, analyzed the confusion matrix for KNN to determine which label is most commonly confused with each true label. The results are shown in the table below.

True Label	Most Common Mistaken Label	% of Times Assigned to That Label
![image](https://user-images.githubusercontent.com/123693018/229372554-e461ff9b-0768-4f79-b37b-ca1cc86dfe4c.png)


Parameter Selection
Performed a parameter selection process for each algorithm and found the best hyperparameters. The results are shown in the table below.

![image](https://user-images.githubusercontent.com/123693018/229372636-14577151-8109-45f0-9b9d-f15f93420db0.png)

MLPs with MNIST
Also trained a Multi-Layer Perceptron (MLP) on the MNIST dataset with default parameters and reported the training and validation losses after different number of epochs.
![image](https://user-images.githubusercontent.com/123693018/229372681-5deae9ee-b96e-436d-b922-863c640bf91f.png)


Finally, we found the best model with the following hyperparameters: number of epochs = 100, learning rate = 0.001, hidden size = 128, optimizer = Adam. The training, validation, and test errors for this model are shown below.
![image](https://user-images.githubusercontent.com/123693018/229372740-7cf43e5e-1b5d-4168-8edd-cb7ec47c220d.png)
