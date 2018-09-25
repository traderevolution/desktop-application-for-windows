# Super DOM

The Super DOM panel's active field looks fairly similar to the Market depth ladder, but orders can be placed simply by clicking on the cells in Buy/Sell columns.

To open the Super DOM panel, go to Terminal -&gt; Super DOM:

![](../../.gitbook/assets/31.png)

The Symbol lookup is at the top of the Super DOM panel.

![](../../.gitbook/assets/32.png)

* Compress spread – allows skipping empty levels between the best bid and best ask;
* Autocenter button – allows auto centering the panel relatively to spread;
* Mouse trading button – allows one-click trading with the help of the mouse.

Day high/low – allows showing current high/low levels.

![](../../.gitbook/assets/33.png)

Right click tapping within the Market depth section, evokes the Context menu of the panel.

![](../../.gitbook/assets/34%20%281%29.png)

* Compress spread – allows skipping empty levels between the best Bid and best Ask;
* Autocenter – allows auto centering the panel relatively to spread;
* Day high/low – allows showing current high/low levels;
* Settlement price – allows displaying settlement price on the chart.
* Previous settlement price – allows displaying previous settlement price on the chart.
* Antagonistic size bars – allows to determine the direction of volume histograms. If true, the histograms appear from the different boundaries of the column ‘Size’. If false, the histograms appear from the left boundary of the column ‘Size’. Default state: true;
* Full-size cells – allows extending the bars;

![](../../.gitbook/assets/35%20%281%29.png)

![](../../.gitbook/assets/36%20%281%29.png)

* Settings – allows opening a settings tab.

The bottom position bar shows the current state of the position: open price, opened position quantity, current profit and loss.

![](../../.gitbook/assets/p-bar.png)

When clicking on the P/L value, the following options can be selected: Ticks/Fractional ticks for Forex/Points.

Furthermore, Ticks/Fractional ticks for Forex/Points can be selected in 'Show offset in' in the section 'Trading defaults' of the 'General settings'.

Position bar has extended functionality for Multiple position mode:

When clicking the Price value, one of two options can be selected: Average open price or Break-even.

Break-even = \(Long qty.\*Average long – Short qty.\*Average short\)/\(Long qty. – Short qty.\)

When clicking on QTY value, one of two options can be selected: Net QTY or Gross QTY.

1. Net QTY = Qty1 + Qty2 + Qty3
2. Gross QTY = \|Qty1\| + \|Qty2\| + \|Qty3\|

The color of QTY cell depends on the side of the position:

1. If all positions have Side = Long, qty. cell will be colored in blue;
2. If all positions have Side = Short, qty. cell will be colored in red;
3. If positions are multidirectional, then qty. cell is not colored;
4. If there are no positions, qty. cell will not be colored and qty. value = N/A.

* When trading multi-position symbols, open price of all the positions is calculated as weighted average value;
* The Orders column shows all pending orders and allows their modification. Limit orders are displayed as numbers, and Stop orders - as underlined numbers. Group of orders is displayed with two vertical lines of the pending order left side;
* The Size column shows how many trade operations with Ask/Bid are available at a specific price;
* Clicking on Cancel buy, Cancel sell, or Cancel all will close all buy, sell, or total orders respectively for the currently displayed symbol and account;
* Close position button allows closing the current position by selected symbol and account.

On the right side of the Matrix panel there is a built-in Order entry panel. The order amount can be specified on the top of panel. Also the TIF of the order, SL/TP offset and Trailing stop.

Click on Buy Market or Sell Market to Buy/Sell at market price.

**Mouse trading** – allows trading using mouse \(when the corresponding button is activated on the top of the panel\). Clicking on the Buy column allows placing Buy orders, on the Sell column – Sell orders. You can switch the order type from Limit to Stop using the hotkey "Shift" \(can be changed in General settings - &gt; Hotkeys - &gt; Matrix\).

Mouse trading rules:

* When sliding with cursor within any item in the Market depth section the certain cell in the column should be highlighted;
* If there is no order on the current price, it can be exposed by clicking on the empty cell of the column Buy or Sell;
* If there is an order on the current price, then you can open a new one by clicking on it;
* If an order is opened on the current price, then clicking on the cross in the right side of its area will lead to its cancellation;
* If several orders are opened on the current price \(summary volume is shown in the orders area\), then when canceling the order the first exposed order will be cancelled in the first place.

Clicking on the group of orders on one price allows showing the list of pending orders.

![](../../.gitbook/assets/sup.png)

