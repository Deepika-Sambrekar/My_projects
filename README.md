Finance Stack: Backtesting Investment Strategies (US Stocks)
Project Overview
Finance Stack is a project that explores various investment strategies using Python, focusing on backtesting to evaluate the performance of these strategies over time. The project leverages tools like Pandas, SQL, JSON, and Web APIs to provide practical experience in real-world machine learning and finance projects.

This repository contains the code, data, and resources needed to implement and backtest a range of strategies on U.S. stocks, particularly with the Dow Jones Industrial Average (DJI). Through detailed data visualization and strategy analysis, this project helps in understanding and improving investment decision-making.

Project Features
Data Handling and Visualization: Integrate and manipulate data from various sources using Pandas and SQL, and visualize returns to gain insights.
Backtesting a Simple Momentum Strategy:
Buy and Hold (Passive): A basic strategy where we invest in the DJI and hold without further action, maintaining a +1 position daily.
Simple Momentum (Active):
Invest (+1) in DJI if today’s return is positive.
Short-sell (-1) DJI if today’s return is negative.
Contrarian Strategy Backtesting: Test and evaluate a contrarian approach.
Advanced Strategies and Model Evaluation:
Simple Moving Averages: Integrate moving average techniques to inform decision-making.
Backtesting vs. Fitting: Explore the differences and impacts of backtesting versus model fitting.
Perfect Strategy (Hypothetical): Simulate a strategy where we predict future returns to gauge the upper bounds of investment potential.
Requirements
Python Libraries: Pandas, Matplotlib, NumPy, SQLAlchemy
SQL Database: For efficient data handling and storage.
Web APIs: For pulling real-time or historical stock data (e.g., Alpha Vantage, Yahoo Finance).
