# Account details

The Account details screen is accessible through the Watchlist, Positions and Orders screens. Tap the ‘Projected balance’ section to open Account details screen. To select the account available for a user, tap the![](../../../.gitbook/assets/4%20%2839%29.png)button at the top of the screen:

![](../../../.gitbook/assets/1%20%2837%29.png)

In order to view detailed information about an account, tap its name.

![](../../../.gitbook/assets/2%20%2868%29.png)

P/L, % = Open Gross P/L \* 100 / \(projectedBalance - Open Gross P/L\) 

Risk level – displays how an account is close to portfolio liquidation.

![](../../../.gitbook/assets/3%20%2822%29.png)

* Balance – current realized balance of the account. If there is trading with pending valuation, balance won’t change before clearing, on which P/L will be credited by covered trades or delivery of funds will be performed by uncovered trades; Fees are charged off from the balance at the time of accrual;
* Projected balance – future balance which includes all accrued and not accrued profit/loss. After closing all positions, accrual of fees and assets' delivery, the balance becomes equal to a projected balance:

Projected balance = Balance + Unsettled cash + Loss + Profit + Blocked for Stocks + Option premium, where:

Unsettled cash – cash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;

Profit/Loss – current open profit/loss by positions;

Blocked for Stocks – amount of funds debited from a balance in case of trading with symbols with Stocks pre-paid margin type. After closing such position, funds will be returned to an account:

Blocked for stocks = abs \(∑ Stock operation\), abs - module.

Option premium – option premium value which will be debited from or credited to an account while closing all positions for options with Option trading style 'Premium-style' or 'Mark-to-market'. Option trading style is set up by a broker:

when 'Premium-style':

Option premium = ∑ \(Open price \* Qty \* Lot size \* Cross price\), where:

Open price – an average price of a position opening;

Qty – a position's qty in lots;

Lot size = Tick cost / Tick size;

Cross price – an average cross price of a position opening for converting into account's currency.

when 'Mark-to-market':

Option premium = ∑ \(Current price \* Qty \* Lot size \* Cross price\), where:

Current price – a current option price, which depends upon 'Calculate PnL/margin from' set up by a broker for an instrument.

* Available funds – amount of funds which can be used for placing a new order. If Available funds = 0, then it is allowed to send only close orders, and orders that decrease volume of the position.

Available funds = Balance& All risks - Margin used;

* Margin available – full margin which is available to maintain portfolio on the current moment. If Margin available = 0, Stop out starts to trigger;
* Init. margin req – amount of the initial margin blocked for all positions and orders taking into account the margin crossing;
* Warning margin lvl – shows Maintenance margin level when the margin warning message is sent:

Warning margin lvl = \(Margin warning% / 100\) \* \(Balance&All risks - Stock orders req\);

* Blocked balance – balance blocked by broker or by user for withdrawal/transfer;
* Cash balance – current cash balance of the account;
* Unsettled cash – сash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;
* Withdrawal available – shows an amount of cash that you can withdraw immediately from your account:

Withdrawal available = Available funds – Credit value – Profit – Unsettled profit + Unused unsettled negative cash for stocks – Unsettled positive cash for stocks + Unused unsettled negative premium - Unsettled positive premium + Unsettled premium from open sell - Used premium from open sell, where:

Credit value – credited funds available to trade with but unavailable to withdraw;

Profit – current open profit, calculated for all instruments on a selected account.

For such margin types, as 'Security fully paid' and 'Stocks pre-paid' Profit isn't taken into account.  
  
For Options with Option trading style 'Premium-style' in buy positions Profit is taken into account.  
  
For Options with Option trading style 'Premium-style' in sell positions Profit isn't taken into account.  
  
For Options with Option trading style 'Mark-to-market' in sell positions Profit is taken into account.  
  
For Options with Option trading style 'Mark-to-market' in buy positions Profit isn't taken into account.

Option trading style is set up by a broker;

Unsettled profit – realized profit for all positions, which has not been delivered to an account yet and will be delivered in accordance with T+n settlement system;

Unused unsettled negative cash for stocks - value of unsettled cash, blocked for instruments with 'Stocks pre-paid' margin type. Is taken into account when 'Use unsettled negative cash for stocks in Margin available' is disabled by a broker for 'Stocks pre-paid' margin type;

Unsettled positive cash for stocks - value of unsettled cash, which was returned when selling stocks. For instruments with 'Stocks pre-paid' margin type. Is taken into account when 'Use unsettled positive cash for stocks in Margin available' is enabled by a broker for 'Stocks pre-paid' margin type;

Unused unsettled negative premium – unsettled negative option premium, which is taken into account when 'Use unsettled negative premium in Margin available' is disabled by a broker for such margin types, as 'Derivatives risk module' and 'CBOE';

Unsettled positive premium - unsettled positive option premium, which is taken into account when 'Use unsettled positive premium in Margin available' is enabled by a broker for such margin types, as 'Derivatives risk module' and 'CBOE';

Unsettled premium from open sell – unsettled uncovered option premium for opening short positions. It is taken into account when 'Use unsettled premium from open sell in Margin available' is enabled by a broker for such margin types, as 'Derivatives risk module' and 'CBOE';

Used premium from open sell – settled uncovered option premium for opening short positions, which is taken into account when 'Use premium from open sell in Margin available' is enabled by a broker for such margin types, as 'Derivatives risk module' and 'CBOE'.

* Init. margin req, % – shows how much margin is used in relation to Balance&All risks:

Initial margin req, % = \(Initial margin req/ \(Balance&All risks - Stock orders req\)\)\*100%;

* Blocked for stocks – amount of funds debited from balance in case of trading with symbols with Stocks pre-paid margin type. After closing such position, funds will be returned to account;
* Stocks value – total cost of stocks, positions which were opened on the selected account:

Stocks value = ∑ \(Current stock price \* Amount \* Cross price\), where:  
 Amount – a current stocks' quantity in the position 'Qty \* Lot size'; Qty is qty in lots.

* Open positions – currently opened positions;
* Working orders – all created orders which are visible for a user;
* Option premium req – option premium for buy orders;
* Stocks liquidity – a part of a total cost of assets, which is accounted in available margin if there are assets on the account of a trader.

Stocks liquidity = ∑ \(Amount \* Price \* CrossPrice \* \(Liquidity rate/100\)\) Amount - a current stocks' quantity on the account 'Qty \* Lot size'; Qty is qty in lots.

* Stocks orders req – total margin blocked for orders with Stock pre-paid margin type;
* Option value – сurrent option value in portfolio. Can be positive for a long Net position, or negative for a short Net position. Option value is calculated only for Options with Option trading style 'Premium-style' or 'Mark-to-market'. Option trading style is set up by a broker:

Option value = ∑ \(Current option price \* Amount \* Cross price\), where:

Current option price – a current price of an option, which depends upon 'Calculate PnL/margin from' set up by a broker;  
Amount – a current amount of options in a position;  
Cross price – a current cross price in account's currency.

* Today’s net profit – Net Profit/Loss for today;
* Today’s fee ­– amount of fees paid for today.

