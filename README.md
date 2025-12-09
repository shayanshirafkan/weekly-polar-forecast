# weekly-polar-forecast
Polar Motion Forecasting with Harmonic + LSTM

Description:
This repository contains a Python script to predict polar motion (x and y) using a hybrid approach:

Harmonic model for periodic components (Chandler, annual, semiannual)

LSTM neural network for residuals

The model predicts the next 10 days of polar motion, allowing weekly updates and recursive multi-step predictions (APKs).

Features

Download and merge latest C04 and Bulletin EOP data

Fit harmonic model for trends and periodic signals

Standardize residuals and train an LSTM model

Recursive multi-step prediction for multiple APKs

Compute daily MAE for evaluation

Plot predicted vs actual values
