# Backtesting Types/Setup

### **Backtesting Types**

There are two types of backtesting available in EvoCode:

* Quick backtesting
* Visualize backtesting

 Select Backtesting mode on the top menu of EvoCode window by clicking on the![](../../.gitbook/assets/3%20%2841%29.png) button.

The Quick backtesting allows users rapidly testing strategies on historical data without the chart visualization during backtesting. In this mode, the chart with all details about opened and closed positions will only appear after the backtesting is finished.

The Visualize backtesting option allows users to see what is happening on the chart while the backtest is taking place.

### **Backtesting Setup** 

Before start of backtesting user can setup all required properties. Click on the![](../../.gitbook/assets/1%20%2815%29.png)button to evoke the Backtesting Setup window.

![](../../.gitbook/assets/2%20%2841%29.png)

* Main symbol – evokes the lookup for selection of the main symbol for backtesting.
* Additional symbols – evokes the lookup for selection of additional symbols for backtesting.
* Aggregation – allows to select the type of aggregation \(time\) of historical data.
* Range – allows selecting time interval during which the module backtesting will be conducted. It is also available to select custom range by selecting ‘Custom’ option in the drop-down menu.
* Modeling scheme – the following schemes are available:

         -  1m - Close – one minute bars close price are used for generation.

         -  1m - Open – one minute bars open price are used for generation.

         -  1m - OHLC – one minute bars: Open, High, Low, Close, prices are used for generation.

         -  1 D - Close – one day bars close price are used for generation.

         -  1 D - Open – one day bars open price are used for generation.

         -  1 D - OHLC – one day bars: Open, High, Low, Close, prices are used for generation.

* Balance – initial deposit amount.
* Latency – time latency during backtesting process which emulates the slippage that occurs during a real trade.
* Execution by – allows to select which type of historical data will be played for backtesting. Cancel Day Orders Time – allows to select time when all user’s daily orders will be closed.

