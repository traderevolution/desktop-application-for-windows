# Account performance

Account performance panel is a tool for traders that provides detailed information on the selected accounts. This panel contains a massive array of trading statistics, various P/L charts, data about trade population and drawdowns. Statistics can be shown for operations against various accounts and time periods from 1 day to years chosen in the top section of the Performance panel. It is also possible to set a custom range for statistics displaying.

Account performance panel offers the feature of exporting all statistics and charts to HTML format as a report. To take advantage of this option use the 'Export to HTML' button located on the top right corner of the panel. The report is generated for the selected accounts over the chosen period considering values displayed in the corresponding tabs.

![](../../../.gitbook/assets/1%20%287%29.png)

Account performance panel consists of 2 tabs: ‘Performance Data’ and ‘Performance Charts’.

![](../../../.gitbook/assets/2%20%289%29.png)

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

