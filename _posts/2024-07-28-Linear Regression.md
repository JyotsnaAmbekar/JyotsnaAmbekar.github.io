---
layout: post
title: "Linear Regression"
date: 2024-07-28 10:00:00 -0000
categories: blog
---

# Everything you need to know about Linear regression assumptions.

Here are the key assumptions:

## Linearity:

The relationship between the independent variables and the dependent variable is assumed to be linear. This means that changes in the independent variables result in a constant change in the dependent variable.

## Independence of Residuals:

The residuals (the differences between the observed and predicted values) should be independent of each other. In other words, the error term for one observation should not provide information about the error term for another observation.

## Homoscedasticity (Constant Variance of Residuals):

The variance of the residuals should remain constant across all levels of the independent variables. Homoscedasticity ensures that the spread of residuals is consistent throughout the range of predicted values.

## Normality of Residuals:

The residuals are assumed to follow a normal distribution. This assumption is important for making valid statistical inferences and constructing confidence intervals. However, linear models can be robust to deviations from perfect normality, especially with larger sample sizes.

## No Perfect Multicollinearity:

There should not be perfect multicollinearity among the independent variables. Perfect multicollinearity occurs when one predictor variable is a perfect linear function of another, making it impossible to isolate their individual effects.

## No Endogeneity:

The model assumes that the independent variables are not correlated with the residuals. Endogeneity arises when there is a two-way causal relationship between the independent variables and the error term.

## No Autocorrelation of Residuals:

The residuals should not exhibit autocorrelation, meaning that there should be no systematic pattern in the residuals over time or across observations.
