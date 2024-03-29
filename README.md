# Data-Mining-Breast-Cancer

Hello! 

This is Ziyan Lin, a graduate student from Johns Hopkins University, majoring in applied math and statistics.

In this repository, there is a group project developed by data mining. Group members are Ziyan Lin, Xiao, Sun, Han Wang, Mengnan Zhao, and Siyao Zhu.

The purpose of this project is to predict whether a breast cancer is malignant or benign based on ten real-valued features: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. The dataset includes 569 observations, and it is retrieved from https://www.kaggle.com/uciml/breast-cancer-wisconsin-data.

The whole dataset was split into training and testing sets, swarm plots and heatmap were used to select features and confirm that there are no correlated features based on feature importance method. Two different thresholds were generated and produced two groups of features: one has only five features; another one has about fifteen features. Both groups were applied by data mining methods, such as Random Forest, SVM, logistic regression, and QDA. For each classifier, 10-fold cross validation with accuracy as cv score is used when training. In conclusion, five features seem to be enough to predict whether a breast cancer is malignant or benign.

This repository contains all [code for data mining](https://github.com/lzykaren/Data-Mining-Breast-Cancer/blob/master/Project%20Code.ipynb), and [one final poster](https://github.com/lzykaren/Data-Mining-Breast-Cancer/blob/master/Project%20Poster.pdf). If you have any question or suggestion, please feel free to contact me. Thank you very much.

My email address: ziyanlin3@gmail.com


