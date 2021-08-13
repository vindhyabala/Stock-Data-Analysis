# Stock-Data-Analysis
Analyze SPY and BAC datasets and run ML classifiers. Label each week as 'green" or "red".
 a "green" week means that is was a good week to be invested
for that week (from the rst to last trading day of this week,
typically from Monday to Friday).
 a "red" week means that it was not a good week to be
invested but to keep money in cash (e.g. prices fell or there
was too much volatility in the price).
Implement a number of machine learning
classifiers to predict labels. Define 
a set of numeric features for each week (e.g. average of daily
returns and average volatility). Train the
classifier using these features and labels from year 1 and then,
using features for year 2, predict labels for year 2. Compute accuracy of the classifier.
