# Technical report template — Ryan Epperly

> **Internal authoring template.** Do not publish a report as complete until the underlying analysis has been checked. Do not call a personal technical report "peer reviewed" without an actual external peer-review process.

## Cover page

- **Project title:** [Descriptive engineering title]
- **Author:** Ryan Epperly
- **Affiliation:** Virginia Tech, Aerospace Engineering (student)
- **Date and version:** [YYYY-MM-DD, v1.0]
- **Report type:** Independent technical report / student engineering project
- **Code and data:** [Repository or archive links, where release is permitted]
- **Disclosure note:** [Confirm any institutional, employer, or sponsor restrictions before publishing]

## Abstract (150–250 words)

State the engineering problem, scope, methods, evidence-based result(s), limitations, and main conclusion. Write only after results are finalized.

## 1. Problem statement and motivation

What question does this study address? Why is it important? Define quantitative objectives and scope boundaries.

## 2. Background and sources

Summarize governing theory and prior work with traceable references. Check each citation against the actual publication (authors, date, title, DOI).

## 3. Mathematical model

Define coordinates, state variables, units, governing equations, assumptions, and parameter values.

| Parameter | Meaning | Value | Units | Source |
| --- | --- | --- | --- | --- |
| [parameter] | [definition] | [value] | [SI unit] | [reference] |

## 4. Numerical or experimental methodology

State procedures, computational environment, solver/integration schemes, initial conditions, boundary conditions, random seeds, measurement models, and input datasets. Link to code or reproducibility materials if permitted.

## 5. Verification and validation

- **Verification:** Show that the implementation solves the equations as intended (units, convergence, conservation checks, benchmarks, expected special cases).
- **Validation:** Compare the model to appropriate external evidence, if available. Do not conflate a plausible graph with validation.
- **Uncertainty:** Discuss measurement noise, model-form uncertainty, parameter sensitivity, and failure modes.

## 6. Results

Present numbered figures and tables with labeled axes and units. Explain all results and distinguish calculated outcomes from assumptions, forecasts, and illustrative examples. Never invent metrics.

## 7. Discussion and limitations

Explain what the model demonstrates, what it does not establish, and any simplifying assumptions or safety implications.

## 8. Conclusion and future work

Summarize supported findings and propose concrete follow-up experiments or code improvements.

## References

Use a consistent bibliographic format. Cite datasets, reference models, software documentation, and papers that were actually consulted.

## Appendix: reproducibility checklist

- [ ] Script or method version and dependencies recorded
- [ ] Inputs, units, and source data documented
- [ ] Random seeds saved where relevant
- [ ] Plots traceable to the reported runs
- [ ] Claims checked against calculations
- [ ] All references verified
- [ ] Confidentiality and disclosure review completed
- [ ] AI editorial assistance disclosed accurately, if used

## Suggested AI-use disclosure

"AI tools assisted with editing and document formatting. The author reviewed the resulting text and verified the engineering calculations, references, and technical conclusions."

Use this only when it accurately describes the work.