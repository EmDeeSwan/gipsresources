---
aliases:
  - TWR
  - TIME-WEIGHTED RETURN
  - TIME-WEIGHTED RETURNS
tags: []
---
# TIME-WEIGHTED RETURN (TWR)
## Definition
A method of calculating period-by-period returns that reflects the change in value and negates the effects of [[EXTERNAL CASH FLOW|EXTERNAL CASH FLOWS]].
### Portfolio Calculation Methods
[[#Original Dietz Method]]
[[#Modified Dietz Method]]
[[#Internal Rate of Return (IRR) Method]]
### Composite Calculation Methods
[[#Beginning Assets Weighting Method]]
[[#Beginning Assets Plus Weighted External Cash Flow Method]]
[[#Aggregate Return Method]]
[[#Example Calculation Comparison]]
## Portfolio Calculation Methods
### Original Dietz Method
The returns calculated for each sub-period are geometrically linked according to the following formula:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.1.png)

- where r<sub>t</sub><sup>TWR</sup> is the time-weighted return for period t and period t consists of I sub-periods

The chief advantage of valuing a portfolio at the time of large cash flows and calculating sub-period returns is that it calculates a better estimate than the midpoint or day-weighting methods. The major disadvantage is that it requires precise valuation of the portfolio each time a large cash flow occurs. In practice, this means that firms must have the ability to value portfolios on a daily basis. If all investments are not accurately priced for each sub-period valuation, errors generated in the return calculation may be greater than the errors caused by using the midpoint or day-weighting approximation methods. In such cases, it is important to be able to correct for errors, such as missed security splits, mispricings, and improperly booked transactions, because day-to-day compounding will not correct for them automatically if external cash flows occur.

As of 1 January 2005, the calculation of portfolio returns that adjust for daily-weighted external cash flows is required, if daily returns are not calculated. The denominator in the calculation of a TWR that adjusts for daily-weighted external cash flows reflects the weighting of external cash flows for the days they have been in the portfolio and available for investment during the period. A firm must create a composite-specific policy for the treatment of external cash flows and apply the policy consistently. Examples of acceptable methods for calculating returns that adjust for daily-weighted external cash flows are the Modified Dietz method and internal rate of return (IRR). These methods are estimates of TWRs.

### Modified Dietz Method
The Modified Dietz method improves upon the Original Dietz method, which assumes that all external cash flows occur during the midpoint of the period. In an attempt to determine a more accurate return, the Modified Dietz method weights each external cash flow in the denominator by the amount of time it is held in the portfolio. The formula for estimating the TWR using the Modified Dietz method is

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.2.png)

where

- _r_<sub>t</sub><sup>MD</sup> = the Modified Dietz return for the portfolio for period _t_
- _V_<sub>t</sub><sup>E</sup> = the ending value of the portfolio for period _t_
- _V_<sub>t</sub><sup>B</sup> = the beginning value of the portfolio for period _t_
- _i_ = the number of external cash flows _(1, 2, 3, . . . I)_ in period _t_
- _CF_<sub>i,t</sub>= the value of external cash flow _i_ in period _t_
- _w_<sub>i,t</sub> = the weight of external cash flow _i_ in period _t_ (assuming the external cash flow occurred  
	at the end of the day), as calculated according to the following formula:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.3.png)

where

- _w_<sub>i,t</sub> = the weight of external cash flow _i_ in period _t_, assuming the external cash flow occurred at the end of the day
- _D_<sub>t</sub> = the total number of calendar days in period _t_
- _D_<sub>i,t</sub> = the number of calendar days from the beginning of period _t_ to external cash flow _i_

The numerator of _w_<sub>i,t</sub> is based on the assumption that the external cash flows occur at the end of the day. If external cash flows were assumed to occur at the beginning of the day, the numerator would be ((_D_<sub>t</sub> – _D_<sub>i,t</sub>) + 1). A firm may choose to use a beginning-of-day or end-of-day external cash flow assumption or some combination of the two. The key is to establish a policy and treat external cash flows consistently.

The chief advantage of the Modified Dietz method is that it does not require portfolio valuation on the date of each external cash flow. Its chief disadvantage is that it provides a less accurate return than when the portfolio is valued at the time of each external cash flow. The estimate suffers most when a combination of the following conditions exists:
1. One or more large external cash flows occur, and
2. external cash flows occur during periods of high market volatility – that is, the portfolio’s returns are significantly non-linear.

The following is an example of a return calculation using the Modified Dietz method. The example is for a portfolio with a beginning value of $100,000 on 31 May, an ending value of $135,000 on 30 June, and external cash flows of -$2,000 on 6 June and $20,000 on 11 June. Assume the external cash flows were reflected at the end of the day.

|31 May|Beginning Value (BV)|$100,000|
|---|---|---|
|6 June|Cash Flow (CF)|-$2,000|
|11 June|Cash Flow (CF)|$20,000|
|30 June|Ending Value (EV)|$135,000|

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.4.png)

**_W_** is the weight of the external cash flow for the month. Because June has 30 days and the external cash flows were assumed to occur at the end of the day, the weights of the external cash flows are calculated as (30 – 6)/30 = 0.80 and (30 – 11)/30 = 0.6333, respectively.

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.5.png)

If the firm’s policy was to treat external cash flows as occurring at the beginning of the day, the firm would have added one to the numerator in the weight calculation, and the weights to be multiplied by the external cash flows would be calculated as (30 – 6 + 1)/30 = 0.8333 and (30 – 11 + 1)/30 = 0.6667, respectively.

The following is an example of a return calculation using the Modified Dietz method and revaluing during the month for a large cash flow (assumed to be 10% in this example). To calculate performance for the month, we must calculate performance for the sub-periods before and after the large external cash flow and then geometrically link the sub-period returns. In this example, we use the same data as in the prior example but instead value the portfolio at the time of the large cash flow on 11 June.

|31 May|Beginning Value (BV)|$100,000|
|---|---|---|
|6 June|Cash Flow (CF)|-$2,000|
|11 June|Cash Flow (CF)|$20,000|
|11 June|Ending Value (EV)|$125,000|
|30 June|Ending Value (EV)|$135,000|

#### Sub-period 1 Calculation, from 31 May through 11 June:
Because sub-period 1 has 11 days and the external cash flows are assumed to occur at the end of the day, the weight of the external cash flow on the sixth day is (11 – 6)/11 = 0.4545. The weight of the cash flow on the 11th would be zero because it is assumed to happen at the end of the day on  
11 June, which is when the portfolio was revalued.
![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.6.png)

#### Sub-period 2 Calculation, from 11 June through 30 June:
![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.7.png)

To calculate the monthly return, geometrically link sub-period returns 1 and 2:

(1 + 0.0706) x (1 + 0.08) – 1 = 0.1563, or 15.63%.

Other formulas in addition to the Modified Dietz method for calculating approximate _TWRs_ are also permitted.

### Internal Rate of Return (IRR) Method
The IRR, which is a money-weighted return, is the implied discount rate or effective compounded rate of return that equates the present value of cash outflows with the present value of cash inflows. The IRR method is an acceptable method to use to calculate a TWR when **_no large cash flows occur during the sub-period_**. To create a TWR, the IRRs before and after the large cash flow are calculated and then linked together geometrically.

The IRR is the value of _R_ that satisfies the following equation:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.24.8.png)

where _V<sub>E</sub>_ and _W<sub>i</sub>_ are the same as for the Modified Dietz method.

The external cash flows, _CF<sub>i</sub>_, are also the same as with the Modified Dietz method with one important exception: The value at the beginning of the period is also treated as an external cash flow – that is, _V<sub>B</sub> = CF<sub>0</sub>

The IRR is obtained by selecting values for _R_ and solving the equation until the result equals _VE_. For example, if three external cash flows (including the value at the beginning of the period) have occurred, the formula will have three terms:

_VE = CF<sub>0</sub>(1+R)<sup>W0</sup>+CF<sub>1</sub>(1+R)<sup>W1</sup>+CF<sub>2</sub>(1+R)<sup>W2</sup>_

The first term deals with the first external cash flow, CF<sub>0</sub>, which is the value of the portfolio at the beginning of the period; Wi is the proportion of the period when the external cash flow _CF_<sub>i</sub> was held in the portfolio. Because CF<sub>0</sub> is in for the whole period, W<sub>0</sub> = 1. The larger the value of _CF_<sub>i</sub> in the term, the more it will contribute to the total, but the smaller the exponent (i.e., the value of _W_<sub>i</sub>), the less the term will contribute to the sum. The usual effect is that the first term, with a large CF<sub>0</sub> and W<sub>0</sub> equal to 1, will contribute far more than the other terms.

The advantages and disadvantages of the IRR method are the same as those of the Modified Dietz method. The IRR method has the additional disadvantage of requiring an iterative process solution. It is also possible to have multiple answers if both positive and negative external cash flows occur.

## Composite Calculation Methods
### Beginning Assets Weighting Method
The _Beginning Assets Weighting_ method for calculating composite returns, Rt, uses the formula

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.1.png)

where

- _R<sub>t</sub>_ = the beginning assets weighted return for the composite for period _t_
- _k_ = the number of portfolios (1, 2, 3, . . . , _K_) in the composite at the beginning of period _t_
- _V<sup>B</sup><sub>k,t</sub>_ = the beginning value of portfolio _k_ for period _t_
- _r<sub>k,t</sub>_ = the return of portfolio _k_ for period _t_

The Beginning Assets Weighting method can also be expressed as

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.2.png)

where
_W<sup>B</sup><sub>k,t</sub>_ is the weight of the value of portfolio _k_ as a fraction of total composite asset value based on beginning asset values for period _t_ and can be calculated according to the following formula:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.3.png)

### Beginning Assets Plus Weighted External Cash Flow Method
The _Beginning Assets Plus Weighted External Cash Flow_ method represents a refinement to the Beginning Assets Weighting method. Consider the case in which one of two portfolios in a composite doubles in value as the result of a contribution on the third day of a performance period. Under the Beginning Assets Weighting method, this portfolio would be weighted in the composite based solely on its beginning value (i.e., not including the contribution). The Beginning Assets Plus Weighted External Cash Flow method resolves this problem by including the effect of external cash flows in the calculation. Assuming that external cash flows occur at the end of the day, the weighting factor for each external cash flow is calculated using the same methodology as in the Modified Dietz method as follows:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.4.png)

where

- _w<sub>i,k,t</sub>_ = the weight of external cash flow _i_ in portfolio _k_ in period _t_, assuming the external cash flow occurred at the end of the day
- _D<sub>t</sub>_= the total number of calendar days in period _t_
- _D<sub>i,k,t</sub>_ = the number of calendar days from the beginning of period _t_ to external cash flow _i_ in portfolio _k_

The Beginning Assets Plus Weighted External Cash Flow composite return can be calculated as follows:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.5.png)

where

-  _R<sub>t</sub>_ = the beginning assets plus weighted external cash flow composite return for period _t_
- _V<sup>B</sup><sub>k,t</sub>_ = the beginning value of portfolio _k_ for period _t_
- _i_ = the number of external cash flows (1, 2, 3, . . . , _I_) in portfolio _k_
- _CF<sub>i,k,t</sub>_ = the _i_th external cash flow in portfolio _k_ for period _t_
- _w<sub>i,k,t</sub>_ = the weight of external cash flow _i_ in portfolio _k_ for period _t_
- _r<SUB>k,t</SUB>_ = the return for portfolio _k_ for period _k_

The Beginning Assets Plus Weighted External Cash Flow composite return method can also be expressed by the following formula:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.6.png)

where

- _R<sub>t</sub>_ = the beginning assets plus weighted external cash flow composite return for period _t_
-  _r<SUB>k,t</SUB>_ = the return for portfolio _k_ for period _t_
- _V<sub>k,t</sub>_ = the beginning value plus weighted external cash flows of portfolio _k_ for period _t_, as calculated by the following formula:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.36.7.png)

where

- _V<sub>k,t</sub>_ = the value of portfolio k’s beginning assets plus weighted external cash flows for period _t_
-  _V<sup>B</sup><sub>k,t</sub>_ = the beginning value of portfolio _k_ for period _t_
- _i<sub>k</sub>_ = the number of external cash flows (1, 2, 3, . . . , I) in portfolio _k_
- _CF<sub>i,k,t</sub>_ = the ith external cash flow in portfolio _k_ for period _t_
- _w<sub>i,k,t</sub>_ = the weight of external cash flow _i_k for period _t_

### Aggregate Return Method
The _Aggregate Return_ method combines all the composite assets and external cash flows before any calculations occur to calculate returns as if the composite were one portfolio. Therefore, unlike the Beginning Assets Weighting method or the Beginning Assets Plus Weighted External Cash Flow method, the Aggregate Return method does not use portfolio returns.
### Equal-weighted
The formula for the equal-weighted composite return, REQUAL, is

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/4.A.1.13.png)

where R<sub>PORT1</sub> is the time-weighted return for the first portfolio in the composite, R<sub>PORTi</sub> is the timeweighted return for the _i_ th portfolio in the composite, and _n_ is the number of portfolios in the composite.
### Example Calculation Comparison
The following examples show how to calculate a composite return using the Beginning Assets Weighting method, the Beginning Assets Plus Weighted External Cash Flow method, and the Aggregate Return method, assuming that external cash flows occur at the end of the day.
#### Composite Return
##### Beginning Assets Weighting Method:

|Portfolio|BMV|Portfolio Weight|Portfolio Return|Weighted Return|
|---|---|---|---|---|
|A|450,000|17.08%|12.00%|2.05%|
|B|785,000|29.79%|14.00%|4.17%|
|C|1,400,000|53.13%|11.00%|5.84%|
|Total|2,635,000|100.00%||12.06%|

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_asset_owners/22.A.21.21.png)

##### Beginning Assets Plus Weighted External Cash Flow Method:

|Portfolio|BMV|Weighted  <br>Cash Flows|BMV plus  <br>Wtd CFs|BMV plus  <br>Wtd CFs|Portfolio  <br>Return|Weighted  <br>Return|
|---|---|---|---|---|---|---|
|A|450,000|75,000|525,000|18.95%|12%|2.27%|
|B|785,000|120,000|905,000|32.67%|14%|4.57%|
|C|1,400,000|(60,000)|1,340,000|48.38%|11%|5.32%|
|Total|2,635,000|135,000|2,770,000|100.00%||12.17%|

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_asset_owners/22.A.21.22.png)

##### Aggregate Return Method (using Modified Dietz method):

(Assuming the large cash flow level is established at the composite level and none of the cash flows qualifies as a large cash flow)

|Portfolio|BMV|EMV|Cash Flows|Weighted CFs|Portfolio Return|
|---|---|---|---|---|---|
|A|450,000|665,000|150,000|75,000|12%|
|B|785,000|1,140,000|240,000|120,000|14%|
|C|1,400,000|1,440,000|(120,000)|(60,000)|11%|
|Total|2,635,000|3,245,000|270,000|135,000||

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_asset_owners/22.A.21.23.png)

When using the aggregate method, a manager may encounter a situation in which the composite return falls outside the range of portfolio-level returns for a given period. This scenario can occur if the policies used to calculate portfolio-level returns do not flow through to the aggregate composite-level return calculation policies. “Flowing through” to the composite means that if any portfolio is valued during the month because of a large cash flow, the entire composite would also be valued and the sub-period return calculated for both the portfolio and the composite. A firm may establish large cash flow policies, however, such that only those portfolios in the composite that experience a large cash flow during the month are valued at the time of the large cash flow and any portfolios that did not experience a large cash flow are not valued during the month. In such a situation, the composite return may be outside the range of portfolio-level returns for a given period. To prevent this situation from occurring, the firm should consider establishing a policy wherein all portfolios in the composite are valued if any portfolio in the composite is valued during the month because of large cash flows. Once a firm has established large cash flow policies for a composite, the firm must apply the large cash flow policies consistently.