# biomedical-ai
Machine learning for application in biology and medicine

## Project description

In this project, I am showcasing my module for developing machine learning models for day algorithmic trading on 1-minute bars. So far I have managed to hit up to 10% monthly (~300% year) returns in backtests on a single stock.

#### How to use this

First, read the project description below and check out the 'trading_ml_model_showcase' notebook'. It will walk you through stages of creating an ML model for trading, from feature extraction to backtesting. 

The main module '/stonks' contains functions for extracting features from stock price data (bars), feature selection, labelling target variables, training the model and backtesting. The '/scraper' folder contains a web scraping algorithm I wrote for Wall Street Journal headlines and analysing their relationship to stock and commodity prices. You can run the 'web_scraper_demonstration' script to see how this model works.

## Highlights

### Feature extraction

The first stage is extracting features from time series price data. For that I use common techincal indicators such as exponential moving 
