
# LSTM and GRU Time Series Forecasting(MLP PROJECT SUBMISSION)

## Overview
This repository contains an implementation of LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) networks for time series forecasting. The code is based on the method described in the white paper titled "Forecasting with Deep Learning" by Gissel Velarde, published in The Data Digest, Volume 2, Issue 8, 2022, by Vodafone. The original paper can be accessed here https://arxiv.org/pdf/2302.12027v1.pdf and  - 
The implementation and experiments described in the paper are open-source and available in this repository.
https://github.com/Alebuenoaz/LSTM-and-GRU-Time-Series-Forecasting/tree/main.

## Changes Made
The original code from the paper was adapted and modified to enhance the model architectures, incorporate advanced techniques such as dropout layers for regularization, and improve data preprocessing methods using the StandardScaler. These modifications aimed to achieve better predictive performance and model robustness compared to the original implementation.

## Contents
RNN_multi.ipynb: Contains the original implementation of the RNN model as described in the paper.

RNN_multi_Improved.ipynb: Contains the improved implementation of the RNN model with modifications and enhancements.

BANKEX.csv: Sample dataset used for testing and evaluation.

activities.csv: Another sample dataset used in the original paper for experimentation.

README.md: This README file providing an overview of the repository.

## Instructions

To run the code and replicate the experiments:

Install the required dependencies mentioned in requirements.txt.

Run RNN_multi.ipynb  for the original RNN implementation.

Run RNN_multi_Improved.ipynb for the improved RNN implementation.

## Results and Discussion

The results of the experiments conducted using the improved RNN model showcase significant improvements in predictive accuracy and model performance compared to the original RNN model. The README file provides a detailed discussion of the results, including statistical tests and comparisons.

## Original RNN Results :
Mean values:
LSTM and Baseline (RMSE): 51.0
GRU and Baseline (RMSE): 55.0
LSTM and GRU (RMSE): 46.0
LSTM and Baseline (DA): 54.5
GRU and Baseline (DA): 51.0
LSTM and GRU (DA): 49.5
Final LSTM MSE Loss: 0.00016071223944891244
Final GRU MSE Loss: 0.00018687710689846426

## Improved RNN Results :
Ensemble Model (DA): 0.0
Mean values (RMSE) across 10 samples:
Original Mean RMSE: 5.59795917e+05
Improved Mean RMSE: 1.00000000e+00

For a detailed understanding of the methodology, experimental setup, and results, refer to the original paper and the code files in this repository.

Future Directions

Future extensions and improvements to the codebase may include:

Integration of attention mechanisms for enhanced model focus.

Exploration of hybrid models combining RNNs with other deep learning architectures.

Incorporation of external factors or domain knowledge to enrich model understanding and accuracy.


Note: The white paper referenced in this README can be accessed here, and the original GitHub repository for the code can be found here.
