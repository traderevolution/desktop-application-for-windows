# Regression line

Linear regression is a statistical tool used to predict future values ​​based on past values. In the case of security prices, it is commonly used to determine when prices are overextended.

The Linear regression trendline uses least squares to plot a straight line through prices to minimize the distance between the prices and resulting trendline.

The Linear regression line, used to determine the direction of the trend, runs through a set of prices so that there is the smallest distance between all price points and the regression line. Instead of a price chart with scattered price points, the Linear regression line allows to clearly see if prices are moving up, down, or sideways.

Prices tend to move above and below the Linear regression line. As a result, when prices are below the line, analysts usually predict that prices will rise, and when they are above the line, prices are predicted to return toward the Linear regression line.

### Calculation

The Linear regression indicator is calculated by fitting a linear regression line to the values for a given period and then determining the current value for that line. The Linear regression line is a straight line that is closest to all of the target values.

LRI = p \* LRI period + b

p = \(LRI period \* sum XY – sum X \* sum Y\) / \(LRI period \* sum XX – sum X \* sum X\)

b = \(sum Y \* sum XX – sum X \* sum XY\) / \(LRI period \* sum XX – sum X \* sum X\)

where:

sum X – sum of periods;

sum Y – sum of prices;

sum XY – sum of periods \* price;

sum XX – sum of squared price.

### Main parameters

* Period of linear regression – number of periods for calculating the linear regression coefficients. The default value is 2. 
* Sources prices for MA – determines the type of price at which the moving average will be calculated. Possible values: Close, Open, High, Low, Typical, Medium, Weighted.

The Regression line indicator is actually tomorrow's price prediction plotted today. If prices are consistently above or below the forecast price, expect them to quickly return to more realistic levels. In other words, the Regression line indicator shows where prices "should" trade on a statistical basis, and any excessive deviation from the Regression line is likely to be short-lived. The indicator itself looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2823%29.jpg)

