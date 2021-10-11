# EMA (Exponential moving average)

The Exponential moving average is a** **type of moving average that is similar to a simple moving average, except that more weight is given to the latest data. The Exponential moving average is also known as the "Exponentially weighted moving average". 

The Exponential moving average can be used as a crossover system. For a crossover system, the user can insert three different Exponential moving averages. Typically, the lengths of these Moving averages are short-, intermediate-, and long-term. The commonly used system is 4, 9, and 18 intervals or periods. The interval can be in ticks, minutes, days, weeks, or months; it is a function of the chart period.

Moving averages work best in trending markets. A buy signal occurs when the short-term and intermediate-term averages cross from upward above the longer-term average. Conversely, a sell signal is issued when the short-term and intermediate-term averages cross from above to below the longer-term average. The user can utilize the same two Moving average signals, but most market technicians suggest using longer-term averages when trading only two Exponential moving averages in a crossover system.

Another trading approach is to use the current price concept. If the current price is above the Exponential moving averages, you buy. Liquidate this position when the current price crosses below either Moving average. For a short position, sell when the current price is below the Exponential moving average. Liquidate that position when the current price rises above the Exponential Moving Averages.

### Calculation

An exponentially smoothed Moving average is calculated by adding a certain share of the current closing price to the previous moving average value. With exponentially smoothed Moving averages, recent close prices are of more value. P-percent exponential moving average will look like this:

EMA = (CLOSE (i) \* P) + (EMA (i - 1) \* (1 - P))

Where:

CLOSE (i) — current period close price;

EMA (i - 1) — value of the Moving Average of a preceding period;

P — the percentage of using the price value.

### Main parameters

* Period: EMA period, 9 by default;
* Source price for EMA: Close, Open, High, Low, Median, Typical, and Weighted.

This technical indicator looks as follows on the chart:

![](<../../../../.gitbook/assets/screenshot\_1 (14).jpg>)
