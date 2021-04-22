# 💹Financial Analysis and the Prediction of Stock Returns

# Part 1: 🔎Exploratory-Data-Analysis-(EDA) [(nbviewer link)](https://nbviewer.jupyter.org/github/Madhur6234/Financial-Analysis/blob/master/Exploratory-Data-Analysis-%28EDA%29.ipynb)

This part of the project focuses on exploratory data analysis of Indian bank stock prices from the year **2006** to the end of the year **2020**. 

This project focuses on bank stocks and sees how they progressed throughout the '[2008 financial crisis](https://www.history.com/news/2008-financial-crisis-causes)' to the end of 2020 and during the '[2020 Stock Market Crash also known as Coronavirus Crash](https://en.wikipedia.org/wiki/2020_stock_market_crash)'.

Data collected from [Yahoo Finance](https://in.finance.yahoo.com/)

#### 🔧Libraries used:
* For data analysis:
    * numpy
    * pandas
    * matplotlib
    * seaborn
    * pandas visualization

#### 🏧List of Bank:
1. State Bank of India = [SBIN.NS](https://in.finance.yahoo.com/quote/SBIN.NS?p=SBIN.NS&.tsrc=fin-srch)      
2. HDFC Bank = [HDFCBANK.NS](https://in.finance.yahoo.com/quote/HDFCBANK.NS?p=HDFCBANK.NS&.tsrc=fin-srch)
3. Axis Bank = [AXISBANK.NS](https://in.finance.yahoo.com/quote/AXISBANK.NS?p=AXISBANK.NS&.tsrc=fin-srch)
4. Kotak Mahindra Bank = [KOTAKBANK.NS](https://in.finance.yahoo.com/quote/KOTAKBANK.NS?p=KOTAKBANK.NS&.tsrc=fin-srch)
5. Bank of Baroda = [BANKBARODA.NS](https://in.finance.yahoo.com/quote/BANKBARODA.NS?p=BANKBARODA.NS&.tsrc=fin-srch)
6. Punjab National Bank = [PNB.NS](https://in.finance.yahoo.com/quote/PNB.NS?p=PNB.NS&.tsrc=fin-srch)
7. ICICI Bank = [ICICIBANK.NS](https://in.finance.yahoo.com/quote/ICICIBANK.NS?p=ICICIBANK.NS&.tsrc=fin-srch)
8. Yes Bank = [YESBANK.NS](https://in.finance.yahoo.com/quote/YESBANK.NS?p=YESBANK.NS&.tsrc=fin-srch)


## 💡Conclusion From Analysis:
* **It has seen that 'March 2020' have the worst returns for most of the banks. The reason behind this is the [2020 Stock Market Crash also known as Coronavirus Crash](https://en.wikipedia.org/wiki/2020_stock_market_crash).**
* **It can also be observed that 'October 2008' also have the worst returns for some banks. The reason behind this is the [2008 financial crisis](https://www.history.com/news/2008-financial-crisis-causes).**
* **`Yes Bank` stocks would be classified as to be the riskiest over the entire period. Although it shows good growth from the start of 2014 till the end of 2018, then the stocks started to fall.**
* **Punjab National Bank and Bank of Baroda stocks started to fall from early 2018.**
* **`Kotak Mahindra Bank` stocks show the best growth over other banks.**

# Part 2: 💸Prediction-of-Stock-Returns

This part of the project focuses on predicting the stock returns of Indian Banks with different types of Machine Learning estimators.

Evaluate which machine learning estimator is best for finding the stock returns.

#### 🔧Libraries used:
* For pre-processing and modelling data:
    * numpy
    * pandas
    * matplotlib
    * scikit-learn (sklearn)
    * tensorflow
    * keras

>**Let's analyze the data of `Kotak Mahindra Bank` for predicting the stock returns, as it shows the best growth over other banks.**

**Machine Learning Models: *[(nbviewer link)](https://nbviewer.jupyter.org/github/Madhur6234/Financial-Analysis-and-the-Prediction-of-Stock-Returns/blob/master/Prediction-of-Stock-Returns-with-Machine-Learning-Models.ipynb)***

    1. Linear Regression
    2. Random Forest Regression
    3. Support Vector Machine
    4. Bayesian Ridge Regression
    5. Gradient Boosting Regression

**Recurrent Neural Network Model: *[(nbviewer link)](https://nbviewer.jupyter.org/github/Madhur6234/Financial-Analysis-and-the-Prediction-of-Stock-Returns/blob/master/Prediction-of-Stock-Returns-with-Recurrent-Neural-Network.ipynb)***

    1. Long Short-Term Memory (LSTM)

## 💡Conclusion After Evaluation:
* **After evaluation, it is found that both `Linear Regression` and `Bayesian Ridge Regression` are almost similar while predicting the stock price.**

* **The best model to predict the stock price is the `Long Short-Term Memory (LSTM)` among all of the evaluated models.**
