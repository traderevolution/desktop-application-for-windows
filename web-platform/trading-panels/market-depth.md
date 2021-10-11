# Market depth

The Market depth panel allows traders to view and trade Level II quotes. To open a new Market depth panel, go to Terminal -> Market depth.

![](../../.gitbook/assets/md-w.png)

The Market depth panel consists of several sections:

* Level I - only Level I quotes;
* Position bar - short information about opened positions (quantity, average price, current profit and loss);
* Order entry is a compact bar similar to the Order entry panel. The quantity, type and Validity of an order, limit and stop price can all be adjusted here.
* Detailed quote section - this section includes the latest quotes data similar to Watchlist panel. But unlike Level I quotes, it shows the total volume at each price level. On the left side are Bid volumes, and on the right one – Ask volumes;

 The detailed quote section is the main part of the Market depth panel, and all other bars can be hidden. To select the way the panel looks, open context menu -> View:

![](<../../.gitbook/assets/2 (38).png>)

Mirror view - if checked, Ask section columns of Market depth panel will be displayed backwards.

In the detailed quote section, offers with equal prices are grouped by the same color. There are five available color groups. The quotes with best prices are placed on the top and regrouped each time a new quote comes.

The detailed quote section is displayed as a table with the following columns:

* MPID (market participant ID) – ECN or exchange, where the orders are set;
* Price – buy or sell price from the highest Bid and the lowest Ask to lower Bids and higher Asks;
* Size – the volume being offered to purchase at a specified Bid price or to Sell at a specified Ask price;
* Time – time of offer;
* Avg. price – the price with slippage that appears because of low liquidity;
* Total size – the aggregated traded volume;
* Order – order number of this current price;
* Contr CCY value – the value of Ask/Bid size recalculated in the quoting currency, Price \* Ask/Bid size;
* Contr CCY Total value – the value of total Ask/Bid size recalculated in the quoting currency, Price \* Total Ask/Bid size.

### **Active columns and substitution of parameters in OE**

* Size – when clicking on the Size column, the price and size values will be substituted in OE;
* Total size – when clicking on the Total size column, the price and total size values will be substituted in OE;
* Price – when clicking on the Price column, only the price value will be substituted in OE (for Limit order – limit price, for the Stop limit order, Stop order, Trailing stop – stop price).

### &#xD;**Coloring methods**

The Market depth panel offers 3 coloring methods for Level 2 quotes. To set up the coloring method, go to the Context menu - > Coloring method.

* By price level – coloring system by color levels depending on price;
* Relative to volume – Level 2 quotes are colored on the assumption that the max volume has the most saturated color; 
* Size histogram – histograms are built according to volumes.

### Data source

In the Market depth panel a user can see the the extended information about the source of Last, Bid and Ask prices. In order to open the table with the detailed information, click on the![](<../../.gitbook/assets/1 (161).png>)arrow and the widget will be shown:

![](<../../.gitbook/assets/screenshot\_2 (19).png>)

