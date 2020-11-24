# QStick

The QStick indicator is a technical analysis indicator developed by Tushar Chand as the candle quantifier. It is calculated by taking a moving average with an 'n' period of the difference between the opening and closing prices. A QStick value greater than zero means that most of the last 'n' days have been up, indicating that buying pressure is increasing. When the QStick indicator is less than zero selling pressure has been increasing. Thus, this indicator provides an approximation of the exponential moving average \(or EMA\) of the security, the opening price, the closing price, and their difference, as well as these values ​​of the simple moving averages \(or SMA\).

QStick, like many other technical indicators, provides a range of trading signals based on readings and divergences. Following are the three basic rules for trading with QStick:

1. Crossovers: the QStick oscillates above and below the zero line. The most basic trading principle is to buy a security on a cross up over the zero line and to sell the security on a cross down through the zero line. This technique will work well in sideways markets as the security is more likely to adhere to support and resistance levels.
2. Extreme Levels: the QStick also provides extreme readings that can often indicate market tops and bottoms. The QStick value has no upper or lower limit, so traders will have to look at previous tops and bottoms in the indicator when they run counter to impulsive moves.
3. Divergence: the last trading rule for the QStick indicator is to look for divergences between the price of the security and the indicator. Traders will want to buy the security if the QStick increases and the price decreases. Conversely, traders will want to sell when the QStick falls and the price rises.

### Calculation

The QSticks simply plots an n-period moving average that shows the difference between the close and open prices:

QStick = MA \(n, \(Close - Open\)\),

Where 'n' is the amount of periods for calculating themoving average.

### Main parameters

* Period – for selecting the period of Moving average, 20 by default;
* MA type – for selecting the type of Moving average, available types are Simple, Exponential, Modified, Linear weighted.

QStick can provide many informative trading signals. Extremely low QStick values together with a reversal tendency give a buy signal. Finding QStick at the top and starting reduction is a sell signal. In case the figures of QStick differ much from prices, it is a sign to follow the QStick direction to forecast price trend.

This indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_2%20%2825%29.jpg)

