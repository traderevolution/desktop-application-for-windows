# BBF \(Bollinger bands flat\)

Bollinger bands flat indicator provides the same data as Bollinger bands but is displayed in a separate field and thus makes it easy to determine whether prices are in or out of the band. 

This indicator consists of:

* Positive deviation – shows the value of the positive standard deviation, shifted N times up;
* Negative deviation – shows the value of the negative standard deviation shifted N times down;
* Delta – shows the difference between the current value and the value of the moving average at a given point. 

### Calculation

As can be understood from the above, only three components of the indicator are calculated:

Delta = ClosePrice - MA, where

ClosePrice is the current value of the Close price,

MA - the value of the moving average.

Positive deviation = A \* D, where

A - deviation parameter value,

D - dispersion relative to the moving average,

Negative deviation = \(-1\) __A \* D

### Main parameters

* Interval – provides the ability to set the number of confidence intervals, 20 by default;
* Deviation – for setting the required deviation, 2 by default;
* Type of Moving average – moving average calculation type: Simple, Exponential, Modified, Linear weighted;
* Apply to – type of price at which the indicator will be calculated: Close, Open, High, Low, Typical, Medium, Weighted.

This looks as follows on the chart:

![](../../../../../.gitbook/assets/1%20%289%29.jpg)

