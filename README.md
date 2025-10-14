# Stock Market Portfolio Project - AAPL Intraday Analysis and Prediction

## Project Overview

This project focuses on analyzing and modeling 5-minute interval stock market data for Apple (AAPL) obtained from the Alpha Vantage API. The project demonstrates a workflow that includes data acquisition, cleaning, exploratory data analysis (EDA), feature engineering, building and evaluating predictive models (Simple Linear Regression and XGBoost), and exploring other financial modeling techniques like Geometric Brownian Motion and Markov Chains.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Setup and Installation](#setup-and-installation)
- [Notebook Structure and Analysis](#notebook-structure-and-analysis)
- [Key Findings and Model Performance](#key-findings-and-model-performance)
- [Geometric Brownian Motion Simulation](#geometric-brownian-motion-simulation)
- [Markov Chain Model](#markov-chain-model)

## Data Sources

- **Alpha Vantage API:** Provides historical intraday (5-minute interval) and daily adjusted stock data for AAPL.
- **MarketAux API:** Used to fetch relevant news headlines.

**Note on API Keys:**
To run this notebook, you will need API keys for both Alpha Vantage and MarketAux. Free tier limitations may apply, affecting the amount and type of data you can fetch. The notebook attempts to use endpoints and parameters available in the free tiers where possible.

Store your API keys securely in Google Colab Secrets (under the "🔑" icon in the left sidebar) with the following names:
- `ALPHA_VANTAGE_API_KEY`
- `MARKETAUX_API_KEY`
