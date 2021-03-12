# Return

The “Return, %” tab shows statistics by the portfolio as well as by a single asset/Cash.

![](https://lh4.googleusercontent.com/wC2AvGiG-Z_dRkJDo-sbD5_7n3dEuo8EdyVYPKSCzZNJDMpFQ-OHstDKtpfzigMmS29N4mFZaqZqK8dlv1lzRK6rbkw9WX5cVqLeS9yQX2Mo3_sCCyfzGDfEundoZfLShOjnFE4-)

A user can see two charts which are displayed in one coordinate system:

* chart with markers - shows the “Portfolio monthly return” value since the moment of investment. 
* histogram \(bar chart\) - shows Monthly instrument return and Monthly Cash return since the moment of investment. 

A table with the monthly returns is also available on the Return screen. The following data is displayed in the table:  


* Date - the values are displayed for the specified month.
* Portfolio return, % - shows the total Portfolio return in the corresponding month.

Tap the selected number of bars on the histogram to change the data in the table according to the selected month and detailed information about returns by each asset/Cash will be displayed. Selected bars will be highlighted on the histogram.

Above the table a user can see the chosen month and the total Portfolio return. The color scheme of instruments in the table corresponds with the colors of bars on the histogram. The Month return of each instrument is shown next to the instrument name.

In order to go back to the previous model of data display, tap the empty space on the diagram or tap the "X" button near the Portfolio return at the active period.

![](https://lh4.googleusercontent.com/r5M3pBRiqIVrxScBbEZrjbodyLQjMklJGIf7kulGAyEBBw8HDRVGLAUSOHlCq1jAVeT1ghFBU9cjbxohgNTxpzY9IT20tWumX7AA8rR5jnOE9JwKleFS7ZcFaKLocv1NvtHn1kOk)

### Calculations

**Portfolio monthly return:**

_Monthly return\(i\),% = \(\(EOMPortfolioBalance\(i\) - Deposits\(i\) + Withdrawals\(i\) + Transfers\(i\) + TransferAndWithdrawal fees\(i\)  - EOMPortfolioBalance\(i-1\)\)/EOMPortfolioBalance\(i-1\)\)\*100%_

_Monthly return\(i\),$ = EOMPortfolioBalance\(i\) - Deposits\(i\) + Withdrawals\(i\) + Transfers\(i\) + TransferAndWithdrawal fees\(i\)  - EOMPortfolioBalance\(i-1\)_

where:

* i - current month;
* EOMPortfolioBalance\(i\) - the Projected balance value at the end of the current month;
* Deposits - the sum of all Deposit transactions by the account since the beginning of the specified month;
* Withdrawals - the sum of all Withdrawal operations by the account since the beginning of the specified month;
* Transfers - the sum of all Transfer operations by the account since the beginning of the specified month;
* TransferAndWithdrawal fees - the sum of all Transfer fee and Withdrawal fee operations by the account since the beginning of the specified month;
* EOMPortfolioBalance\(i-1\) - the Projected balance value for the last date of the month that precedes the specified month.

**Monthly instrument return:**

_Monthly instrument return\(i\) = \(\(EOMLastPrice\(i\) - EOMLastPrice\(i-1\)\)/EOMLastPrice\(i-1\)\)\*100%_  


where:

* i - current month;
* EOMLastPrice\(i\) - the Last price value at the end of the current month;
* EOMLastPrice\(i-1\) - the Last price at the end of the month that precedes the specified month. If there is no such value, then during the first month the Monthly return will be calculated by the formula:

_Monthly instrument return\(i\) = \(\(EOMLastPrice\(i\) - OpenPrice\(i\)\)/OpenPrice\(i\)\)\*100%_

**Monthly Cash return:**

_Monthly Cash return\(i\),% = \(\(EOMNetCash\(i\) - Deposits\(i\) + Withdrawals\(i\) + Transfers\(i\) + TransferAndWithdrawal fees\(i\) + StockOperation\(i\) - EOMNetCash\(i-1\)\)/EOMNetCash\(i-1\)\)\*100%_

where:

* i - current month;
* EOMNetCash\(i\) - the net Cash value at the end of the current month;
* Deposits - the sum of all Deposit transactions by the account since the beginning of the specified month;
* Withdrawals - the sum of all Withdrawal operations by the account since the beginning of the specified month;
* Transfers - the sum of all Transfer operations by the account since the beginning of the specified month;
* TransferAndWithdrawal fees - the sum of all Transfer fee and Withdrawal fee operations by the account since the beginning of the specified month;  
* StockOperation\(i\) - the sum of all Stock operations by the account since the beginning of the specified month;
* EOMNetCash\(i-1\) - the net Cash value at the end of the month that precedes the specified month.

