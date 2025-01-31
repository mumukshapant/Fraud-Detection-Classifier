# Bank Fraud Detection 

Dataset on https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022
Reference Paper - https://proceedings.neurips.cc/paper_files/paper/2022/hash/d9696563856bd350e4e7ac5e5812f23c-Abstract-Datasets_and_Benchmarks.html

## Overview
This project aims to tackle the challenge of Bank Fraud Detection by implementing various classification models. Our primary objective is to minimize False Negatives, ensuring fraudulent transactions are accurately identified. We have trained and fine-tuned over 5 classifier algorithms leveraging Linear Regression, Logistic Regression, Decision Trees, Gradient Boosting Machine, and Multilayer Perceptron. 

We handled outliers from raw data. Performed Data Preprocessing, Feature Engineering, and Ablation analysis and applied cross-validation on data to ensure robust generalization to unseen data.

Among the models tested, **Gradient Boosting Machine (GBM)** provides the best performance, achieving an accuracy of **82%** with optimized hyperparameters, including a learning rate of 0.0947, a max_depth of 5, and max_features set to 'sqrt'. This model produces a False Negative count of 619 instances, as shown in the confusion matrix. Overall, it successfully classifies 82% of instances, with balanced precision and recall for both classes. 

The Logistic Regression model, when fine-tuned, achieves 80% accuracy, and its F1-scores indicate that it generalizes reasonably well to unseen test data.
