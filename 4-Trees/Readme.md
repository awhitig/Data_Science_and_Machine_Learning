## Decsion Trees

Within this directory, you will find two implementations of decision trees. The first file, DecisionTree.ipynb, consists of a classification example predicting country region based on a grouping of continuous variables from a global happiness survey. The second file, RegressionTree.ipynb, is a regression example predicting starting median salary by college type and college region. Both examples serve to illustrate the uses and drawbacks of decision trees for both classification and regression problems.

Packages Used:
1. matplotlib
2. numpy
3. seaborn
4. sklearn

In this section two datasets are used. The first, found within 2015.csv, consists of global happiness survey data from many countries as well as the regions of those countries. The happiness survey data is in a continuous format with a score and a number of factors indicating strength of impact (ex. freedom,  health). This data is used within tbe DecisionTree.ipynb file to show decision tree classification. This dataset is also used within the KNN, ensemble, and K-means examples for reference. The second dataset consists of three csv files degrees-that-pay-back.csv, salaries-by-college-type.csv, and salaries-by-region.csv. That I have joined within the RegressionTree file. The daa consists of categorical college type and region and a continuous repsonse median starting salary. The dataset is used to demonstrate te regression ability of a decision tree. For contrast, this dataset is also used within the ensemble section. Both datsets were obtained from Kaggle.com as .csv files. 
