# Module-5-Challenge

Financial Planning w/ Monte Carlo Simulations in Python

[![Financial-plan-circles-clear-1024x995.png](https://i.postimg.cc/CMPL6FBj/Financial-plan-circles-clear-1024x995.png)](https://postimg.cc/rz4kD29m)

# Module 5 Challenge

In this challenge, I decided to start a fintech consulting firm that focuses on projects to benefit local communities. I just won my first contract with a large credit union. This project entails building a tool to help credit union members evaluate their financial health. 

Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.

---

## Technologies

The data we're analyzing comes from a jupyter notebook that we've created and imported files to. We'll be using Python to run and read our data. 

* [jupyter] - (https://github.com/jupyter/notebook) - Helps us run our code and get the information we need from the data listed in csv files.


---

## Installation Guide

In order for us to get the data we need we must import pandas, plots and the csv files we want to observe.

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
import numpy as np
from MCForecastTools import MCSimulation

%matplotlib inline
```

---

## Usage

To find the information needed we build a jupyter notebook and run various functions to pull the data from csv files.

```python
# Visualize the 30-year Monte Carlo simulation by creating an
# overlay line plot
MC_threeyear.plot_simulation()
```

[![output.png](https://i.postimg.cc/cJrVCS4N/output.png)](https://postimg.cc/061tXhwt)
---

## Contributors

Brought to you by Elgin Braggs Jr.

---

## License

MIT