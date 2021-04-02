# Bootstrapping-on-a-dataset-using-Python
The bootstrap method is a resampling technique used to estimate statistics on a population by sampling a dataset with replacement. It can be used to estimate summary statistics such as the mean or standard deviation. It is used in applied machine learning to estimate the skill of machine learning models when making predictions on data not included in the training data.
This procedure of using the bootstrap method to estimate the skill of the model can be summarized as follows:
1.	Choose a number of bootstrap samples to perform
2.	Choose a sample size
3.	For each bootstrap sample
1.	Draw a sample with replacement with the chosen size
2.	Fit a model on the data sample
3.	Estimate the skill of the model on the out-of-bag sample.
4.	Calculate the mean of the sample of model skill estimates.

****************************************************************
Cross-validation is a technique for evaluating ML models by training several ML models on subsets of the available input data and evaluating them on the complementary subset of the data. ... In k-fold cross-validation, you split the input data into k subsets of data (also known as folds).

The Leave-One-Out Cross-Validation, or LOOCV, procedure is used to estimate the performance of machine learning algorithms when they are used to make predictions on data not used to train the model.

