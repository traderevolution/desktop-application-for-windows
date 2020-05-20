# Assets

Assets screen contains information about all assets by the chosen account\(-s\). If different accounts have the same asset, then it is displayed in different rows in the table.

Assets screen can be accessed from Positions screen by moving the slider button to Assets.

![](https://lh5.googleusercontent.com/jBXUvWCt9K122SyDExAr_J5DCqDSvTtBMZovu1otMCuKAyDUp-lFJw1Ga1yPVFIcZWsd5YxgyiIs460jYfcOHgf0IQXEFD7wVkLGOmNORG_hBb3ldYowECkiK__K49-E997Q8ktB)

For each asset the following information is available:

* Default symbol – allows showing the instrument name from the setting ‘Pricing instrument’.
* Start day qty. \(SOD qty\)  – asset quantity at the user’s account at the beginning of a day. While logging in it is sent from a server.
* Current value for sell – allows showing the price of the asset, which is available for the sell by Current price.

Current value for sell = Available for sell \*Current price \* CrossPrice  


Swipe left a chosen asset and tap ‘Sell Asset’ button to make a corresponding action.

![](https://lh4.googleusercontent.com/6JWM_BWnyHfL4ulwt1lf043CohV8VlObKIDmivgbPZAeNY1r3qSbOfwC4kEcZRhsn-2IqyQVbp_GdWAqZ42q1LCf5hxvpLKx-0Hp4Aeu1cCiV3SNIwTxWCn2IBOusZBo0eeRFMI2)

To open additional data by the chosen asset, tap on it and the table with data will be displayed.

![](https://lh6.googleusercontent.com/wf2ymmEtIE8IDD_jKSGZnLdvvXCGiS8gMU9W-pzCZ7MhJMUGjxukW3FG5AeAIql2RKJ8Kgsxp-D2f9rh8ufgYpmn1SXrMmepnANE_Yn8wjiAF60hQyNfgvkcC0FFVwedpzXM_cc7)

There are the following information is available in the table:

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

![](https://lh5.googleusercontent.com/vuSTDjqSX_rvOwFNcYL6e4MC4nEXnXwK0LEQC2YBdqI9URXsGL54X-sA4cMRCG6RI5OPvL3GIUt_QcOi0sX0YJOwtJGL8wSE8yoN5rV6icv7UIbtfRCzOGqPWIV6zf99X3Wob_vf)

‘Sell asset’ button allows to launch Order entry in order to sell asset.

![](https://lh6.googleusercontent.com/3zHW_KezwxuBvv1d6nv3fADFrl8uyzNN7qf4F41YNg2YKXBN9Qo_GakQ8XmME2jZ8_mrZh61PHAYRGTBxKC5PSNYEbKsE8tX0kSUtMQ4UvokN2c36WVWFZ0YpSDMLji9_rquku3B)

