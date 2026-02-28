# CleanCity — System Under Test (Quick Overview)

This document provides a concise overview of the **System Under Test (SUT)** to support execution of the QA artefacts contained in this repository.

The application is included **solely for reproducibility of testing activities** and was not authored or modified as part of this QA case study.

## Application Access Options

### Option 1: Static HTML Version

This option allows immediate interaction with the application without local setup and is suitable for exploratory and manual testing.

**How to run:**
1. Open `index.html` in a modern browser
2. No installation or build steps required

**Limitations:**
- No build tooling
- Limited parity with the React version
- Automation is not supported in this mode

### Option 2: React Application (Recommended)

This option reflects the full application behavior used during manual and automated testing.

**Prerequisites**
- Node.js (LTS recommended)
- npm

**Run locally**

````
bash
npm install
npm start
````

The application will be available at:
```
http://localhost:3000
```

## Known Risk Areas (High-Level)

The following areas were identified as higher risk during test planning and informed exploratory and regression focus:

* Form validation gaps across multiple user flows
* State update inconsistencies after user actions
* Filtering logic producing incorrect results
* Accessibility omissions (e.g. missing alt-text)
* UI feedback not reflecting underlying state changes

Detailed findings and evidence are documented in:

* `tests/manual/defect_report.md`
* `reports/defect-summary.md`

## Browser Coverage

Manual and exploratory testing was executed across:

* Chrome
* Firefox
* Edge

## Test Data Assumptions

The application initializes with mock request data persisted in localStorage.
Sample identifiers referenced in test cases include:

* REQ001
* REQ002
* REQ003
* REQ004
* REQ005

## Related Documentation

* `SETUP_INSTRUCTIONS.md` - detailed environment setup
* Root `README.md` - QA case study narrative
* `tests/` - manual and automated test artefacts
* `reports/` - execution summaries and outcomes