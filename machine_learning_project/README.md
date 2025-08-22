## 1. Introduction

Natural Language Processing (NLP) is presently among the hottest scientific fields with an enormous growth rate of the relevant research. Sentiment analysis is a popular NLP problem that aims at the automatic identification of the polarity in user reviews, tweets, blog posts, comments, forum discussions and so on.

In the vast majority of cases, sentiment analysis is treated as a text classification problem. If the involved text polarity is binary (i.e., positive or
negative, good or bad), then binary text classification models are trained by
utilizing two class labels. On the other hand, in case the polarity falls into a
closed score range (e.g., 1–5, 1–10, etc.), then each individual score is treated
as a separate class label and multi-class classification approaches are applied.

In this assignment you will explore various classifiers on NLP sentiment analysis. The purpose is to measure their performance on a dataset that derives from X (formerly Twitter) and contains user opinions about a US Airliner.


### Classifiers
The classifiers to be studied are:
* $C_1$: Logistic Regression
* $C_2$: Support Vector Machines (Linear kernel) - hint: use [`LinearSVC`](https://scikit-learn.org/dev/modules/generated/sklearn.svm.LinearSVC.html)
* $C_3$: Random Forests
* $C_4$: Feed-forward Neural Network


### Dataset

The classification performance of the abovementioned models will be studied on the `Twitter_US_Airline_Sentiment.csv` dataset ([see more details here](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)).




