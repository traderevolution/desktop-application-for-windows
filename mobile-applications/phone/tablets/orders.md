# Orders

The Orders screen allows to view three lists of orders:

![](../../../.gitbook/assets/1%20%28150%29.png)

* Working orders – shows orders that are waiting for execution.
* Filled orders – shows executed orders.
* Orders history – each row displays info regarding creation, modification, execution or cancelling of orders.

Buy orders are displayed in the list with blue arrow, sell orders – with red.

Each section consists of the cards list with short information about the orders: for Working orders – symbol name, quantity, open price, order type; for Filled orders – symbol name, order type, Net P/L, quantity. In order to get full information about the symbol on which the order was created, tap the symbol name.

* Date/Time – date and time when the order was placed \(executed, filled, modified, or cancelled\).
* Current price – market price obtainable from broker.
* Stop price – stop price for special Stop and Trailing stop orders.
* Validity – allows specifying order validity by selecting among the following time frames: Day, GTC, IOC, GTD, FOK, GTS.
* Order ID – unique number that the trading system assigns to each order. If a position is opened based on an order, the position will have the same number.
* Stop loss – stop loss price set for the order.
* Take profit – take profit price set for the order.
* Qty. remaining – difference between quantity and executed quantity when only part of the order was executed.
* Bound to – ID of the order which another order is bound to; if the former is executed, system will cancel the latter.
* Account – login name of the account that opened the order.

Additional columns for Filled orders section:

* Trade ID – unique number of the trade.
* Exposure – quantity recalculated in account currency.
* Fee – shows commission connected with the trade.
* Bought – if Side = Buy, then this column shows the value of Price \* Lot size \* Qty in base currency; if Side = Sell, then this column shows the value of Price \* Lot size \* Qty in quoting currency.
* Sold – if Side = Sell, then this column shows the value of Price \* Lot size \* Qty in base currency; if Side = Buy, then this column shows the value of Price \* Lot size \* Qty in quoting currency.
* Trade volume – shows total volume of the trade.
* Price – shows price for Market and Limit orders, and Limit price for Stop limit orders. 

Filled orders and Orders history sections can be viewed by selected date range, available values here are: daily, two days to date, week to date, month to date. To choose the date range, tap the button![](../../../.gitbook/assets/calendar.jpg).

![](../../../.gitbook/assets/2%20%2888%29.png)

![](../../../.gitbook/assets/2%20%28126%29.png)

In order to modify active order, tap the ‘Modify’ button and the following screen will be opened:

![](../../../.gitbook/assets/5%20%2858%29.png)

Here user can modify price, quantity, Validity, Stop loss, Trailing, and Take profit. In addition, order can be executed at a market price. 

{% hint style="warning" %}
If Stop limit order is activated, the Stop price field will be disabled in Modify screen. Thus, only Limit price can be modified. The same is true for closing Stop loss limit orders.
{% endhint %}

In order to cancel the order, tap the 'Cancel' button.

