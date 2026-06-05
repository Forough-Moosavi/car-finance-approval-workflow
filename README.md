# Car Finance Approval Workflow

## Overview

This project demonstrates a complete end-to-end business process automation solution built using Microsoft Power Platform.

The solution automates the car finance application process from submission to final decision, reducing manual work, improving tracking, and ensuring a consistent approval workflow.

The project integrates Microsoft Forms, Power Automate, Excel Online, Outlook, and Power BI into a single automated workflow.

---

## Business Problem

Manual finance application processing often involves:

- Repetitive data entry
- Email back-and-forth communication
- Approval delays
- Lack of visibility into application status
- Difficult reporting and tracking

This solution addresses these challenges by creating a fully automated approval process.

---

## Solution Architecture

The workflow performs the following steps:

1. Applicant submits a finance application using Microsoft Forms.
2. Power Automate retrieves the submitted information.
3. A unique Application ID is generated automatically.
4. Application details are stored in Excel Online.
5. An approval request is sent to the reviewer.
6. Reviewer approves or rejects the application.
7. Excel records are automatically updated.
8. Applicant receives an email notification with the final decision.
9. Power BI provides reporting and analytics on submitted applications.

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Microsoft Forms | Application collection |
| Power Automate | Workflow automation |
| Excel Online | Application database |
| Outlook | Email notifications |
| Approval Actions | Decision management |
| Power BI | Reporting and dashboarding |

---

## Workflow Features

### Automated Application Intake

Applications are collected through a structured Microsoft Form and processed automatically.

### Unique Application ID Generation

Each submission receives a unique identifier for tracking and reporting.

Example:

APP-20260605-145453

### Automated Approval Process

Applications are routed automatically to an approver without manual intervention.

### Approval and Rejection Handling

The workflow supports:

- Approval
- Rejection

with automatic status updates.

### Email Notifications

Applicants receive automated notifications after a decision is made.

### Excel-Based Tracking

All applications are stored centrally and updated automatically.

### Business Reporting

Power BI dashboards provide visibility into:

- Application volumes
- Approval rates
- Rejection rates
- Total requested finance amounts
- Priority distribution

---

# Process Flow

```text
Application Form
       ↓
Power Automate
       ↓
Generate Application ID
       ↓
Store in Excel
       ↓
Approval Request
       ↓
Approve / Reject
       ↓
Update Excel
       ↓
Notify Applicant
       ↓
Power BI Dashboard
```

---

## Screenshots

### Application Form

![Application Form](screenshots/form.png)

Applicant-facing form used to submit finance requests.

---

### Power Automate Workflow

![Workflow](screenshots/flow.png)

End-to-end workflow built using Microsoft Power Automate.

---

### Approval Request Email

![Approval Request](screenshots/approval-email.png)

Approval request automatically delivered to the reviewer.

---

### Excel Application Database

![Excel Output](screenshots/excel-output.png)

Centralized application tracking and status management.

---

### Approved Notification

![Approved Email](screenshots/approved-email.png)

Automatic approval notification sent to applicants.

---

### Rejected Notification

![Rejected Email](screenshots/rejected-email.png)

Automatic rejection notification sent to applicants.

---

### Power BI Dashboard

![Power BI Dashboard](screenshots/dashboard.png)

Interactive dashboard for monitoring application activity and approval performance.

---

## Key Skills Demonstrated

- Business Process Automation
- Microsoft Power Automate
- Microsoft Forms Integration
- Excel Online Integration
- Outlook Automation
- Approval Workflows
- Process Design
- Workflow Development
- Data Tracking
- Dashboard Development
- Power BI Reporting

---

## Potential Enhancements

Future versions may include:

- Multi-level approvals
- Risk scoring engine
- AI-assisted application assessment
- Dataverse integration
- SharePoint integration
- Automated fraud checks
- Applicant self-service portal
- Advanced Power BI analytics

---

## Author

**Forough Moosavi**

Data Analyst | Business Intelligence | Process Automation

LinkedIn:
https://www.linkedin.com/in/forough-s-moosavi

---

## License

This project is provided for educational and portfolio purposes.
