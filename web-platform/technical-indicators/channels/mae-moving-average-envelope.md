# MAE \(Moving average envelope\)

The Moving average envelope is an indicator that is based on a simple or exponential moving average and sets bands based on a given percentage deviation, thus creating envelopes. Then these envelopes can be used in two forms:

a\) Envelopes can be used to determine the trend of a currency pair when the market is trending.

b\) In cases where the market is range-bound, the moving average envelope indicator can also be used to indicate when a currency pair is oversold or overbought, just like a momentum oscillator would.

The Envelopes technical indicator is formed with two Moving averages, one of which is shifted upward and the other downward. The selection of the optimal relative number of band margins shifts is determined by market volatility: the higher it is, the stronger the shift.

Envelopes define the upper and lower margins of the price range. A sell signal appears when the price reaches the upper margin of the band; a buy signal appears when the price reaches the lower margin.

The logic behind the Envelopes is that overzealous buyers and sellers push the price towards extreme values \(i.e., upper and lower bands\), at which point the prices often stabilize, moving towards more realistic levels.

### Calculation

UPPER BAND = SMA \(CLOSE, N\) \* \[1 + K / 1000\]

LOWER BAND = SMA \(CLOSE, N\) \* \[1 - K / 1000\]

Where:

UPPER BAND — upper indicator line;

LOWER BAND — lower indicator line;

SMA — Simple Moving Average;

CLOSE — close price;

N — averaging period;

K / 1000 — shifting value from the average \(measured in basis points\).

### Main parameters

The parameters of the Moving average envelopes depend on your trading/investing goals and the characteristics of the security involved. Traders will likely use shorter \(faster\) moving averages and relatively tight envelopes. Investors will likely prefer longer \(slower\) moving averages with wider envelopes.

* Mode. Upper Line: Upper Band, Lower Line: Lower Band;
* Period: Averaging period for calculating the main line;
* Type of MA: Simple, Exponential, Modified, Linear weighted;
* Deviation: Percent deviation from the main line, default is 0.1;
* Source price for MA: Close, Open, High, Low, Median, Typical, and Weighted.

This indicator looks as follows on the chart:

![](../../../.gitbook/assets/mae%20%281%29.jpg)

