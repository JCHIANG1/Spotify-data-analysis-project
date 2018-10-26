## Spotify data analysis project

### Dataset Information 
This is a dataset of 1420 songs with 12 numerical attributes and 1 categorical attributes from Spotify's API. For each song, there is a "mood" label that recommend the best timing to listening to the song. 

### The First Notebook
The goal of the first notebook is to
1. explore and clean the data, solve the class imbalanced problem 
2. apply three main classification approaches used in data mining: Naïve Bayes, decision trees, and k-nearest neighbors.
3. parameters tunning for the decision trees and k-nearest neighbors models to avoid overfitting and to find the parameter configuration that yields the best performance
4. report performance and misclassification matrix on both training set and testing set 
5. find variables that are most relevant for the classification process.

### The Second Notebook
The goal is to 
 1. repeat the holdout procedure to evaluate the model performance with confidence interval
 2. analyze and compare the model perfomance with the paired t test
 3. evaluate probabilistic classifiers with ROC, Lift curves and gain chart to report insights
