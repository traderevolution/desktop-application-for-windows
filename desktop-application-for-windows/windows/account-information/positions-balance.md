# Positions balance

Positions balance panel shows a summary of the user's open positions by each symbol. To open a Positions balance panel, select Terminal -> Positions balance.

![](<../../../.gitbook/assets/14 (1).png>)

A user can select an account or a group of accounts for which he wants to see information.

The following columns are available in the panel:

* Symbol – ** **the instrument name.
* Net position qty. – net amount of opened positions.
* Break-even point – shows the price where Profit/Loss will be zero.

![](https://gblobscdn.gitbook.com/assets%2F-LMCqxhh2XAdWPUjcvxR%2F-MQIR50JOX7EHn3l1Qou%2F-MQIT3l5yiZLLxLxSFua%2F22.png?alt=media\&token=b1aefce9-3ed1-4ff3-a8fc-dfca3d9a9db4)

_where:_

_N - the number of open positions for the selected instrument;_

_OPi - Open price;_

_qty i - the volume of the "i" position, taking into account the sign, for a short position the sign is “-”, for a long position the sign is “+”._

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
* Position value – current value of the position. Calculation is based on current market price.

![](<../../../.gitbook/assets/screenshot\_2 (16).png>)

For long position: _Position value = Position exposure + Gross P/L_

For short position: _Position value = Position exposure - Gross P/L_

User has a possibility to close all positions through the context menu.

The total is shown in account currency if accounts by all opened positions have the same account currency; if accounts by which users have opened positions have different account currencies, then total is displayed in server currency.

{% hint style="warning" %}
Positions having the "Trading mode = Corporate actions" are displayed as separate rows.
{% endhint %}
