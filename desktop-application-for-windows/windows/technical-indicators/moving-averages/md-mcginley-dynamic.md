# MD \(McGinley dynamic\)

A little known technical indicator developed by John McGinley in 1990. The indicator attempts to solve a problem inherent in moving averages that use fixed time intervals \(i.e. moving averages with a period of 10 or 21\), the problem that causes those moving averages to be outrun in fast markets.

The McGinley Dynamic indicator \(MD\) was developed to avoid false trading signals due to volatility spikes. While this looks like a "normal" moving average, it actually uses an offset to push the moving average forward 1 period and a volatility filter to avoid reversals. While simple and exponential moving averages are faster than the MD, the MD adjusts to faster/slower moving markets and has a more stable track record when associated with longer-term trends. 

Key findings of the indicator are:

* The McGinley Dynamic Indicator is a type of moving average that has been designed to better track the market than existing moving average indicators;
* The McGinley Dynamic indicator solves the problem of changing market speeds by including an automatic adjustment factor in its formula that speeds up or slows down the indicator in trending or ranging markets;
* The McGinley Dynamic Indicator enhances conventional moving averages by minimizing price separation and volatile reversals to more accurately reflect price movement.

### Calculation

The indicator is calculated using the following simplified formula:

Dynamic = Yesterday's EMA + \( \( Today's close - Yesterday's EMA \) / \( Today's close / Yesterday's EMA \* 125 \) \)

Where: 

* 125 - smoothing factor \(periods\) set by default;
* EMA – Exponential moving average.

### Main settings

The main setting of this indicator, which differs from others, is Periods of smoothing i.e. the number of periods involved in smoothing the indicator.

Bullish, Buy Signals and Bearish, Sell Signals.

McGinley indicator should be combined with moving averages to form a Forex trading system. This indicator should be used as the smoothing mechanism where the moving average is volatile or ranging:

* Bullish, Buy Signal – buy signal is generated when the price crosses above the indicator;
* Bearish, Sell Signal – sell signal is generated when the price crosses below the indicator.

This indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_2%20%2814%29.jpg)

