# Time-Series-Analysis-on-NIFTY-Data

This project is my practice work on understanding time series data and forecasting predictions . I have worked on NIFTY (National stock exchange FIFTY) data as it holds a significant trend of change across time. Nifty is the Index used by the National Stock Exchange and is made by the combination of National and Fifty (Nifty). Unlike Sensex, Nifty collects the sample of 50 performing and luring stocks to determine the market trends.Nifty picks stocks from different sectors. Some of these include the stocks from the sectors such as IT, Consumer Goods, financial services, automobiles, telecommunication, etc. I have used ARIMA model to forecast patterns and trends in the data accross different industrial spectrums.

<p>Time series means that a series of data points indexed in time order. The following are some of the most frequently asked questions: what will happen with our metrics in the next day/week/month/etc., how many users will instal our app, how much time will they spend online, how many actions will users complete, and so on. We can address these prediction tasks in a variety of ways, depending on the situation.

<p>Depending on the appropriate quality of the prediction, the duration of the forecast period, and, of course, the amount of time we have to select features and tune parameters to achieve desired results, we can approach these prediction tasks in a variety of ways.</p>

<p>Forecasting : The science of forecasting is the art of predicting the future. Businesses can use historical data to consider patterns, make predictions about what will happen and when, and then incorporate the knowledge into their future plans for everything from product demand to marketing.</p>

<p>To solve such problem we can have two kinds of approaches
    <li>Time Series Approach</li>
    <li>Machine Learning Approach</li></p>
  
<p><b>Data collection and preparation</b>:</p>
 20 years of data  is collected from NSE website and it consists of four features such as high, low, open and close.

<p>Description of columns in the file:</p>
  <li>Date — Date of trade
  <li>Open — The open is the starting period of trading on a securities exchange or organized over-the-counter market.
  <li>High — Highest price at which a stock traded during the course of the trading day.
  <li>Low — Lowest price at which a stock traded during the course of the trading day.
  <li>Close — The close is a reference to the end of a trading session in the financial markets when the markets close for the day.


<p><b>EDA</b>:
 The primary goal of EDA is to support the analysis of data prior to making any conclusions. It may aid in the detection of apparent errors, as well as a deeper understanding of data patterns, the detection of outliers or anomalous events, and the discovery of interesting relationships between variables.
    <li>There was a drastic drop in stock prices in the 2007-2009 period.This  can be attributed to the Great Recession that happened during this period.
    <li>Also, there is a drop in stock prices in the year 2016. This can be attributed to Demonetisation drive by the central government.
    <li>Again ,there is a drastic drop in stock prices in 2020. This is due to the global breakdown amid coronavirus pandemic induced lockdown in India.
    <li>By the end of 2020, the stock price started rising.This can be attributed to the lifting of lockdown in the country and across the world.
 
  <p><b>Feature Engineering</b>:
  The features we have are low in number and we don't have that data of the day when we actually want to do prediction. 
  So here comes the importance of feature engineering. Features are created using  the stock  data features based on
      <li>Lag features
      <li>Time  and Features
      <li>Window features such as Rolling and Expanding features using MA and EWMA techniques.
      <li>Volatility
  </p> 
  
  <p><b>Building Time Series Forecasting model</b>:
  The following techniques are used to forecast Close price of NIFTY 50 stock.
     <li>ARIMA using the dependent variable only.
     <li>ARIMAX using the dependent variable and exogenous features and fit the model.
  </p>
