# Working orders & Positions

Working orders/Positions panels show the orders/positions that were opened during the backtesting. 

The following columns are available for the Positions panel:

![](../../.gitbook/assets/1%20%2811%29.png)

* Account – login name of an account that opened a position;
* Symbol – a traded symbol;
* Symbol description - comments to an instrument;
* Symbol type – a symbol's market category \(CFD, spot, stocks, etc.\);
* Position ID – a unique number that the trading system assigns to each position;
* Side – type of trade \(Long or Short\);
* Open price – price at which a position was opened;
* Current price – a market price obtainable from a broker;
* Quantity – amount of a position, either in lots or in units, depending on what is selected in the Settings dialog box;
* Date/Time – date and time when a position was opened;
* Gross P/L – profit/loss in account currency, calculated on base of price difference:

        For Long position: Gross P/L = Qty. \* Lot size \* \(Current price - Open price\)

        For Short position: Gross P/L = Qty. \* Lot size \* \(Open price - Current price\)

        P/L for Spreadbet instrument type is calculated depending on price change in ticks:

        For Long position: Gross P/L = Qty. \* Bet size \* Cross price \* \(\(Current price - Open price\)/Tick size\)\)

        For Short position: Gross P/L = Qty. \* Bet size \* Cross price \* \(\(Open price - Current price\)/Tick size\)\)

        Cross price is applied in the case when account currency doesn't correspond to the Betting currency.

* P/L, offset – profit/losses in points;
* Position exposure – exposure of a position, in the account currency. Calculated on base of an open price:

        Position exposure = Price \* Quantity \* Lot size \* Cross price \(quoting CCY &gt; account currency\) – calculation for Forex

        Position exposure = Price \* Quantity \* \(Tick cost/Tick size\) \* Cross price \(quoting CCY &gt; account currency\) – calculation for Futures

        In all cases Cross price \(quoting CCY &gt; account currency\) is a current cross price.

* Position value – current value of a position. Calculated on base of a current market price:

        For Long position: Position value = Position exposure + P/L

        For Short position: Position value = Position exposure – P/L

* Expiry date – date of contract expiration;
* SL price – Stop loss price set for a position;
* TP price – Take profit price set for a position;
* SL, value – shows a Stop loss sum in account currency which a trader risks by each symbol, if Stop loss triggers. Also, SL sum by all positions are output in Totals on the bottom of the panel, in order to know how much trader can lose;
* Trading exchange - indicates whether the instrument has a stock exchange or off-exchange type.

    And for the Working orders panel:

![](../../.gitbook/assets/screenshot_2.png)

* Symbol – name of the instrument to be traded.
* Side – type of the trade to be performed \(Buy or Sell\).
* Date – date, on which the order was placed.
* Time – time when the order was placed.
* Type – the order type.
* Quantity – the order amount measured in lots or in currency units, depending on what is selected in the Settings dialog box.
* Price – price, at which the order is to be executed.
* Stop price – stop price for special stop order.
* Current price – market price obtainable from broker.
* TIF – the order's time in force.
* Qty. filled – executed quantity of the order when only part of the order was executed.
* Qty. remaining – difference between quantity and executed quantity when only part of the order was executed.
* Order ID – unique number that the trading system assigns to each order. If a position is opened based on an order, the position will have the same number.
* Account – login name of the account that placed the order.
* SL price – stop loss price set for the order.
* TP price – take profit price set for the order.
* Bound to \(OCO\) – ID of the order which another order is bound to; if the former is executed, system will cancel the latter.
* Symbol type – market category of the instrument \(CFD, spot, stocks, etc.\).
* Symbol description – comments to the instrument.
* Trading exchange – indicates whether the instrument has a stock exchange or off-exchange type.
* Status – status of the current order. It can have the following values: Created, Partially filled, Off market, Cancelling, Modified;
* Strike price – price of option contract performance.
* Expiry date – date of contract expiration.

### **Context menu**

The following functions can be realized through the context menu:

* Export – allows to export table to CSV or Excel format.
* Group by – allows to group positions by symbol, account, expiry date, side, symbol type, symbol description, and to group working orders by the same parameters as well as by date, time, TIF, Qty. filled, Qty. remaining, exchange, status.
* Show close orders \(SL/TP\) – if checked, closing orders will be shown \(only for Working orders panel\).

