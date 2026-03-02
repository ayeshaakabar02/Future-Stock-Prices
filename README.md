📌 Objective
Use historical stock data to forecast the next day’s closing price of a selected stock (e.g., Apple, Tesla) using regression models.

📊 Dataset
Historical stock data fetched from Yahoo Finance using the yfinance Python library.
Features used: Open, High, Low, Volume
Target: Next day’s Close price

⚡ Key Features
Fetch historical stock data for any ticker symbol (AAPL, TSLA, etc.)
Train Linear Regression and Random Forest Regressor models
Visualize actual vs predicted closing prices
Easy to extend for multiple stocks or models
Quick, short-term prediction ideal for daily forecasts

🛠️ Tools & Technologies
Python 3.x
Libraries: pandas, numpy, yfinance, scikit-learn, matplotlib, seaborn
Regression models: Linear Regression, Random Forest Regressor

🔧 How it Works
Load historical stock data using yfinance.
Prepare features (Open, High, Low, Volume) and target (Next day Close).
Train Linear Regression or Random Forest model.
Predict next day’s closing price.
Plot actual vs predicted prices to evaluate model performance.

