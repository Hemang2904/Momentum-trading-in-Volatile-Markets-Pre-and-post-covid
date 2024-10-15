
# Momentum trading in Volatile Markets Pre and post covid

A brief description of what this project does and who it's for
Profitability in Momentum Strategies: Pre and Post COVID-19 Analysis

Overview

This project investigates the performance and profitability of momentum trading strategies before and after the onset of the COVID-19 pandemic. By analyzing stock market data from 2019 (pre-COVID), 2020, and 2021 (during and post-COVID), the project aims to understand how market volatility and changes in economic conditions affected the efficacy of these strategies.

Momentum strategies involve buying stocks that have performed well in the past and selling those that have underperformed. This analysis examines whether these strategies were profitable during normal market conditions compared to the extreme fluctuations seen during the pandemic.

Project Structure

# 1. Required Python Libraries
The notebook starts by listing and importing necessary libraries such as:

Pandas for data manipulation 

NumPy for numerical calculations

Matplotlib & Seaborn for data visualization

Scikit-learn for statistical analysis and potential feature engineering

# 2. Data Loading
The project utilizes historical stock data, which is loaded from a local or online source. This dataset includes:

Stock prices across multiple companies listed on major exchanges.
Relevant financial indicators and dates ranging from 2019 to 2021.

# 3. Data Preprocessing
Preprocessing is a critical step that involves:

Cleaning missing or incorrect data entries.
Formatting dates and standardizing numerical values.
Filtering the dataset to focus on data from 2019, 2020, and 2021 to reflect pre- and post-pandemic analysis.

# 4. Filtering and Grouping Data
The data is filtered to include stocks from each of the three years of interest, ensuring a consistent comparison across time periods. Stocks are then grouped by their symbols for analysis.

# 5. Momentum Calculation
A core part of the analysis is calculating momentum, which is defined by:

Momentum Formula: (Price_today - Price_n_days_ago) / Price_n_days_ago

The function computes momentum over varying time frames (e.g., 1 month, 3 months) to capture short-term and long-term trends.

# 6. Performance Evaluation of Momentum Strategies
Using the calculated momentum, the project evaluates:

The profitability of buying high-momentum stocks and selling low-momentum ones.

Profitability metrics such as average returns, win rate, and Sharpe ratio.

# 7. Volatility Analysis

In addition to momentum, the analysis considers stock volatility, especially during the high-uncertainty periods of the pandemic:

Standard deviation of stock prices is used to measure volatility.
Volatility trends are compared across 2019, 2020, and 2021.

# 8. Adjusting for Volatility
To refine the analysis, the project adjusts momentum strategies by factoring in volatility, ensuring risk-adjusted returns:

Stocks with high momentum but low volatility are preferred for risk-averse strategies.
The modified approach is compared against the traditional momentum strategy.

# 9. Visualization and Results
The analysis includes visualizations such as:

Line plots to show momentum trends over time.
Bar charts comparing strategy returns across different years.
Heatmaps of correlation matrices to illustrate relationships between variables.

# 10. Conclusions and Insights
The notebook concludes with key findings about how the momentum strategy performed before and after the COVID-19 pandemic, identifying:

Significant trends in profitability and risk.

Potential reasons for changes in strategy efficacy.

Insights for traders looking to apply momentum strategies in volatile markets.

 # Getting Started

Prerequisites
Make sure you have the following Python packages installed:

pandas

numpy

matplotlib

seaborn

scikit-learn

You can install the packages using:



pip install pandas numpy matplotlib seaborn scikit-learn 

Running the Notebook

Open the Jupyter notebook environment.

Load the provided .ipynb file.

Run the cells sequentially to reproduce the analysis. Make sure to modify any file paths or dataset links as necessary.
Data Sources
Historical stock data for various companies (ensure you have the relevant data files in the correct format).

Publicly available datasets can be used, or you may choose to download data via financial APIs like Alpha Vantage or Yahoo 
Finance.
Future Work

This project could be extended by:

Analyzing additional financial metrics (e.g., earnings reports, P/E ratios).
Expanding the timeframe to include more years, offering a broader understanding of market cycles.
Applying machine learning to predict momentum shifts or detect patterns in volatile market behavior.

Conclusion

This project provides an in-depth look at how external events, like the COVID-19 pandemic, can drastically affect trading strategies. It offers valuable insights for financial analysts and traders interested in understanding momentum behavior in different market conditions.
