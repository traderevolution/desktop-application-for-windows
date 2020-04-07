# Filled orders

Filled orders panel displays trading history performed during backtesting.

![](../../.gitbook/assets/2%20%2827%29.png)

The following columns are available in the panel:

* Symbol – name of the traded instrument;
* Side – type of trade \(Buy or Sell\);
* Quantity – amount of the trade;
* Price – shows price at which the order fills;
* Date/Time – date/time when the operation was executed.
*  Trade ID – unique number of the trade;
* Order ID – unique number that the trading system assigns to each order. If a position is opened based on an order, the position will have the same number;
* Exposure – quantity recalculated in account currency;
* Order type – type of order;
* Account – an account's name of a user who created an order;
* Gross P/L – total profit/loss of the trade;
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

* Expiry date – date of contract expiration;
* Strike price – price of option contract performance.

### **Context menu**

Customer can also use standard functions from context menu of the panel:

* Clear – allows deleting all orders from the panel;
* View on chart – allows showing trades on the chart;
* Export – allows to export table to CSV or Excel format;
* Group by – allows to group orders by symbol, account, side, order type, date/time;
* Search – allows to show/hide a search lookup in the panel.

