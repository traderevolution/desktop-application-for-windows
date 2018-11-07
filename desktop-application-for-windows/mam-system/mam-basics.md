# MAM basics

MAM, or Multi-account manager, is a module which allows asset managers to trade on multiple client accounts by one click. The main benefit of MAM is bulk order execution with instant allocation to the prelinked accounts.

To begin a MAM group, a money manager must firstly have client accounts linked to his User ID. All account types can be linked to a money manager and added to a MAM group, but it is not possible to group accounts with One position per symbol with accounts that have Multiple positions per symbol settings permissions.

MAM groups may have an unlimited quantity of accounts. Trading within the MAM panel is fully functional and supports Stop loss, Take profit, and order modifying. Positions can be partially closed as well.

Account statistics is available for the prelinked accounts.

### Allocation methods

There are four allocation methods available in MAM:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Allocation method</th>
      <th style="text-align:left">Formula</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Lot multiplier</td>
      <td style="text-align:left">
        <p>
          <img src="../../.gitbook/assets/1 (26).png" alt/>
        </p>
        <p>MVol - order size entered by manager;</p>
        <p>Vol i - volume of open positions on the subaccount;</p>
        <p>k - coefficient from the accounts section of the MAM panel.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Lot allocation</td>
      <td style="text-align:left">
        <p>
          <img src="../../.gitbook/assets/2 (26).png" alt/>
        </p>
        <p>Vol i - volume of open positions on the subaccount;</p>
        <p>MVol - order size entered by manager;</p>
        <p>Lot i – the coefficient setting for the subaccount;</p>
        <p>∑ Lot – sum of all coefficients of all active accounts.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Proportional by balance</td>
      <td style="text-align:left">
        <p>
          <img src="../../.gitbook/assets/3 (22).png" alt/>
        </p>
        <p>balance i - the balance of the subaccount;</p>
        <p>∑balance - the balance of all active subaccounts.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Proportional by equity</td>
      <td style="text-align:left">
        <p>
          <img src="../../.gitbook/assets/4 (3).png" alt/>
        </p>
        <p>Equity i - the equity of the subaccount;</p>
        <p>∑Equity - the sum of equity of all subaccounts.</p>
      </td>
    </tr>
  </tbody>
</table>

