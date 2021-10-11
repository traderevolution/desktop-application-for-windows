# Chart overview

The Chart panel allows to view quotes history and analyze market patterns.

To open the Chart panel, select 'Terminal -> Chart'.

![](<../../../../.gitbook/assets/test-chart (1).png>)

### Chart parameters

* Symbol lookup – a field for selection of a symbol to be displayed on the chart;
* Account lookup – a field for selection of an account for visual trading;
* Aggregation – a menu for selection of a desired aggregation type. The following aggregation types are available: Tick, Time, Renko;
*    Chart style – allows to select a style of symbol price movements. The following styles are available:

    * Line;
    * Bar;
    * Candle;
    * Dots;
    * Dotted line;
    * Histogram;
    * Area.


* Drawings – allow activating drawing toolbar on the chart;
* Indicators – allow to open Indicators lookup window;
* Mouse trading – allows to activate trading from the chart with a mouse;

Clicking on the 'Mouse trading' button turns it blue![](../../../../.gitbook/assets/mouse-small.png)and changes the cursor's view to the following:![](../../../../.gitbook/assets/mouse-trading-small.png). Pressing and holding the key 'Command' leads to the same result. 

When 'Mouse trading' is enabled, pressing the mouse's keys allows to place an appropriate order.

If the cursor is higher than the current price, you can send:

* Buy Stop order – left click of the mouse;
* Sell Limit order – right click of the mouse.

If the cursor is lower than a current price, you can send:

* Buy Limit order – left click of the mouse;
* Sell Stop order – right click of the mouse.

During the Mouse trading, order marker is visible on the chart. If order is buy, then order marker will be blue; and if order is sell, then order marker will be red.

To disable trading from the chart with a mouse, click on the 'Mouse trading' button again, or just stop holding the 'Command' key.

* Chart Order entry – opens built-in Order entry panel.

![](../../../../.gitbook/assets/oe-small.png)

* Scroll – a tool for chart history scrolling;
* Zoom control buttons – allow to zoom out (-) and zoom in (+) on the chart and to activate manual scaling of the chart by an allocated area.

#### &#xD;**Price scale zooming**

User can zoom in or out on the chart by price scale (vertically). Click on the price axis, drag it up and down to scale the price axis.

**Chart zooming**

The chart can be zoomed in using the "Shift + mouse wheel" hotkey combination. 

{% hint style="warning" %}
Please note that in this case, not the usual zooming combination with a "Ctrl" button is used, since this button is already used for visual trading.
{% endhint %}

When using this hotkey combination, zooming occurs to the mouse cursor point, that is, the chart remains centered. This feature works when the mouse cursor is over the chart.

#### **Scrolling the chart**

To scroll the chart horizontally, just drag the scroll in the Timeline section, or click inside the chart and drag it left or right.

Right-clicking on the Timeline evokes the additional option:

Show separators – this option displays the vertical lines on the chart to separate different days, weeks, months and years.

#### **Refreshing the chart**

Charts refresh automatically. If, however, a user needs to refresh the chart manually, right-click inside of the Chart and select ‘Refresh’. This action will reload the chart data and redraw the chart.

### &#xD;**Right information button**

Working with right mouse button, user can get the following information:

* Bars – the number of bars between two selected points.
* ∆Time – time past between two selected points.
* ∆Price – price difference between two selected points at each end of the line.
* Ticks – price difference shown in ticks between two selected points.
* Profit – shows how much a trader could earn if the price has gone up/down from point 1 to point 2. 

In order to get this information, right-click on the chart and hold the mouse key, then lead it across the screen to the needed point.

![](../../../../.gitbook/assets/right-button-small.png)

{% hint style="warning" %}
Note that the color of the text and background displayed in this info window can be changed via the corresponding color pickers in the chart preferences, 'Info window' section.
{% endhint %}

### Data source <a href="data-source" id="data-source"></a>

In the Chart panel a user can see the the extended information about the source of Last, Bid and Ask prices. In order to open the table with the detailed information, click on the![](<../../../../.gitbook/assets/image2-kopiya (1).png>)arrow and the widget will be shown:

![](<../../../../.gitbook/assets/image3 (1).png>)
