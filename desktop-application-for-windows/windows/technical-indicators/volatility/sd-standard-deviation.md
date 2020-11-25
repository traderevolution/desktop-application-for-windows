# SD \(Standard deviation\)

Standard deviation is a way of measuring price volatility by correlating a price range with its moving average. The higher the indicator value, the wider the spread between the price and its moving average, the more volatile the instrument and the more scattered price bars become. The lower the indicator value, the smaller the spread between the price and its moving average, the less volatile the instrument, and the closer the price bars become to each other. The standard deviation is used as part of other indicators such as Bollinger Bands. It is often used in combination with other signals and analysis methods.

The market behavior represents the interchange of high trading activity and languid market. So, the indicator can be interpreted easily:

* if its value is too low, i.e., the market is absolutely inactive, it makes sense to expect a spike soon;
* otherwise, if it is extremely high, it most probably means that activity will decline soon.

**Use of the Standard deviation indicator**

Using the probability distribution models allows you to create many trading strategies, but the most common use of the standard deviation indicator is to predict price reversals based on the principle of reversion to the mean. Retracement to the average is basically the principle on which oscillators like the Relative Strength Index are constructed. It argues that each deviation from the mean must be followed by a return to the same so that the overall distribution of prices fits the standard distribution.

For example, if a currency is oscillating between 1.2700 and 1.3700 for an extended period of time, with much of the movement bound in the middle of the range, you can trade the pattern by assuming mean regression on the basis of a standard distribution.

Conversely, if prices are clustered at the edges of the same range, for example, around 1.3600-1.3700, or 1.2700 and 1.2800, the probability distribution of the prices may not be standard, and using the standard deviation indicator for trading while assuming mean regression may be disastrous.

### Calculation

StdDev \(i\) = SQRT \(AMOUNT \(j = i - N, i\) / N\)

AMOUNT \(j = i - N, i\) = SUM \(\(ApPRICE \(j\) - MA \(ApPRICE , N, i\)\) ^ 2\)

Where:

StdDev \(i\) — Standard Deviation of the current bar;

SQRT — square root;

AMOUNT\(j = i - N, i\) — sum of squares from j = i - N to i;

N — smoothing period;

ApPRICE \(j\) — applied price of the j bar;

MA \(ApPRICE , N, i\) — moving average value with the N period on the current bar;

ApPRICE \(i\) — applied price of the current bar.

### Main parameters

* Sources prices for MA – Close, Open, High, Low, Median, Typical, Weighted;
* Type of Moving average – Simple, Exponential, Modified, or Linear weighted;
* Period – period of indicator, default is 20.

The Standard deviation technical indicator looks as follows:

![](../../../../.gitbook/assets/screenshot_2%20%2832%29.jpg)

