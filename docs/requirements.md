# Requirements

These requirements describe a low-fidelity academic prototype. They are testable targets for the proposed system, not claims about the current myASNB application.

## Functional requirements

- **FR1:** The system shall accept a savings goal, monthly contribution, saving period, and optional assumed growth rate.
- **FR2:** The system shall allow a user to select two or three funds for comparison.
- **FR3:** The system shall display selected fund details in matching rows, including objective, price type, risk information, fees, and a source link.
- **FR4:** The system shall filter funds using published eligibility information or selected fund attributes.
- **FR5:** The system shall update an illustrative savings calculation when the user changes the contribution, period, or assumed rate.
- **FR6:** The system shall explain each highlighted difference and display the relevant source date or a missing-information notice.

## Non-functional requirements

- **NFR1 — Response time:** At least 95% of comparison and filter changes shall appear within 3 seconds when tested with 100 mock fund records.
- **NFR2 — Privacy:** The academic prototype shall neither request nor store passwords, MyKad numbers, bank account details, or live ASNB credentials.
- **NFR3 — Usability:** At least 4 of 5 test users shall locate the fee information for two selected funds within 3 minutes without help.
- **NFR4 — Accessibility:** Every interactive control shall include a visible label, and keyboard navigation shall display a visible focus indicator.

## Requirement traceability

| Objective | Related requirements |
|---|---|
| Consistent fund comparison | FR2, FR3, FR4, NFR1 |
| Editable savings scenario | FR1, FR5, NFR1 |
| Clear explanations and sources | FR3, FR6, NFR3, NFR4 |
| User control and privacy | FR4, FR6, NFR2 |

The numeric thresholds are proposed acceptance targets for a future prototype. They are not measured results and do not describe the performance of the live myASNB application.
