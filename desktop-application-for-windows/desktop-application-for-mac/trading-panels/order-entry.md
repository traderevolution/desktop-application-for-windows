# Order entry

Order entry panel allows a user to place market or pending orders. To open the panel, select Terminal -&gt; Order entry. Additionally, this panel can be seen within Chart:

![](../../../.gitbook/assets/oe-mac-3.92.png)

This panel contains the following settings:

* Account – the account used for an order creation;
* Symbol – the symbol available for the trade;
* Side – allows to activate Buy or Sell side;
* Quantity – an amount of lots in which an order is placed;
* Order type – defines the type of the order: Market, Limit, Stop, Stop limit, Trailing stop, OCO:

1. Market order is an order to buy or sell a security at the best available price immediately;
2. Limit order is placed to buy or sell a security at specified price or better;
3. Stop order is placed to buy or sell a security when its price surpasses a particular point, thus ensuring a greater probability of achieving a predetermined entry or exit price, limiting the investor's loss or locking in his or her profit. The![](../../../.gitbook/assets/mac-oe-kopiya.png)icon informs a user that additional Limit price is available if the checkbox 'Use stop limit instead of stop' is active in the Preferences;  
4. Stop limit order will be executed at a specified price \(or better\) after given stop price has been reached. Once the stop price is reached, the stop-limit order becomes a limit order to buy \(or sell\) at the limit price or better;
5. OCO \(One-Cancels-the-Other\) is an order stipulating that if one part of the order is executed, then the other part is automatically canceled;
6. "Sell" trailing stop order sets the stop price at a fixed amount below the market price on the trailing offset. As the market price rises, the stop price rises by the trail amount, but if the stock price falls, the stop loss price doesn't change, and a market order is submitted when the stop price is hit. "Buy" trailing stop orders are the mirror image of sell trailing stop orders;

* TIF - Time-in-force option which allows traders to be more specific about time parameters in which an order is placed. This is especially important for active traders. It can be Day, GTC, IOC, FOK, GTD:

1. A Day order, as the name implies, is valid for the current trading day;
2. GTC \(Good till cancelled\) orders, on the other hand, will remain alive until they are cancelled or the contract expires;
3. IOC \(Immediate or cancel \) requires the whole or part of the order to be executed immediately after it has been brought to the market;
4. FOK \(Fill or kill\) requires to execute the entire transaction immediately and completely or not to execute it at all;
5. GTD \(Good till date\) order will be cancelled on specified date if not executed or until the contract expires;

* Stop price \(for the "Stop order" type\) - allows entering the order stop price;
* Limit price \(available together with Stop price for the "Stop order" and "OCO" order types; also available for the "Limit order" type\) - allows entering the order limit price;
* Tr. stop offset \(for the "Trailing stop" type\) - allows entering the order trailing stop price.
* SL/TP price - allows to set Stop loss and Take profit prices.

![](../../../.gitbook/assets/image%20%2828%29.png)

When![](https://lh3.googleusercontent.com/GorKXTd_KCxMmtRs3gRICVHDJL0cIa1C-Hdg8HtbUnSFtFRA0KIysRo9e1yeh5MPPm5YlfyGVlZqP3ypguEeRAf4xLeQ4p2xEVmACCNWu6ESLb8DBmUxuVWPOMLKOf7n8RcLnuqP)icon is activated![](https://lh4.googleusercontent.com/opZF6TnmrMrQ3ZY2SKJYsPgGYjxZbG1v_aTqzzFit9JfoDGzkx6eHrjRtgGByjNEI3n6NGQBKVmjMt-R2j12bQ7a0hGO-aYd7PrEBvkjGVmUWYCrZXSH951YAIOPqa_wcsQf2-lp)by clicking on it, and checkbox 'Use stop limit instead of stop' is true \(a setting located in Trading defaults tab of the Preferences\), the additional field 'SL limit price' will appear. It shows Limit price which is set for SL order. The field can be also displayed as 'SL limit offset'. This field shows Limit offset for SL order. The dependence is related to the values in which SL is displayed -  in price or offset.

It is always possible to manage risks by setting trailing stop on the order with the left clicking a special button![](../../../.gitbook/assets/grey.png)located near Stop loss. The blue color of the button![](../../../.gitbook/assets/blue.png)indicates that the trailing stop is activated.

Order entry panel has two additional sections which display important information: VWAP and Margin. 

* VWAP section - allows displaying VWAP prices section \(Bid, Spread, Ask\) in the Order entry panel. It shows prices of order executions including slippage effect that will take place depending on order quantity user set.
* Margin section - allows displaying Margin section in the Order entry panel.

The **Margin** section is divided on two parts: Risks and Fees.

Risks details section shows all values in account currency:

* Balance - an account's balance;
* Available funds – amount of funds for placing new orders;
* Margin available – available margin for trading;
* Initial margin – minimum account balance required to open the position;
* Maintenance margin – minimum account balance required to keep this position open;
* Warn. margin  – margin value, for which the warning is triggered;
* Impact on portfolio – shows impact of the order fill on available funds considering all other positions/orders;
* After trade funds – shows value of available funds remaining after filling the order:

After trade funds = Available funds + Impact on portfolio - Fee;

* Blocked for stocks – amount of funds debited from the balance in the case of trading with symbols with Stocks pre-paid margin type;
* Spread initial loss – shows initial loss on the spread:

Spread initial loss = \(Ask - Bid\) \* Tick cost \* Qty.

* P/L per Tick - displays data for Symbols:

 P/L per Tick = Tick cost \* Qty - if a Symbol type is one of these: Futures, Options, Spreadbet;

P/L per Tick = Tick size \* Lot size \* Qty \* Cross-price **-** if a Symbol type is NOT one of these: Futures, Options, Spreadbet, Index;

P/L per Tick - no information for Index.

**Fees** part shows commission for a trade:

Total fee – shows the commission total on the trade. It is displayed depending upon commission plan settings on the Server.

Information of the Margin section can be updated by clicking on the button![](../../../.gitbook/assets/oe-time.png)at the right corner at the bottom of the Margin section, or by default it is updated every 30 seconds.

