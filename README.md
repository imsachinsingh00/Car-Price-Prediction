# Gold Price Prediction

This project builds a regression model to predict gold prices based on several economic indicators and historical data.

## 📁 Project Structure

- `Gold Price prediction.ipynb`: Jupyter notebook for training the regression model.
- `gold.csv`: Dataset file with historical data and economic features.
- `README.md`: Documentation.

## 📊 Dataset Description

The dataset includes features like:
- SPX (S&P 500 Index)
- USO (Crude Oil Price)
- SLV (Silver Price)
- EUR/USD exchange rate
- Gold Price (target)

## ⚙️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

Install with:
```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Open the notebook `Gold Price prediction.ipynb` in Jupyter.
2. Ensure `gold.csv` is present in the same directory.
3. Execute cells to perform EDA, feature correlation, model training, and evaluation.

## 🧠 Model Used

- Linear Regression
- Evaluation metrics: Mean Absolute Error, Mean Squared Error, R² Score

## 📈 Sample Output

The model predicts the gold price and plots actual vs. predicted values.

## 📄 License

MIT License.
