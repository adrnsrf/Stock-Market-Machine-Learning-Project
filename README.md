# Stock-Market-Machine-Learning-Project
This is a machine learning project with the intent of finding a single profitable trade per day in the market.

Each day, there are many fluctuations in stock prices. I want to explore if I can develop a machine learning system that can help me find one trade per day to make a small gain.

The problem is set up like this:  
*Will ___ stock have an ___% increase between time _____ and the end of the trading day?*

For my first model, I was looking at a group of tech stocks and determining if I could find a 0.5% between 12pm EST and end of day. 

The script will pull the 5 minute price data for the past 60 days (Yahoo API limit for intraday data) for each stock, transform the data to add features I believe have an impact on the outcome, and applies a system of logistic regression models to determine the outcome. 

After doing an experiment for 3 months, the model showed promising results. I have added the CSVs for the results I logged during this period. 

Please note that this is an experiment that is a work in progress. The code is not the most efficient, since I was mostly focusing on getting the results I wanted. 


