# Filled orders

Filled orders panel displays trading history. To open the Filled orders panel select Terminal -> Filled orders.

![](<../../../.gitbook/assets/2 (36).png>)

 User can select time period for which he wants to see trades. 

Click on![](<../../../.gitbook/assets/3 (23).png>)and choose the time filters.

The following columns are available in the panel:

* Trade ID – unique number of the trade.
* Order ID – unique number that the trading system assigns to each order. If a position is opened based on an order, the position will have the same number.
* Symbol – name of the traded instrument.
* Exposure – quantity recalculated in account currency.
* Order type – type of order.
* Symbol type – market category of the symbol (CFD, spot, stocks, etc.).
* Account – an account's name of a user who created an order.
* Side – type of trade (BUY or SELL).
* Quantity – amount of the trade.
* Price – shows price at which the order fills.
* Execution fee – commission connected with the trade.
* Gross P/L – total profit/loss of the trade.
* Net P/L – profit/losses for the symbol including commission.
* Time – time when the operation was executed.
* Date – date when the operation was executed.
* Login – login of the user.
* Bought

\- In case of Forex:

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in base currency;

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

\- In case of Futures, Futures CFD, Options

with 'Quoting type=Tick cost/Tick size':

if 'Side = Buy', then this column shows the value of 'Qty';

if 'Side = Sell', then this column shows the value of 'Qty \* Tick cost/Tick size \* Price'.

with 'Quoting type=Lot size':

if 'Side = Buy', then this column shows the value of 'Qty';

if 'Side = Sell', then this column shows the value of 'Qty \* Lot size \* Price'.

\- In other cases:

if 'Side = Buy', then this column shows the value of 'Qty. \* Lot size' – amount of bought assets (contracts, equities);

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

* Sold

\- In case of Forex:

if 'Side = Sell', then this column shows the value of 'Price \* Lot size \* Qty.' in base currency;

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency.

\- In case of Futures, Futures CFD, Options

with 'Quoting type=Tick cost/Tick size':

if 'Side = Buy', then this column shows the value of 'Qty\* Tick cost/Tick size \* Price';

if 'Side = Sell', then this column shows the value of 'Qty'.

with 'Quoting type=Lot size':

if 'Side = Buy', then this column shows the value of 'Qty \* Lot size \* Price';

if 'Side = Sell', then this column shows the value of 'Qty' .

\- In other cases:

if 'Side = Buy', then this column shows the value of 'Price \* Lot size \* Qty.' in quoting currency;

if 'Side = Sell', then this column shows the value of 'Qty. \* Lot size' – amount of sold assets (contracts, equities).

* Rebates – shows amount of money that was returned/paid for filling this order which added/removed liquidity.
* Expiry date – date of contract expiration.
* Strike price – price of option contract performance;
* Trading exchange – displays a trading exchange where the order was placed;
* Product type – displays the product type;
* Description – contains a short description of the instrument by which the event was executed.

