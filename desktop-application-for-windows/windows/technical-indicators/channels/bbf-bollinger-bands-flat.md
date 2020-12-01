# BBF \(Bollinger bands flat\)

**Bollinger bands flat** indicator provides the same data as Bollinger bands but is displayed in a separate field and thus makes it easy to determine whether prices are in or out of the band. 

This indicator consists of:

* Zero line – shows zero on the chart for user convenience;
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

* Sources prices for MA – the type of price at which the indicator will be calculated for the selected period. Available values: Low, Open, High, Close, Typical, Medium, Weighted;
* Type of moving average – type of moving average calculation. Available values: Simple, Exponential, Modified, Linear weighted;
* Period – the number of periods involved in the indicator calculation;
* Deviation – the number of standard deviations;
* Shift – the number of indicator values by which there will be a shift up or down by the number of standard deviations.

This looks as follows on the chart:

![](../../../../.gitbook/assets/bbf%20%286%29.jpg)

