# Keltner channel

The Keltner channel is a technical analysis indicator that shows a central moving average line plus the channel lines at a distance above and below. The indicator is named after Chester W. Keltner, who described it in his 1960 book "How to make money in commodities". This name was applied by those who heard of it from him, but Keltner itself called it the ten-day moving average trading rule and indeed made no claim to any originality for the idea.

In Keltner's description, the centerline is a 10-day simple moving average of the typical price, where the typical price each day is the average of high, low, and close,

Typical price = \(high + low + close\)/3

The lines above and below are drawn at a distance from this centerline, a distance that is a simple moving average of trading ranges over the past 10 days \(i.e. a range from high to low on each day\).

The trading strategy is to treat a close above the upper line as a strong bullish signal or a close below the lower line as a strong bearish sentiment and buy or sell with the trend accordingly, but perhaps with other indicators to confirm. Exits can be based on a very conservative Stop loss, a rather high Take profit, and a cross with the centerline. On the chart, this looks as follows:

![](../../../../.gitbook/assets/screenshot_1%20%2811%29.jpg)

### Input parameters

* Source prices for a Moving average \(Low, High, Close, Open, Typical, Medium, Weighted\);
* Moving average type \(Simple, Exponential, Modified, Linear weighted\);
* Moving average period;
* Channel width coefficient.

