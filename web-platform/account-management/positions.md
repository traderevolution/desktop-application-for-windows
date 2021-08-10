# Positions

Positions panel lists all currently opened positions. When a new position is opened, it will appear in this panel immediately. To open Positions panel, select Terminal -&gt; Positions:

![](../../.gitbook/assets/1%20%2865%29.png)

The following columns are available in the panel:

* Symbol – a traded symbol;
* Account – login name of an account that opened a position;
* Login – login of a user;
* Symbol description – comments to an instrument;
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

* P/L, offset – profit/losses in ticks;
* Net P/L – profit/loss for a position excluding fee:

        Net P/L = Gross P/L - Fee

* Position exposure – exposure of a position, in the account currency. Calculated on base of an open price:

        Position exposure = Price \* Quantity \* Lot size \* Cross price \(quoting CCY &gt; account currency\) – calculation for Forex

        Position exposure = Price \* Quantity \* \(Tick cost/Tick size\) \* Cross price \(quoting CCY &gt; account currency\) – calculation for Futures

        In all cases Cross price \(quoting CCY &gt; account currency\) is a current cross price.

* Position value – current value of a position. Calculated on base of a current market price:

        For Long position: Position value = Position exposure + P/L

        For Short position: Position value = Position exposure – P/L

* Fee – shows total commission amount taken for a position;
* Swaps – amounts collected/paid out by a broker when a position is rolled over to a new value date;
* Expiry date – date of contract expiration;
* Strike price – price of option contract performance;
* Route – name of a route;
* SL price – Stop loss price set for a position;
* TP price – Take profit price set for a position;
* SL limit price – Limit price set for SL order;
* Close – allows to close a selected position.

### **Buttons toolbar**

The most important functions related to Positions can be viewed as buttons in the toolbar of the panel.

* Close all – closes all opened positions;
* CLX all – closes all opened positions and cancels all orders;
* Close negative – closes the positions with negative P/L;
* Close positive – closes the positions with positive P/L;
* Close – closes all positions by selected symbol and account;
* Close selected – closes all selected positions;
* CLX – closes opened positions and cancels orders by selected symbol and account;
* Close long – closes the positions with Side = Long;
* Close short – closes the positions with Side = Short.

To select the buttons to be displayed, simply right-click on the toolbar of the panel and select the needed buttons from the menu.

{% hint style="warning" %}
Clicking these buttons doesn't evoke confirmation screens, even if confirmations are enabled in the 'General settings'.
{% endhint %}

### **Context menu**

The following functions can be realized through context menu:

* Modify position – allows adding SL/TP orders to selected position manually;
* Close position – allows closing selected positions;
* View – allows to show toolbar;
* Group by – allows to group positions by account, login, symbol, symbol description, symbol type, side, expiry date, strike price;
* Exercise options – sends an exercise request for the Option position. Available for single positions opened for Options with Exercise style=American, inactive for multiple selected positions. 

  After clicking this menu item, a confirmation dialog box is displayed with the Position ID, Symbol, Side, Quantity to close, Open price, Current price, Gross P/L to close, Account, Date/Time position parameters.

  Clicking the "Exercise" button in the confirmation box, creates a request for the Option exercise, which switches the position to Pending exercise status and prevents performing the following operations for the position: **Close position, Close by\(ID\), Reverse, Reverse by \(ID\).**

  The mentioned actions are reenabled for the position after the "Cancel exercise" action is performed.

* Cancel exercise – cancels an exercise request for the selected Option position with Pending exercise status. Available for single positions opened for Options with Exercise style=American, inactive for multiple selected positions.

  After clicking this menu item, a confirmation dialog box is displayed, which requires a confirmation of canceling an Option exercise request. After the exercise Option request is canceled, the **Close position, Close by\(ID\), Reverse, Reverse by \(ID\)** operations become allowed for the position.



