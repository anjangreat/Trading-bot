This repository contains a modular algorithmic trading bot framework designed for both statistical mean reversion and machine learning–based trading strategies.
The project provides two independent backtesting engines:

MeanRevBacktester — for quantitative/statistical strategies (e.g., Bollinger Bands, z-score mean reversion)

MLBacktester — for machine learning–driven predictive strategies (e.g., regression, classification-based signal generation)

Both modules share a unified API for data handling, signal generation, performance evaluation, and visualization.

The SMA Backtester is a lightweight and modular Python engine to evaluate Simple Moving Average crossover strategies for financial assets.
It’s ideal for testing trend-following logic, such as Golden Cross (SMA50 > SMA200) or Death Cross (SMA50 < SMA200) setups, before deploying them in live trading.
