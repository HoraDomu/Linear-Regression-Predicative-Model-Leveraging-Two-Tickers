Stock Regression Analyzer

A Python tool to analyze the relationship between two stocks using linear regression. Compare their 6-month closing prices and visualize the correlation with a regression line.

💡 Features

Fetch 6-month stock data from Yahoo Finance using yfinance.

Automatically handle adjusted closing prices.

Compute linear regression to quantify the relationship between two stocks.

Display intercept, slope, and R² score for statistical insight.

Visualize data points and regression line using matplotlib.

Handles missing data and overlapping dates automatically.

🛠 Installation

Clone the repository:

git clone <repository_url>
cd <repository_folder>


Install dependencies:

pip install yfinance pandas matplotlib scikit-learn

🚀 Usage

Run the script:

python main.py


Enter two stock tickers when prompted:

Enter Ticker 1: AAPL
Enter Ticker 2: MSFT


The script will:

Download 6 months of closing prices.

Print a preview of overlapping data.

Compute and display regression results:

Intercept (β0): 10.42
Slope (β1): 1.15
R^2 score: 0.8723


Show a scatter plot with the regression line.

🔮 Future Improvements

Allow user-defined date ranges for analysis.

Compare multiple stocks simultaneously.

Export regression statistics and graphs to CSV or image files.

Add statistical significance metrics like p-values and confidence intervals.

📦 Dependencies

yfinance
: Download stock data.

pandas
: Data manipulation.

matplotlib
: Plotting and visualization.

scikit-learn
: Linear regression and model evaluation.
