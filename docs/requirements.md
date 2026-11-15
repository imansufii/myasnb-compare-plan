# Requirements

These requirements describe a low-fidelity academic prototype. They are testable targets for the proposed system, not claims about the current myASNB application.

## Functional requirements

- **FR1:** The system shall allow a user to enter a savings goal, monthly contribution, saving period, and optional hypothetical growth rate.
- **FR2:** The system shall allow a user to select two or three ASNB funds for comparison.
- **FR3:** The system shall display the selected funds in matching rows that include objective, price type, risk information, fees, and an official source link.
- **FR4:** The system shall filter funds using published eligibility information and user-selected fund attributes.
- **FR5:** The system shall recalculate an illustrative savings scenario when the user changes the contribution, period, or hypothetical growth rate.
- **FR6:** The system shall explain each highlighted difference and display its source date or a missing-information notice.

## Non-functional requirements

- **NFR1 — Performance:** At least 95% of comparison and filter updates shall appear within 3 seconds when the prototype is tested with up to 100 mock fund records.
- **NFR2 — Privacy:** The prototype shall not request, transmit, or store passwords, MyKad numbers, bank-account details, or live ASNB credentials.
- **NFR3 — Usability:** At least 4 of 5 test participants shall locate the fee information for two selected fictional funds within 3 minutes without assistance.
- **NFR4 — Accessibility:** Every interactive control shall have a visible text label, and every keyboard-focusable control shall display a visible focus indicator during keyboard navigation.

## Requirement traceability

| Objective | Related requirements |
|---|---|
| Consistent fund comparison | FR2, FR3, FR4, NFR1 |
| Editable savings scenario | FR1, FR5, NFR1 |
| Clear explanations and sources | FR3, FR6, NFR3, NFR4 |
| User control and privacy | FR4, FR6, NFR2 |

The numeric thresholds are proposed acceptance targets for a future prototype. They are not measured results and do not describe the performance of the live myASNB application.
