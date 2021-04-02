# Position sizing

Position sizing is the size of a position within a portfolio or the dollar amount that an investor is going to trade. It allows investors to control risk and maximize returns.  When determining appropriate position sizing, an investor's account size and risk tolerance are taken into account.

If the Position sizing function is available, then the![](../../../.gitbook/assets/image1-kopiya.png)button will be displayed next to the “Quantity” field. 

![](../../../.gitbook/assets/image1%20%282%29.png)

When a user clicks on this button for the first time, the info screen with the following message will be shown:

"The position size calculator is a risk management tool that allows calculating the quantity based on the maximum allowed percentage \(or fixed cash\) loss for the account. Specify the account risk and the trade's stop loss. The calculation will be performed automatically."

If a user unchecks the "Show next time" setting, the next time the button is clicked, the info screen will not be shown. When a user clicks on the “Ok” button on the info window, additional fields will appear in the Order entry panel for automatic calculation of the quantity. When clicking on the Position sizing button, it turns yellow and the “Quantity” field becomes disabled.

![](../../../.gitbook/assets/image%20%2871%29.png)

* Account risk - the amount of losses for the account selected in the lookup. A user can select the risk unit in the auxiliary control section: Fixed or Percentage:
* Fixed - the currency of the account that is selected in the Order entry is displayed in the auxiliary section;
* Percentage - percentage is displayed in the auxiliary section.
* Percentage risk/Cash risk - recalculation into the opposite risk unit. If Fixed is specified in the Account risk, then here the Percentage will be displayed and vice versa.
* SL with the ability to enable Trailing stop - allows setting the SL level in absolute or in offset. It depends on the condition of the “Set SL/TP values in offset” setting.
* SL limit price - the parameter is displayed when the “Use stop limit instead of Stop” is activated in the General setting.
* SL offset/SL price - recalculation into the value that is opposite to the value in the “SL limit price” field.  If “SL price” is displayed in the “SL limit price” field, then “SL offset” value will be displayed here and vice versa.

Note: if SL is forbidden, then the Position size calculator will be disabled.  


### Calculations

Quantity with consideration of the propensity to risk, is calculated by the formula:

_**Quantity = \(Risk per trade, ccy \* crossPrice\) / Risk per share**_ ,

where:

- Risk per trade - risk propensity in the account currency.  This is the value that a user enters into the “Account risk” field. If a value is entered in percentage, then it will be determined how much it is in the account currency by the formula: \(Available funds \* Risk,%\) / 100%;

- crossPrice - cross rate from the account currency to the quote currency of the instrument;

- Risk per share is calculated by formulas:

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left">For the quote currency tickCost/tickSze</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">When Set SL/TP values in offset = false:</td>
      <td style="text-align:left">
        <p>Risk per share = abs(Price - SL price) or</p>
        <p>Risk per share = abs(Price - SL limit price) if Use Stop limit instead
          of Stop is used</p>
      </td>
      <td style="text-align:left">Risk per share = abs(Price - SL price)*tickCost/tickSize</td>
    </tr>
    <tr>
      <td style="text-align:left">When Set SL/TP values in offset = true and Show offset in = Ticks:</td>
      <td
      style="text-align:left">
        <p>Risk per share = SL offset * tick size or</p>
        <p>Risk per share = (SL offset + SL limit offset) * tick size if Use Stop
          limit instead of Stop is used</p>
        </td>
        <td style="text-align:left">Risk per share = SL offset * tickCost</td>
    </tr>
    <tr>
      <td style="text-align:left">When Set SL/TP values in offset = true and Show offset in = Points:</td>
      <td
      style="text-align:left">
        <p>Risk per share = SL offset or</p>
        <p>Risk per share = (SL offset + SL limit offset) if Use Stop limit instead
          of Stop is used</p>
        </td>
        <td style="text-align:left">Risk per share = SL offset*tickCost/tickSize</td>
    </tr>
    <tr>
      <td style="text-align:left">When Set SL/TP values in offset = true and Show offset in = Ticks (fractional
        ticks for Forex):</td>
      <td style="text-align:left">
        <p>Risk per share = SL offset * 10 * tick size or</p>
        <p>Risk per share = (SL offset + SL limit offset) * 10 * tick size if Use
          Stop limit instead of Stop is used</p>
      </td>
      <td style="text-align:left">The same as for offset in ticks</td>
    </tr>
  </tbody>
</table>

Note: For Buy order: Risk per share = Price - SL price; for Sell order: Risk per share = SL price - Price.  

