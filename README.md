# Estimating Goal Probabilities in Football Based on Event and Tracking Data

## Overview

This project focuses on estimating goal probabilities in football using event and tracking data. It explores statistical modelling techniques to develop a model for estimating the probability of a goal.

## Model Selection

The `model_selection.Rmd` file contains the code used to select an extended logistic regression model through stepwise regression.

Backward elimination was used as the model selection approach. This procedure starts with a model containing all candidate predictors and iteratively removes predictors to identify a more parsimonious model.

The `stepAIC()` function from the R `MASS` package was used to perform the selection procedure, with the Akaike Information Criterion (AIC) serving as the model selection criterion.

## Tools and Methods

- **Language:** R
- **Modelling approach:** logistic regression
- **Model selection:** Backward stepwise regression
- **Selection criterion:** Akaike Information Criterion (AIC)

## Files

- `model_selection.Rmd` — R Markdown file containing the code used for model selection.

## Skills Demonstrated

- Logistic regression
- Statistical model selection
- Backward elimination
- Information-criterion-based model comparison
- Reproducible analysis using R Markdown
