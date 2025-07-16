# Quantum and Classical Portfolio Optimization

This project explores different approaches to financial portfolio optimization using both classical methods and quantum-based techniques. It uses a historical stock market dataset to compare the efficiency of both models.

## Project Structure

```
├── dataset/                          # CSV files with historical stock price data
│ ├── all_stocks_5yr.csv
│ └── stocks_cleaned.csv
├── notebooks/                        # Notebooks with the different experiments
│ ├── Classical_Approximation.ipynb
│ ├── Quantum_Approximation.ipynb
│ └── Preprocess_Stocks.ipynb
├── LICENSE                           # Project license
└── README.md
```

## Notebooks

- `Preprocess_Stocks.ipynb`: Cleans and prepares the original dataset (`all_stocks_5yr.csv`) for analysis.
- `Classical_Approximation.ipynb`: Implements classical portfolio optimization models (e.g., mean-variance).
- `Quantum_Approximation.ipynb`: Simulates a quantum approach to portfolio optimization using various techniques with Qiskit.


## Dataset

The data comes from a CSV file (`all_stocks_5yr.csv`) containing historical stock prices from the S&P 500 over five years. The `stocks_cleaned.csv` file contains a cleaned and analysis-ready version of the data.

## Licencia

This project is licensed under the terms of the MIT License. See the `LICENSE` file for more details.
