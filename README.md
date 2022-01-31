# Zero Inflated Time Series Analysis of Terrorism in India

## Abstract

With recent advent of statistical analytics in various fields zero inflation has become a common nuisance. Such an explosive number of zeros has become a necessary detail to be addressed while analyzing the number of terrorist attacks in India. This article tries to exploit an observation-driven model to handle this issue. Time-series modelling of count data is a challenging topic and since popular auto-regressive and moving average (ARMA) models are restricted to continuous state-space they have been included in modelling the distributional parameters. The counts given the past history of the process and other information from covariates is assumed to follow a mixture of a Poisson distribution and a distribution degenerate at zero, with a time dependent mixing parameter 𝜋𝑡 . Since, count data usually suffers from overdispersion, a Gamma distribution is used to model the excess variation, resulting in a zero inflated Negative Binomial (NB) regression model with mean parameter 𝜆𝑡 . Linear predictors with auto regressive and moving average type terms and trend are fitted to 𝜆𝑡 and 𝜋𝑡 through canonical link generalized linear models.

## Dataset
[Global Terrorism Database](https://www.start.umd.edu/gtd/)
