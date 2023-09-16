# Toxic Comment Classifier - Kaggle

Toxic Comment Classifier Kaggle using NLP and ML Algorithms.

## Problem Description

Multilabel Classification

We were required to use the training dataset to train the model to identify different labels, and apply the model on the testing dataset.

## Datasets

This is a multilabel classification dataset.

The dataset contains 3 attributes (id, comment_text, Prediction) with 6 labels in prediction to classify. There are two files in the dataset train (containing 111723 samples) and test (containing 47848 samples).

* Training - [train.csv](https://raw.githubusercontent.com/ayushabrol13/toxic-comment-classifier-kaggle/master/train)
* Testing - [test.csv](https://raw.githubusercontent.com/ayushabrol13/toxic-comment-classifier-kaggle/master/test)

## Evaluation

The evaluation metric for this assignment is Mean F1-Score. The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision p and recall r. Precision is the ratio of true positives (tp) to all predicted positives (tp + fp). Recall is the ratio of true positives to all actual positives (tp + fn). The F1 score is given by:

    𝐹1=2𝑝⋅𝑟𝑝+𝑟 where 𝑝=𝑡𝑝/𝑡𝑝+𝑓𝑝, 𝑟=𝑡𝑝/𝑡𝑝+𝑓𝑛
    
The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.

Submission Format
Submission files should contain two columns: Id and Prediction. Prediction should be comma separated.

For example

ID Prediction

0 1,0,1,0,0,1

1 1,0,1,0,0,1
