# Positions balance

Positions balance panel shows a summary of the user's open positions by each symbol. To open a Positions balance panel, select Terminal -&gt; Positions balance.

![](https://lh3.googleusercontent.com/rq10TuwrGGbDjgJblmM-CobdcW6e0VTh4PsH5Au-3LW0xCyOAQ8zVVn9pKgBmn1nwztgkawo9U_9EYo2zQQNpv-el9B9AjGUCM7MDQyzL-Qz9lNefE78Luixq2gW8YIQilo514AM)

A user can select an account or a group of accounts for which he wants to see information.

For a user who has several accounts or Linked accounts, there is an Account lookup located at the panel’s toolbar. It allows selecting an account by which the data will be displayed in the panel. Furthermore, the Account lookup contains the Multi-select mechanism.

![](https://lh5.googleusercontent.com/of0ZNzlBp75pa0GUpg8kRqsJdjbdXCW3dxPHZ4KTSZNvVjeTnxG4jPeLxACLrmE6cWw43VOnPcjxRXR8OTOZp3bGIMboJBsxq_2h2fm0LFC4yPdOIT_rjOcniA5NXfJIVofS1sTh)

The following columns are available in the panel:

* Symbol – the instrument name.
* Net position qty. – net amount of opened positions.
* Break-even point – shows the price where Profit/Loss will be zero.

![](../../.gitbook/assets/22%20%282%29.png)

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
* Strike price – price of option contract performance.
* Expiration date – date of contract expiration.
* Symbol type – type of the symbol.
* Position value – the current value of the position. Calculation is based on the current market price.

![](../../.gitbook/assets/screenshot_2%20%2815%29.png)

For long position: _Position value = Position exposure + Gross P/L_

For short position: _Position value = Position exposure - Gross P/L_

User has a possibility to close all positions through the context menu.

The total is shown in account currency if accounts by all opened positions have the same account currency; if accounts by which users have opened positions have different account currencies, then total is displayed in server currency.  


