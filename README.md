# Titanic Challenge

In this code, we compare three main classifiers: Support Vector Machine, Fully Connected Neural Network and Random Forest.

In order to compare their performance, we assess the time needed to train them on a training set, the accuracy reached on the test set and the confusion matrices.

In order to see the impact of synthetic data, we have also created fake data (inputs/swimworld.csv and inputs/titanic_tailor.csv). These data correspond to the fact that the passenger belonged or not to swimming club (0 or 1) and the weight and the height of the passenger. These synthetic data are only used to see their impact on the result of the classification. 

The main script is the file titanic_main.ipynb.
The script extraction.ipynb is used to extract the data from the csv.files
The script prepareData.ipynb is used to prepare the data: split them into training and test set, carry out PCA
The script confusion_matrix.ipynb is used to draw a confusion matrix by taking in input the predicted and the real labes of the test set.

## Libraries

numpy / sklearn

## Functions

confusion_matrix.ipynb : creates nice confusion matrices
extraction.ipynb : extract the data from the csv.files
prepareData.ipynb : pre-process the data
