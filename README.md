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

## Sample Data

<img width="287" alt="Screenshot 2020-03-20 at 5 17 58 PM" src="https://user-images.githubusercontent.com/40054373/77543258-72b46f00-6ecd-11ea-87cc-b524695716f2.png">

## Model

<img width="606" alt="Screenshot 2020-03-20 at 5 21 58 PM" src="https://user-images.githubusercontent.com/40054373/77543313-865fd580-6ecd-11ea-936d-ff416154546f.png">

## Results

<img width="398" alt="Screenshot 2020-03-20 at 5 22 55 PM" src="https://user-images.githubusercontent.com/40054373/77543375-9a0b3c00-6ecd-11ea-8155-776d4dbed6f6.png">


