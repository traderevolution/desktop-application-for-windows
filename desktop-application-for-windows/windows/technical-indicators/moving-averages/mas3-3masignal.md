# MAS3 \(3MASignal\)

As the name of this technical indicator implies, its plotting is based on the intersection of three Moving averages, namely: Short moving average, Middle moving average, and Long Moving Average. Utilizing this technical indicator the user can get three signals in one: the intersection of three moving averages.

### Calculation

This indicator is calculated in three stages. At the first stage, the number of the period from which the indicator will be calculated is determined. For this, the following values specified by the user in the settings are used: short period, middle period, long period, and amount of bars passed before opening position. 

At the second stage, a moving average is calculated for all three periods. 

At the third stage, the indicator value is calculated cyclically. The number of calculation cycles is equal to the number of bars passed before the opening position. If the number of bars passed before an opening position is negative or equal to zero, then the indicator value at any point is equal to zero. 

During the first calculation cycle of the current indicator value, the following conditions are checked:

1 condition: midMA&gt; lgMa. If True, then the following condition is checked: midMA &lt;shMa. If True, then assign the current indicator value equal to 1 and start the next calculation cycle. If False, then check condition 2;

2 condition: midMA&gt; shMa. If True then the following condition is checked: midMA &lt;lgMa, If True - assign the current indicator value equal to -1 and start the next calculation cycle. If False, then assign the current indicator value equal to 0.

On the second and following cycles, until reaching the number of bars passed before opening position:

The indicator value is calculated for the period that is away from the current period by the number of the calculation cycle in the same way as in the first cycle.

2 conditions are checked:

1 condition. The value of the indicator obtained in the previous calculation cycle is compared with 1. If True, the following condition is checked: the indicator value for the period that is away from the current one by the number of the calculation cycle is not equal to 1. True - the indicator value on this calculation cycle is assigned 0 and moving to the next calculation cycle.

2 condition. The current value of the indicator obtained in the previous cycle is compared with -1. If True, the following condition is checked: the indicator value for the period that is away from the current one by the number of the calculation cycle is not -1. True - the indicator value for this calculation cycle is assigned 0 and moving to the next calculation cycle.

If none of the conditions is met, then the indicator value for this calculation cycle remains the same and moving to the next calculation cycle.

### Main parameters

* Short moving average – the number of periods involved in calculating the moving average;
* Middle moving average – the number of periods involved in calculating the moving average;
* Long moving average – the number of periods involved in calculating the moving average;
* Amount of bars passed before opening positions – the number of bars that are taken into account in calculating the current value.

This technical indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2817%29.jpg)

