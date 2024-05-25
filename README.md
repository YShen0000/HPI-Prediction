# J.P. Morgan Asset Management Project: House Price Index Analysis

## Objective
This comprehensive report integrates learnings from prior literature with empirical analysis to deepen the understanding of the Housing Price Index (HPI) dynamics in various urban contexts. As part of a broader, multi-semester project aimed at developing an accurate predictive model for HPI, with a special emphasis on forecasting recessions for investment purposes, the study focuses on four cities: Dallas, Denver, Miami, and San Diego. Exploring microeconomic elements that influence HPI, drawing insights from significant works such as "House of Debt" by Atif Mian and Amir Sufi, and delving into the Housing Price-Income ratio—as well as the Fragility Index—help to establish a solid foundational understanding of regional real estate trends.

Crucial factors examined comprise new home construction, existing supply, housing price-rent ratio, and the impact of geographic and political constraints on housing supply and prices. The report also analyzes building permits data to discern trends in housing developments and their correlation with HPI. Utilizing the Federal Reserve Economic Data (FRED) API, the study accesses vital metrics, including mortgage rates, credit availability, corporate debt outstanding, Median Household Income (MHI). It even incorporates industry-level indices, representing the luxury and automobile sectors.

A pivotal part of our contribution involves advancing the model's framework using a Gated Recurrent Unit (GRU) to predict HPI. This process involves data series smoothing and data augmentation, then introduction of a 1-Layer GRU with random search to decide the activation function and learning rate. The study meticulously examines the effectiveness of various variables and their combinations in predicting HPI, highlighting the challenges of overfitting and emphasizing the need for model refinement.

## Models
- Baselines: LSTM, ARIMA, SVM
- Regime Detection: HMM, R2D2
- Feature importance: Decision Tree
- Prediction: GRU, ACRNN, Brute Force

## Smoothing, Normalization, Regularization
- Brownian Bridge Interpolation
- Gaussian Filter
- Lag Detection: Granger Casuality Test
- PCA
- Ledoit-Wolf Shrinkage
- Oracle Approximating Shrinkage
