# HV \(Historical volatility\)

Historical volatility is a measure of how much the price deviates from the average over a period of time that can be set. The more the price fluctuates, the higher the indicator value. Note that it does not measure the direction of price change, but only how volatile the price is. There are several reasons why it is important to pay attention to volatility, but this is mainly related to identifying possible risks: if it rises, both risk and market volatility increase, and vice versa. Traders can use the indicator to mark an instrument with high volatility, which could indicate a change in trend. The indicator is most often used in combination with other signals.

In addition, Historical volatility can be utilized as an instrument by traders who only trade underlying financial instruments. Measuring market volatility can influence investor expectations about how much or to what extent the market might change and offers some guidance for making price predictions and executing trades.

### Calculation

In the classic sense, the historical volatility is determined by the following formula:

![](../../../../.gitbook/assets/image%20%2840%29.png)

Where:

 σ_std_ – standard deviation of the asset prices, i.e. measure of the sweeping movement;

√T – bringing the volatility indicator to the specified period \(most often to the annual value\);

P_i_ – price of _i_ value \(here can be one of four bar prices\).

Generally, the standard deviation is calculated either in absolute values, i.e. in the prices of the specific asset, or relative values \(%\). The value of volatility allows assessing the riskiness of the asset based on the different factors:

* Liquidity – the lower the asset liquidity, the higher the volatility, since the amount of people willing to buy or sell the asset is less. For example, if to consider the commodity market, orange juice is much more volatile than the cotton market i.e. this instrument is subjected to a sharp surge in prices. If to consider the equities, then less liquid equities are also prone to such outbursts because a major player that comes again can effortlessly "inflate" the prices;
* The release of important reports – usually the volatility is sharply increased after the release of important reports, such as changes of the Fed interest rate, changes in the unemployment rate, quarterly reports about company’s profits, as well as data on oil and other;
* The economic situation in a particular country – the higher the uncertainty in the political and economic life of the country, the more risky the investments will be.

### Main parameters

* STD period – period of standard deviation, by default = 30;
* Volatility period – period of the volatility, measured in days, by default = 365;
* Sources prices for MA – Close, Open, High, Low, Medium, Typical, and Weighted;
* All history – if checked, the percentile calculation is realized using the whole history;
* History period – allows to set up a history period for the percentile calculation. 'All history' checkbox has priority when setting both, the checkbox and 'History period';
* Sources prices for HV – HV and percentile or Only percentile.

The indicator itself looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2832%29.jpg)

