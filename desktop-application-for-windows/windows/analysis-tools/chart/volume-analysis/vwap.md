# VWAP+

VWAP+ allows calculating a cumulative volume-weighted average price for defined period.

![](../../../../../.gitbook/assets/screenshot_2%20%2838%29.jpg)

Visible – controls visibility of the render on a chart. Default state – False.

Historical mode – allows determining whether the render will count its historical values. Default state – False.

* If Historical mode is checked, then render counts both historical and current values.
* If Historical mode is not activated, then render counts only current values.

Line \#1:

Line visible – allows visibility of a certain line of render. Default state – False.

Calculation cycle – cycle for calculation of cumulative VWAP+ value. The following options are available:

* Custom cycle – default value, with this value the length of the renderer calculation cycle is set by the user;
* Intraday – render counts its cumulative values from the beginning of a trade day till the end of each trade day with the period which is set in ‘Intraday cycle’.

Days number – number of days for calculating the values of the volume analysis by ticks, if Calculation cycle is set to “Custom cycle”;

Start/End day time – allows to determine time of start and end of a day;

Intraday cycle – allows to determine the period of a cumulative calculation of values of render in minutes from the beginning of every trade day.

VWAP = ∑ price i \* size i / ∑ size i,

where 'size i' is the volume traded at 'price i' .

Intraday cycle – defines the period of cumulative calculations of render values in minutes from the beginning of a trade day. In one trade day can be lots of intraday cycles.

Line style – a set of standard controls for settings of visual look of a render.

Line \#2 and Line \#3 have the same settings as Line \#1.

![](../../../../../.gitbook/assets/screenshot_1%20%2845%29.jpg)



