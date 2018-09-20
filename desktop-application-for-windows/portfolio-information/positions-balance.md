# Positions balance

Positions balance panel shows a summary of users opened positions by symbol. To open a Positions balance panel, select Terminal -&gt; Positions balance.

![](../../.gitbook/assets/14%20%281%29.png)

User can select account or group of accounts for which he wants to see information.

The following columns are available in the panel:

* Symbol – title of the instrument.
* Net position qty. – net amount of opened positions.
* Break-even point – shows the price where Profit/Loss will be zero.

Break-even point = \(Long qty.\*Average long – Short qty.\*Average short\)/\(Long qty. – Short qty.\)

* Current price – current market price.
* Gross P/L – profit/loss in the accounts currency.
* Long qty. – total amount of long positions by symbol.
* Average long – average price of long positions.
* Short qty. – total amount of short positions by symbol.
* Average short – average selling price of short positions.
* Net exposure – net exposure for opened positions by symbol.
* Gross exposure – the total exposure for open positions by symbol.
* Exp. date – date of contract expiration.
* Strike price – price of option contract performance.
* Position value – current value of the position. Calculated based on current market price.

Position value = Sum \(Position value\[i\] \* Cross price\[i\]\)

For long position: Position value = \(Position exposure + Gross P/L\)

For short position: Position value = \(Position exposure - Gross P/L\)

User has a possibility to close all positions through context menu.

The total is shown in account currency if accounts by all opened positions have the same account currency; if accounts by which user have opened positions have different account currencies, then total is displayed in server currency.

