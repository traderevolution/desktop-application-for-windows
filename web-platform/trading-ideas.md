# Trading ideas

A Trading idea or simply an Idea is an investment recommendation based on the market analysis. It includes predefined parameters for order placement as well as text description and chart snapshot.

The panel allows to send Ideas and subscribe to them, depending on the user’s role – user-analyst or user-subscriber.

### **User-analyst**

User-analyst is a user who can create, delete and send Ideas to user-subscribers but is not allowed to trade by himself. For the user-analysts the Ideas analyst panel is available in the terminal from the ‘Tools’ list in the Top menu. Ideas analyst panel contains 2 tabs:

**New** – ​tab that allows setting all parameters for sending a new Idea:

![](../.gitbook/assets/sending-with-product-type.png)

In order to send an Idea, a user-analyst has to specify mandatory order parameters:

* Symbol – allows selecting the instrument that will be used in the Idea;
* Side – allows selecting Idea operation side: buy or sell;
* TIF – dropdown list for selecting the order TIF type \(Day, GTC, IOC, FOK, GTD\);
* Product type – dropdown list for selecting the type of the product for the Idea. This parameter becomes available, when the product type for the symbol used differs from the General. Available options: Intraday, Delivery.

With that, if the product type available to the User subscriber differs from the one specified in the Idea by the User analyst, the User subscriber can switch from "_Delivery"_ to "_Intraday"_ product type:

![](../.gitbook/assets/selection.png)

If there is only one product type available to the User subscriber and it differs from the one specified in the Idea by the User analyst, in the Idea view for the subscriber, only the available product type is displayed with no option to change it by the User subscriber;

* Limit price – field for entering the limit price for the order;
* SL price – Stop Loss price of the order;
* SL offset – field that shows the SL offset value;
* TP price – Take Profit price of the order;
* TP offset – field that shows the TP offset value;
* Current price – field that shows the current symbol price \(if available\);
* Lifetime – allows specifying the period of the idea lifetime, during which a user-subscriber can accept the idea. Format: “hh:mm” \(hours:minutes\). \(min = 00 hours : 01 minutes; max = 24 hours : 00 minutes\);
* Title – allows entering a title of the Idea. The title cannot contain more than 50 symbols.

The following options are not mandatory:

* Description – allows entering a description of the Idea; 
* Add chart screen – allows attaching a Chart snapshot to the Idea. Clicking on the button ‘Add chart screen’ opens the detached Chart by the chosen instrument. Then just press the button ‘Take snapshot’ and click on a tick. After taking a snapshot, the button ‘Add chart screen’ will change to ‘Remove’, click on it in order to delete the Chart screen. The![](../.gitbook/assets/7%20%288%29.png)

After specifying all the parameters of the Idea, the user-analyst needs to click on the ‘Send’ button to send the idea. In case of a successful Idea sending, the user gets a notification:

![](../.gitbook/assets/sent-successfully-new.png)



![](../.gitbook/assets/trading-idea2.png)





After expiration of the Idea, it will be removed from the panel. In order to delete the Idea, click on the 'Delete' button located next to its lifetime.

![](../.gitbook/assets/screenshot_2%20%2812%29.png)

### **User-subscriber** 

User-subscriber is a user who is subscribed to user-analyst’s Ideas. For the user-subscribers, only the subscriber panel is available in the terminal and they can only see and accept Ideas. Click the![](../.gitbook/assets/1%20%2883%29.png)

To receive an Idea and place the order based on this idea, the instrument used in the idea must be available to the user-subscriber. After receiving a new Idea, the notification with the number of received Ideas will appear in the main upper panel of the terminal near the Alerts icon:

![](../.gitbook/assets/idea-notification.png)



![](../.gitbook/assets/trading-idea1.png)

In the panel, the user-subscriber can see the text description of the idea, remaining lifetime, Take profit, Limit price and Stop loss values of the Idea, can view the Chart snapshot \(if added\) and place the order based on the idea. User-subscriber can also select or enter the quantity for the Idea order to place by using the drop-down Quantity list. After clicking on the ‘Place sell/buy order’ button in the open Idea, an order placement confirmation dialog box is displayed:

![](../.gitbook/assets/6%20%2836%29.png)

Click on the ‘Yes’ button to place an order based on the Idea. After the order is placed, the User can manage it together with the existing orders.
