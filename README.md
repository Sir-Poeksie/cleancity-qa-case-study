# 🧪 CleanCity — QA Case Study (Web Platform)

**Role:** QA Engineer (Manual + Automation)
**Scope:** Web-based application
**Focus:** Functional testing • Regression • Bug reporting • Test automation

## Overview

This repository contains a QA case study for CleanCity, a web-based application used as a test subject to demonstrate professional QA execution.

The purpose of this project is to showcase:

- Manual testing approach
- Test planning and execution
- Clear defect reporting
- Risk-based automation decisions
> This is a QA artefact, not an application development project.

## Testing Scope

### In Scope

* Functional testing
* Regression testing
* Exploratory testing
* Cross-browser testing (Chrome, Firefox, Edge)
* UI-level automation (critical paths)

### Out of Scope

* Backend testing
* Performance testing
* Security testing
* CI/CD integration
* Mobile testing

## QA Approach

Testing was conducted using a risk-based strategy, focusing on:

- Core user flows
- Data validation
- State changes
- Error handling
- Usability risks

Manual testing was executed first to establish system understanding and defect baselines.
Automation was introduced selectively for stable, high-value user journeys.

## Repository Structure
```
cleancity-qa-case-study/
├── app/                     # Original application (unmodified)
├── tests/
│   ├── manual/
│   │   ├── test-plan.md
│   │   ├── test-cases.md
│   │   ├── exploratory-notes.md
│   │   └── defect-report.md
│   └── automation/
│       ├── cypress/
│       ├── jest/
│       └── automation-scope.md
├── reports/
│   ├── test-execution-report.md
│   ├── defect-summary.md
│   └── qa-summary.md
└── README.md
```

## Manual Testing

Manual testing focused on:

- User input validation
- Data persistence
- Filtering and state updates
- Error messaging and edge cases
- Basic accessibility and usability signals

Test cases were designed to be:

- Clear
- Reproducible
- Traceable to observed behavior

## Defect Reporting

Defects were logged with:

- Clear reproduction steps
- Expected vs actual behavior
- Severity and impact assessment

The goal was clarity and actionability, not volume.

## Test Automation

Automation was implemented to validate:

- Critical user flows
- Regression-prone functionality

### Tooling

- **Cypress** — End-to-end testing
- **Jest** — Component-level validation

Automation intentionally avoids full coverage in favor of:

- Stability
- Maintenance cost awareness
- Execution value

See `automation-scope.md` for rationale.

## Reporting & Outcomes

Testing concluded with:

- Test execution report
- Defect summary
- QA sign-off summary highlighting risks and recommendations

These artefacts reflect how QA results are communicated to **stakeholders and product teams**.

## Notes

- This project represents **QA execution only**
- The application under test was not authored by the QA engineer
- All findings are based on observed system behavior

## Author

**Mpumelelo Theophilas Nxazonke**
<br/>QA Engineer • SDET
<br/>South Africa

## License

MIT License
Educational and portfolio use only
