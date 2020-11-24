# PPO \(Percentage price oscillator\)

The Percentage price oscillator \(PPO\) measures momentum. As with many technical analysis indicators, it is based on a moving average, which is used to show how price trends change over time.

A moving average takes previous closing price data over a period of time and averages that information to show a trend. The PPO is based on an Exponential moving average \(EMA\), which means that the latest price data has more weight.

A long EMA will provide more gradual moves as more price data is captured within it. The shorter EMA will move faster and converge to intraday price movement as the period shortens. Any EMA should be of the appropriate length to capture the current trend and eliminate random noise.

PPO and MACD are momentum indicators that measure the difference between 26-period and 12-period exponential moving averages. The main difference between these indicators is that the MACD reports the absolute difference between the EMAs, while the PPO expresses this difference as a percentage. This allows the trader to use the PPO indicator to easily compare assets with different prices.

When the PPO is above zero, it helps to confirm the uptrend as the short-term EMA is above the long-term EMA. When the PPO is below zero, the short-term EMA is below the long-term EMA, indicating a downtrend. Some traders prefer to accept buy signals only when the PPO is above zero or when the price shows a generally upward trajectory. Likewise, when the PPO is below zero, they can ignore buy signals and/or only accept short sell signals.

Crossing the center line also generates trading signals. Traders view a move from below to above the center line as bullish and a move from above to below the center line as bearish. PPO crosses the center line at the intersection of the 12-period and 26-period moving averages.

### Main parameters

* Fast EMA period – for selecting the period of fast EMA, 12 by default;
* Slow EMA period – for selecting the period of slow EMA, 26 by default;
* Signal EMA period – for selecting the period of signal EMA, 9 by default.

The indicator itself looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2823%29.jpg)

