# Personal Finance Decision Models

A collection of Excel-based financial decision models designed for the public seminars I host as Local Coordinator of Students for Liberty Sweden. Each model helps non-technical audiences think through a real financial decision using proper finance methodology — net present value, sensitivity analysis, total cost of ownership, and break-even analysis.

The models follow three design principles:

1. **Decision-relevant outputs.** Each model produces a clear recommendation alongside the numbers that drive it. Users see not just *what* the answer is but *why*.
2. **Editable assumptions.** All inputs are isolated in yellow cells. Conclusions can be stress-tested by changing assumptions — no buried hardcodes.
3. **Methodological transparency.** Color coding (yellow inputs, blue outputs, green calculations) follows industry-standard financial-modeling conventions. Methodology is documented in-sheet.

These were built using AI-assisted workflows (ChatGPT, Claude). I specified the model structure, validated the math, iterated on assumptions and edge cases, and refined the user experience for non-technical readers.

---

## Models

### 1. Buy vs Rent — Ending Wealth Comparison

A 50-year NPV-based comparison of buying versus renting a home, with break-even analysis identifying the holding period at which buying overtakes renting.

**Methodology.** Full mortgage amortization, property appreciation, rent growth, inflation-adjusted owner recurring costs (property tax, insurance, HOA), and selling costs at exit. The renter's counterfactual invests the down payment plus the monthly cash-flow differential at a user-specified ROI. Buyer and renter ending wealth are both discounted to present value using a user-specified discount rate.

**Key outputs.** NPV of buyer ending wealth, NPV of renter ending wealth, NPV advantage, break-even holding period, full year-by-year wealth comparison table over 50 years.

### 2. Sweden Used Car — 10-Year Total Cost of Ownership

A monthly TCO model for buying and operating a used car in Sweden over a 10-year horizon, with both nominal and discounted (NPV) cumulative cost tracking.

**Methodology.** Separate cost streams for purchase price, fuel (price per litre × consumption × monthly mileage), insurance, vehicle tax, and scheduled maintenance — each escalated at a user-specified inflation rate and discounted at a user-specified rate. Maintenance schedule lives on a dedicated sheet for events like servicing, tire changes, and major repairs.

**Key outputs.** Total undiscounted 10-year cost, total discounted cost (NPV), average monthly cost, cost breakdown by category, monthly and cumulative cost trajectories.

### 3. Financial Decision Toolkit

A multi-sheet workbook with three independent decision models, each with stress-test scenarios and plain-English interpretation of results.

- **Debt vs Invest.** Compares paying down debt with surplus cash versus investing it, tracking ending net worth under three return scenarios (conservative / base / optimistic). Includes a split-strategy option and identifies the break-even gross investment return at which the two strategies are equivalent.
- **Subscription Audit.** Catalogs recurring subscriptions with cost, frequency, usage level, and price-growth assumptions. Surfaces cancellation candidates ranked by annual cost relative to actual use.
- **Cheap vs Durable Appliance.** Lifecycle cost comparison using both Present Value of total cost and Equivalent Annual Cost (EAC) to make options with different lifespans directly comparable. Includes energy cost, repair timing, and replacement cycles.

### 4. Avanza Credit Monitor

A margin-account risk monitor for users of Avanza's portfolio credit product. Projects debt growth under monthly compounding and flags when a deposit or partial liquidation will be required to stay under the loan-to-value (LTV) threshold.

**Methodology.** Monthly interest compounding on utilized credit, LTV ratio tracking against a user-set maximum threshold, projection over a user-specified horizon. Headroom and required deposit / sale calculated month by month.

**Key outputs.** Current LTV, current headroom, debt after horizon, deposit/sale required at horizon, full projection table flagging months where action is needed.

---

## How to use

1. Download the `.xlsx` file you want.
2. Open it in Excel for full formula support — Google Sheets and Numbers may break some functions.
3. Edit the yellow input cells. All outputs and tables recalculate automatically.
4. Stress-test by varying assumptions. The conclusions are only as good as the inputs.

## A note on scope

These are decision aids, not financial advice. They are built to help people *think clearly* about financial trade-offs by making the underlying mechanics explicit. They do not capture every real-world variable (e.g., tax-rule changes, behavioral factors, liquidity preferences) and should be used as one input among several.

---

## About

Built and maintained by Manuel A. Alvarez — Business & Financial Analyst, focused on econometrics, financial modeling, and data-driven decision-making.

- Email: noloalvartz@gmail.com
- Seminars: [The Student's Journal on YouTube]
- Articles: wespeakfreely.org
- Community: Students for Liberty Sweden (@esflsweden)
