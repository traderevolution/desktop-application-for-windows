# Alerts

To open the Alerts panel, click the ![](https://lh5.googleusercontent.com/n2puwM_iP0RhExOYxuStFTb0KAj3U9VyChXkuK5xqJyLinpJePyWaP7Z7VDDq0A5ny7Y-Ikdlv3sLjIJacCBsj5-V7nMej_DAT49oTHxY0mA14RTeCI3BtgCQUEo-xD2ZAjfdaN3) button which is located at the header of the TraderEvolution terminal to the left from the Account details widget. In order to create an alert, click the ![](https://lh4.googleusercontent.com/zS8b00jKEKBimYMVHx6ALm06Xa_Fj3_Dbny-wia9ksi4rHmhJGRcOv_hCIkB7bTLNjMm_UXHM7mKBfVOqfu7HM6q3eoE-T6Y515K9QndcjcoTEDAzK0AfXda7YtBUTEfF8NLLW7x) button at the bottom of the panel.

A user can find Bid, Ask, Last, Change%, and Volume data by the instrument selected in the symbol lookup of the panel.

![](../../../.gitbook/assets/new%20%281%29.jpg)

The following settings are available when creating an alert:

* Symbol – standard lookup for instrument selection;
* Action – allows to select the action that will take place when the alert is triggered, the available values are:
  * Place order + Notify – alert is performed according to notification type and order placing occurs;
  * Notify – user is notified without placing an order;
* Order parameters – appears only if Action is set to ‘Place order + Notify’. At this point, there is an ‘Order entry’ button by clicking on which a full form for placing an order will be opened;
* Notification type – combobox for selecting the type of notification, multiselect is available:
  * Email – an alert containing the text from the ‘Alert message’ field will be sent to the user by email;
  * Push notification – an alert containing the text from the ‘Alert message’ field will be sent to the user via push notification;
  * Pop-up – an alert containing the text from the ‘Alert message’ field will be sent to the user in pop-up message;
  * Sound – a musical alert will be played to the user in the client.
* Alert type – allows to set an alert type. Available options are: Ask, Bid, Last, Change%, Volume;
* Condition – allows to set an alert condition. Available values are: &gt;,&lt;,&gt;=,&lt;=;
* Value – allows to set a value of Alert type for reaching the condition;
* Importance – allows to define the alert importance. The following options are available: High, Medium, Low. After the alert execution, the user gets a notification with the corresponding color of the indicator which depends on importance of the alert:

![](../../../.gitbook/assets/new2.jpg)

* Expiration – date/time picker that allows specifying the period of the alert lifetime. The expiration date and time are set in the corresponding calendar control:

![](../../../.gitbook/assets/2a22cdd3-efeb-468a-acc6-ca8124d46599.jpg)

The default expiration value is today + 30 days. 

* After execute – allows to select alert behavior after execution. Available options are ‘Stop’ - alert is not active but stored in the list of alerts, and ‘Remove’ - alert is removed after execution;
* Alert message – input field for entering the alert message text. The text in the message box is generated automatically in accordance with the alert parameters, but the user can customize the notification text if needed;
* Create/Cancel buttons – pick the appropriate action after setting the alert parameters. The ‘Create’ button is colored in accordance with the alert importance.

### Alert management

The user can browse through created alerts and work with them in the Alerts tab – both with executed and not executed ones. The maximum number of alerts which can be added to the panel is 100. The Alerts tab looks as follows:

![](../../../.gitbook/assets/3%20%2811%29.jpg)

The tab itself contains the table with alerts which consists of the following columns:

* Symbol – name of the instrument for which the alert was created;
* Condition – displays the condition upon reaching which the alert must be executed;
* Controls – set of controls for each alert, namely:
  * Play – this button is visible for executed alerts only, clicking this button will restart the alert with existing settings;
  * Stop – this button is visible for non-executed alerts only, clicking this button will stop the alert;
  * Edit – allows to open the editing screen, this screen is similar to the Create alert;
  * Remove – this button allows to remove the existing alert.

### Alerts on chart

The chart displays all active alerts for the instrument selected in the symbol lookup. If the alert is executed, it will not be shown on the chart, but its presence in the panel is controlled by the ‘After execute’ parameter. The chart displays all alerts for an instrument, for Ask, Bid, Last types.

In order to create a new alert on the chart, click the![](https://lh6.googleusercontent.com/68Su5s9Y1fkJnc3hB9Gw7W1oFeW6RnEeq7N_AzV7Jn5gLL8kLgc9hfPuAV4JIkpfw2-32RTslBybkVMjLbOV2rUxcTx0AuD8cjx_mrw9D9-9WLGFljRrBJ9KlMYuWLmnk4V6ens3)button that appears next to the price scale when the user hovers over a certain price level:

![](../../../.gitbook/assets/image%20%2853%29.png)

All active alerts created for the same instrument are visible on the chart. After execution, the alert is removed from the chart. The buttons for editing ![](https://lh5.googleusercontent.com/_-_WvFGiyqCfE64TXDDysPn8Leub7wi8j42X2ubOEzmSofAf3BAkzekd9To4IHBZaXWjeJGjXKhS2T8YfczovuIam7OlkYPBT-nW9BQMF_H43LyjGPS_1Y5QaU3FE5kR24q3n5iT) and removing ![](https://lh6.googleusercontent.com/NMQO03k-O5rTZCOqnMjFvI6l-b5_jBTfATOeS5pmnexih2FCi9Ksys6NNrIb-qXdA4fx9omibVBM-swmrDHCfNHm-vRTIbvXHn6wOEM4eEpzz0GsG3-ouPHfLLP5R5VDw1Jt7JqO) an alert become visible when the user clicks the alert icon. The color of the alert icon depends on the importance of the alert.

Clicking the Edit control will open the Editing screen. Editing the alert from the chart is also possible using the Drag&Drop function. When using this function, the alert is modified without additional confirmation, just drag the alert to the required position.

