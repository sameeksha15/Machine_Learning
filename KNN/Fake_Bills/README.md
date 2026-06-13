# Fake Bills Detection (KNN)

This project focuses on distinguishing between genuine and counterfeit banknotes using K-Nearest Neighbors.

## Dataset
The dataset (`fake_bills.csv`) provides dimensional and printed features of banknotes, such as diagonal layout, height (left and right), margins, and length.

## Objective
To build a classification model capable of authenticating bills based on geometric and physical measurements.

## Methodology
Within `Fake_Bills.ipynb`, the data is explored for distinguishing patterns, preprocessed, and fed into a KNN classifier. The optimal number of neighbors (k) is determined to maximize detection accuracy.
