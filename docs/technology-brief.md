# Technology Brief: Decision Support System

## Concept

A Decision Support System (DSS) helps a person examine a choice by organising relevant data, applying transparent models or rules, and presenting alternatives through an interactive interface. It supports judgement rather than replacing the decision maker. For MyASNB Compare and Plan, official fund information would provide the data, user selections would provide the decision context, and simple models and rules would produce comparisons and explanations. The investor would remain responsible for the final choice.

This is a conceptual, knowledge-driven DSS with explainable assistance. It does not use a trained machine-learning model, connect to a real ASNB account, or claim to produce investment recommendations.

## Proposed architecture

```mermaid
flowchart LR
    A[Official fund information] --> B[Source date and field validation]
    C[User goal and selections] --> D[Scenario and comparison models]
    B --> D
    B --> E[Eligibility and explanation rules]
    D --> F[Compare and Plan interface]
    E --> F
    F --> G[Investor reviews evidence and decides]
```

1. **Data layer:** verified published fund attributes and official document links.
2. **Model layer:** comparison logic and an illustrative savings calculation.
3. **Knowledge layer:** eligibility, missing-data, and explanation rules.
4. **Interface layer:** side-by-side information, assumptions, warnings, and sources.
5. **Decision maker:** the user reviews the evidence and makes the final decision.

## Suitable methods

### 1. Multi-criteria comparison

Different options can be examined across criteria such as fee clarity, goal alignment, risk compatibility, price type, and eligibility. A rigorous Multi-Criteria Decision Analysis (MCDA) requires carefully defined criteria, justified scoring, stakeholder input, and sensitivity analysis. The simple weighted example below is therefore an educational illustration, not a formal fund rating or complete MCDA exercise.

### 2. What-if analysis

A scenario model can show how changing a monthly contribution, saving period, or hypothetical rate changes an illustrative result. The interface should separate total contributions from hypothetical growth, show every assumption, and state that the result is not a forecast.

### 3. Knowledge-based rules

Visible rules can explain eligibility conditions, missing values, and why two fields differ. A rule should use verified information and state its reason. When evidence is unavailable, the system should direct the user to an official source rather than invent a value.

## Illustrative worked example

The following options, scores, and weights are fictional and are used only to demonstrate a transparent calculation.

| Criterion | Weight | Option A | Option B |
|---|---:|---:|---:|
| Fee information clarity | 40% | 4/5 | 3/5 |
| Alignment with savings goal | 35% | 4/5 | 5/5 |
| Risk compatibility | 25% | 3/5 | 4/5 |
| **Weighted result** | **100%** | **3.75/5** | **3.95/5** |

- Option A: `(0.40 × 4) + (0.35 × 4) + (0.25 × 3) = 3.75`
- Option B: `(0.40 × 3) + (0.35 × 5) + (0.25 × 4) = 3.95`

Option B scores higher under these invented assumptions, but the system should expose the underlying information and allow the user to question whether the criteria and weights reflect their priorities.

## Fit to the problem

The DSS approach fits because the proposed problem involves comparing several attributes, exploring assumptions, and explaining trade-offs. Its main benefits are a consistent comparison, visible assumptions, source links, and user control.

Important limitations and risks include:

- **Stale or incomplete data:** outdated fields could mislead users, so every field needs a source and date.
- **False certainty:** a scenario or score can look predictive, so hypothetical output must be labelled and explained.
- **Privacy and security:** a classroom prototype should not request credentials or financial identifiers.
- **Over-reliance:** users may treat a comparison highlight as advice even when it is only decision support.

## Alternative

A simpler alternative is a well-organised directory of official factsheets with a glossary. It would be easier to maintain and would reduce calculation risk, but users would still compare documents and work through scenarios themselves. The interactive DSS concept is worth exploring if future validation shows that the added complexity improves understanding.

## Sources used in this brief

See [References](references.md) for the verified source list. The main conceptual sources are Sprague (1980), the UK government MCDA guidance (2024), NIST IR 8312 (2021), ISO 9241-210:2019, official ASNB pages, and the Securities Commission Malaysia unit trust guidelines.
