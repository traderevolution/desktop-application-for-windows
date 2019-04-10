# Currencies exposure

Currencies exposure panel shows a summary of the amount of each currency for which user has open positions.

To open a new Currencies exposure panel, select Terminal -&gt; Currencies exposure.

![](../../../.gitbook/assets/15%20%283%29.png)

User can select accounts for which he wants to see the information in the panel.

The following columns are available in the panel:

* Currency – title of the currency for which user has opened positions.
* Amount – currency amount for all opened positions.

Amount \(Net qty.\) = Sum of all positions \(Buy/Sell\) by base & counter currencies

Base currency: 

Buy: Pos. amount \* Lot size  
Sell: - Pos. amount \* Lot size

Counter currency:  
 Buy: - Pos. amount \* Lot size \* Pos. open price  
 Sell: Pos. amount \* Lot size \* Pos. open price

For Futures and Options:

Base currency:  
 Buy: Pos. amount  
 Sell: - Pos. amount

Counter currency:

Buy: \(- Pos. amount \* Pos. open price\)/Tick cost\*Tick size  
 Sell: \(Pos. amount \* Pos. open price\)/Tick cost\*Tick size

* Gross P/L – current profit or loss for all opened positions.
* Exposure – exposure of all opened positions, calculate on base of open price.
* Amount exp./cl. – current value of all opened positions, calculate on base of market price.

The total is shown in account currency if accounts by all opened positions have the same account currency; if accounts by which user have opened positions have different account currencies, then total is displayed in server currency.

