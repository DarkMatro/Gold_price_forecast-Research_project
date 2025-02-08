# Gold price Time-Series Analysis and Forecasting Research Project

This repository contains code and experiments for a research project focused on time-series forecasting using a range of machine learning and statistical methods. The goal is to identify the best-performing models for long-term trend prediction.

## Project Overview

The project is divided into two main stages:
1. **Exploratory Data Analysis (EDA) and Model Testing**:
    - Conducted extensive data cleaning and visualization.
    - Tested several machine learning models, including:
        - Moving average, ETS
        - Prophet
        - ARIMA, ARIMAX, ARFIMA
        - StatsForecats: ARIMA, ETS, CES, Theta, MFLES, TBATS
        - LGBMRegressor, CatBoost
        - RNN based NN: RNN, LSTM, GRU, TCN, DeepAR, DRNN, BiTCN
        - MLP based NN: MLP, NBEATS, NBEATSx, NHITS, Dlinear, NLinear, TiDE, DeepNPTS
        - Kolmogorov-Arnold Networks (KANs)
        - Transformer based NN: TFT, Vanilla Transformer, Informer, Autoformer, FEDformer, PatchTST, iTransformer
        - TimesNet (CNN)
        - Multivariate NN: StemGNN, TSMixer, TSMixerx, MLPMultivariate, SOFTS, TimeMixer
        - TimeLLM, TimeGPT

2. **Long-Period Testing of Best Models**:
    - Evaluated the top-performing models identified in the first stage on extended datasets to validate their robustness and accuracy.

## Notebooks

### 1. `1_EDA_Models_Test.ipynb`
- Contains:
  - Data preprocessing steps.
  - Exploratory data analysis with visualizations to identify trends, seasonality, and anomalies.
  - Initial testing and evaluation of multiple models for time-series forecasting.

### 2. `2_Best_Models_Long_Period_Test.ipynb`
- Focuses on:
  - Long-term validation of the best-performing models.
  - Comparison of predictions with actual data to evaluate model stability over extended periods.

## Results

As a result, the studied models did not show good results, which indicates the absence of a pattern in the price of gold. None of the models turned out to be better than baseline in the studied period with 60-days horizon forecast.
