# Order entry

Order entry panel allows to place market or pending orders. To open the Order entry panel select   Terminal -&gt; Order entry.

![](../../.gitbook/assets/1%20%2827%29.png)

This panel contains the following settings:

* Account – the account used for an order creation;
* Symbol – the symbol available for the trade;
* Side – allows to activate Buy or Sell side;
* Quantity – an amount of lots in which an order is placed. The![](../../.gitbook/assets/2%20%2832%29.png)button near this field allows to select among default values for Quantity from the drop-down list. The item ‘Set defaults’ calls the Types manager panel, allowing to edit the default values;
* Order type – defines the type of the order: Market, Limit, Stop, Stop limit, Trailing stop, OCO:

1. Market order is an order to buy or sell a security at the best available price immediately;
2. Limit order is placed to buy or sell a security at specified price or better;
3. Stop order is placed to buy or sell a security when its price surpasses a particular point, thus ensuring a greater probability of achieving a predetermined entry or exit price, limiting the investor's loss or locking in his or her profit;
4. Stop limit order will be executed at a specified price \(or better\) after given stop price has been reached. Once the stop price is reached, the Stop limit order becomes a Limit order to buy \(or sell\) at the limit price or better;
5. OCO \(One-Cancels-the-Other\) is an order stipulating that if one part of the order is executed, then the other part is automatically canceled;
6. ‘Sell’ trailing stop order sets the stop price at a fixed amount below the market price on the trailing offset. As the market price rises, the stop price rises by the trail amount, but if the stock price falls, the stop loss price doesn't change, and a market order is submitted when the stop price is hit. ‘Buy’ trailing stop orders are the mirror image of sell trailing stop orders;

* TIF – Time-in-force option which allows traders to be more specific about time parameters in which an order is placed. This is especially important for active traders. It can be Day, GTC, IOC, FOK, GTD:

1. A Day order, as the name implies, is valid for the current trading day;
2. GTC \(Good till cancelled\) orders, on the other hand, will remain alive until they are cancelled or the contract expires;
3. IOC \(Immediate or cancel\) requires the whole or part of the order to be executed immediately after it has been brought to the market;
4. FOK \(Fill or kill\) requires to execute the entire transaction immediately and completely or not to execute it at all;
5. GTD \(Good till date\) order will be cancelled on specified date if not executed or until the contract expires;

* Stop price \(for the ‘Stop order’ type\) – allows entering the order stop price;
* Limit price \(available together with Stop price for the ‘Stop order’ and ‘OCO’ order types; also available for the ‘Limit order’ type\) – allows entering the order limit price;
* Tr. stop offset \(for the ‘Trailing stop’ type\) – allows entering the order trailing stop price.

You can set up set the Stop loss and Take profit directly from the Order entry panel if needed. It is always possible to manage risks by setting Trailing stop on the order by clicking on a special![](../../.gitbook/assets/3%20%2833%29.png)button located near Stop loss. The blue color of the![](../../.gitbook/assets/4%20%284%29.png)button indicates that the Trailing stop is activated. 

Order entry panel has the additional VWAP section which displays important information. VWAP section allows displaying VWAP prices section \(Bid, Spread, Ask\) in the Order entry panel.

![](../../.gitbook/assets/5%20%2833%29.png)

