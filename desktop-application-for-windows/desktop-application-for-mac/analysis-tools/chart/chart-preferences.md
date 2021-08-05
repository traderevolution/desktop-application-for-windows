# Chart Preferences

A user can open the ‘Chart Preferences’ window through the context menu of the Chart.

The ‘Chart Preferences’ window contains the following sections, stored into the tabs: 

### **Style**

![](../../../../.gitbook/assets/chart-preferences%20%281%29.png)

This section allows to adjust the following:

* Style – allows to select a style of symbol price movements. The following styles are available: Line, Bar, Candle, Dots, Dotted line, Histogram, Area;
* Data type – allows to select a data acceptance type. The following types are available: Default by symbol, Bid, Last, Ask. The 'Default by symbol' depends upon server preferences;
* Color schemes for all data types: Body, Border, Wick, Doji. 

### **View**

![](../../../../.gitbook/assets/mac-watermark.png)

The following adjustments are available here:

General:

* Background color – allows to select chart's background color;
* Display volume bars – allows to show volume bars on the chart;
* Show drawing toolbar – allows to activate drawing toolbar on the chart;
* Show toolbar – when checked, the chart's toolbar is active;

Watermark:

* Watermark mode – allows displaying the Symbol/Description watermark \(or both\) as well as hiding it.
* Watermark color – allows to select the watermark color or make it transparent in order to hide it;

Crosshair:

* Activate crosshair – if checked, the cursor lines are active on the chart;
* Crosshair style – allows to set up color, shape and thickness of the cursor lines.

Time to next bar:

* Display time to next bar – allows to show time to the next bar on the chart;
* Colors – allows to choose the font and background colors.

**Scale**

![](../../../../.gitbook/assets/screenshot_4%20%284%29.jpg)

This tab includes the sub-sections allowing particular adjustments of the chart:

Grid:

* Show grid – if checked, the chart's grid, helpful for viewing X and Y axes relation, is visible;
* Grid style – allows to select a grid's color, grid lines' shape and thickness;
* Colors – allows to set up the font's color.

Zoom:

* Scale – allows to choose the type of scaling: Auto or Manual;
* Fit orders/positions – if checked, all orders/positions will be fit into chart scaling;
* Fit settlement prices – if checked, the settlement prices will be fit into chart scaling;
* Fit day High/Low – if checked, the day High/Low prices will be fit into chart scaling, this option is enabled in case the ‘Auto scale’ type is selected and vice versa - disabled if the ‘Manual scale’ is selected;
* Fit alerts – if checked, then alerts will be fit into chart scaling.

Show:

* Show extended session – if checked, then all data received from the server will be displayed on the chart, if unchecked, then only data related to the Main session will be displayed;
* Highlight extended sessions – color picker for selecting the background color of the area, which falls within the extended session.

Highlighted prices:

* Show previous close – allows to show the previous close price on the chart;
* Previous close style – allows to select the style of the 'Previous close price' line, color, line type and line thickness are available for selection;
* Show day High/Low – allows to show the day High/Low prices on the chart;
* Day High/Low style – allows to select the style of the 'Day High/Low prices' lines, colors, line types and lines thickness are available for selection;
* Show settlement price – allows to show the current settlement price on the chart;
* Settlement price style – allows to choose the style of the 'Settlement price' line;
* Show previous settlement price – allows to show the previous day settlement price on the chart;
* Previous settlement price style – allows to choose the style of the 'Previous settlement price' line.

Time separators:

* Show day – if checked, the day-by-day separators are displayed on the chart;
* Day style – allows to adjust color, shape and thickness of the day-by-day separating lines;
* Show week – if checked, the week-by-week separators are displayed on the chart;
* Week style – allows to adjust color, shape and thickness of the week-by-week separating lines;
* Show month – if checked, the month-by-month separators are displayed on the chart;
* Month style – allows to adjust color, shape and thickness of the day-by-day separating lines;
* Show year – if checked, the year-by-year separators are displayed on the chart;
* Year style – allows to adjust color, shape and thickness of the year-by-year separating lines. 

### **Trading**

![](../../../../.gitbook/assets/4%20%286%29.png)

  
The following adjustments are available in this section:

* Opened positions – if checked, opened positions will be displayed on the chart;
* Long – allows to adjust the style of long positions on the chart;
* Short – allows to adjust the style of short positions on the chart;
* Working orders – if checked, working orders will be displayed on the chart;
* Buy – allows to adjust the style of working orders with 'Side=Buy' on the chart;
* Sell – allows to adjust the style of working orders with 'Side=Sell' on the chart;
* Bound positions/orders by left side – allows displaying active positions/orders on the left side of the Chart area. 

### **Order entry**

![](../../../../.gitbook/assets/5%20%2826%29.png)

This tab includes the sub-sections allowing particular adjustments of the chart's Order entry:

General:

Show chart order entry – if checked, the chart order entry will be displayed on the chart.

Quick trading – allows to hide/show the following chart order entry elements:

* Show close orders \(SL/TP\);
* Buy/Sell Market;
* Buy Ask/Sell Bid;
* Buy Bid/Sell Ask.

Hot buttons:

If checked, the following hot buttons will be shown in the built-in Order entry:

* Close;
* Reverse;
* Cancel buy;
* Cancel sell;
* Cancel all.

{% hint style="warning" %}
Using hot buttons doesn't evoke confirmation screens, even if confirmations are enabled in the 'Preferences' window.
{% endhint %}

### **Info window**

![](../../../../.gitbook/assets/mac1.jpg)

* Info window mode – allows to set up the style of displaying the Info window. You can select from the following Info window modes: Separate Window, Attached To Cursor, Hidden.
* Activate short mode – if checked, the Info window fields' names will be displayed in a short mode on the chart:

![](../../../../.gitbook/assets/new-info-window-short-mode%20%281%29.png)

* Colors – allows to select the Info window's font and background colors. 

{% hint style="warning" %}
Please note that this setting allows changing the background and text colors for various info windows, for example, those that are expanded when using the 'Right information button' on the chart.
{% endhint %}

Fields – this section allows to select fields for displaying information in the 'Info window'. The following fields are available, mark the needed ones as checked:

* \#Bar;
* Date;
* Time;
* Open;
* High;
* Low;
* Close;
* High - Low;
* Change, %;
* Ticks;
* Volume.

### **Managing adjustments**

The 'Chart Preferences' window contains the following buttons to manage adjustments:

* ![](../../../../.gitbook/assets/set-as-default%20%282%29.png)–   allows to set all current 'Chart Preferences' adjustments as default ones;
* ![](../../../../.gitbook/assets/reset%20%283%29.png)–   allows to reset all the 'Chart Preferences' adjustments to 'User Defaults' or to 'Factory Defaults'. 'User Defaults' are the last adjustments, which were stored into the system by clicking on the button 'Set As Default'.

### Alerts

![](../../../../.gitbook/assets/screenshot_3%20%2818%29.jpg)

The following settings are available when creating an alert:

* Notification type – combobox for selecting the type of notification, multiselect is available:
* * Email – an alert containing the text from the ‘Alert message’ field will be sent to the user by email;
  * Push notification – an alert containing the text from the ‘Alert message’ field will be sent to the user via push notification;
  * Pop-up – an alert containing the text from the ‘Alert message’ field will be sent to the user in pop-up message;
  * Sound – a musical alert will be played to the user in the client.
* Importance – allows to define the alert importance. The following options are available: High, Medium, Low. After the alert execution, the user gets a notification with the corresponding color of the indicator which depends on importance of the alert:
* After execute – allows to select alert behavior after execution. Available options are ‘Stop’ - alert is not active but stored in the list of alerts, and ‘Remove’ - alert is removed after execution;
* Show alerts – allows to show/hide alerts on the chart, checked by default.



