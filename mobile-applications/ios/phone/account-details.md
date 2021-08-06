# Account details

The Account details screen is accessible through the Watchlist, Positions and Orders screens. Tap the ‘Projected balance’ section to open Account details screen. To select the account available for a user, tap the![](../../../.gitbook/assets/first%20%281%29.png)button at the top of the screen:

![](../../../.gitbook/assets/1%20%28115%29.png)

In order to view detailed information about an account, tap its name.

![](../../../.gitbook/assets/2%20%2899%29.png)

P/L, % = Open Gross P/L \* 100 / \(projectedBalance - Open Gross P/L\) 

Risk level – displays how an account is close to portfolio liquidation.

![](../../../.gitbook/assets/3%20%2884%29.png)

* Balance – current realized balance of the account. If there is trading with pending valuation, balance won’t change before clearing, on which P/L will be credited by covered trades or delivery of funds will be performed by uncovered trades; Fees are charged off from the balance at the time of accrual;
* Projected balance – future balance which includes all accrued and not accrued profit/loss. After closing all positions, accrual of fees and assets' delivery, the balance becomes equal to a projected balance:

Projected balance = Balance + Unsettled cash + Loss + Profit + Blocked for Stocks + Option premium, where:

Unsettled cash – cash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;

Profit/Loss – current open profit/loss by positions;

Blocked for Stocks – amount of funds debited from a balance in case of Equities trading. After closing such position, funds will be returned to an account:

Blocked for stocks = abs \(∑ Stock operation\), abs - module.

Option premium – option premium value.

Option premium = ∑ \(Open price \* Qty \* Lot size \* Cross price\), where:

Open price – an average price of a position opening;

Qty – a position's qty in lots;

Lot size = Tick cost / Tick size;

Cross price – an average cross price of a position opening for converting into account's currency.

* Available funds – amount of funds which can be used for placing a new order. 

Available funds = Balance& All risks - Margin used;

* Margin available – full margin which is available to maintain portfolio on the current moment. 
* Init. margin req – amount of the initial margin blocked for all positions and orders taking into account the margin crossing;
* Warning margin lvl – shows Maintenance margin level when the margin warning message is sent:

Warning margin lvl = \(Margin warning% / 100\) \* \(Balance&All risks - Stock orders req\);

* Waived margin –the amount in the account currency that is deducted from Initial and Maintenance margin requirements for the account;
* Blocked balance – balance blocked by broker or by user for withdrawal/transfer;
* Cash balance – current cash balance of the account;
* Unsettled cash – сash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;
* Withdrawal available – shows an amount of cash that you can withdraw immediately from your account:

Withdrawal available = Available funds – Credit value – Profit – Unsettled profit + Unused unsettled negative cash for stocks – Unsettled positive cash for stocks + Unused unsettled negative premium - Unsettled positive premium + Unsettled premium from open sell - Used premium from open sell **-** Stocks liquidity + Withdrawable cash for stocks + Withdrawable unsettled profit/loss + Withdrawable unsettled collateral + Unused intraday initial margin - Used overnight initial margin for intraday, where:

Credit value – credited funds available to trade with but unavailable to withdraw;

Profit – current open profit, calculated for all instruments on a selected account.

Unsettled profit – realized profit for all positions, which has not been delivered to an account yet and will be delivered in accordance with T+n settlement system;

Unsettled positive cash for stocks - value of unsettled cash, which was returned when selling stocks;

Unsettled premium from open sell – unsettled uncovered option premium for opening short positions;

Used premium from open sell – settled uncovered option premium for opening short positions;

{% hint style="warning" %}
"Unused intraday initial margin" and "Used overnight initial margin for intraday" participate in the calculation only during those periods of the trading session for which Is Intraday = true. For other periods, they do not participate, since the margin is already blocked by Overnight coefficients.
{% endhint %}

* Init. margin req, % – shows how much margin is used in relation to Balance&All risks:

Initial margin req, % = \(Initial margin req/ \(Balance&All risks - Stock orders req\)\)\*100%;

* Blocked for stocks – amount of funds debited from balance in case of Equities trading. After closing such position, funds will be returned to account;
* Stocks value – total cost of stocks, positions which were opened on the selected account:

 Stocks value = ∑ \(Current stock price \* Amount \* Cross price\), where:  
 Amount – a current stocks' quantity in the position 'Qty \* Lot size'; Qty is qty in lots.

* Open positions – currently opened positions;
* Working orders – all created orders which are visible for a user;
* Option premium req – option premium for buy orders;
* Stocks liquidity – a part of a total cost of assets, which is accounted in available margin if there are assets on the account of a trader.

Stocks liquidity = ∑ \(Amount \* Price \* CrossPrice \* \(Liquidity rate/100\)\) Amount - a current stocks' quantity on the account 'Qty \* Lot size'; Qty is qty in lots.

* Stocks orders req – total margin blocked for Equities;
* Option value – сurrent option value in portfolio. Can be positive for a long Net position, or negative for a short Net position. 

Option value = ∑ \(Current option price \* Amount \* Cross price\), where:

Current option price – a current price of an option;  
Amount – a current amount of options in a position;  
Cross price – a current cross price in account's currency.

* Today’s net profit – Net Profit/Loss for today;
* Today’s fee ­– amount of fees paid for today;
* Warn. margin req. – warning margin requirement for positions and orders;
* Warn. margin req.% – warning margin requirement in relation to Balance&All risks;
* Margin before warning ****– margin available before the warning triggering;
* Day trader pattern protection –  displays whether protection against accidental marking the account as the Day trader pattern is activated. Available states are ‘Enabled’ or ‘Disabled’;
* Available day trades –  displays the number of intraday trades that can be performed before the system classifies this user/account as a Day trader pattern.

