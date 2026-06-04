# Car Finance Approval Workflow

An end-to-end approval workflow built using Microsoft Power Platform components.

## Overview

This project demonstrates how Microsoft Forms, Power Automate, Excel Online, and Outlook can be integrated to automate a complete approval process.

The workflow collects car finance applications, generates unique application IDs, routes requests for approval, updates records automatically, and notifies applicants of the final decision.

---

## Technologies Used

- Microsoft Forms
- Power Automate
- Excel Online
- Outlook
- Approval Actions

---

## Workflow

1. User submits a finance application through Microsoft Forms.
2. Power Automate retrieves the form response.
3. A unique Application ID is generated automatically.
4. The application is stored in Excel Online.
5. An approval request is sent to the reviewer.
6. The reviewer approves or rejects the application.
7. Excel is updated automatically with:
   - Status
   - Decision Date
8. The applicant receives an email notification with the final decision.

---

## Features

- Automatic Application ID generation
- Excel-based application tracking
- Approval / Rejection workflow
- Automated email notifications
- Decision date logging
- End-to-end automation without coding

---

## Screenshots

### Application Form

![Application Form](screenshots/form.png)

### Power Automate Workflow

![Workflow](screenshots/flow.png)

### Approval Request Email

![Approval Email](screenshots/approval-email.png)

### Excel Database

![Excel Output](screenshots/excel-output.png)

### Approved Notification

![Approved Email](screenshots/approved-email.png)

### Rejected Notification

![Rejected Email](screenshots/rejected-email.png)

---

## Future Improvements

- Power BI dashboard integration
- Application analytics
- Multi-level approvals
- AI-assisted risk assessment
- Dataverse integration

---

## Author

Forough Moosavi
