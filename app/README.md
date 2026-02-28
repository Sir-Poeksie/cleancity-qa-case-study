# CleanCity: Waste Pickup Scheduler

> ⚠️ **Important**  
> This application is included solely as a **System Under Test (SUT)** to support the QA artefacts in this repository.  
> The QA engineer did not author or modify the application code.

A web-based waste pickup scheduling application used as a controlled system for demonstrating professional QA execution. The application simulates public and administrative user flows and contains known limitations and inconsistencies relevant to testing scenarios.

## Purpose

The application provides a realistic surface for evaluating:

- Multi-page user flows
- Form validation and error handling
- State management and persistence
- UI accessibility and usability signals
- Filtering and data presentation logic
- Administrative workflows
- Responsive behavior across viewports

## Application Overview

### Key Pages

1. **Home (`/`)**
   - Waste pickup request form
   - Client-side validation behavior

2. **Dashboard (`/dashboard`)**
   - View and filter pickup requests
   - Status indicators and table rendering

3. **Feedback (`/feedback`)**
   - Submit reports for missed pickups
   - Request ID validation behavior

4. **Awareness (`/awareness`)**
   - Educational content
   - Image-based layout (accessibility review)

5. **Admin (`/admin`)**
   - Request status management
   - UI state updates and persistence

## Technology Stack

- **Frontend:** React 18
- **Routing:** React Router DOM
- **Styling:** CSS
- **Data Layer:** localStorage (no backend)
- **Test Framework (included):** React Testing Library

## Setup & Execution

### Prerequisites

- Node.js (LTS)
- npm

### Local Execution

```
npm install
npm start
```

The application will be available at:
```
http://localhost:3000
```

## Known Limitations & Risk Areas

The application exhibits behavior that informed QA focus areas, including:

* Incomplete or inconsistent form validation
* Filtering logic producing incorrect results
* UI state not updating immediately after actions
* Accessibility gaps (e.g. missing alt attributes)
* Edge-case handling for long or invalid inputs

These behaviors are documented through:

* Manual test cases
* Exploratory notes
* Defect reports

## Data Characteristics

* Mock pickup requests (REQ001–REQ005)
* Multiple locations and statuses
* Persisted via browser storage

## License

This application is included for educational and portfolio demonstration purposes.