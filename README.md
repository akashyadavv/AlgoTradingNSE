# Algorithm Trading with ML on NSE stocks.
A project that tries to influence buying and selling of stocks using an algorithmic model built using an ensemble of KNN, Decision Tree, Random forest and SVM. The model depicts an ideal scenario for maximizing profits from a trade. A momentum strategy that is used to predict 
trading signal has been modelled based on a set of rules using various technical indicators.

The result of the analysis is the predicted trend of the market index, which can be used to set out some trading rules:
• If the next day trend is Uptrend, then the decision is BUY
• If BUY decision already exists, then HOLD
• If the next day trend is Downtrend, then the decision is SELL
• If SELL decision already exists, then HOLD
According to the result obtained with these rules, the return of strategy has been calculated.

#Results

An accuracy of 94.2% was achieved which indicates that our model has the capability of reducing the losses compared to the actual returns; if they were calculated on the basis of the previous day's closing price.

