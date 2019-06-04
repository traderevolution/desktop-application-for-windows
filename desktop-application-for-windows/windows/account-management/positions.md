# Positions

Positions panel lists all currently opened positions. When a new position is opened, it will appear in this panel immediately.

To open Positions panel, select Terminal -&gt; Positions:

![](../../../.gitbook/assets/9%20%289%29.png)

The following columns are available in the panel:

* Account – login name of an account that opened a position;
* Login - login of a user;
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
* SL price – Stop loss price set for a position;
* TP price – Take profit price set for a position;
* SL, value – shows a Stop loss sum in account currency which a trader risks by each symbol, if Stop loss triggers. Also, SL sum by all positions are output in Totals on the bottom of the panel, in order to know how much trader can lose.

### **Buttons toolbar**

The most important functions related to Positions can be viewed as buttons in the toolbar of the panel.

* Breakeven – allows modifying Stop loss orders to breakeven;
* Close all – closes all opened positions;
* CLX all – closes all opened positions and cancels all orders;
* Reverse all – reverses all positions;
* Close negative – closes the positions with negative P/L;
* Close positive – closes the positions with positive P/L;
* Close – closes all positions by selected symbol and account;
* Close selected – closes all selected positions;
* Reverse – reverses positions by selected symbol and account;
* Reverse selected – reverses all selected positions;
* CLX – closes opened positions and cancels orders by selected symbol and account;
* Close long – closes the positions with Side = Long;
* Close short – closes the positions with Side = Short.

To select the buttons to be displayed, simply right click on the toolbar of the panel and choose the needed buttons from the menu. The following hot buttons are checked by default: Close all, CLX all, Close negative, Close positive, Close selected and Reverse selected.

Note: clicking on these buttons doesn't evoke confirmation screens, even if confirmations are enabled in the 'General settings'.

### **Context menu**

The following functions can be realized through context menu:

* Modify position – allows adding SL/TP orders to selected position manually;
* Modify SL to breakeven – allows modifying Stop loss orders to breakeven;
* Quick SL/TP – allows quick adding SL/TP orders to selected position;
* Close position – allows closing all selected positions, all positions by selected symbol, all positions by selected account, all positions;
* Mutual close – allows closing opposite positions;
* Reverse – allows reversing all selected positions, all positions by selected symbol, all positions by selected account, all positions;
* View – allows to show total values and to show toolbar.



