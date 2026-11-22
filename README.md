# Comparing Calibration Methods for Predicting NC-to-MCI

Evaluating Temperature Scaling, Beta Calibration and Isotonic Regression on Machine Learning Models

Authors: Ivana Královicsová, Ing. Martina Billichová, PhD.
Faculty of Informatics and Information Technologies, Slovak University of Technology in Bratislava
Výberový seminár, FIIT STU, 2026

## About

This repository contains the proof of concept for our paper and also our paper. We compare three post-hoc
calibration methods (temperature scaling, beta calibration and isotonic regression) applied to
three machine learning models (logistic regression, random forest and XGBoost) that predict
whether a patient will develop mild cognitive impairment (MCI) within four years.

The methods are evaluated using the expected calibration error (ECE), the Brier score,
reliability diagrams and AUC.

## Files

- "IvanaKralovicsova_Zadanie3_PoC" – code with comments and results
- "IvanaKralovicsova_Zadanie3_VedeckyClanok" - the paper
- "reliability diagram *.png" – reliability diagrams for each model

## Data

We used data from the NACC (National Alzheimer's Coordinating Center) database (https://naccdata.org).

The notebook expects the files "train.csv" and "test.csv" in the same folder.

## Requirements

Python 3 with the libraries: numpy, pandas, scipy, scikit-learn, xgboost, matplotlib

## Acknowledgments

The NACC database is funded by NIA/NIH Grant U24 AG072122. NACC data are contributed
by the NIA-funded ADRCs.
