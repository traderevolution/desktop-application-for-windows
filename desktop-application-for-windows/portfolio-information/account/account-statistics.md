# Account statistics

Account statistics panel is a tool for traders that provides detailed information on the selected accounts. This panel contains a massive array of trading statistics, various P/L charts, data about trade population and drawdowns. Statistics can be shown for operations against various accounts and time periods from 1 day to years chosen in the top section of the panel. It is also possible to set a custom range for statistics displaying.

Account statistics panel offers the feature of exporting all statistics and charts to HTML format as a report. To take advantage of this option use the 'Export to HTML' button located on the top right corner of the panel. The report is generated for the selected accounts over the chosen period considering values displayed in the corresponding tabs.

![](../../../.gitbook/assets/1%20%287%29.png)

Account statistics panel consists of 2 tabs: ‘Performance Data’ and ‘Performance Charts’.

![](../../../.gitbook/assets/account-statistics.jpg)

At the top right corner of the panel, you can find ‘Account link’ button and ‘Menu’ button.

Select ‘Show toolbar’, to make Account lookup, Data filter and ‘Export’ button visible. In the Data filter, you can choose options ‘Daily’ or ‘Range’. 

### **Performance Data**

3 parameters:

* Start capital – shows balance value at the beginning of the selected period.
* Final capital – shows balance value at the end of the selected period.
* Net P/L – shows total Net P/L for the selected period.

All information in the ‘Performance Data’ tab is divided into three following sections:

1. Cumulative P/L
2. Trades population
3. Drawdowns

The table consists of 4 columns:

* Variables – in this column, user can find the names of the parameters.
* Total – in this column, user can find parameters for Short and Long trades.
*  Long – in this column, user can find parameters for Long trades.
* Short – in this column, user can find parameters for Short trades.

Let’s consider all the tabs in details.

The first section is **Cumulative P/L**. Here users can see all the information on their trading results and capital. In the ‘Total’ tab, the value of all settled and unsettled P/L account operations is displayed. Operation values can also be viewed separately divided by operation type \(‘Long’ and ‘Short’ tabs\).

Cumulative P\L :

*  Profit factor – indicator of profitability showing what average profit in relation to loss is. Calculated as:

Profit factor = \(avr\_TP \* %TP\)/\(avr\_SL \* %SL\), where:

avr\_TP – size of the average profitable trade \(in ccy\);

%TP – probability of the profitable trade receiving;

avr\_SL – size of the average losing trade \(in ccy\); avr\_SL is always taken modulo.

%SL – probability of the losing trade receiving.

* Fee = \(Fee/Start capital\)\*100%
*  Expected payoff – mathematical expectation of win. This parameter to be calculated statistically represents average profit/loss factor of one trade. Calculation formula:

Expected payoff = \(avr\_TP \* %TP\) – \(avr\_SL \* %SL\), where

avr\_TP – size of the average profitable trade \(in ccy\);

%TP – probability of the profitable trade receiving;

avr\_SL – size of the average losing trade \(in ccy\); avr\_SL is always taken modulo.

%SL – probability of the losing trade receiving.

* Recovery factor – is a ratio of the net profit to the maximum drawdown. Calculation formula:

Recovery factor = Net profit / Max DD, where

Max DD – module of the maximum drawdown \(in ccy\);

Net profit – trading result for the analyzed period.

* Sharpe Ratio – is a ratio of the expected payoff to the standard deviation. Calculation formula:

Sharpe Ratio = Expected payoff/STD, where

STD – standard deviation of the trading results;

STD = SQRT\(1/\(n-1\) \* SUM\(xi-avr\_x\)^2\)

* Win/Loss Ratio   – is a ratio of the probability of the profitable trade receiving to the probability of the losing trade receiving. Calculation formula: Win/Loss ratio =%TP/%SL
*  Equity linearity factor – shows the dispersion degree of the balance chart relative to its regression line. Calculation algorithm:

  1\) Calculate the linear regression on the cumulative array of points of the balance \(equity\).

  Ŷ = a + b\*x

![](../../../.gitbook/assets/3%20%288%29.png)

2\) Calculate the standard deviation \(SD\):

![](../../../.gitbook/assets/4%20%281%29.png)

3\) Plot +1SD and -1SD from obtained regression line.

       4\) Calculate the percentage of points that went beyond the boundaries of standard deviation:

 Equity linearity factor = \(Number of points that are below and above the SD lines/Total number  of points\) \* 100%

 The closer the factor to 100%, the more linear the balance chart.

Trades population:

* Trades Loss – shows total loss by all losing trades for period.
* Trades Win – shows total profit by all winning trades for period.
* Average Loss – displays the average P/L value for losing trades.
* Average Win – displays the average P/L value for winning trades.
* Max. consecutive Loss – shows the longest series of losses in a row among the total number of trades, and their value in the money.
* Max. consecutive Win – shows the longest series of wins in a row among the total number of trades, and their value in the money.
* Largest Loss – displays the largest profit loss of one trade for the selected period.
* Largest Win – displays the largest profit win of one trade for the selected period.

Drawdowns:

*  Maximal drawdown – is the highest difference between one of local upper extremums of the balance chart and the following lower extremums.

        Maximal drawdown, % = \(Maximal drawdown ÷ Peak Balance value\) \* 100%

*  Absolute drawdown – is the difference between the current capital and current local upper extremum.
* Average drawdown – is the arithmetic average of all drawdowns over a given time period.
* Average drawdown, % – is the ratio of the sum of the drawdowns expressed as a percentageto the total number of drawdowns.

       Average drawdown, % = Sum \(DD1,% +…+DDn,%\)/N

### **Performance Charts**

Performance Charts tab allows users to view changes of their balances and P/L graphically.

Chart selector allows to choose the type of data to be displayed.

* Cumulative P/L
* Aggregate P/L
* Trades Population
* Drawdowns

If you choose ‘Cumulative P/L’ or ‘Aggregate P/L’, you can select by what trades you want to see a chart:

* Total – allows building a chart by short and long trades.
* Long – allows building a chart by long trades.
* Short – allows building a chart by short trades.

### **Cumulative P/L chart**

Cumulative P/L chart allows users to view changes of their balances and P/L graphically. Cumulative P/L chart in the **Operations** mode displays how a user’s balance was changed depending on the trade operations performed within the selected period. Operations mode is opened by default, if a user changes mode, he can return to Operations mode by clicking on the button ![](../../../.gitbook/assets/5%20%284%29.png).

![](../../../.gitbook/assets/3%20%2816%29.png)

Horizontal scale allows plotting P/L chart by operations or by hours/days/months for chosen in the main panel window period of time. If section 'hours/days/months' is selected, then all operations are aggregated by hours/days/months. Click on the buttons![](../../../.gitbook/assets/7%20%2817%29.png)to select the corresponding modes.

Section 'Total' is selected and displayed by default in all the tabs. Volume bars are plotted on the chart regardless of selected horizontal scale type \(Operations, Hours, Days, etc.\). Volume is displayed in lots.

### **Aggregate P/L Chart**

![](../../../.gitbook/assets/4%20%2812%29.png)

**Aggregated P/L** charts display Gross and Net P/L for selected 'aggregation' interval.

Aggregation interval – allows aggregating P/L chart by the needed periods: by months, by days, by hours. Option 'Hours' \(i.e. By hour of the day\) is set by default. The charts can be also displayed by side of the trading, available side tabs are: Total, Buy, Sell.

### **Trades Population Chart**

![](../../../.gitbook/assets/5%20%2823%29.png)

**Trades population** consists of two charts:

* Pie chart, which illustrates the completed trades number for each individual symbol and shows their values in % from total trades number, and
* Profitable chart of the selected symbol from the pie chart.

When user clicks on the sector of a pie chart.

Profitable chart displays Cumulative P/L and volumes of trades made for the selected symbol within specified period.

### **Drawdowns Chart**

![](../../../.gitbook/assets/6%20%286%29.png)

Drawdowns chart shows the graphical distribution of drawdowns built trade by trade. Volumes of the trades are also displayed on the chart.

