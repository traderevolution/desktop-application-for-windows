# Assets

Assets panel contains information about all assets by the chosen account\(-s\). If there is the same asset on different accounts, then it is displayed for each account in the corresponding table rows.

![](../../.gitbook/assets/assets2.png)

### **Columns**

A user can choose the columns, which have to be displayed by right-click on one of the column names.

There are the following columns in the table:

* Asset name – name of the asset, which is set on a server.
* Default symbol – allows showing the instrument name from the setting ‘Pricing instrument’.
* Exchange – allows showing the exchange which is set on a server for the Default symbol.
* Account – name of the account, which contains the asset.
* Start day qty – asset quantity at the user’s account at the beginning of a day. While logging in it is sent from a server.
* Today traded qty – the quantity of the asset which was traded by all instruments for which this asset was pre-selected, but only for Product type=Delivery. The quantity of all Buy trades is counted with ‘+’, the quantity of all Sell trades is counted with ‘-‘.
* Current qty – current quantity of the asset on the account.
* Current price – current Last price on the instrument Default symbol.
* Current value – current asset value available for selling.

Current value = Current qty. \* Current price \* CrossPrice.

The same context menu allows to filter data in a table, reset the panel's view to factory defaults and to open the 'Assets Preferences' window.

### **Context menu**

Right-click on the Assets panel evokes the context menu which includes the following options:

* Search – allows to show/hide a Search lookup in the panel;
* Show totals – allows to show/hide the row showing the total values for columns;
* Duplicate panel – allows to make a copy of a current panel;
* Preferences – opens the 'Assets Preferences' menu.



