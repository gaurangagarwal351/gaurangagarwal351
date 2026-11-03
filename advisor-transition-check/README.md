# Advisor Transition Check

An interactive financial modeling demo comparing a Current Investment (CI) with a Proposed Investment (PI), accounting for transition costs, annual fees, withdrawal taxes and retirement income needs.

## Try the demo

Download [index.html](./index.html) using GitHub’s **Download raw file** button, then open the downloaded file in a web browser. No installation or server is required.

## Features

- Editable client assumptions and three example profiles.
- Portfolio projections through age 90.
- Bear, base and bull return scenarios.
- Comparison of 0%, 25%, 50%, 75% and 100% transition allocations.
- Transition costs, estimated break-even age and fund depletion indicators.
- Responsive chart and comparison tables.

## Implementation

HTML, CSS, vanilla JavaScript and SVG. All calculations run in the browser; no account or backend is required.

## Model assumptions

Uses annual compounding, constant returns within each scenario, proportional withdrawals across holdings, flat effective withdrawal taxation and upfront costs proportional to assets moved. The allocation is selected by average modeled age-90 outcome across three equally weighted scenarios. Negative modeled values represent accumulated unmet withdrawals, rather than actual negative account balances. Income inflation is applied from the specified retirement age.

This is an illustrative modeling prototype. Results depend on inputs and simplifying assumptions and are not investment or tax advice.
