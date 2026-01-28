# Stock Prediction Model

This repository contains a **Jupyter Notebook** and related files for a stock prediction project using historical S&P 500 data. The model uses a **Random Forest Classifier** to predict whether the stock price will go up or down based on features such as Open, Close, High, Low, and Volume.

## Files

- `stock_prediction_model.ipynb` – The main Jupyter Notebook containing the model, data preprocessing, and evaluation.
- `sp500.csv` – CSV file containing historical S&P 500 stock data.
- `.ipynb_checkpoints/` – Jupyter notebook checkpoint files (ignored in GitHub).

## Features

- Data preprocessing and cleaning
- Random Forest model training
- Predictions and evaluation
- Feature importance analysis

## How to Run

1. Clone this repository:

```
git clone https://github.com/yourusername/your-repo.git
cd your-repo
Install required packages:
```

2. Install required packages:
```bash
pip install pandas scikit-learn matplotlib
```
3. Open the notebook:

```bash
jupyter notebook stock_prediction_model.ipynb
```
4. Run all cells in order.

## Notes

- The notebook currently uses a **Random Forest model** with default hyperparameters.  
- Make sure `sp500.csv` is in the same folder as the notebook.

## Credit

This project was inspired by the YouTube tutorial: [Stock Price Prediction Tutorial](https://www.youtube.com/watch?v=1O_BenficgE).
