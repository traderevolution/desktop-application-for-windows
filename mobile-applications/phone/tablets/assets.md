# Assets

Assets screen contains information about all assets by the chosen account\(-s\). If different accounts have the same asset, then it is displayed in different rows in the table.

Assets screen can be accessed from Positions screen by moving the slider button to Assets.

![](https://lh6.googleusercontent.com/YJ2YWBtUYMKzHehfWuZjF639QlqsCjRBpq6JqMK3SGQm7D3ahrmGg3L-dMRtz2shZ6RRObsYeAKK3bvt87aevNMRvYcXhIcEwllZdniKtvVbaNMG-o-iT_TyqAGgqJDY5x-yKglq)

For each asset the following information is available:

* Default symbol – allows showing the instrument name from the setting ‘Pricing instrument’.
* Start day qty. \(SOD qty\)  – asset quantity at the user’s account at the beginning of a day. While logging in it is sent from a server.
* Current value for sell – allows showing the price of the asset, which is available for the sell by Current price.

Current value for sell = Available for sell \*Current price \* CrossPrice  


To open additional data by the chosen asset, tap on it and the table with data will be displayed.

The following information is available in the table:

* Asset name – name of the asset, which is set on a server.
* Exchange – allows showing the exchange which is set on a server for the Default symbol.
* Account – name of the account, which contains the asset.
* Start day Qty. for Margin available – while logging in, the user gets information from the correspondent field on a server.
* Liquidity rate% – the price of each asset at the user's account can be used for the opening of a position by other instruments. This price should be counted in Margin available in that interest proportion which is defined in this setting. Default value is 0. Maximal value is 100.
* Intraday qty. – the quantity of the asset which was traded by all instruments for which this asset was pre-selected, but only for Product type=Delivery. The quantity of all Buy trades is counted with ‘+’, the quantity of all Sell trades is counted with ‘-‘.
* Available qty. – quantity of the asset, which is available for sell.

If Today traded qty.&gt;=0, then Available for sell = Start day qty.

Otherwise, Available for sell = Start day qty. - \|Today traded qty.\|

* Current price – current Last price on the instrument Default symbol.
* Sell exchange – allows showing a list of all exchanges where the asset is traded. 

![](https://lh4.googleusercontent.com/Gpfgzt1Zo4-IHEBRXwQl03IMkRZH6-xXitdBbZ2vJCjKZEqT9yUeHJ22TpRayci-OEsKKu1OnGzv6fAc2Q3MvfVk3hLNAN7StZRXyMqDxYhfyqBMlqvXL4EihEiDz-BftO0A3PBO)

‘Sell asset’ button allows to launch Order entry in order to sell asset.

![](https://lh6.googleusercontent.com/k7-smnNTq9YbiRFhgSq5whWz4Jkdmb0uo6OjetzRsS8ueoOUGF2o_FXQ66XfYFOTlta8Nb0VZ4_0lM0qP0NUmSMUfgPeXxSKCoEFOiBFFu8HR7rewF1Vcc9hCNi2NbHwA7jhMQpg)

