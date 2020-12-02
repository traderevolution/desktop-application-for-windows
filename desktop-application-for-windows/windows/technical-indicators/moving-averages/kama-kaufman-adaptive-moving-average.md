# KAMA \(Kaufman adaptive moving average\)

The KAMA indicator, i.e. Kaufman adaptive moving average was created by Perry J. Kaufman and presented in his 1998 book "Trading Systems and Methods, 3rd Edition". Kaufman created KAMA to take market noise into account. If there is an Uptrend with some small swings prevailing on the market, the market noise will be negligible and KAMA follows the price very closely. On the other hand, if the market moves sideways \(ranging market\) – this means that the Close price closes some days up, some days down, the market noise is very high. KAMA follows the price at a larger distance in order to then reduce the number of false signals.

SC \(Smoothing constant\) is a standard part of the moving average plotting. SC determines the level to which the moving average is sensitive to existing price fluctuations. SC moves in the range from 0 to 1. The lower the Smoothing constant, the less sensible the moving average is. The main advantage of KAMA over other moving averages is that it takes into account not only the direction but also market volatility. KAMA adjusts its length according to prevailing market conditions.

### Calculation

ER \(Efficiency Ratio = Direction/Volatility\)

ER = \[ABS \(Closet - Closet-n\]/ \[n ∑ \(ABS \(Closet – Closet-1\)\)\],

n - is a selected number of days for the moving average calculation. If each day would close higher than the previous day, the ER would be 1. If the market moved sideways with any price change at all, ER would be 0.

Determine the shortest and longest moving average that will be used in the KAMA calculation to determine the Smoothing constant \(SC of these averages\). Kaufman recommended using a range of 2 to 30 days.

SC = ER \* \(Fast SC – Slow SC\) + Slow SC

KAMA shortens and extends the time period used for moving average calculation according to the conditions that prevail on the market. KAMA becomes more sensible or robust depending on the market. Despite the fact that KAMA will be calculated as a 30-days Moving average during a volatile market, it still moves slightly up and down. Kaufman recommended making SC less sensible by its squaring:

C = SC \* SC

C is the final smoothing constant that is used for the KAMA calculation. The final KAMA calculation is similar to the EMA calculation:

KAMA = Kamat-1 + \[\(C \* \(Closet – Kamat-1\)\]

Compared to the Simple moving average \(MVA, SMA\), KAMA has less lag and generates fewer false signals. KAMA can also be used to smooth out some other technical indicators. This indicator looks as follows on the chart:

![](../../../../.gitbook/assets/screenshot_1%20%2839%29.jpg)

