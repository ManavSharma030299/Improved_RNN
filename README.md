
# LSTM and GRU Time Series Forecasting(MLP PROJECT SUBMISSION)
Overview
This repository contains an implementation of LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) networks for time series forecasting. The code is based on the method described in the white paper titled "Forecasting with Deep Learning" by Gissel Velarde, published in The Data Digest, Volume 2, Issue 8, 2022, by Vodafone. The original paper can be accessed here - https://github.com/Alebuenoaz/LSTM-and-GRU-Time-Series-Forecasting/tree/main.
The implementation and experiments described in the paper are open-source and available in this repository.

## Changes Made
The original code from the paper was adapted and modified to enhance the model architectures, incorporate advanced techniques such as dropout layers for regularization, and improve data preprocessing methods using the StandardScaler. These modifications aimed to achieve better predictive performance and model robustness compared to the original implementation.

## Contents
code_1_original_rnn.py: Contains the original implementation of the RNN model as described in the paper.

code_2_improved_rnn.py: Contains the improved implementation of the RNN model with modifications and enhancements.

BANKEX.csv: Sample dataset used for testing and evaluation.

activities.csv: Another sample dataset used in the original paper for experimentation.

README.md: This README file providing an overview of the repository.

## Instructions

To run the code and replicate the experiments:

Install the required dependencies mentioned in requirements.txt.

Run code_1_original_rnn.py for the original RNN implementation.

Run code_2_improved_rnn.py for the improved RNN implementation.

## Results and Discussion

The results of the experiments conducted using the improved RNN model showcase significant improvements in predictive accuracy and model performance compared to the original RNN model. The README file provides a detailed discussion of the results, including statistical tests and comparisons.

For a detailed understanding of the methodology, experimental setup, and results, refer to the original paper and the code files in this repository.

Future Directions

Future extensions and improvements to the codebase may include:

Integration of attention mechanisms for enhanced model focus.

Exploration of hybrid models combining RNNs with other deep learning architectures.

Incorporation of external factors or domain knowledge to enrich model understanding and accuracy.


Note: The white paper referenced in this README can be accessed here, and the original GitHub repository for the code can be found here.
