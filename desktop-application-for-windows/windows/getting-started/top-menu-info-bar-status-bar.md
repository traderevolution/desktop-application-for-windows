# Top menu, Info bar, Status bar

### **Top** **menu**

![](../../../.gitbook/assets/te.png)

* Terminal: access to various panels which allow to trade, analyze trading activity, and monitor market conditions.
* Tools: access to Strategy manager, MAM, Synthetic instruments, Aggressor Balance Beta, News, RSS, Economic calendar.
* More: access to TraderEvolution Global website, log file, private log file, data folder, About current version screen.
* Alerts: access to the Alerts panel;
* Ideas: access to the Trading Ideas panel;
* Balance & Projected balance: access to account information;
* Account: Account statistics, Withdrawal, Transfer, Reports, Change password, Change trading password.
* Help: access to TraderEvolution Guide.
* Settings: access to general settings of the terminal. Read more about this section here: [https://guide.traderevolution.com/project/desktop-application-for-windows/getting-started/general-settings](https://guide.traderevolution.com/project/desktop-application-for-windows/getting-started/general-settings)
* Log in: evokes login screen.
* Connection status: shows the status of connection to the server.
* Ping information: shows the response time of the server \(ms\) to which the client is connected.

### **Info bar**

Info bar can be enabled or hidden via the General tab in General settings.

It looks as the following:

![](../../../.gitbook/assets/screenshot_7%20%281%29.jpg)

You can customize it via its context menu. To open the Info bar's context menu, right-click anywhere on the 'Info bar':![](../../../.gitbook/assets/2%20%2831%29.png).

* Tape rolling – when checked, the 'Info bar' moves horizontally along the application's window width;
* Customize – opens the 'Customize info bar' menu:

![](../../../.gitbook/assets/info-bar.gif)

This menu allows to select a set of elements to be displayed in the 'Info bar'.

The checkbox 'Tape rolling' allows to enable/disable the Info bar's horizontal movement along the application's window width. 

The control![](../../../.gitbook/assets/4%20%2848%29.png)opens a list of elements' groups for particular elements selection. The groups 'Account details', 'Symbols' and 'Clocks' are available here:

* Account details – opens the 'Customize account details' menu:

![](../../../.gitbook/assets/5%20%287%29.png)

This menu contains an account lookup for users having more than one account.

The following sub-groups of elements displaying account details are available here: General, Margin, Account activity, Today results, Risk management, Info.

To select element\(s\) from the sub-group\(s\), check needed element\(s\) and press the button 'OK'. Press the button 'Close' to cancel the selection and to quit the 'Customize account details' menu.

* Symbols –   opens the Customize symbols window. The user can select symbol\(s\) to be displayed in the 'Info bar' here. ****After clicking the![](https://lh4.googleusercontent.com/eXennB7RAUSoZbuVQoiBMSonrhnlqHYeoylOjYu6H0NOfJC6p1I2xkAOb3tKagjWNG5b_J8M7zuYOV1q08-Z1iTW5ivCvrIw8nqoqJmV5c8v8_IK6iDLgCn-clCO6bMlVvZanTBs), the Symbol lookup window will be opened for adding the necessary instruments. 

{% hint style="warning" %}
Please note that the user can add several instruments or all at once, in which case the lookup value will display ‘All’. 
{% endhint %}

The user can also add the same instrument several times, for example, if the instrument is duplicated three times, the lookup value will look as follows: Instrument lookup = “3 Items”.

![](../../../.gitbook/assets/screenshot_1%20%285%29.jpg)

In the 'Info bar' near the selected symbol the user can find the Last price \(the last trade price\), Change \(absolute price deviation from a Previous close price\), and Change, % \(price deviation from a Previous close price as a percentage\) checkboxes. All three settings can be active at the same time, in which case the Last price will be displayed in white, the Change price will be displayed in green, and the Change price, % will also be displayed in green, but with a '%' symbol next to the value. 

*  Clocks – shows a list of time zones:

![](../../../.gitbook/assets/screenshot_3%20%286%29.jpg)

Check needed clock\(s\) to be displayed in the 'Info bar'. There is also the Customize item in the list of time zones. This item allows access to the full list of available time zones, in order to add the necessary ones to the Clocks list, just tick the necessary checkboxes in the ‘Use time zone’ column. At the bottom of this window there is a button that allows resetting the displayed time zones to default:

![](../../../.gitbook/assets/screenshot_4%20%281%29.jpg)

All selected elements via the 'Customize info bar' menu are displayed in the 'Info bar'. They are also arranged in this menu in the form of hierarchical tree. To remove an element from the 'Info bar', select it with highlighting in the 'Customize info bar' hierarchical tree, right-click it and select 'Delete' or click on the button![](../../../.gitbook/assets/7%20%287%29.png).

To remove more than one element, hold the key 'Ctrl', select as much elements as you need, right-click anywhere on the highlighted area and select 'Delete'.  
  
The following buttons allow to manage the 'Customize info bar' hierarchical tree's view:

* ![](../../../.gitbook/assets/8%20%2822%29.png)– click to collapse each tree's entity;
* ![](../../../.gitbook/assets/9%20%2813%29.png)– click to expand each tree's entity.

The button 'OK' allows to apply the 'Customize info bar' menu's arrangement to the 'Info bar'.

The button 'Cancel' allows to quit this menu without applying the arrangement to the 'Info bar'.

### **Status bar**

The Status bar, located at the bottom of the screen, makes it possible to "stream" information such as news and many others. The Status bar can be customized to show only information that user needs.

![](../../../.gitbook/assets/status-bar.png)

The Status bar displays \(from left to right\):

* Workspace\(s\) – shows a particular configuration of panels, toolbars, charts and/or table layouts that makes up trading environment.
* Trading notifications – notifications about changes in the terminal and server. A notification appears when a deal ticket comes, then it disappears.
* Event log – shows a log of all events that occurred during work sessions.
* Lock trading – disables making all trading operations. After pressing the button, the notification in the center of the screen and the warning signs appear and it shows that trading is locked.
* Date/Time – the current time or date; or both date and time.

Clicking the date and time section will open the window for selecting the Terminal time zone:

![](../../../.gitbook/assets/screenshot_1%20%288%29.jpg)

This window contains the time zones available for the user, the first in the list is the user's local time zone, the second is the time zone of the server. The last on the list is the ‘Customize’ item, to get to this point, scroll down the list of time zones. Select the ‘Customize’ item in order to open the ‘Select time zones’ window where the user can redefine the default list of time zones:

![](../../../.gitbook/assets/screenshot_2%20%286%29.jpg)

Check the required time zones in order to include them in the default list and click ‘OK’. It is also possible to return the list to its default state by clicking the ‘Reset to default’ button.

{% hint style="warning" %}
Please note that after changing the time zone, the time display will immediately change in the panels listed below.
{% endhint %}

* Event log – time in the ‘Date’ column for Daily and Range query;
* Symbol info – instrument trading session time;
* Watchlist/Market depth – time in the ‘Last date’ column;
* Chart – time displayed at the bottom of the chart, also, when the time zone is changed, the display of trades on the chart will be automatically redrawn in accordance with the selected time zone;
* Time & Sales – time in the ‘Time’ column;
* Position/Working orders – time in the ‘Date/Time’ column;
* Filled orders/Orders history – time in the ‘Date’ column for Daily and Range query;
* High/Low list – time in the ‘Time’ column.  

