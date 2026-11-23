
# LabLink — Making College Laboratories More Accessible

A GenAI-powered campus laboratory resource-sharing platform that helps students discover, request, and book specialised equipment, development kits, and laboratory workstations across departments.

## Features

- **Equipment Discovery:** Explore laboratory resources across multiple departments.
- **Smart Hardware Advisor:** Find suitable equipment based on project requirements.
- **Intelligent Slot Booking:** Request equipment and workstation slots.
- **Project-Based Requests:** Submit requests with project details, deadlines, and requirements.
- **Faculty Approvals:** Faculty can review, approve, or reject booking requests.
- **Conflict Resolution:** Weighted allocation logic recommends fair and feasible alternatives when scheduling conflicts occur.
- **Resource Utilisation Analytics:** Monitor equipment usage and availability.
- **Verification Suite:** Built-in checks for functionality, security, and accessibility.

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Gemini API (optional AI-generated explanations)
- Browser session storage

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Ruhan1007/lablinkruhan.git
```

### 2. Open the Project

Open the `index.html` file in a modern web browser.

No additional dependencies are required for the core application.

## AI Integration

LabLink supports optional Gemini API integration to generate natural-language explanations and recommendations.

The core equipment-matching and conflict-resolution functionality can operate without an API key.

For production deployment, API requests should be routed through a secure backend rather than exposing API credentials in browser-side code.

## Security and Accessibility

The prototype includes:
- HTML output escaping to reduce XSS risks.
- Session-based API key storage.
- Accessibility landmarks and interface considerations.
- Input validation and resource allocation checks.
- A built-in verification suite.

**Note:** This is a hackathon prototype. Student and faculty views demonstrate the intended workflows. Production use would require institutional authentication, server-side authorization, persistent database storage, and secure API handling.

## Conflict Resolution

LabLink uses weighted allocation logic to evaluate competing equipment requests based on:
- Project deadlines.
- Equipment availability.
- Student requirements.
- Resource suitability.
- Alternative equipment availability.

The system recommends feasible allocations to improve fairness and resource utilisation.

## Project Scope

The current prototype demonstrates the main LabLink workflows using predefined sample equipment and request data with browser-side application state.

Future enhancements could include:
- Centralised database integration.
- Real-time booking synchronisation.
- Institutional student and faculty authentication.
- Role-based access control.
- Automated notifications.
- Advanced AI-powered scheduling.

## Problem Statement Alignment

| Requirement | LabLink Implementation |
|---|---|
| Equipment discovery | Cross-department equipment registry |
| Intelligent slot booking | Booking request workflow |
| Project-based access | Project requirement submission |
| Faculty approvals | Faculty approval interface |
| Conflict resolution | Weighted allocation and alternative recommendations |
| Resource optimisation | Utilisation analytics |
| GenAI integration | Optional Gemini-powered explanations |

## Running the Project

Open the `index.html` file in a modern browser.

For online hosting, the project can be deployed using Vercel or GitHub Pages.

## License

This project was developed as a hackathon prototype for educational and demonstration purposes.
