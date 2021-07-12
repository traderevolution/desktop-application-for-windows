# Stochastic \(Stochastic slow\)

Developed by George C. Lane in the late 1950s, the Stochastic oscillator is a momentum indicator that shows the location of the close relative to the high-low range over a set number of periods. The indicator can range from 0 to 100.

The closing price tends to close near the high in an uptrend and near the low in a downtrend. If the closing price then slips away from the high or the low, then momentum is slowing. Stochastics are most effective in broad trading ranges or slow-moving trends. Two lines are graphed, the slow oscillating %K and a moving average of %K commonly referred to as %D.

The difference between the Slow and Fast stochastic oscillators is the Slow %K incorporates a %K slowing period of 3 that controls the internal smoothing of %K. Setting the smoothing period to 1 is equivalent to plotting the Fast stochastic oscillator.

### Calculation <a id="calculation"></a>

**Stochastic oscillator**

The Stochastic oscillator has four variables:

1. %K periods. The number of time periods used in the stochastic calculation;
2. %K slowing periods. This value controls the internal smoothing of %K. A value of 1 is considered a fast stochastic; a value of 3 is considered a slow stochastic;
3. %D periods. This is the number of time periods used when calculating a moving average of %K;
4. %D method. The method \(i.e., Exponential, Simple, Smoothed, or Weighted\) that is used to calculate %D.

Stochastic is calculated by the following formulas:

%K = \(Close – Low \(%K\)\) / \(High\(%K\) – Low\(%K\)\) \* 100, where

* Close — today’s closing price;
* Low \(%K\) — lowest low in %K periods;
* High \(%K\) — highest high in %K periods.

The %D moving average is calculated using the formula:

%D = SMA \(%K, N\), where

* N — smoothing period;
* SMA — Simple moving average.

Once the %K line climbs into the 80 and above the region of the Stochastic scale, analysts consider this to be an overbought condition. This could lead to a sell-off forcing the price downwards.

When the %K line falls below 20 on the Stochastic scale, the market may now consider the currency pair to be oversold. As a result, traders may start buying thereby lifting the price higher as the market scoops up a "bargain".

Range lines with values of 20 and 80 are generally accepted constants for this indicator.

**Slow stochastic oscillator**

* Slow %K = Fast %K smoothed with 3-period SMA
* Slow %D = 3-period SMA of Slow %K

The data for the SMA calculating are the values of the stochastic oscillator, calculated using the formula above in this article.

The Slow stochastic applies further smoothing to the Stochastic oscillator in order to reduce volatility and improve signal accuracy. Trading signals are the same as for the Stochastic oscillator.

Signals are listed in order of their importance:

1. Go long on bullish divergence \(on %D\) where the first trough is below the Oversold level;
2. Go long when %K or %D falls below the Oversold level and rises back above it;
3. Go long when %K crosses above %D.

Short signals:

1. Go short on bearish divergence \(on %D\) where the first peak is above the Overbought level;
2. Go short when %K or %D rises above the Overbought level then falls back below it;
3. Go short when %K crosses below %D.

### Main parameters <a id="main-parameters"></a>

* Period of indicator – number of data that is involved in the calculation of the stochastic oscillator, 10 by default;
* %K period – number of periods involved in the smoothing of the Stochastic oscillator, 3 by default;
* %D period – number of periods used when calculating a moving average of %K, 3 by default.

The indicator itself looks as follows on the chart:

![](../../../../.gitbook/assets/mac%20%283%29.png)

