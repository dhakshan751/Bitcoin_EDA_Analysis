# Bitcoin_EDA_Analysis

Bitcoin Price EDA Analysis Project


Introduction
This project focuses on the analysis of Bitcoin price data to gain insights into its historical trends and variations. The analysis covers a range of aspects, including data pre-processing, visualizations, and exploration of key features such as open, high, low, and close prices.

Project Structure
The project is organized into different sections, each serving a specific purpose. Below is an overview of the main sections:

Data Import and Initial Analysis:

The project starts by importing necessary libraries and reading the Bitcoin price data from a CSV file (bitcoin_price_Training - Training.csv).
Initial data exploration is performed, checking data types, missing values, and duplicate entries.
The dataset is then sorted chronologically from the oldest to the most recent entries.
Visualizing Bitcoin Price Trends:

Time series plots are created to visualize the open, high, low, and close prices over the entire dataset.
Both simple and log scaling are applied to observe the trends from different perspectives.
Exploratory Data Analysis (EDA):

EDA is conducted at various granularities, including yearly, monthly, and quarterly averages.
Trends in the closing prices are analyzed to identify patterns and potential insights.
Daily Percentage Change Analysis:

Daily percentage changes in closing prices are computed to analyze the volatility of Bitcoin.
Visualizations, including line plots and histograms, provide insights into the daily variations.
Candlestick Charts:

Candlestick charts are utilized to visualize stock data, providing a comprehensive view of open, high, low, and close prices.
A sample candlestick chart is generated and displayed for better understanding.
Interactive Visualizations:

The project leverages Plotly and Cufflinks to create interactive visualizations.
Interactive line plots and candlestick charts enhance the user experience.
Getting Started
To run the project, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/dhakshan751/Bitcoin_analysis.git
Install the required packages:

bash
Copy code
pip install pandas numpy seaborn matplotlib plotly cufflinks
Open the Jupyter notebook checkpoint.ipynb:

bash
Copy code
jupyter notebook checkpoint.ipynb
Execute the notebook cells sequentially to perform the analysis step by step.

Conclusion
The Bitcoin price analysis project provides valuable insights into the historical trends and variations in Bitcoin prices. The visualizations and exploratory data analysis contribute to a better understanding of the cryptocurrency market.

Feel free to explore additional analyses or customize the project based on your specific interests.
