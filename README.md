# Portoflio Optimization and Efficient Frontier

This project provides an example of an investment portfolio optimization tool. At first, the main statistics are calcualted: mean, standard deviation and covarince matrix, accompanied by the correlation heatmap graph of the portfolio's assets. It calculates the optimal asset allocation using the Maximum Sharpe Ratio and Minimum Variance portfolios, visualised through Pie Chart for better visual representation. In addition to this, the efficient frontier of the portfolio is provided with both Optimized Sharpe ratio and Minimum Variance points presented on the graph. In the last part, the cumulative returns of the resulted portoflios are compared to the returns of S&P500 as a benchmark using interactive graph from PlotLy library which should provide more precise information about the returns at different periods.
The chosen assets were taken from the porfolio of my close friend, the risk free rate being assumed at 3%. 

## Features of the script
 - **Data Retrieval:** Download data from Yahoo finance (or any API, CSV files, etc.)
 - **Portfolio Perfomance:** Calculate mean, standard deviation and covariance matrix, which are crucial for further metrics estimation and optimization.
 - **Correlation Heatmap:** Build a correlation heatmap of the assets in the portfolio to get better view at the current realtions between the assets.
 - **Sharpe Ratio Optimization:** Calcualte Sharpe Ratio (negative) and provide optimization of it.
 - **Minimum Variance Optimization:** Calculate portoflio variance and provide optimization of it.
 - **Results of Optimizations:** Provide results calculated for both optimized portfolios and build a pie chart respresenting the resulted asset allocations.
 - **Efficient Frontier:** Estimate and build efficient frontier graph.
 - **Benchamark Comparison:** Build an interactive graph of cumulative returns for optimized portfolios, equally weighted portfolio and the benchmark(S&P500).

### Motivation

The main goal for doing this project was to further enhance my python analytical skills that I absorbed during completing my Seminar Project at the University, alongside with exploring different portfolio management approaches. Another goal that I clearly achieved while doing this project was the improvement of my understading in the theory behind working with investment portfolios. 
The script provides a valuable tool for any user to analyse and optimize their investment portfolio using one of the most basic  and common used metrics in portfolio management.
