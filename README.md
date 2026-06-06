# Car Finance Approval Workflow

## Overview

This project demonstrates a complete end-to-end business process automation solution built using Microsoft Power Platform.

The workflow automates the car finance application process from submission through approval, decision notification, Excel tracking, API enrichment, and Power BI reporting.

The solution integrates Microsoft Forms, Power Automate, Microsoft Graph API, Excel Online, Outlook, Approval Actions, and Power BI into a single automated business workflow.

---

## Business Problem

Manual finance application processing often involves:

- Repetitive data entry
- Approval delays
- Email back-and-forth communication
- Limited visibility into application status
- Inconsistent tracking
- Difficult reporting and analytics

This project addresses these challenges by automating the entire approval lifecycle.

---

## Solution Architecture

```text
Microsoft Forms
       ↓
Get Response Details
       ↓
Generate Application ID
       ↓
Microsoft Graph API
       ↓
Parse JSON Response
       ↓
Store Data in Excel Online
       ↓
Manager Approval Request
       ↓
Approve / Reject Decision
       ↓
Update Excel Status
       ↓
Applicant Notification Email
       ↓
Power BI Dashboard
```

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Microsoft Forms | Application collection |
| Power Automate | Workflow automation |
| Microsoft Graph API | User profile retrieval |
| HTTP Requests | API communication |
| Parse JSON | Response processing |
| Excel Online | Application database |
| Outlook | Email notifications |
| Approval Actions | Decision management |
| Power BI | Reporting and analytics |

---

## Workflow Features

### Automated Application Intake

Applications are collected through Microsoft Forms and processed automatically.

### Unique Application ID Generation

Every submission receives a unique identifier.

Example:

```text
APP-20260605-145453
```

### Microsoft Graph API Integration

The workflow automatically retrieves:

- User name
- Email
- Office location
- Surname

using Microsoft Graph API and stores the information in Excel.

### Automated Approval Process

Applications are routed automatically to reviewers.

### Approval & Rejection Handling

The workflow supports both approval and rejection paths with automatic updates.

### Email Notifications

Applicants receive automated emails once a decision is made.

### Excel Tracking

All applications are stored and updated automatically.

### Power BI Reporting

Business dashboards provide real-time visibility into application activity.

---

# Process Walkthrough

## Step 1 — Finance Application Form

Applicants submit their finance requests using Microsoft Forms.

![Application Form](screenshots/form.png)

---

## Step 2 — Power Automate Workflow

The workflow retrieves form responses, generates Application IDs, enriches data through Microsoft Graph API, and stores records in Excel.

![Workflow Overview](screenshots/flow-overview.png)

---

## Step 3 — Approval Workflow

The application is automatically routed to a reviewer for approval or rejection.

![Approval Workflow](screenshots/approval-workflow.png)

---

## Step 4 — Manager Approval Request

The reviewer receives an approval request containing the application details.

![Approval Request](screenshots/approval-email.png)

---

## Step 5 — Application Database

Application data is stored automatically in Excel Online.

![Excel Database](screenshots/excel-output.png)

---

## Step 6 — Enriched Application Records

The workflow enriches application data using Microsoft Graph API and updates records automatically.

![Excel Results](screenshots/excel-results .png)

---

## Step 7 — Applicant Approval Notification

If approved, the applicant receives an automatic approval email.

![Approved Email](screenshots/approved-email.png)

---

## Step 8 — Applicant Rejection Notification

If rejected, the applicant receives an automatic rejection email.

![Rejected Email](screenshots/rejected-email.png)

---

## Step 9 — Power BI Dashboard

Business users can monitor applications, approval rates, rejection rates, and trends through Power BI.

![Power BI Dashboard](screenshots/dashboard.png)

---

## Skills Demonstrated

- Business Process Automation
- Microsoft Power Automate
- Microsoft Forms Integration
- Microsoft Graph API
- REST API Integration
- HTTP Requests
- JSON Parsing
- Excel Online Integration
- Outlook Automation
- Approval Workflows
- Conditional Logic
- Data Tracking
- Power BI Reporting
- Business Intelligence
- Low-Code Development

---

## Business Benefits

- Reduced manual effort
- Faster approval processing
- Automated communication
- Centralized application tracking
- Improved reporting visibility
- Scalable business workflow

---

## Future Enhancements

Potential future improvements include:

- Multi-level approvals
- AI-assisted application assessment
- Risk scoring engine
- Dataverse integration
- SharePoint integration
- Automated fraud detection
- Applicant self-service portal
- Advanced Power BI analytics
- Python-based reporting automation

---

## Author

**Forough Moosavi**

Data Analyst | Business Intelligence | Process Automation

LinkedIn:

https://www.linkedin.com/in/forough-s-moosavi

---

## License

This project is provided for educational, demonstration, and portfolio purposes.
