# Positions

The Positions screen is accessible through the Main menu of the platform. It displays all opened positions. Every new opened position appears in this screen immediately.

![](<../../../.gitbook/assets/1 (123).png>)

The Positions screen displays a list of opened positions with short information about a symbol on which every position was opened: quantity and open price. Quantity of long positions is blue, quantity of short positions – red.

In order to get full information about a symbol, tap a symbol's name.

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

    The mentioned actions are reenabled for the position after the "Cancel exercise" action is performed;
*   Cancel exercise – cancels an exercise request for the selected Option position with Pending exercise status. Available for single positions opened for Options with Exercise style=American, inactive for multiple selected positions.

    After clicking this menu item, a confirmation dialog box is displayed, which requires a confirmation of canceling an Option exercise request. After the exercise Option request is canceled, the **Modify position, Close position, Close all **operations become allowed for the position.

In addition, you can close all positions by tapping the button ‘Close all’ located at the top right corner of the Positions list.

In order to modify a position, tap the 'Modify' button and the following screen will be opened:

![](<../../../.gitbook/assets/2 (109).png>)

Here you can modify Stop loss price, Take profit price or Trailing stop offset.

In order to close a position, tap the button 'Close'.
