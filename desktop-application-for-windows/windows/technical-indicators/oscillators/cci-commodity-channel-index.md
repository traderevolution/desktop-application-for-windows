# CCI \(Commodity channel index\)

The commodity channel index \(CCI\) is an oscillator originally introduced by Donald Lambert in 1980. Since its inception, the indicator has gained popularity and is now a very common tool for traders to identify cyclical trends not only in commodities but also in equities and currencies The CCI can be adjusted to the timeframe of the market being traded by changing the averaging period.

Commodity channel index technical Indicator \(CCI\) measures the deviation of a commodity's price from its average statistical price. High index values indicate that the price is unusually high compared to the average one, while low values indicate that the price is too low. Despite the name, the Commodity channel index can be applied for any financial instrument, not just commodities.

There are two basic techniques for using the Commodity channel index:

* Divergence detection: a divergence occurs when the price reaches a new maximum, and the Commodity channel index cannot rise above the previous highs. This classical divergence is usually followed by price correction;
* As an indicator of overbuying/overselling: the Commodity channel index usually fluctuates in the  ±100 range. Values above +100 indicate an overbought state \(and the likelihood of a corrective decline\), and values below -100 indicate an oversold condition \(and a probability of a corrective increase\).

CCI typically oscillates above and below the zero line. Normal oscillations will occur within the range of +100 and −100. Readings above +100 imply an overbought condition, while readings below −100 imply an oversold condition. As with other overbought/oversold indicators, this means that there is a greater likelihood that the price will correct to more representative levels.

### Calculation

To find the typical price, you need to add the HIGH, LOW, and CLOSE prices of each bar, and then divide the result by 3:

TP = \(HIGH + LOW + CLOSE\) / 3

To calculate the n-period Simple moving average of typical prices:

SMA \(TP, N\) = SUM \(TP, N\) / N

To subtract the resulting SMA \(TP, N\) from the typical prices of each of the preceding n periods:

D = TP - SMA \(TP, N\)

To calculate the n-period Simple moving average of the absolute D values:

SMA \(D, N\) = SUM \(D, N\) / N

To multiply the received SMA \(D, N\) by 0,015:

M = SMA \(D, N\) \* 0,015

To divide M by D:

CCI = M / D,

where:

HIGH — maximum bar price;

LOW — minimum bar price;

CLOSE — close price;

SMA — Simple moving average;

SUM — sum;

N — number of periods used for the calculation.

### Main parameters

* Period of moving average – number of periods involved in the calculation, 14 by default;
* Type of the moving average – for selecting the MA type, available values: Simple, Exponential, Modified, Linear weighted.

The indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2822%29.jpg)

