# Time Series Detrending 1
In this project, we impelement different methods to remove the trend in a time series data. The suitable method for detrending depends on the type of the trend in the data, if the trend is deterministic or stochastic.

* **Differentiation:** The detrended data can be obtained by taking the difference between each data point and the previous data point at a particular distance of that (differentiation distance).

* **Simple Moving Average:** It takes the arithmetic mean of a given set of values over a specific period of time in the past.

* **Linear Regression:** If there is a deterministic linear, quadratic, or polynomial trend, we can fit a linear regression model on the data.

* **Hodrick-Prescott (HP)-Filter:** This filter separates a time series into a trend and a cyclical component.

* **Baxter-King Approximate Band-Pass Filter:** This is a symmetric moving average filter where it excludes high and low frequencies.

* **Christiano-Fitzgerald Approximate Band-Pass Filter:** This is a generalization of the Baxter-King filter and can be seen as weighted moving average. However, this filter is asymmetric about time and it uses the entire data.


-----------------------------------------------------
This project is adapted from the following webpages:

https://blog.faradars.org/%d8%ad%d8%b0%d9%81-%d8%b1%d9%88%d9%86%d8%af-%d8%b3%d8%b1%db%8c-%d9%87%d8%a7%db%8c-%d8%b2%d9%85%d8%a7%d9%86%db%8c-%d8%af%d8%b1-%d9%be%d8%a7%db%8c%d8%aa%d9%88%d9%86/

https://www.statsmodels.org/dev/examples/notebooks/generated/tsa_filters.html

