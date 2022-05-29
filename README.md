# datamining-project
This notebook applies SVM, KNN classification algorithms, and Clustering by K-Means algorithms.
It analyzes dataset by plotting multiple diagrams to further understand variables relationships, correlations, etc, plots include violin plots, heatmap, etc. 
It also preprocesses the dataset before applying any algorithm, like dropping irrelvant columns-dataitems that are reduntant, scaling of data, Normalization of data, etc
The dataset used is Credit Card Fraud Detection, where there are independent variables and a class label of whether a Credit Card is a Fraud or not
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
This notebook also has accuracy measures applied to each algorithm along with other performance measures, like f1 score, precision, recall, etc. 
A confusion matrix is plotted for each algorithm as well. 
Visualization for each algorithm is also covered in this notebook, however, dimensionality reduction , PCA, or selection of strongly correlated variables were used as the data dimensions were too big to plot.

dataset link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
