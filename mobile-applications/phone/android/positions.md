# Positions

The Positions screen displays all opened positions. Every new opened position appears in this screen immediately.

![](<../../../.gitbook/assets/1 (99).png>)

The Positions screen displays a list of opened positions with short information about a symbol on which every position was opened: quantity and open price. Quantity of long positions is blue, quantity of short positions – red.

When viewing a position, the user can quickly switch to the chart to assess its current state and return back to the selected position. In order to do this swipe left the card of the selected position and the following buttons will become available:

![](<../../../.gitbook/assets/screenshot\_2 (5).jpg>)

To quickly go to the chart, just tap the corresponding icon. To return back to the order, tap the ‘Back’ button depicted as an arrow![](https://lh5.googleusercontent.com/FeoB164MubEhRzjZI288O316A51qKXagx2sSMaReRPOJ5NDeC1l862wWctT_U2Wkbuni-qTC-7pAzYNKFJxG5Z_SP7h57i4K3CKTGGyWTnOqE0msvOjWah_NT\_36eIuww74QtXeI)in the upper left part of the chart. The same actions can be performed with superpositions as well.

In order to get full information about a symbol, tap a symbol's name.

![](<../../../.gitbook/assets/2 (86).png>)

* Fee – shows the total commission amount taken for a position;
* Date/time – shows date and time when a position was opened;
* Current price – market price obtainable from a broker;
* Stop loss – Stop loss price set for a position;
* Take profit – Take profit price set for a position;
* Position ID – unique number that the trading system assigns to each position;
* Open price – price at which the position was opened;
* Account – login name of an account that opened a position;
*   Exercise – sends an exercise request for the Option position. Available for single positions opened for Options with Exercise style=American, inactive for multiple selected positions. 

    After clicking this menu item, the Position exercise request confirmation dialog box is displayed. Clicking the "Exercise" button in the confirmation box, creates a request for the Option exercise, which switches the position to Pending exercise status and prevents performing the following operations for the position:** Modify position, Close position, Close all.**

    The mentioned actions are reenabled for the position after the "Cancel exercise" action is performed.
*   Cancel exercise – cancels an exercise request for the selected Option position with Pending exercise status. Available for single positions opened for Options with Exercise style=American, inactive for multiple selected positions.

    After clicking this menu item, a confirmation dialog box is displayed, which requires a confirmation of canceling an Option exercise request. After the exercise Option request is canceled, the **Modify position, Close position, Close all **operations become allowed for the position.   

In order to modify a position, tap the 'Modify' button and the following screen will be opened:

![](<../../../.gitbook/assets/3 (74).png>)

Here you can modify stop loss, take profit or trailing stop.

In order to close a position, tap the button 'Close', and the following intuitive screen allowing a partial position closing will be opened:   

                                              ![](<../../../.gitbook/assets/4 (40).png>) 

The field 'Qty. to close' allows to indicate some quantity of lots to close. This option is active, when it is allowed on the server-side with broker's settings. Also, the 'Position closing' confirmation must be activated in the ‘Settings’ menu.
