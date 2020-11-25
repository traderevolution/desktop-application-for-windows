# SI \(Swing index\)

The Swing Index was developed by Wells Wilder to assess the direction of a price change and its strength in relation to price swings. The Swing Index uses data from the last two bars in order to determine a possible trend change over a longer period of time. Specifically, Swing Index helps identify moments when investors change their trading behavior - moments when price changes \(previously aligned with price swings\) begin to move in the opposite direction of swings when a previously strong and consistent group of investors \(Bulls or Bears\) becomes weaker and short-lived only. Since the Swing Index uses data from only two bars to determine the possible development of a longer trend, it mainly attracts short-term intraday traders who are most interested in short-term price fluctuations.

According to Technical Analysis theory,

* a buy signal can be considered when the Swing Index crosses over zero value - the trader can expect a short-term upward price movement - the price is not growing yet, but we have an upward swing;
* a sell signal can be viewed when the Swing Index falls below zero - the trader can expect a short-term downward price movement - the price has not yet moved down, but we are starting to have a downward swing.

### Calculation

The basic formula for the Swing Index is:

Swing Index = 50 \* \[ { Cy - C + 0.5\(Cy - Oy\) + 0.25\(C - O\) } / R \] \* \(K / T\)

Where:

C = Today's closing price

L = Today's lowest price

O = Today's opening price

Cy = Yesterday's closing price

Ly = Yesterday's lowest price

Oy = Yesterday's opening price

Hy = Yesterday's highest price

K = the larger of either \(Hy - C\) or \(Ly - C\)

R = A variable based on the relationship between today's closing price and yesterday's high and low

To calculate R, determine the largest of:

1. Hу - C
2. Lу - C
3. Hу - Lу

If \(1\) is the largest, R = \(Hу - C\) - .5\(Lу - C\) + .25\(C - O\)

If \(2\) is the largest, R = \(Lу - C\) - .5\(Hу - C\) + .25\(C - O\)

If \(3\) is the largest, R = \(Hу - Lу\) + .25\(C - O\)

T = move limit in one direction

### Main parameters

T -  move limit value in one direction, default is 300.0

The indicator looks as follows on the chart

![](../../../../.gitbook/assets/screenshot_1%20%2833%29.jpg)

