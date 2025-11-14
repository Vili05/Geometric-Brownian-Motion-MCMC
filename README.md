# Geometric Brownian Motion + NUTS sampler + Microsoft Stock Data

In this project I estimated parameters of geometric Brownian motion process given as
```math
dS_{t} = \mu S_{t} dt + \sigma S_{t} dW_{t},
```
where $S_{t}$ is a price at time $t$, $\mu$ is the expected return and $\sigma$ is the volatility of the stock price. $W_{t}$ is a Wiener process.
Given the stock price data, the objective was to estimate the parameters $\mu$ and $\sigma$. For estimation NUTS sampler from the PyMC package was used.
From the file "GBM_NUTS_Microsoft.pdf" the written report of the project can be found. The file "GBM_NUTS_Microsoft.ipynb" consists the Python code of the
project and the csv-file consists the data.
