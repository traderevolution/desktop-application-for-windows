# Order entry

Order entry panel allows to place market or pending orders. To open the Order entry panel select Terminal -&gt; Order entry.

![](../../../../.gitbook/assets/screenshot_1%20%2819%29.png)

This panel contains the following settings:

* Account - the account used for an order creation;
* PoA - the list, which allows selecting among Power of attorney persons that can trade on behalf of the the account owner;
* Symbol - the symbol available for the trade;
* Side - allows to activate Buy or Sell side;
* Quantity - an amount of lots in which an order is placed. The button![](../../../../.gitbook/assets/27.png)near this field allows to select among default values for Quantity from the drop-down list. The item 'Set defaults' calls the Types manager panel, allowing to edit the default values;
* Order type - defines the type of the order: Market, Limit, Stop, Stop limit, Trailing stop, OCO:

1. Market order is an order to buy or sell a security at the best available price immediately;
2. Limit order is placed to buy or sell a security at specified price or better;
3. Stop order is placed to buy or sell a security when its price surpasses a particular point, thus ensuring a greater probability of achieving a predetermined entry or exit price, limiting the investor's loss or locking in his or her profit. The![](../../../../.gitbook/assets/info%20%281%29.png)icon informs a user that additional Limit price is available if the checkbox 'Use stop limit instead of stop' is active in General settings; 
4. Stop limit order will be executed at a specified price \(or better\) after given stop price has been reached. Once the stop price is reached, the stop-limit order becomes a limit order to buy \(or sell\) at the limit price or better;
5. Trailing stop order sets the stop price at a fixed amount below the market price on the trailing offset. As the market price rises, the stop price rises by the trail amount, but if the stock price falls, the stop loss price doesn't change, and a market order is submitted when the stop price is hit. 'Buy' trailing stop orders are the mirror image of sell trailing stop orders;
6. OCO \(One-Cancels-the-Other\) is an order stipulating that if one part of the order is executed, then the other part is automatically canceled;

*  Validity – allows specifying order validity by selecting among the following time frames: Day, GTC, IOC, GTD, FOK. This is especially important for active traders:

1. A Day order, as the name implies, is valid for the current trading day;
2. GTC \(Good till cancelled\) orders, on the other hand, will remain alive until they are cancelled or the contract expires;
3. IOC \(Immediate or cancel\) requires the whole or part of the order to be executed immediately after it has been brought to the market;
4. FOK \(Fill or kill\) requires to execute the entire transaction immediately and completely or not to execute it at all;
5. GTD \(Good till date\) order will be cancelled on specified date if not executed or until the contract expires;
6. On open \(MOO\) orders are executed on the market open; 
7. On close \(MOC\) orders are executed on the market close;

* Received by - drop-down menu that determines the way the user issued a command on the order processing. The following values are available for selection in the list:

1. Voice - the command for processing the order was issued via a phone call;
2. Symphony - the command for processing the order was issued via the Symphony platform;
3. Email - the command for processing the order was issued in an email;
4. Bloomberg - the command for processing the order was issued via the Bloomberg Messenger;
5. Result of option expiry - the command for processing the order originated from an option expiration;
6. Option Exercise - the command for processing the order originated from an option exercise;
7. Reuters messenger - the command for processing the order was issued via the Reuters messenger;
8. OE - admin performs operations on the order;
9. Corporate action - the command for processing the order was issued via a corporate action.

{% hint style="warning" %}
If the user performs actions on the position or modifies the order from one of the menus, in which this parameter is available the "Received by" value is automatically switched to "OE".
{% endhint %}

* Stop price \(for the 'Stop order' type\) - allows entering the order stop price;
* Limit price \(available together with Stop price for the 'Stop order' and 'OCO' order types; also available for the 'Limit order' type\) - allows entering the order limit price;
* Tr. stop offset - \(for the 'Trailing stop' type\) - allows entering the order trailing stop price.

A user can set up set the Stop loss and Take profit directly from the Order entry panel if needed. 

![](../../../../.gitbook/assets/image%20%2821%29.png)

When![](https://lh3.googleusercontent.com/GorKXTd_KCxMmtRs3gRICVHDJL0cIa1C-Hdg8HtbUnSFtFRA0KIysRo9e1yeh5MPPm5YlfyGVlZqP3ypguEeRAf4xLeQ4p2xEVmACCNWu6ESLb8DBmUxuVWPOMLKOf7n8RcLnuqP)icon is activated![](https://lh4.googleusercontent.com/opZF6TnmrMrQ3ZY2SKJYsPgGYjxZbG1v_aTqzzFit9JfoDGzkx6eHrjRtgGByjNEI3n6NGQBKVmjMt-R2j12bQ7a0hGO-aYd7PrEBvkjGVmUWYCrZXSH951YAIOPqa_wcsQf2-lp)by clicking on it, and checkbox 'Use stop limit instead of stop' is true \(a setting located in Trading defaults tab of General settings\), the additional field 'SL limit price' will appear. It shows Limit price which is set for SL order. The field can be also displayed as 'SL limit offset'. This field shows Limit offset for SL order. The dependence is related to the values in which SL is displayed -  in price or offset.

It is always possible to manage risks by setting Trailing stop on the order by clicking on a special![](../../../../.gitbook/assets/tr-stop-1.png)button located near Stop loss. The blue color of the![](../../../../.gitbook/assets/tr-stop2%20%281%29.png)button indicates that the Trailing stop is activated. 

The first modification/placement of a Tr. stop order is carried out at the price which is available in the terminal at the time of these actions. In this case, the price at which the modification/placement of the Tr. stop occurs, can be seen in the confirmation screen.

* Get snapshot - this button is intended to get a snapshot of the actual quotes for the current Symbol. After clicking the button, the snapshot window will be opened. The window header displays the time when the snapshot was made, and in the window itself the user can find the following data:

![](../../../../.gitbook/assets/windows_snap.png)

1. Price - displays prices for Symbol in the context of Last/Bid/Ask;
2. Size - volumes for Symbol at the specified Price in the context of Last/Bid/Ask;
3. Change - price change, calculated by the formula _Change = Last price - Previous close_;
4. Change, % - price change as a percentage, calculated by the formula _Change,% = \(Last price - Previous close\) / Previous close\) \* 100%_;
5. Today high - highest price of the day for the current Symbol;
6. Today low - lowest price of the day for the current Symbol;
7. Today volume - current day volume for Symbol.

The "Get snapshot" button allows to update the information in this window.

Order entry panel has two additional sections which display important information: VWAP and Margin. VWAP section - allows displaying VWAP prices section \(Bid, Spread, Ask\) in the Order entry panel. It shows prices of order executions including slippage effect that will take place depending on order quantity user set.

![](../../../../.gitbook/assets/29%20%281%29.png)

* Margin section - allows displaying Margin section in the Order entry panel.

The **Margin** section is divided on two parts: Risks and Fees.

Risks details section shows all values in account currency:

* Balance - an account's balance;
* Available funds – amount of funds for placing new orders;
* Margin available – available margin for trading;
* Initial margin – minimum account balance required to open the position;
* Maintenance margin – minimum account balance required to keep this position open;
* Warn. margin  – margin value, for which the warning is triggered;

{% hint style="warning" %}
When the 'Tiered price based custom coeffieicent' margin calculation type is selected for the symbol, the margin req. values are displayed for all the Tiers set
{% endhint %}

* Impact on portfolio – shows impact of the order fill on available funds considering all other positions/orders;
* After trade funds – shows value of available funds remaining after filling the order:

After trade funds = Available funds + Impact on portfolio - Fee;

* Blocked for stocks – amount of funds debited from the balance in the case of trading with symbols with Stocks pre-paid margin type;
* Spread initial loss – shows initial loss on the spread:

Spread initial loss = \(Ask - Bid\) \* Tick cost \* Qty.

* P/L per Tick – displays data for Symbols:

P/L per Tick = Tick cost \* Qty - if a Symbol type is one of these: Futures, Options, Spreadbet;

P/L per Tick = Tick size \* Lot size \* Qty \* Cross-price **-** if a Symbol type is NOT one of these: Futures, Options, Spreadbet, Index;

P/L per Tick - no information for Index;

* Allow short positions – shows whether short positions opening is allowed for the symbol; 

**Fees** part shows commission for a trade. The fees shown depend on the Commission plan settings of the User:

* Fill per lot – shows the fee paid for each traded lot.
* Total fee – shows the commission total on the trade. 

Information of the Margin section can be updated by clicking on the button![](../../../../.gitbook/assets/30.png)at the right corner at the bottom of the Margin section, or by default it is updated every 30 seconds.

A user can click and drag the border of the panel to resize it to desired width.

### Data source

In the Order entry panel a user can see the the extended information about the source of Last, Bid and Ask prices. In order to open the table with the detailed information, click on the![](../../../../.gitbook/assets/screenshot_11%20%281%29.png)button and the widget will be shown:

![](../../../../.gitbook/assets/screenshot_2%20%2817%29.png)



