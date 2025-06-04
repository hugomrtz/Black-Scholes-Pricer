# Black-Scholes-Pricer

This project implements a basic Black-Scholes model for pricing European call and put options.

It calculates:
- Theoretical prices of call and put options
- Option Greeks (delta, gamma, theta, vega)
- Interactive payoff diagrams (visible when run in Google Colab or a local Python environment)

---

## Features

- Black-Scholes pricing formulas
- Customizable parameters: ticker symbol, strike price, time to maturity, interest rate, and volatility
- Greeks computation for risk analysis
- Payoff visualization for both call and put options using Plotly

---

## How to Run

Recommended: Run in **Google Colab**

1. Open the `.ipynb` notebook in Google Colab
2. Adjust the input parameters (`ticker`, `K`, `T`, `r`, `sigma`)
3. Run all cells to view results and plots

---

## Example Output
Current Spot price for AAPL: 203.27
Call price: 28.08
Put price: 0.80
Delta Call: 0.9209
Gamma: 0.0068
Theta Call: -10.33
Vega: 21.17

********

Note: Graphs and plots only appear when executing the notebook in a compatible environment. GitHub does not render dynamic plots.

## Requirements

- Python 3.x
- numpy
- scipy
- matplotlib
- plotly
- yfinance

All dependencies are automatically installed via pip when running in Google Colab.

---

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it for educational or professional purposes.
