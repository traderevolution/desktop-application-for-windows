# ATR \(Average true range\)

Average True Range \(ATR\) is a technical analysis volatility indicator originally developed by J. Welles Wilder, Jr. for commodities. The indicator does not show the price trend, but simply shows the degree of price volatility. The average true range is an N-day exponential moving average of the true range values. Wilder recommended a 14-period smoothing.

Average True Range can often reach a high value at the bottom of the market after a sheer fall in prices occasioned by panic selling. Low values of the indicator are typical for the periods of sideways movement of long duration which happen at the top of the market and during consolidation. Average True Range can be interpreted according to the same principles as other volatility indicators. The principle of forecasting based on this indicator can be worded the following way: the higher the value of the indicator, the higher the probability of a trend change; the lower the indicator’s value, the weaker the trend movement.

The ATR is commonly used as an exit method that can be applied regardless of how the entry decision is made. One popular technique that is known as "chandelier exiting" was developed by Chuck LeBeau. According to this technique, a trailing stop is placed below the highest high the stock has reached since you entered the trade. The distance between the highest high and the stop level is defined as multiple ATR values. For example, we can subtract three times the ATR value from the highest high since entering the trade.

### Calculation <a id="calculation"></a>

The range of a day’s trading is simply _high – low_. The true range extends it to yesterday’s closing price if it was outside of today’s range:

_True range = max \[\(high – low\), abs \(high – closeprev\), abs \(low – closeprev\)\]_

The true range is the largest of the:

* Most recent period's high minus the most recent period's low;
* Absolute value of the most recent period's high minus the previous close;
* Absolute value of the most recent period's low minus the previous close.

The ATR at the moment of time t is calculated using the following formula:![](https://gblobscdn.gitbook.com/assets%2F-LMCqxhh2XAdWPUjcvxR%2F-MMynEAEOWVQ1f2RCFoU%2F-MMyrHeMakt-_VzscswZ%2Fimage.png?alt=media&token=ea77c4c0-50c6-4d86-a513-d0049af5c951)

The first ATR value is calculated using the arithmetic mean formula:![](https://gblobscdn.gitbook.com/assets%2F-LMCqxhh2XAdWPUjcvxR%2F-MMynEAEOWVQ1f2RCFoU%2F-MMyrQATeFMk0WWdVFjr%2Fimage.png?alt=media&token=8dc3e01e-dfbe-4cbd-8246-31f10c9c18f0)

**ATR analysis basics**

* The greater the indicator value, the greater the possibility for a trend reversal;
* The smaller the value, the weaker the trend.

### Main parameters <a id="main-parameters"></a>

* Period – number of periods involved in the indicator calculation, 13 by default;
* Type of moving average: Simple, Exponential, Modified, Linear weighted.

The indicator looks as follows on the chart:

![](../../../../../.gitbook/assets/atr%20%283%29.jpg)

