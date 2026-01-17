## Crypto Price Direction Prediction with Random Forest and LSTM

This repository contains the source code and experimental pipeline used in the paper:

**"Machine Learning Applied to Cryptoassets: A Comparative Evaluation between Random Forest and LSTM for Price Direction Prediction"**,  
submitted to the *Journal of the Brazilian Computer Society (JBCS)*.

## Overview
The project provides a controlled and reproducible comparison between:
- Random Forest (RF)
- Long Short-Term Memory networks (LSTM)

applied to the task of **cryptocurrency price direction prediction**, formulated as a supervised classification problem.

Experiments are conducted using historical market data obtained from the **Binance exchange**.

## Repository Structure
- `src/`: implementation of RF and LSTM models and utilities
- `data/`: scripts and instructions for data acquisition and preprocessing
- `results_rf/`, `results_lstm/`: individual model results
- `results_comparison/`: comparative analysis outputs
- `figures/`: plots used in the paper
- `main.py`: main experimental pipeline
- `requirements.txt`: Python dependencies

## Reproducibility
All experiments were conducted using fixed random seeds and consistent data splits.
The raw data are not redistributed due to legal and ethical constraints, but can be obtained directly from Binance using the provided scripts.

## Requirements
Python 3.9+

Install dependencies with:
```bash
pip install -r requirements.txt
