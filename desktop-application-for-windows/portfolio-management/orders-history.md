# Orders history

Order history panel allows to view system actions related to opening and closing orders \(SL/TP\). This can be particularly useful for monitoring specific details regarding creation, modification, removal, and execution of orders.

To open Order history panel, select Terminal -&gt; Order history:

![](../../.gitbook/assets/1%20%2831%29.png)

The following columns are available in the panel:

* Account – a login name of an account that opened an order;
* Symbol – a symbol for which an order was created;
* Side – a trade type \(Buy or Sell\);
* Event – an event identifier. The following values are available: Executed, Created, Modified, Canceled;
* Type – an order type;
* Price – an order price which a trade took place at;
* Quantity – a filled amount of an order, in lots or in currency units, depending on what is selected in the settings dialog box;
* Time – time of an order placement;
* Order ID – an order's unique identifier. If a position is opened based on an order, this position will have the same number;
* Date – an order's placement date;
* TIF – an order's time in force;
* Stop price – stop price for a special stop order;
* Login – a user's login;
* Symbol type – a symbol's market category \(CFD, Spot, Stocks, etc.\);
* Bought

- In case of Forex:

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in base currency;

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

- In case of Futures, Futures CFD, Options

with 'Quoting type=Tick cost/Tick size':

if 'Side = Buy', then this column shows the value of 'Qty';

if 'Side = Sell', then this column shows the value of 'Qty \* Tick cost/Tick size \* Price'.

with 'Quoting type=Lot size':

if 'Side = Buy', then this column shows the value of 'Qty';

if 'Side = Sell', then this column shows the value of 'Qty \* Lot size \* Price'.

- In other cases:

if 'Side = Buy', then this column shows the value of 'Qty. \* Lot size' – amount of bought assets \(contracts, equities\);

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

* Sold

- In case of Forex:

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in base currency;

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

- In case of Futures, Futures CFD, Options

with 'Quoting type=Tick cost/Tick size':

if 'Side = Buy', then this column shows the value of 'Qty\* Tick cost/Tick size \* Price';

if 'Side = Sell', then this column shows the value of 'Qty'.

with 'Quoting type=Lot size':

if 'Side = Buy', then this column shows the value of 'Qty \* Lot size \* Price';

if 'Side = Sell', then this column shows the value of 'Qty' .

- In other cases:

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency;

if 'Side = Sell', then this column shows the value of 'Qty. \* Lot size' – amount of sold assets \(contracts, equities\).

* Strike price – price of an option contract performance;
* Expiry date – a contract expiration date.



