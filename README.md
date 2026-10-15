# Estimating Goal Probabilities in Football Based on Event and Tracking Data

## Overview

This Master's thesis investigates whether Bayesian hierarchical modelling can improve goal probability predictions in football compared with frequentist approaches.

The thesis explores Bayesian hierarchical models incorporating teams, players, goalkeepers, and player positions.

The results indicate that the extended Bayesian hierarchical model, which incorporates player position as an additional hierarchy, achieved better in-sample Brier scores and log loss than the frequentist model. Its performance was also close to StatsBomb's benchmark. Model comparison using Expected Log Predictive Density (ELPD) favoured the extended Bayesian model, while prior sensitivity analysis highlighted the importance of prior specification when interpreting the results.

## Project Status

The thesis has been completed. The code is being reviewed and updated before the full project is made publicly available on GitHub. This process includes removing confidential information and making other necessary adjustments.

Currently, only the `model_selection.Rmd` file has been uploaded. The remaining code files will be added gradually as they are reviewed and prepared for public release.

## Model Selection

The `model_selection.Rmd` file contains the code used to select the extended logistic regression model through backward stepwise regression, using the `stepAIC()` function and the Akaike Information Criterion (AIC) as the model selection criterion.

## Technologies and Methods

- R and R Markdown
- Bayesian hierarchical modelling
- Logistic regression
- Frequentist and Bayesian model comparison
- Brier score and log loss
- Expected Log Predictive Density (ELPD)
- Prior sensitivity analysis
