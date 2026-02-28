# CleanCity — QA Case Study (Web Platform)

**Role:** QA Engineer (Manual + Automation)  
**System Type:** Web-based application  
**Focus:** Functional testing • Regression • Defect reporting • Risk-based automation  

## Overview

This repository presents a **QA case study** demonstrating end-to-end quality assurance execution against a real-world-style web application.

The objective of this case study is to showcase **how QA decisions are made and communicated**, including:

- Structured manual testing
- Exploratory testing and risk discovery
- Clear, actionable defect reporting
- Judicious use of test automation
- Professional QA reporting to stakeholders

> This repository represents **QA execution**, not application development.

## Testing Scope

### In Scope
- Functional testing
- Exploratory testing
- Regression testing
- Cross-browser validation (Chrome, Firefox, Edge)
- UI-level automation for critical paths

### Out of Scope
- Backend/API testing
- Performance testing
- Security testing
- CI/CD integration
- Mobile testing

## QA Strategy & Approach

Testing followed a **risk-based strategy**, prioritizing:

- Core user journeys
- Data validation and persistence
- State transitions and UI feedback
- Error handling and usability risks

Manual testing was conducted first to establish:
- System understanding
- Defect baselines
- Risk concentration areas

Automation was introduced selectively for **stable, high-value flows** where regression risk justified the maintenance cost.

## Repository Structure
```
cleancity-qa-case-study/
├── app/ # System Under Test (unmodified)
├── tests/
│ ├── manual/ # Test plan, cases, defects, exploration
│ └── automation/ # Cypress and Jest suites
├── reports/ # Execution summaries and QA sign-off
└── README.md
```

## Manual Testing

Manual testing focused on:

- Input validation and boundary conditions
- Data persistence and state updates
- Filtering and conditional rendering
- Error messaging and negative scenarios
- Basic accessibility and usability signals

All test cases were designed to be:
- Reproducible
- Traceable to observed behavior
- Written for clarity and execution efficiency

---

## Defect Reporting

Defects were documented with emphasis on:
- Clear reproduction steps
- Expected vs. actual behavior
- Severity and user impact

The intent was **actionability**, not defect volume.

---

## Test Automation

Automation was implemented to validate:
- Critical user flows
- Regression-prone functionality

### Tooling
- **Cypress** — End-to-end UI validation
- **Jest** — Component and logic-level checks

Automation scope was intentionally constrained to balance:
- Stability
- Maintenance cost
- Execution value

Rationale is documented in `tests/automation/automation-scope.md`.

---

## Reporting & Outcomes

Testing concluded with:
- Test execution reporting
- Defect summaries
- QA sign-off highlighting risks and recommendations

These artefacts demonstrate how QA outcomes are communicated to **product teams and stakeholders**.

---

## Notes

- This repository represents **QA execution only**
- The application under test was not authored or modified
- All findings are based solely on observed system behavior

---

## Author

**Mpumelelo Theophilas Nxazonke**  
QA Engineer • SDET  
South Africa  

---

## License

MIT License  
Educational and portfolio use only