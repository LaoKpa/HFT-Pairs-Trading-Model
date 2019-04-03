# HFT-Pairs-Trading-Model
A Pairs Trading model with Kalman Filter tested on High Frequency Data.

Its a extended test for the Pairs Trading with Kalman Filter by David Edwards of Quantopian. I liked his code just because the Kalman recalculates the Hedge Ratio efficiently at each iteration and is also compartively faster than than a OLS regression so it makes it suitable for HFT. The test was conducted on various frequencies - 5s,1m of (NSE Stocks).

# Prerequisite
* PyKalman 

# Performance

Image

# Features
+ Real Time Beta
+ Kalman Filter Average for Estimation

# Reference
+ Original work of David Edwards - https://www.quantopian.com/lectures/example-kalman-filter-pairs-trade
+ Kalman Filter (Wiki) - https://en.wikipedia.org/wiki/Kalman_filter

# Disclosure Note:
The above backtest doesn't represent the profitablity of the Algorithm. Investing the above algorithm with your own due-diligence, any kind of loss or profit the author is not repondsible. But do let me know if you got profitable using my algorithm ;).

