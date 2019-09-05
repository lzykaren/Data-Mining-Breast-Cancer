# Data-Mining-Breast-Cancer

Hello! 

This is Ziyan Lin, a graduate student from Johns Hopkins University, majoring in applied math and statistics.

In this repository, there is a group project developed by data mining. Group members are Ziyan Lin, Xiao, Sun, Han Wang, Mengnan Zhao, and Siyao Zhu.

The purpose of this project is to predict whether a breast cancer is malignant or benign based on ten real-valued features: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. The dataset includes 569 observations, and it is retrieved from https://www.kaggle.com/uciml/breast-cancer-wisconsin-data.

We split whole dataset into training and testing set, used swarm plots and heatmap to select features and confirmed that there are no correlated features based on feature importance method. We set two different thresholds and finally kept two groups of features: one has only five features; another one has about fifteen features. Both groups were applied by data mining methods, such as Random Forest, SVM, logistic regression, and QDA. For each classifier, 10-fold cross validation with accuracy as cv score is used when training. In conclusion, we found that five features seem to be enough to predict whether a breast cancer is malignant or benign.

This repository contains all code for classification, and one final poster. If you have any question or suggestion, please feel free to contact me. Thank you very much.

My email address: ziyanlin3@gmail.com


