# Orders & Positions history

### **Orders history**

Orders history panel shows all orders sent during the backtesting. History range can be set in Backtesting setup -&gt; Range.

![](../../.gitbook/assets/1%20%2844%29.png)

The following columns are available in the panel:

* Account – an account's name of a user who created an order;
* Symbol – a symbol for which an order was created;
* Side – a trade type \(Buy or Sell\);
* Type – an order type;
* Price – an order price at which a trade took place;
* Quantity – a filled amount of an order, in lots or in currency units, depending on what is selected in the settings dialog box;
* Date/Time – date and time of an order placement;
* Order ID – an order's unique identifier. If a position is opened based on an order, this position will have the same number;
* TIF – an order's time in force;
* Stop price – stop price for a special stop order;
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
* Expiry date – a contract expiration date;
*  Trading exchange – indicates whether the instrument has a stock exchange or off-exchange type.

Customer can also use standard functions from context menu of the panel:

* Clear – allows deleting all orders from the panel;
* Search – allows to show/hide a Search lookup in the panel;
* Export – allows to export table to CSV or Excel format;
* Group by – allows to group orders by symbol, account, side, event, type, date/time, bought, sold.

### **Positions history**

Positions history panel shows positions which were opened for a certain period during the backtesting. 

![](../../.gitbook/assets/screenshot_10.png)

The following columns are available in the panel:

* Account – login name of an account that opened a position;
* Symbol – a traded symbol;
* Position ID – a unique number that the trading system assigns to each position;
* Open price – price at which a position was opened;
* Quantity – amount of a position, either in lots or in units, depending on what is selected in the Settings dialog box;
* Gross P/L – profit/loss in account currency, calculated on base of price difference:

           For Long position: Gross P/L = Qty. \* Lot size \* \(Current price - Open price\)

           For Short position: Gross P/L = Qty. \* Lot size \* \(Open price - Current price\)

           P/L for Spreadbet instrument type is calculated depending on price change in ticks:

           For Long position: Gross P/L = Qty. \* Bet size \* Cross price \* \(\(Current price - Open price\)/Tick size\)\)

           For Short position: Gross P/L = Qty. \* Bet size \* Cross price \* \(\(Open price - Current price\)/Tick size\)\)

           Cross price is applied in the case when account currency doesn't correspond to the Betting currency.

* Open time – time when position was opened;
* Open date – date when position was opened;
* Close time – time when position was closed;
* Close date – date when position was closed;
* Operation – type of trade \(Buy or Sell\).

For this panel the same functions as for Orders history are available in context menu.

