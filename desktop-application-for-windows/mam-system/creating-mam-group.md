# Creating MAM group

The MAM panel can be found by navigating to Tools -&gt; MAM. This panel gives indicative information on both groups and linked accounts. The panel also features a built-in Order entry panel for quick trading. The MAM panel can be linked to other panels. The MAM panel can be closed after use without saving - all changes are saved automatically.

### **Creating a MAM group**

To create a MAM group, open the MAM panel and click Create group.

![](../../.gitbook/assets/6%20%2814%29.png)

Now, enter a group name and choose an Allocation type. Click on the button in column "Remove" to delete the group from the list.

![](../../.gitbook/assets/7%20%2810%29.png)

The following columns are available in the Groups section:

* Group name – the name of your MAM group.
* Balance – shows current realized balance of MAM group, i.e. total balance of all accounts included in MAM group.
* Projected balance – future balance of MAM group which includes all accrued and not accrued profit/loss.
* Margin available – available margin for trading with MAM group.
* Allocation type – allows choosing the type of allocation for sub accounts included in MAM group. Four types are available here:

1. Lot multiplier – this method is used to allocate quantity of the master trade to the sub accounts included to the MAM group according to the coefficient set for each of these sub accounts which will be multiplied on master trade quantity.
2. Lot allocation – this method is used to divide quantity of the master trade to the sub accounts included to the MAM group according to the set Lot coefficient of the sub accounts. The allocation to the sub accounts will be proportional to the set lot sizes provided for each of them.
3. Proportional by balance – this method is to calculate the proportion of the master trade quantity \(which is set in OE section by MAM manager\) according to the balances of the sub accounts included to the MAM group. The fraction of the master trade quantity is calculated automatically and doesn’t require additional settings.
4. Proportional by projected balance – this method is to calculate the proportion of the master trade quantity \(which is set in OE section by MAM manager\) according to the projected balances of the sub accounts included to the MAM group. The fraction of the master trade quantity is calculated automatically and doesn’t require additional settings.

* Remove – the button which is used to delete selected MAM group.

The group is now created and accounts can be added to it. To add an account, click Add account. To delete an account, click on the button in "Remove" column.

![](../../.gitbook/assets/8%20%283%29.png)

Clicking Add accounts will open an Accounts lookup panel, which can be used to select prelinked accounts. The money manager will only see accounts which are linked to his User ID. Select the desired accounts and click OK.

The following columns are available in the Accounts section:

* Active – the account state, if this option is unchecked, account will not take part in the trading with MAM group.
* Remove – the button which is used to delete selected account from MAM group.
* Account – the account's unique identifier.
* User login – the account's corresponding login ID.
* Quantity – shows quantity which will be allocated to the corresponding account.
* Coefficient – allows indicating special coefficient which is used for allocation types: Lot multiplier and Lot allocation.
* Percent, % – shows the percent of quantity which will be allocated to the sub accounts depending on selected allocation type.
* Balance – shows current realized balance of the corresponding account. If there is trading with pending valuation, balance won’t change before clearing.
* Projected balance – future balance of the corresponding account which includes all accrued and not accrued profit/loss.
* Available funds – amount of funds for placing new orders.
* Margin available – the available margin for trading.
* Initial margin – minimum account balance required to open the position.
* Maintenance margin – minimum account balance required to keep this position open.
* Risk level – shows current level of risks. Risk level = \(Maintenance margin/Balance + All risks\)\*100%
* Impact on portfolio – shows how many initial margin will the order require considering all other positions/orders.
* After trade funds – shows how many available funds remain after placing the order.

After trade funds = Available funds – Impact on portfolio - Fee

* Performance fee – shows the percent from profit which the corresponding account will pay to MAM manager.
* Fee type – shows the type of management fee which will be charged from the corresponding account. Available fee types are:

1. Percent of net liquidation value – this fee type is taken daily at the end of each trading day \(is set in %\).
2. Flat fee – this fee is taken daily at the end of each trading day.
3. Percent of annual P/L – this commission is taken one-time at the end of the year \(is set in %\).
4. Percent of Market-to Market P/L – this fee is taken by the same logic as a previous one, only as a base of calculation is taken not an annual, but quarterly profit. And fee is taken in the end of each quarter respectively.

* Management fee – shows value of the corresponding fee type set for accounts added to the MAM group.

Now the accounts have been successfully added to the MAM group and the money manager can select accounts to trade with. There are several options available when accounts are added. Now the money manager can perform trades.

![](../../.gitbook/assets/5%20%2814%29.png)



