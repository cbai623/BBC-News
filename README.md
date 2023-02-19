# BBC-News Text Data Analysis Project

This project involved conducting an analysis of a text dataset, with the goal of extracting features, building and training models, and comparing supervised and unsupervised learning.

Overview

The project consisted of the following three main steps:

Extracting word features and exploratory data analysis (EDA): This involved downloading the text datasets, checking for metrics such as dataset size and null values, creating histograms and wordclouds, cleaning and tokenizing the text data, and using the TF-IDF method to convert the text into a matrix format.

Building and training models: This step included developing functions for finding the best label permutations, predicting the category based on the fitted matrix, and identifying the optimal combination of parameters for the NMF model. The training set was used for matrix factorization, and a list of top words used for each topic was printed to confirm correct topic assignment. The accuracy rate for the training dataset was over 92%, and a confusion matrix was generated for visual inspection.

Comparing with supervised learning: In this step, the SGD Classifier from the sklearn library was used to determine the mean cross-validation score of the predictions for four different dataset sizes: 10%, 20%, 50%, and 100%. The best result was achieved with 10% of the dataset, with a score of 98%, demonstrating that supervised learning generated the best results.

Requirements

The following libraries were used in this project:

numpy
pandas
matplotlib
seaborn
sklearn
nltk

How to use

Clone this repository to your local machine.
Install the required libraries using pip or conda.
Run the Jupyter Notebook to see the full project.

Credits

This project was completed by Chris Bai. The data used in this project was obtained from https://www.kaggle.com/competitions/learn-ai-bbc/data.

Conclusion
This project provides valuable insights into how text data can be analyzed and utilized for predictive modeling purposes. By following the steps outlined in this project, users can learn how to extract features from text data, build and train models, and compare supervised and unsupervised learning methods.
