# Black-Scholes-Options-Calculator

Given user input of 
  Stock Name, 
  Option Price paid, 
  Implied Volatility, 
  Date to Expiration,
  Number of Contracts, 
  Strike Price,
  Option Type,
  and Current price of Stock
Calculate the
  Options greeks
  Expected price of option
  Total Profit/Loss

Black-Scholes is based on European options which assumes Constant risk free rate, constant implied volatility. This is not the case ppractically
Another assumption is that you only sell options at the strike price. This is different for American options where you can have profits before strike date.

Future Updates can include more vizualization of options, Stress testing under different scenerios using Monte-Carlos, Comparing different models, Using real-time information to calculate actual profit/loss in real time.


This is a simple calculator as it relys on user input, and not real time data of buying and selling. There is also less error handling and functions like monte carlos risk simulation or stress testing the portfolio. I used this to understand the model.
