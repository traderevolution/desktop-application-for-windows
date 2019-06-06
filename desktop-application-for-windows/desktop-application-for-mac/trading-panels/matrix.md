# Matrix

The Matrix panel allows to view open positions, pending orders, market prices, quantity and P/L. Furthermore, a trader can place an order just in 1 click using this panel. 

To open the Matrix panel, go to Terminal -&gt; Matrix:

![](../../../.gitbook/assets/matrix.png)

The Symbol lookup is at the top of the Matrix panel.

![](../../../.gitbook/assets/toolbar.png)

* Compress spread – allows skipping empty levels between the best bid and best ask;
* Auto-centring button – allows auto-centering the panel relatively to spread;
* Mouse trading button – allows one-click trading with the help of the mouse.

Day high/low – allows showing current high/low levels.

![](../../../.gitbook/assets/super-dom.png)

Right-clicking within the Market depth section evokes the Context menu of the panel.

![](../../../.gitbook/assets/matrix-context-menu1.png)

* View – allows to show/hide Position bar and built-in Order entry;
* Set hotkeys – allows to open the ‘General’ tab in the ‘Hotkeys Preferences’ window;  
* Compress spread – allows skipping empty levels between the best Bid and best Ask;
* Last price indicator – allows to show last price indicator;
* Auto-centring – allows auto-centring the panel relatively to spread;
* Show day high/low – allows showing current high/low levels;
* Settlement price – allows displaying settlement price;
* Previous settlement price – allows displaying previous settlement price;
* Antagonistic size bars – allows to determine the direction of volume histograms. If true, the histograms appear from the different boundaries of the column ‘Size’. If false, the histograms appear from the left boundary of the column ‘Size’. Default state: true;
* Full-size cells – allows extending the bars;

![](../../../.gitbook/assets/small-size.png)

![](../../../.gitbook/assets/full-size.png)

* Preferences – allows opening ‘Matrix Preferences’ dialog box.

The bottom position bar shows the current state of the position: open price, open position quantity, current profit and loss.

![](../../../.gitbook/assets/screen-shot1-2018-12-19-at-6.10.png)

When clicking on the P/L value, the following options can be selected: Ticks/Points.

QTY cell changes its color depending on the side of the position:

1.    If all positions have Side = Long, qty. cell will be colored in blue;

2.    If all positions have Side = Short, qty. cell will be colored in red;

3.    If positions are multi-directional, then qty. cell is not colored;

4.    If there are no positions, qty. cell will not be colored and qty. value = N/A.

* When trading multi-position symbols, open price of all the positions is calculated as weighted average value;
* The Orders column shows all pending orders and allows their modification. Limit orders are displayed as numbers, and Stop orders - as underlined numbers. Group of orders is displayed with two vertical lines of the pending order left side;
* The Size column shows how many trade operations with Ask/Bid are available at a specific price;
* Clicking on Cancel buy, Cancel sell, or Cancel all will close all buy, sell, or total orders respectively for the currently displayed symbol and account;
* Close position button allows closing the current position by selected symbol and account.

On the right side of the Matrix panel there is a built-in Order entry panel. The order amount can be specified on the top of panel. Also the TIF of the order, SL/TP offset and Trailing stop.

Click on Buy Market or Sell Market to Buy/Sell at market price.

**Mouse trading** – allows trading using mouse \(when the corresponding button is activated on the top of the panel\). Clicking on the Buy column allows placing Buy orders, on the Sell column – Sell orders.

Mouse trading rules:

* When sliding with cursor within any item in the Market depth section the certain cell in the column should be highlighted;
* If there is no order on the current price, it can be exposed by clicking on the empty cell of the column Buy or Sell;
* If there is an order on the current price, then you can open a new one by clicking on it;
* If an order is opened on the current price, then clicking on the cross in the right side of its area will lead to its cancellation;
* If several orders are opened on the current price \(summary volume is shown in the orders area\), then when canceling the order the first exposed order will be cancelled in the first place.

Clicking on the group of orders on one price allows showing the list of pending orders.

![](../../../.gitbook/assets/orders.png)

### **Matrix Preferences**

‘Matrix Preferences’ dialog box consists of 3 tabs: View, Columns, Colors. 

**View**

![](../../../.gitbook/assets/1%20%2826%29.png)

* Font – allows to choose the style of the font;
* Show position bar – allows showing position bar;
* Show toolbar – allows showing the toolbar;
* Antagonistic size bars – allows to determine the direction of volume histograms. If true, the histograms are built from the different boundaries of the column ‘Size’. If false, the histograms are built from the left boundary of the column ‘Size’. Default state: true;
* Full-size bars – allows extending the bars;
* Auto-centring – activates auto-centring function;
* Compress spread – allows skipping empty levels between the best Bid and the best Ask;
* Show day high/low – allows showing high/low levels for one day;
* Show last price indicator – allows showing last price indicator;
* Settlement price – allows displaying settlement price**;**
* Previous settlement price – allows displaying previous settlement price.

![](../../../.gitbook/assets/2%20%285%29.png)

Check/uncheck the needed hot buttons in order to display them in the built-in Order entry of the Matrix panel:

* Show close orders \(SL/TP\);
* Buy/Sell Market;
* Buy Ask/Sell Bid;
* Buy Bid/Sell Ask;
* Close;
* Reverse;
* Cancel buy;
* Cancel sell;
* Cancel all.

 **** **Columns**

![](../../../.gitbook/assets/3%20%2841%29.png)

‘Columns’ tab allows to select colors of the columns located in the panel: Buy, Price, Size, Sell.

**Colors**

![](../../../.gitbook/assets/4%20%2835%29.png)

_Table colors:_

Table – color of the table background.

Grid – color of the grid in the Market depth section;

_Level1 colors:_

Coloring settings for Best Ask/Best Bid rows and Last trade indicator.

_Day high/low:_

Coloring setting for Day high and Day low price cells.

_Mouse trading:_ 

Hover – color and style of the line for sliding the cursor through each price level.

![](../../../.gitbook/assets/5%20%2829%29.png)

_Position bar:_

Long/Short/Multiple position – coloring settings for the corresponding positions;

Profit/Loss coloring settings – colors in the Position bar \(Price and QTY\), when P/L is positive/negative.

_Size bars colors:_

Size coloring scheme – allows selecting the coloring scheme of volume indicators. The following options are available: Relative to size, Step to max size.

Max size, lots – allows choosing the maximal size in lots. The field is active when ‘Size coloring scheme’ is ‘Relative to max size’.

Asks/Bids size bars – coloring settings for filling the volumes by Ask and Bid.

