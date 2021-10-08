# Accounts

Accounts panel shows basic details about all accounts that are available for a user.

To open Accounts panel, select Account -&gt; Accounts in the header of TraderEvolution Web platform:

![](../../.gitbook/assets/windows-desk-waived.png)

The Accounts panel is also available in Detailed view in order to show the detailed information in rows. You can see details about any of your accounts or about all together. Click on the Current equity section \(Balance & Projected balance\) located in the header of the Web platform in order to open this panel.

![](../../.gitbook/assets/windows-desk-acc%20%282%29.png)

By clicking on the Account Link button![](../../.gitbook/assets/screenshot_8%20%283%29.png), located at the top right corner of Accounts widget, a user can link panels by account:

![](../../.gitbook/assets/linking%20%283%29.gif)

Please, read more about Account linking [here](https://guide.traderevolution.com/project/web-platform/getting-started/arranging-panels).

The following information about Accounts and calculation formulas are available:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Title</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Formula</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>General</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Balance</td>
      <td style="text-align:left">A current realized balance of an account. If there is trading with pending
        valuation, balance won&#x2019;t change before clearing, on which P/L will
        be credited by covered trades or delivery of funds will be performed by
        uncovered trades. Fees are charged off from a balance at the time of accrual.</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Projected balance</td>
      <td style="text-align:left">A future balance which includes all accrued and not accrued profit/loss.
        After closing all positions, accrual of fees and assets&apos; delivery,
        a balance becomes equal to equity.</td>
      <td style="text-align:left">Projected balance = Balance + Unsettled cash + Loss + Profit + Blocked
        for Stocks, where:
        <br />Unsettled cash &#x2013; realized profit/loss by covered positions, which
        have not been delivered to an account yet and will be delivered in accordance
        with T+n value cycle;
        <br />Profit/Loss &#x2013; current open profit/loss by positions;
        <br />Blocked for Stocks &#x2013; amount of funds debited from a balance in
        case of Equities trading. After closing such position, funds will be returned
        to an account.</td>
    </tr>
    <tr>
      <td style="text-align:left">Balance&amp;All risks</td>
      <td style="text-align:left">Shows an actual current quantity of funds on an account which can be used
        for trading.</td>
      <td style="text-align:left">Balance&amp;All risks = Balance + Unsettled loss + Loss + Unsettled profit
        + Profit, where:
        <br />Unsettled loss &#x2013; realized losses by covered positions which have
        not been delivered to an account yet and will be delivered in accordance
        with T+n value cycle;
        <br />Loss &#x2013; current open losses;
        <br />Unsettled profit &#x2013; profit, which is not delivered to an account
        and will be delivered in accordance with T+n value cycle;
        <br />Profit &#x2013; current open profit.</td>
    </tr>
    <tr>
      <td style="text-align:left">Credit value</td>
      <td style="text-align:left">An amount of credit funds which you can&apos;t withdraw, but can trade
        with.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Available funds</td>
      <td style="text-align:left">Amount of funds which can be used for trading.</td>
      <td style="text-align:left">Available funds = Balance&amp;All risks - Initial margin req - Stock orders
        req</td>
    </tr>
    <tr>
      <td style="text-align:left">Blocked balance</td>
      <td style="text-align:left">Balance blocked by a broker or by a user for withdrawal\transfer.</td>
      <td
      style="text-align:left">Blocked balance = Withdrawal balance + Transfer balance</td>
    </tr>
    <tr>
      <td style="text-align:left">Cash balance</td>
      <td style="text-align:left">A current cash position for an account with taken into account unsettled
        profit/loss.</td>
      <td style="text-align:left">Cash balance = Balance + Unsettled cash</td>
    </tr>
    <tr>
      <td style="text-align:left">Unsettled cash</td>
      <td style="text-align:left">Profit/loss, which will be credited to an account in accordance with T+n
        value cycle.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Withdrawal available</td>
      <td style="text-align:left">Shows an amount of cash that you can withdraw immediately from your account.</td>
      <td
      style="text-align:left">
        <p>Withdrawal available = Available funds &#x2013; Credit value &#x2013;
          Profit &#x2013; Unsettled profit + Unused unsettled negative cash for stocks
          &#x2013; Unsettled positive cash for stocks + Unused unsettled negative
          premium - Unsettled positive premium + Unsettled premium from open sell
          - Used premium from open sell <b>- </b>Stocks liquidity + Withdrawable cash
          for stocks + Withdrawable unsettled profit/loss + Withdrawable unsettled
          collateral + Unused intraday initial margin - Used overnight initial margin
          for intraday, where:</p>
        <p></p>
        <ul>
          <li>Credit value - credited funds available to trade with but unavailable
            to withdraw.</li>
        </ul>
        <p>If Credit value is positive, then we use the current logic and subtract
          this value.</p>
        <p>If Credit value is negative, it means that it has been already substracted
          from the balance and shouldn&apos;t be substracted again.</p>
        <p></p>
        <ul>
          <li>Profit - current open profit, calculated for all instruments on a selected
            account;</li>
          <li>Unsettled profit - realized profit for all positions, which isn&apos;t
            yet settled to an account and will be settled in accordance with T+n settlement
            system;</li>
          <li>Unsettled positive cash for stocks - value of unsettled cash, which was
            returned when selling stocks;</li>
          <li>Unsettled premium from open sell - unsettled uncovered option premium
            for opening short positions;</li>
          <li>Used premium from open sell - settled uncovered option premium for opening
            short positions.</li>
          <li>&quot;Unused intraday initial margin&quot; and &quot;Used overnight initial
            margin for intraday&quot; participate in the calculation only during those
            periods of the trading session for which Is Intraday = true. For other
            periods, they do not participate, since the margin is already blocked by
            Overnight coefficients.</li>
        </ul>
        </td>
    </tr>
    <tr>
      <td style="text-align:left">Interest rate, %</td>
      <td style="text-align:left">Shows an annual interest rate on deposit.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Stocks value</td>
      <td style="text-align:left">A total cost of assets, traded with Stocks pre-paid margin type, positions
        of which are open on a selected account.</td>
      <td style="text-align:left">Stocks value = &#x2211; (Current stock price * Amount * Cross price),
        where:
        <br />Amount - a current stocks&apos; quantity in the position &apos;Qty * Lot
        size&apos;; Qty is qty in lots.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Margin</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Waived margin</td>
      <td style="text-align:left">The amount in the Account currency that is deducted from Initial and Maintenance
        margin requirements for the Account</td>
      <td style="text-align:left">see Initial margin req. and Maint. margin req.</td>
    </tr>
    <tr>
      <td style="text-align:left">Initial margin req</td>
      <td style="text-align:left">Amount of initial margin blocked for all positions and orders taking into
        account a margin crossing.</td>
      <td style="text-align:left">Initial margin req = &#x2211; (Initial margin)+ Fee - Waived margin</td>
    </tr>
    <tr>
      <td style="text-align:left">Initial margin req, %</td>
      <td style="text-align:left">Shows how much margin is used in relation to Balance&amp;All risks.</td>
      <td
      style="text-align:left">Initial margin req,% = (Initial margin req/ (Balance&amp;All risks - Stock
        orders req))*100%</td>
    </tr>
    <tr>
      <td style="text-align:left">Maint. margin req, %</td>
      <td style="text-align:left">Shows current level of risks. When Maint. margin req=100%, stop-out triggers.</td>
      <td
      style="text-align:left">Maint. margin req% = (Maint margin req/ (Balance&amp;All risks - Stock
        orders req))*100%, where Maint margin req=&#x2211; (Maintenance margin)
        + Fee - Waived margin</td>
    </tr>
    <tr>
      <td style="text-align:left">Margin available</td>
      <td style="text-align:left">Full margin which is available to maintain a portfolio in a current moment.</td>
      <td
      style="text-align:left">Margin available = Balance&amp;All risks - Maint. margin req - Stock orders
        req</td>
    </tr>
    <tr>
      <td style="text-align:left">Margin warning level</td>
      <td style="text-align:left">Shows Maintenance margin level, which Warning margin message is sent with.</td>
      <td
      style="text-align:left">Warning margin lvl. = (Margin warning, % / 100) * (Balance&amp;All risks
        - Stock orders req <b>)</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left">Stop out level
        <br />
      </td>
      <td style="text-align:left">The Maint. margin req% value required for a stop out to occur.</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Warning margin</td>
      <td style="text-align:left">A value set on the account&apos;s level. When Maint. margin req, % reaches
        this value, a Warning margin message is sent.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Maint. margin req</td>
      <td style="text-align:left">Total margin used for maintenance of a current portfolio in account currency.</td>
      <td
      style="text-align:left">Maint. margin req = &#x2211;Maint. margin req
        <br />(Maintenance margin req for positions and Initial margin for orders, taking
        into account the margin crossing between orders and positions)</td>
    </tr>
    <tr>
      <td style="text-align:left">Blocked for Stocks</td>
      <td style="text-align:left">Amount of funds debited from a balance in case of trading with symbols
        with Stocks pre-paid margin type. After closing such position, funds will
        be returned to an account. Stock operations can be pending.</td>
      <td style="text-align:left">Blocked for Stocks=abs(&#x2211;Stock operation), where:
        <br />abs - a module;
        <br />Stock operation = - Open price * Qty * Lot size * Cross price (for buy);
        <br
        />Stock operation = Open price * Qty * Lot size * Cross price (for sell).</td>
    </tr>
    <tr>
      <td style="text-align:left">Stock orders req</td>
      <td style="text-align:left">Total margin blocked for orders with Stock pre-paid margin type.</td>
      <td
      style="text-align:left">Stock orders req = &#x2211; Margin for Stocks pre-paid orders</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Account activity</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Open gross P/L</td>
      <td style="text-align:left">A profit or loss on all currently opened positions and currency, recalculated
        in real time based on the most recent quotes</td>
      <td style="text-align:left">Open gross P/L = Sum (Open gross P/L(i))</td>
    </tr>
    <tr>
      <td style="text-align:left">Open net P/L</td>
      <td style="text-align:left">A net profit or loss on open positions.</td>
      <td style="text-align:left">Open net P/L = Sum (Open net P/L(i))</td>
    </tr>
    <tr>
      <td style="text-align:left"># Positions</td>
      <td style="text-align:left">A number of currently opened positions.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"># Orders</td>
      <td style="text-align:left">A number of currently placed pending orders.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Today results</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today&apos;s gross</td>
      <td style="text-align:left">A gross profit for today.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today&apos;s net</td>
      <td style="text-align:left">A total profit or loss realized from positions today.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today&apos;s fees</td>
      <td style="text-align:left">Fees paid today.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today&apos;s volume</td>
      <td style="text-align:left">A total volume traded for today.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"># Today&apos;s trades</td>
      <td style="text-align:left">A number of trades done for today.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today turnover</td>
      <td style="text-align:left">Shows a turnover of funds per day for a current account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Today&#x2019;s rebates</td>
      <td style="text-align:left">Shows a sum of all funds that have been received/paid by a broker for
        the creation/removal of liquidity for a current day. If a received rebates
        is bigger than a paid sum, then rebates value will be positive &quot;+&quot;,
        otherwise negative &quot;-&quot;.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Risk management</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Trading status</td>
      <td style="text-align:left">Trading status of a selected account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Daily loss limit</td>
      <td style="text-align:left">Max loss limit for 1 day, trading is blocked when this limit is reached.</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Weekly loss limit</td>
      <td style="text-align:left">Max loss limit for 1 week, trading is blocked when this limit is reached.</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Total max position qty</td>
      <td style="text-align:left">Max total qty in lots of all positions and orders.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Trailing drawdown level</td>
      <td style="text-align:left">Shows maximum drawdown level for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Daily loss</td>
      <td style="text-align:left">Shows a current net daily loss limit value for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Weekly loss</td>
      <td style="text-align:left">Shows a current net weekly loss limit value for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Daily profit target</td>
      <td style="text-align:left">Maximum value of daily net profit allowed for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Max. day volume</td>
      <td style="text-align:left">Shows a Max. day volume set for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"># Max. positions</td>
      <td style="text-align:left">Shows a Max. qty. of positions.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"># Max. pending orders</td>
      <td style="text-align:left">Shows a Max. qty of pending orders.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Max. order capital</td>
      <td style="text-align:left">Shows a Max. order capital.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Allow overnight trading</td>
      <td style="text-align:left">Shows whether it is allowed or not to transfer positions through night
        for an account.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Max order amount</td>
      <td style="text-align:left">Maximum allowed opening order amount (in the Instrument absolute units)</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Max orders count per day</td>
      <td style="text-align:left">Number of orders that the User can place or modify during a day</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Max drawdown level</td>
      <td style="text-align:left">Minimum allowed Projected balance value that an Account can have</td>
      <td
      style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Day trader pattern protection</td>
      <td style="text-align:left">Displays whether protection against accidental marking the account as
        the Day trader pattern is activated. Available states are &#x2018;Enabled&#x2019;
        or &#x2018;Disabled&#x2019;.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Available day trades</td>
      <td style="text-align:left">Displays the number of intraday trades that can be performed before the
        system classifies this user/account as a Day trader pattern.</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>



