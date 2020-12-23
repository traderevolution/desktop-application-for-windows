# BB \(Bollinger bands\)

Bollinger Bands is a technical analysis tool invented by John Bollinger in the 1980s. Having evolved from the concept of trading bands, Bollinger Bands, and the related %b and bandwidth indicators can be used to measure the "highness" or "lowness" of the price relative to previous trades. Bollinger Bands are a volatility indicator. It is plotted at distances equal to a certain number of standard deviations from the moving average. Since standard deviation value depends on volatility, the bands are self-adjusting: the width of the bands increases when the market is unstable, and decreases in more stable periods.

Bollinger Bands are usually plotted on a price chart, but they can be displayed on the indicator chart as well. Interpretation of the Bollinger Bands is based on the fact that prices tend to stay within the upper and lower boundaries of the band. A distinctive feature of the Bollinger Bands is the spacing due to the price volatility. The second feature of the Bollinger Bands is their variable width due to the price volatility. During periods of significant price changes \(i.e. high volatility\), the bands widen to give more space for the prices. During periods of stagnation \(i.e., low volatility\), bands narrow to keep prices within their boundaries.

Bollinger Bands indicator key points are:

1. Abrupt price changes usually occur after the band narrows, which corresponds to a decrease in volatility.
2. If prices go beyond the range, the continuation of the current trend should be expected.
3. If the pikes and hollows outside the bands are followed by the pikes and hollows within the bands, a trend reversal may occur.
4. A price movement that started from one of the band boundaries usually reaches the opposite one.

Bollinger Bands consist of:

* N-period moving average \(MA\);
* top line at K times an N-period standard deviation above the moving average \(MA + Kσ\);
* bottom line at K times an N-period standard deviation below the moving average \(MA − Kσ\).

Typical values for N and K are 20 and 2, respectively. The default choice for the average is a simple moving average, but other types of averages can be employed as needed. Exponential moving averages are a common second choice. Typically, the same period is used for both the middle line and the calculation of standard deviation.

### Calculation

Bollinger bands are formed by three lines. The middle line \(ML\) is a usual Moving Average.

ML = SUM \(CLOSE, N\) / N = SMA \(CLOSE, N\)

The top line \(TL\) coincides with the midline by a certain number of standard deviations \(D\).

TL = ML + \(D \* SD\)

The bottom line \(BL\) is the middle line shifted down by the same number of standard deviations.

BL = ML - \(D \* SD\)

Where:

SUM \(..., N\) — sum for N periods;  
CLOSE — close price;  
N — indicating the number of periods used in the calculation;  
SMA — Simple Moving Average;  
SQRT — square root;  
SD — standard deviation:

SD = SQRT \(SUM \(\(CLOSE — SMA \(CLOSE, N\)\)^2, N\)/N\)

It is recommended to use 20-period Simple Moving Average as the middle line, and plot the top and bottom lines two standard deviations away from it. Besides, moving averages of less than 10 periods are of little effect.

### Main parameters

* Data type – type of price at which the indicator will be calculated: Close, Open, High, Low, Typical, Medium, Weighted;
* Type of MA – moving average calculation type: Simple, Exponential, Modified, Linear weighted;
* Period – the number of periods involved in the calculation of the moving average, 20 by default;
* Deviation – provides the ability to set the required deviation, 2 by default.

The indicator looks as follows on the chart:

![](../../../../.gitbook/assets/bb%20%287%29.jpg)

