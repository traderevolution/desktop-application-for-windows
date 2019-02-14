# Trading ideas

Trading idea is an investment recommendation based on the market analysis. It includes predefined parameters for order placement as well as text description and chart snapshot.

The panel allows to send Trading ideas and subscribe to them, depending on the user’s role – user-analyst or user-subscriber.

### **User-analyst**

User-analyst is a user who can create, delete and send Trading ideas to user-subscribers but is not allowed to trade by himself. For the user-analysts the Trading ideas analyst panel is available in the terminal from the ‘Tools’ list in the Top menu. Trading ideas analyst panel contains 2 tabs:

**New** – ​tab that allows setting all parameters for sending a new Trading idea:

![](../.gitbook/assets/2%20%2832%29.png)

In order to send a Trading idea, a user-analyst has to specify mandatory order parameters:

* Symbol – allows selecting the instrument that will be used in the Trading idea;
* Side – allows selecting Trading idea operation side: buy or sell;
* TIF – dropdown list for selecting the order TIF type \(Day, GTC, IOC, FOK, GTD\);
* Limit price – field for entering the limit price for the order;
* SL price – Stop Loss price of the order;
* SL offset – field that shows the SL offset value;
* TP price – Take Profit price of the order;
* TP offset – field that shows the TP offset value;
* Current price – field that shows the current symbol price \(if available\);
* Lifetime – allows specifying the period of the idea lifetime, during which a user-subscriber can accept the idea. Format: “hh:mm” \(hours:minutes\). \(min = 00 hours : 01 minutes; max = 24 hours : 00 minutes\);
* Title – allows entering a title of the Trading idea. The title cannot contain more than 50 symbols.

The following options are not mandatory:

* Description – allows entering a description of the Trading idea; 
* Add chart screen – allows attaching a Chart snapshot to the Trading idea. Clicking on the button ‘Add chart screen’ opens the detached Chart by the chosen instrument. Then just press the button ‘Take snapshot’ and click on a tick. After taking a snapshot, the button ‘Add chart screen’ will change to ‘Remove’, click on it in order to delete the Chart screen. The button![](../.gitbook/assets/7%20%285%29.png)  allows to open the full-size screenshot.

After specifying all the parameters of the Trading idea, the user-analyst needs to click on the ‘Send’ button to send the idea. In case of a successful Trading idea sending, the user gets a notification:

![](../.gitbook/assets/3%20%2841%29.png)

**Sent** –​ tab that contains the ideas sent by the user-analyst. In this tab, the user-analyst can see and delete Trading ideas, which lifetime is not expired:

![](../.gitbook/assets/4%20%287%29.png)

The sent Trading idea becomes visible for the user-analyst in the ‘Sent’ tab. In this tab, the user-analyst can view the idea parameters specified before sending.

Click on the certain Trading idea to open it. If a user attaches a chart screenshot, it will be displayed in the Trading idea. Press the screenshot to open it in the full-size mode. In the ‘Chart’ tab user can choose the desired timeframe.

After expiration of the Trading idea, it will be removed from the panel. In order to delete the Trading idea, click on the 'Delete' button located next to its lifetime.

![](../.gitbook/assets/screenshot_2%20%285%29.png)

### **User-subscriber** 

User-subscriber is a user who is subscribed to user-analyst’s Trading ideas. For the user-subscribers only the subscriber panel is available in the terminal and they can only see and accept Trading ideas. Click on the button![](../.gitbook/assets/1%20%2847%29.png)in the Status bar to open this panel. Clicking on this button for the first time evokes the window with Risk disclosure. Pressing the button ‘I agree’ allows to accept it.

To receive a Trading idea and place the order based on this idea, the instrument used in the idea must be available to the user-subscriber. After receiving a new Trading idea, the notification will appear in the Status bar of the terminal.

![](../.gitbook/assets/8%20%2812%29.png)

A user-subscriber can see the sent Trading idea in panel:

![](../.gitbook/assets/5%20%2820%29.png)

In the panel, the user-subscriber can see the text description of the idea, remaining lifetime, Take profit, Limit price and Stop loss values of the idea, can view the Chart snapshot \(if added\) and place the order based on the idea. User-subscriber can also select or enter the quantity of the idea orders to place by using the drop-down Quantity list. After clicking on the ‘Place sell/buy order’ button in the open Trading idea, an order placement confirmation dialog box is displayed:

![](../.gitbook/assets/6%20%2828%29.png)

Click on the ‘Yes’ button to place an order based on the Trading idea.

 

