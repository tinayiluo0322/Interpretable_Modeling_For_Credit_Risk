# Interpretable Modelling of Credit Risk

## Project Description

This project focuses on developing interpretable models for predicting credit risk, emphasizing the importance of using models that are transparent and understandable, especially in high-stakes decision-making scenarios. As Cynthia Rudin highlights in her commentary on interpretability, the reliance on black-box models poses significant risks due to their inherent lack of transparency. Instead, we utilize Generalized Additive Models (GAMs), which provide a balance between model complexity and interpretability, ensuring that the predictions made can be trusted and understood by stakeholders.

## Motivation

Efforts to create "explainable black box models" are inherently flawed because these explanations often fail to capture the true workings of the original models. Rudin's paper underscores that any explanation for a black-box model will be incorrect at times, which limits the trust in both the explanation and the original model. In critical applications such as credit risk modeling, it is crucial to have models that are inherently interpretable, thus ensuring that decisions can be explained and justified.

## Data Source

The dataset used for this project is from the 14th Pacific-Asia Knowledge Discovery and Data Mining conference (PAKDD 2010). It covers the period from 2006 to 2009 and originates from a private label credit card operation of a Brazilian credit company and its partner shops.

- **Dataset Period:** 2006-2009
- **Source:** PAKDD 2010 competition
- **Link:** [PAKDD 2010 Dataset](https://pakdd.org/archive/pakdd2010/)

## Modeling Approach

### Generalized Additive Models (GAMs)
GAMs are a flexible class of models that allow us to capture non-linear relationships between the predictors and the response variable while maintaining interpretability. Unlike Generalized Linear Models (GLMs), GAMs do not assume a strictly linear relationship and instead use smooth functions to model the effects of predictors.

#### Tools and Libraries
- **pyGAM:** A Python library for GAMs, which we use to build and evaluate our models.
  - [pyGAM Documentation](https://pygam.readthedocs.io/en/latest/notebooks/tour_of_pygam.html)
- **mvgam:** An R package considered the gold standard for GAMs, developed by pioneering researchers in the field.
  - [mvgam Documentation](https://nicholasjclark.github.io/mvgam/)
- **statsmodels:** A Python library that includes an implementation of GAMs.
  - [statsmodels GAM](https://www.statsmodels.org/stable/gam.html)
- **Prophet:** A time series forecasting library by Meta, which is based on GAMs.
  - [Prophet Documentation](https://facebook.github.io/prophet/)

## Objectives

1. **Develop Interpretable Models:** Use GAMs to create models that are transparent and provide clear insights into how different factors affect credit risk.
2. **Evaluate Model Performance:** Assess the accuracy and reliability of the GAMs in predicting credit risk, ensuring that they are both effective and interpretable.
3. **Compare with Black-Box Models:** Highlight the advantages of GAMs over traditional black-box models in terms of interpretability and trustworthiness.

## Conclusion

By focusing on interpretable modeling techniques like GAMs, this project aims to demonstrate the feasibility and benefits of using transparent models in credit risk prediction. The insights gained from these models can help financial institutions make more informed decisions, ensuring that the models used in high-stakes environments are both reliable and understandable.

Feel free to explore the repository, follow the analysis, and reach out with any questions or suggestions!
