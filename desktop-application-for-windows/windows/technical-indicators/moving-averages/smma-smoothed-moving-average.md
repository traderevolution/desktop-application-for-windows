# SMMA \(Smoothed moving average\)

The Smoothed moving average is a kind of mix of a Simple moving average and an Exponential moving average, but with a longer period \(about half the EMA period: for example, a 20-period SMMA is almost equal to a 40-period EMA\).

This moving average is used to monitor price changes. The effect of the moving average is to smooth out the price movement so that the long-term trend becomes less volatile and therefore more obvious. When the price rises above the moving average, it indicates that investors are becoming bullish on the commodity. When prices fall lower, it indicates a bearish commodity. In addition, when the moving average crosses the longer-term moving average, research indicates a downward reversal of the market. When the short-term moving average crosses the longer-term moving average, it indicates an upswing in the market. The longer the period of the moving average, the smoother the price movement. Longer moving averages are used to highlight long-term trends.

### Calculation

The first value of the Smoothed moving average is calculated as the simple moving average \(SMA\):

SUM1 = SUM \(CLOSE \(i\), N\)

SMMA1 = SUM1 / N

The second moving average is calculated according to this formula:

SMMA \(i\) = \(SMMA1\*\(N-1\) + CLOSE \(i\)\) / N

Subsequent moving averages are calculated using the following formula:

PREVSUM = SMMA \(i - 1\) \* N

SMMA \(i\) = \(PREVSUM - SMMA \(i - 1\) + CLOSE \(i\)\) / N

Where:

SUM — sum;

SUM1 — total sum of closing prices for N periods; counted from the previous bar;

PREVSUM — smoothed sum of the previous bar;

SMMA \(i-1\) — smoothed moving average of the previous bar;

SMMA \(i\) — smoothed moving average of the current bar \(except for the first one\);

CLOSE \(i\) — current close price;

N — smoothing period.

After arithmetic conversions, the formula can be simplified:

SMMA \(i\) = \(SMMA \(i - 1\) \* \(N - 1\) + CLOSE \(i\)\) / N

### Main parameters

* Period of smoothed moving average – allows specifying the number of periods, over which the indicator is calculated;
* Sources prices for MA – determines the type of price at which the moving average is calculated, available values: Close, Open, High, Low, Median, Typical, Weighted.

The indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2818%29.jpg)

