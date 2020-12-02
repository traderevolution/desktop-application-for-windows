# DMI \(Directional movement index\)

The Directional Movement Index \(also known as DMI\) is a momentum indicator that was developed by J. Welles Wilder in 1978. It is calculated using price, the indicator compares the current price with the previous price range and displays the result as an upward movement line \(+DI\), and a downward movement line \(-DI\) between 0 and 100. DMI is displayed on its own chart separate from the price bars.

DMI will tell you when to be long or short. This is especially useful for trend trading strategies because it differentiates between strong and weak trends, allowing the trader to enter only the strongest trends. DMI works on all timeframes and can be applied to any underlying instrument \(stocks, mutual funds, exchange-traded funds, futures, commodities, and currencies\).

The Directional Movement Index can be used in both ranging and trending markets. In general, when the +DI line is above the -DI line, the market is moving upwards, and when the -DI line is above the +DI line, the market is moving downwards.

### Calculation

The first two auxiliary indicators, +DM and -DM, need to be calculated. On "outside days", the difference between today’s and yesterday’s high corresponds to the auxiliary indicator +DM, and the difference between today's and yesterday's low corresponds to the auxiliary indicator -DM. "inside days" should not be considered for the calculation, therefore zero values are assigned for + DM and -DM on these days.

The so-called "True Range" \(TR\) is now calculated. It is always positive and defines, the following differences as a maximum:

* Day High Today minus Day Low Today,
* Day High Today minus Close Yesterday, or
* Day Low Today minus Close Yesterday.

The + DI upward direction indicator is now calculated by dividing + DM by the True Range. For smoothing purposes, it is usual to add the +DM values for the last fourteen days and divide this by the sum of the TRs for the last fourteen days. The result corresponds to +DI for fourteen days.  
The calculation of -DI is performed analogously. To calculate the DMI, the difference between +DI and -DI is divided by their sum and the result is multiplied by 100.

 +DI = +DM/TR and –DI = - DM/TR

 DMI = \(+ DI – \(- DI\)\) / \(+ DI + \(- DI\)\) \* 100, where

TR is the True Range described above.

### Main parameters

* Period of Moving Average: averaging period for calculation, default is 14;
* Type of the Moving Average: Simple, Exponential, Modified, Linear weighted.

This indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2824%29.jpg)

