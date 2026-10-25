# Predicting Response to Marketing Campaigns

A group coursework project developed for Multivariate Analysis at Instituto Superior Técnico, Universidade de Lisboa.

## Overview

This project studies customer response to a marketing campaign using an iFood campaign dataset. The objective is to identify customers likely to respond while accounting for the costs and returns of contacting them.

Rather than relying on classification accuracy alone, the analysis considers how predicted probabilities and decision thresholds translate into expected profit.

## Methods

- Exploratory analysis of customer characteristics, purchasing behaviour and previous campaign responses.
- Examination of class imbalance and correlations between predictors.
- Principal component analysis (PCA) and PCA-based logistic regression.
- Comparison of classification models, including logistic regression, Lasso-regularised logistic regression, random forests and neural networks.
- Model and decision-threshold assessment using a profit-based framework.
- Assessment of classification uncertainty using PAC and farness diagnostics.

## Main Finding and Limitations

Among the models evaluated in the report, Lasso-regularised logistic regression achieved the highest test-set profit under the assumed payoff structure. This finding applies to the reported dataset and evaluation setup; it does not establish superior performance on future campaigns.

The analysis predicts observed response rather than the causal effect of contacting a customer. The report discusses uplift modelling and further validation as possible extensions.

## Report

[Read the project report](report.pdf)

## Authors

- Bruno Picoto
- David Albino
- Mariana Galego
- Nuno Wang

## Academic context

- **Course:** Multivariate Analysis.
- **Institution:** Instituto Superior Técnico, Universidade de Lisboa.
- **Date:** December 2025.

This is a coursework project, not a production deployment or a claim of affiliation with iFood.

**Disclaimer:** This text was AI generated.
