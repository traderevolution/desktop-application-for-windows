# MMA \(Modified moving average\)

Modified moving average \(MMA\) is an algebraic tool that makes averages more susceptible to price shifts. The Modified moving average is a special case of the Exponential moving average, for which the smoothing constant is equal to the reciprocal of the smoothing interval. This average is a slope that helps it catch up with the rising or falling value of the currency's trading price.

In general, Modified moving averages resemble Simple moving averages but there are some differences. The first point of the Modified moving average is calculated precisely as the first point of the Simple moving average. However, all subsequent points are measured by adding the new price and then subtracting the last average from the resulting sum. MMA is the difference, the new point on the scheme.

### Calculation

MMA = price \* K + MMA \* \(1.0 – K\), where

K = 1/ N

N - period of MA for calculation.

### Main parameters

* Interval of Modified MA – number of periods for calculating the modified moving average, 9 by default;
* Apply to – determines the type of price at which the moving average will be calculated, available values: Close, Open, High, Low, Median, Typical, and Weighted.

This indicator looks as follows on the chart:

![](../../../../../.gitbook/assets/mma%20%283%29.jpg)

