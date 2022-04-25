# FinTech Quantitaive Analysis Using Pandas

*Welcome to my FinTech project as a 'Quantitative Analyst for Retirement Portfolios'*

---

## Background
This program evaluates four new investment portfolios from legendary funds and hedge-fund managers.  It seeks the best retirement portfolio for an investment firm to add to its options for clients. These popular fund managers are called 'Whales' because of their large assets under management(AUM) from previous successes over decades. Each fund manager as a different investment style that yields different performance returns through different economic events and market cycles. 

This analysis will take quantitative measures based on risk management metrics such as daily returns, standard deviation, Sharpe ratios, and betas for all 4 portfolios against market performance of the 'S&P 500'. This will aid in giving a clear picture to find the fund with the best investment potential for a retirement portfolio by analyzing data and visualizing the former risk and return metrics. This will aid the user in determining the top performer with a recommended choice for the investment firm.  

The data and chart visualations should help 'Investment Representatives' efficiently discuss this attractive option with customers as an addition to their retirement portfolios.  

---

## Technologies

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation:

* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) .

* 

---

## Installation Guide

Before running the application first activate the Conda development environment and launch JupyterLab to import the following required libraries apps.

```python libraries
  import pandas as pd 
  import numpy as np 
  from pathlib import Path
  %matplotlib inline 
```

---

## Usage

This application is launched from web-based JupyterLab utilizing Pandas which is designed for data analysis to write and read code in an IDE and review results through the Python libraries. The Anaconda3 software application includes the Pandas libraries; **numpy, %matplotlib inline** to utilize data frames and plot charts in an integrated Conda development environment. 

The program is developed in Jupyter notebooks on a **.ipny** file.  The pandas imports help to **pd.read_csv** data files and place it into a data frame to analyze and visualize it. Using **numpy** library tools facilitates math calculations with large quantities of data sets to get: daily returns, risk and return metrics, standard deviation, and beta. The Pandas **%matplotlib inline** enables functions to create informative visualizations from the Pandas DataFrames and data metrics. 



Finally the **risk_return_analysis.ipny** program as several steps to analyze: performance, volatility, risk, risk-return profile, and portfolio diversification. Through these steps a determination is made for a portfolio recommendation from the four "Whale" fund porfolio managers.  

```python
risk_return_analysis.ipny
```
 

---

## Contributors

*Provided to you by digi-Borg FinTek*, 
Dana Hayes: nydane1@gmail.com

---

## License

Columbia U. Engineering
