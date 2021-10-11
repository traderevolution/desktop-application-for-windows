# Pivot point

The Pivot point is a technical analysis or calculation indicator used to determine the general trend of the market over different time periods. The Pivot point itself is simply the average of the high, low, and close of the previous trading day. The next day, trading above the pivot point is considered to indicate continued bullish sentiment, while trading below the pivot point indicates the bearish sentiment.

The Pivot point is the basis of the indicator, but it also includes other support and resistance levels that are projected based on the pivot point calculation. All of these levels help traders see where the price may be experiencing support or resistance. Likewise, if the price moves through these levels, it gives the trader an indication that the price is moving in that direction.

This indicator is used to plot the lines of support and resistance, calculated on higher timeframes (H1 – W). The lines are plotted according to the principle "from the past to the future", for example, the user wants to plot Pivot lines for the last day in order to use it for trading on the current day (week, month, etc.).

This indicator is a multi-level tool, due to that, the trader can choose the most suitable option based on his/her own preferences and trading timeframe. This tool stands out for its simple settings and accurate information displaying.

Support and resistance levels data obtained with the help of the indicator allows predicting possible levels of Stop Loss and Take Profit with high precision.

### Calculation

Pivot points theory provides several algorithms for the calculation.

**Classic method:**

R3 = 2PP + H – 2L 

R2 = PP + H – L 

R1 = 2PP – L 

PP = (H + L + C)/3 

S1 = 2PP – H 

S2 = PP + L – H 

S3 = 2PP + L – 2H

**Camarilla method**

R3 = C + (H – L) **\* **0.275 

 R2 = C + (H – L) \* 0.182 

R1 = C + (H – L) \*_ _0.0916_ _

PP = (H + L + C) / 3 

S1 = C – (H – L) \* 0.0916 

S2 = C – (H – L) \*_ _0.183 

S3 = C – (H – L)_ \*_ 0.275

**Fibonacci method**

R3 = PP + 1.000 **\* **(H – L)

R2 = PP + 0.618_ \*_ (H – L) 

R1 = PP + 0.382 \*_ _(H – L) 

PP = (H + L + C) / 3 

S1 = PP – 0.382_ \*_ (H – L) 

S2 = PP – 0.618 \*_ _(H – L) 

S3 = PP – 1.000_ \*_ (H – L)

**Woodie method**

R3 = H + 2 **\* **(PP – L)

R2 = PP + (H – L) 

R1 = (2 \* PP) – L

PP = (H + L + 2 \* C) / 4 

S1 = (2 \* PP) – H 

S2 = PP – (H – L) 

S3 = L – 2_ \*_ (H – PP)

**DeMark method**

R1 = X / 2 – L 

PP = X / 4 

S1 = X / 2 – H

if C\[1] < O\[0] then X = (H + (L _ _2) + C) 

if C\[1] >_ _O\[0] then X = ((H_ _ 2) + L + C) 

if C\[1] = O\[0] then X = (H + L + (C \* 2))

where,

* C – Close, the close price in the previous period of the indicator;
* O – Open, the open price in the previous period of the indicator;
* H – High, the max price in the previous period of the indicator;
* L – Low, the min price in the previous period of the indicator;
* R1, R2, R3 – the 1st, 2nd, and 3rd levels of resistance;
* S1, S2, S3 – the 1st, 2nd, and 3rd levels of support;
* PP – Pivot Point, the central axis.

Note: parameters C, O, H, L are taken according to the "Base period" setting.

### Main parameters

* Only current period – defines whether Pivot levels are plotted based on previous periods. Example: if the parameter is set to "true" and the Base period = Day, Value = 1 are specified, then the lines will be plotted based on the previous D1 bar values, but will be plotted on the current day area, i.e. along the X-axis but within the current day range. If the parameter value is "false", then the Pivot lines are also plotted on the historical data, according to the "from the past to the future" principle;
* Base period: hour, day, week, and month;
* Method – allows choosing the method for plotting the indicator, available values: Classic, Camarilla, Fibonacci, Woodie, DeMark.

The indicator itself looks as follows on the chart:

![](../../../.gitbook/assets/pivot-point.jpg)

