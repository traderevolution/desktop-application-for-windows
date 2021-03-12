# Metrics

The Metrics screen shows the Portfolio statistics. A user can see here the invested amount of funds, arithmetic mean income for different time periods, the best year result, the worst year result \(considering profit\), etc.

The statistics data is displayed as cards with a metric name and its value.    ****

![](https://lh3.googleusercontent.com/fFexkbkWlVAvP8FY_gxdfOINN3xSKy3ke8-6nhIFI9f3Ss9iKpWyAf-UQIfEwnJpBbcXJE5BGbnUxfMOTEvBs6DZtte7mvnM4-NFhE9jkDkmS9mtNVgQhYeihmLTOVq3KvQ5IqCD)

The default list of metrics includes the following:

* Invested amount - invested amount of funds;
* Portfolio balance - future settlement account balance considering accrued and non-accrued profits and losses;
* Holding period rate of return - portfolio return since the moment of investment; 
* Max drawdown - the maximum drawdown value. The drawdown value is calculated by the formula:

_**Drawdown\(i\),% = \(EODPortfolioBalance\(i\) — max\(PortfolioBalance\)/max\(PortfolioBalance\)\)\*100%**_

where:

* i - current day;
* EODPortfolioBalance\(i\) - the Projected balance value at the end of the current day;
* max\(PortfolioBalance\) - the maximum Projected balance value for the corresponding account.

The drawdown value can be calculated by the above-mentioned formula if:

_**EODPortfolioBalance\(i\) &lt; max\(PortfolioBalance\)**_

Otherwise, the PortfolioBalance value grows, and the drawdown is equal to 0.00%.

If you don’t need any metric, you can remove it by swiping the card left and tapping the “Remove” button. 

![](https://lh6.googleusercontent.com/Mu0GXyQ8k5UolBO3q98F_wO0GujqeLuvZavQZUw3oll4LMkHlodwDedGchALgwf1cuJ9EnPhRW0eWamasIhriMsdsJQfo9nzQK_YOKrzVzzKHMlQ2AuHlT2VDIeoO2Fm4f3puC6u)

Other metrics can be added optionally. To add a metric, tap the![](https://lh3.googleusercontent.com/mwLy9VITx37fqqx78IPkbg8LIQm7NW12PU4iTYLnj9BRRvbg9mIKTgHkaE696gb-rnKmAtYrZslF1KoooqA3nC8nw6ub6ZLx98eo26km1amPtLXbNVm1gztMX_osUSY3v7q-98yC)button located above the metrics list and select preferred metrics. 

![](https://lh4.googleusercontent.com/rwv89ffnu1teLc2kfcUCKsRmwENEew3jmXsYA-6nFKfiWbizOS_01JQDrmywsYPRzXRSNIx_jt3YqmI5GnYblXH2ByF2pQYvWAFnDSKyJXR-c8RySSMI468xSkMRe0uSm-Ki502H)

“Best month” and “Worst month” metrics are the maximum and the minimum values of Monthly return which is calculated by the following formulas:

_**Monthly return\(i\),% = \(\(EOMPortfolioBalance\(i\) - Deposits\(i\) + Withdrawals\(i\) + Transfers\(i\) + TransferAndWithdrawal fees\(i\)  - EOMPortfolioBalance\(i-1\)\)/EOMPortfolioBalance\(i-1\)\)\*100%**_

_**Monthly return\(i\),$ = EOMPortfolioBalance\(i\) - Deposits\(i\) + Withdrawals\(i\) + Transfers\(i\) + TransferAndWithdrawal fees\(i\)  - EOMPortfolioBalance\(i-1\)**_

where:

* i - current month;
* EOMPortfolioBalance\(i\) - the Projected balance value at the end of the current month;
* Deposits - the sum of all Deposit transactions by the account since the beginning of the specified month;
* Withdrawals - the sum of all Withdrawal operations by the account since the beginning of the specified month;
* Transfers - the sum of all Transfer operations by the account since the beginning of the specified month;
* TransferAndWithdrawal fees - the sum of all Transfer fee and Withdrawal fee operations by the account since the beginning of the specified month;
* EOMPortfolioBalance\(i-1\) - the Projected balance value for the last date of the month that precedes the specified month.

On the list of cards you can see total metrics by the Portfolio. Tap the certain card to watch data by each asset.

![](https://lh3.googleusercontent.com/ECi-eLpvDjVyVvvOVAe_9MRn4LRxpfLJGZJbKzDrz7KWBsBAsmBJxk1mfNS_6VfWPqWIKYDTvvviZ3VS7c9g2Y9kCjYNUibeM0suBBoT1BbkyMvIzmf0LA-W3wgIj07Th5DO2-zI)

