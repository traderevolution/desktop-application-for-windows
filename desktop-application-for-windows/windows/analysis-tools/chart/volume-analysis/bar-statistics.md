# Bar statistics

This functionality allows aggregating information about volumes by each bar in the form of the table. Bar statistics can be opened from the Analysis tools menu by clicking on the button![](../../../../../.gitbook/assets/68.png) or through the Context menu -&gt; Analysis tools -&gt; Bar statistics.

![](../../../../../.gitbook/assets/2%20%2840%29.png)

**Note: to work correctly with the tools of analysis, except Volume bars, it is obligatory to have trade and tick history.**

By default bar statistics contains four rows \(Trades, Total volume, Average size and Delta\), but it can be extended with additional parameters.

The following parameters are available in the Bar statistics section:

![](../../../../../.gitbook/assets/3%20%2828%29.png)

* Visible – controls visibility of the bar statistics on the chart;
* Custom total/buy/sell amount – allows to set up amount that is necessary for calculation of the Custom total/buy/sell volume parameters \(described above\);
* Font color \(+ header font color\), Grid \(+ header grid\) – allows to set up style of the labels and grid displaying;
* Colors – allows color selection for different data types displaying \(specified below\).

Right clicking on the bar statistics header evokes its context menu, where you can enable/disable the visibility of some rows with parameters:

![](../../../../../.gitbook/assets/4%20%2827%29.png)

* Trades – the number of trades by each bar for a specified period of time;
* Volume – total volume by each bar for a specified period of time;
* Buy volume – total buy volume by each bar for a specified period of time;
* Sell volume – total sell volume by each bar for a specified period of time;
* Delta – shows difference between buy volume and sell volume by each bar for a specified period of time. Delta = Buy volume – Sell volume;
* Buy volume, % – total buy volume for a specified period of time expressed as a percentage;
* Sell volume, % – total sell volume for a specified period of time expressed as a percentage;
* Delta, % – Delta index expressed as a percentage. Delta, % = Buy volume, % – Sell volume, %;
* Average size – shows average volume of trades by each bar. Average size = Volume/Trades;
* Average buy size – shows average volume of one buy trade

Average buy size = Total buy volume/ Buy Trades count, where Buy trades count – total number of buy trades for a selected period of time;

* Average sell size – shows average volume of one sell trade

Average sell size = Total sell volume/ Sell Trades count, where Sell trades count – total number of sell trades for a selected period of time;

* Custom volume – this mode summarizes all trades which traded with volume greater than Amount \(set in settings\) and shows percentage of such trades in the total volume

Custom volume, % = Count \(Total volume &gt; Amount\)/ Total trades \* 100%

Amount = Custom total amount \(set in settings\);

* Custom buy volume – this mode summarizes all buy trades which traded with volume greater than Amount \(set in settings\) and shows percentage of such trades in the total buy volume

Custom buy volume, % = Count \(Buy volume &gt; Amount\)/ Buy trades \* 100%

Amount = Custom buy amount \(set in settings\);

* Custom sell volume – this mode summarizes all sell trades which traded with volume greater than Amount \(set in settings\) and shows percentage of such trades in the total sell volume.

Custom sell volume, % = Count \(Sell volume &gt; Amount\)/ Sell trades \* 100%

Amount = Custom sell amount \(set in settings\).

* Reset to defaults – allows to reset settings to defaults.



