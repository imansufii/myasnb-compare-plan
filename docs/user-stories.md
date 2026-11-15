# User Stories and Acceptance Criteria

## US1 Fund comparison

**Linked requirements:** FR2, FR3

As a first-time investor, I want to view the main details of selected funds together, so that I can compare them without switching between separate pages.

**Acceptance criteria**

1. Given two selected funds, when the comparison is opened, then both funds appear in matching rows for objective, price type, risk information, and fees.
2. Given a displayed fund, when the user views its source field, then a working link to an official supporting document or ASNB page is visible.

## US2 Savings scenario

**Linked requirements:** FR1, FR5

As a student saving for a goal, I want to change my monthly contribution and saving period, so that I can explore how much I may be able to contribute.

**Acceptance criteria**

1. Given a valid scenario, when the monthly contribution or saving period changes, then the displayed calculation updates without a page reload.
2. Given a calculated scenario, when results are displayed, then contributions are separated from hypothetical growth and all assumptions are stated with a warning that returns are not guaranteed.

## US3 Eligibility and explanations

**Linked requirements:** FR4, FR6

As a cautious new investor, I want to understand why a fund appears in or is excluded from my comparison, so that I can review the information used.

**Acceptance criteria**

1. Given a published eligibility filter, when the user applies it, then incompatible options are hidden or clearly labelled with the relevant condition.
2. Given a highlighted difference, when it is displayed, then it includes a plain-language explanation and either a source date or a missing-data warning.
