---
aliases:
  - MWR
  - MONEY-WEIGHTED RETURN
  - MONEY-WEIGHTED RETURNS
tags: []
---
# Money-Weighted Return (MWR)
## Definition
The return for a period that reflects the change in value and the timing and size of [[EXTERNAL CASH FLOW|EXTERNAL CASH FLOWS]].
## Methods
[[#Standard Calculation Method]]
[[#Modified Dietz Method]]
### Standard Calculation Method
The IRR is the return for which the net present value of a cash flow series is equated to zero and is calculated by solving for the return that satisfies the following equation:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.29.1.png)

where

- _CF_<sub>i</sub> = external cash flow _i_ (negative values for inflows (paid-in capital) and positive values for outflows (distributions))
- _i_ = number of external cash flows (1, 2, 3, …, _I_) during the measurement period
- _r<sub>IRR</sub>_ = annualized internal rate of return
- _t<sub>i</sub>_ = number of calendar days between the beginning of the measurement period and the date of external cash flow _i_

The SI-IRR is a special version of the IRR in which the period-end value of the investment is treated as a synthetic terminal cash outflow, calculated as follows:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.29.2.png)

where

- _CF_<sub>i</sub> = external cash flow _i_ (negative values for inflows (paid-in capital) and positive values for outflows (distributions))
- _i_ = number of external cash flows (1, 2, 3, …, _I_) during the measurement period
- _r<sub>SI-IRR</sub>_ = annualized since-inception internal rate of return
- _t<sub>i</sub>_ = number of calendar days between the beginning of the measurement period and the date of external cash flow _i_
- _TD_ = total number of calendar days in the measurement period
- _V<sub>E</sub>_ = value of the investment at the end of the measurement period. In the case of closed-end funds, this is typically the net asset value at the end of the measurement period.

Note that the above annualized formula assumes a 365-day year convention and thus may have slight inaccuracies when the measurement period contains one or more leap years.

Firms must calculate and present the annualized SI-IRR. If the period is less than a full year, firms must present the non-annualized SI-IRR. The non-annualized SI-IRR is calculated as follows:

![](https://www.gipsstandards.org/wp-content/themes/gips/pdf_img/for_firms/2.A.29.3.png)

where

- _R<sub>SI-IRR</sub> = non-annualized since-inception internal rate of return
- _r<sub>SI-IRR</sub> = annualized since-inception internal rate of return
- _TD_ = total number of calendar days in the measurement period

As of 1 January 2020, external cash flows must be reflected on a daily basis when calculating an MWR, which results in a more accurate return. Using daily external cash flows means that the external cash flows are dated on the date the external cash flows occur – for example, the date of a capital call or the date of a distribution. For periods prior to 1 January 2020, firms must calculate an MWR by using quarterly or more frequent external cash flows. However, firms should use daily external cash flows in calculating an MWR prior to 1 January 2020 if daily external cash flows are available.

In dealing with legacy cash flow streams that might be dated monthly for periods prior to 1 January 2020, the firm should assume that all external cash flows occurred on a particular date in the month regardless of the actual date of the external cash flow. The same is true if external cash flows are reflected on a quarterly basis. The firm could assume that all external cash flows within the month happened on the last business day of the respective month.

For example, the following table shows the date the cash flow could be reflected for performance purposes if cash flows are not reflected daily.

|Date|Cash Flow|Quarterly Cash Flows|   |Monthly Cash Flows|   |
|---|---|---|---|---|---|
|||Cash Flow|Date|Cash Flow|Date|
|7 Feb 2017|100|||100|28 Feb 2017|
|9 Mar 2017|100|300|31 Mar 2017|100|31 Mar 2017|
|18 Apr 2017|100|||100|30 Apr 2017|
|1 May 2017|100|||100|31 May 2017|
|2 Jun 2017|100|300|30 Jun 2017|100|30 Jun 2017|
|14 Jul 2017|100|||100|31 Jul 2017|
|8 Aug 2017|100|||100|31 Aug 2017|
|9 Sep 2017|100|300|30 Sep 2017|100|30 Sep 2017|
|4 Oct 2017|100|||100|31 Oct 2017|
|8 Nov 2017|100|||100|30 Nov 2017|
|1 Dec 2017|100|300|31 Dec 2017|100|31 Dec 2017|

Stock distributions must be included as external cash flows and must be valued at the time of distribution. The cash flow is reflected on the date the fund distributes the money to the investor.

It is also required that, when calculating pooled fund net returns for inclusion in a GIPS Pooled Fund Report, the pooled fund net returns are net of total pooled fund fees. Total pooled fund fees include all fees and expenses charged to the pooled fund, including investment management fees, administrative fees, and other expenses. Total pooled fund fees do not include sales charges and loads that are associated with buying or selling shares of a pooled fund.

### Modified Dietz Method
In addition to SI-IRR, firms may calculate an MWR using the Modified Dietz method over the entire period. Unlike when being used to calculate a TWR, using the Modified Dietz method to calculate an MWR does not involve the calculation or linking of sub-period returns. A single MWR is calculated for the entire time period presented.

An example follows.

|Modified Dietz|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|Dates (MM/DD/YYYY)|Terminal Value|Cash Flows (CF)|Day of CF/ Valuation|Weighted CF|Numerator|Denominator|Return|
|31 Dec 2016||2,000,000|0|2,000,000||||
|8 Jan 2017||200,000|8|198,905||||
|24 Dec 2017||(50,000)|358|(37,748)||||
|20 Feb 2018||(200,000)|416|(143,053)||||
|6 Mar 2018||150,000|430|105,852||||
|11 Dec 2018||(20,000)|710|(10,281)||||
|25 Jun 2019||100,000|906|37,988||||
|3 Jul 2019||30,000|914|11,232||||
|14 Aug 2019||(50,000)|956|(17,283)||||
|21 Mar 2020||(200,000)|1,176|(39,014)||||
|4 Jun 2020||80,000|1,251|11,499||||
|22 Nov 2020||(50,000)|1,422|(1,335)||||
|3 Dec 2020||150,000|1,433|2,875||||
|31 Dec 2020|2,300,000||1,461||160,000|2,119,637|7.55% Cumulative|
|Total||2,140,000||2,119,637|||1.84% Annualized|

The numerator is the terminal value less the sum of the cash flows (2,300,000-2,140,000), or 160,000.

The denominator is the sum of the weighted cash flows (2,119,637).

The cumulative return is calculated as 160,000/2,119,637, or 7.55%.

To calculate the annualized return, the formula is (1 + r)^(1/n) – 1, where r is the cumulative return and n is the number of years. In this example, it would be:
	= (1 + 0.0755)^(1/4) – 1
	= 1.84%.