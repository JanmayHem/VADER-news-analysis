# VADER-news-analysis
A python program which reads the latest news of stocks, does Valence Aware Dictionary and sEntiment Reasoner Analysis on the news headline and reports how positive, negative or neutral it is for that particular stock.

## Details
The mini-project consists of 3 tickers from FinViz, namely, Amazon, Tesla and Google. The program scrapes news from [FinViz](https://finviz.com/) of the given tickers of the stocks (GOOG for Google, TSLA for Tesla, AMZN for Amazon, ...). Then creates a dataframe, which then uses VADER analysis to identify the effect of the news on the sentiment of the stock and gives a graph along with a negative, neutral, positive and compound score of the headline. 
