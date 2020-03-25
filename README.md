# Outlier Detection in Text Data

## Problem Statement

To detect badly formatted/invalid addresses (Outliers) in a corpus of addresses.

## Unsupervised Approaches 

1. Clustering - DBScan and KModes clustering was done and resultant rules were analyzed.
2. Rule based methods - Based on crude analysis and observation of data.

## Supervised Approach

1. Randomly corrupt some percentage of the total data and mark these s outliers.
2. Train a binary classifier to predict these outliers, with a special attention on recall for outlier class.
3. Generally better, since the model is not deterministic based on rules, but learns the rules during training, which is more robust as far as generalization is concerned.
