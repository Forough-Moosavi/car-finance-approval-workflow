# Car Finance Approval Workflow

## Overview

This project demonstrates an end-to-end business process automation solution built using Microsoft Power Platform.

The workflow automates the car finance application process from submission to approval decision, email notification, data enrichment, Excel tracking, and Power BI reporting.

The solution integrates Microsoft Forms, Power Automate, Microsoft Graph API, Excel Online, Outlook, Approval Actions, and Power BI into one automated workflow.

---

## Business Problem

Manual finance application processing can involve:

- Repetitive data entry
- Approval delays
- Email back-and-forth communication
- Poor visibility of application status
- Inconsistent decision tracking
- Limited reporting capability

This project solves these issues by automating the full application and approval process.

---

## Solution Architecture

```text
Microsoft Forms
       ↓
Power Automate
       ↓
Get Response Details
       ↓
Generate Application ID
       ↓
Microsoft Graph API / HTTP Request
       ↓
Parse JSON Response
       ↓
Store Data in Excel Online
       ↓
Send Email Notification
       ↓
Start Approval Process
       ↓
Approve / Reject Decision
       ↓
Update Excel Status
       ↓
Power BI Dashboard
```

---

## Technologies Used

| Technology | Purpose |
|----------|----------|
| Microsoft Forms | Application submission |
| Power Automate | Workflow automation |
| Microsoft Graph API | User information retrieval |
| HTTP Request | API communication |
| Parse JSON | API response processing |
| Excel Online | Application database |
| Outlook | Email notifications |
| Approval Actions | Approval and rejection process |
| Power BI | Reporting and dashboarding |

---

## Key Features

- Automated finance application intake
- Unique Application ID generation
- Microsoft Graph API integration
- JSON response parsing
- Automated Excel database update
- Approval and rejection workflow
- Automated email notifications
- Status and decision date tracking
- Power BI dashboard for reporting
- End-to-end low-code business automation

---

## REST API and Data Enrichment

The workflow uses an HTTP request to retrieve user profile information through Microsoft Graph API.

The API response is parsed using the Parse JSON action and selected fields are stored in Excel Online.

Retrieved API data includes:

- User profile information
- Office location
- User email
- Surname

This demonstrates practical use of:

- REST API integration
- HTTP requests
- JSON parsing
- Automated data enrichment
- Power Automate API workflows

---

## Screenshots

### Application Form

![Application Form](screenshots/form.png)

---

### Power Automate Workflow

![Power Automate Workflow](screenshots/flow-overview.png)

---

### Approval Request

![Approval Request](screenshots/approval-workflow.png)

---

### Excel Application Database

![Excel Application Database](screenshots/excel-output.png)

---

### Processed Application Results

![Processed Application Results](screenshots/excel-results.png)

---

### Approval Email

![Approval Email](screenshots/approved-email.png)

---

### Rejection Email

![Rejection Email](screenshots/rejected-email.png)

---

### Power BI Dashboard

![Power BI Dashboard](screenshots/dashboard.png)

---

## Skills Demonstrated

- Business Process Automation
- Microsoft Power Automate
- Microsoft Forms Integration
- Microsoft Graph API Integration
- REST API Integration
- HTTP Requests
- JSON Parsing
- Excel Online Integration
- Outlook Automation
- Approval Workflow Design
- Conditional Logic
- Data Tracking
- Power BI Reporting
- Business Intelligence
- Low-Code Development

---

## Business Benefits

- Reduces manual processing
- Improves approval tracking
- Centralizes application data
- Automates applicant communication
- Improves reporting and visibility
- Creates a repeatable approval process
- Supports business decision monitoring

---

## Future Enhancements

Potential future improvements include:

- AI-assisted application assessment
- Risk scoring engine
- Multi-level approvals
- Dataverse integration
- SharePoint integration
- Applicant self-service portal
- Automated fraud checks
- Advanced Power BI analytics
- Python-based analytics reporting

---

## Author

**Forough Moosavi**

Data Analyst | Business Intelligence | Process Automation

LinkedIn:  
https://www.linkedin.com/in/forough-s-moosavi

---

## License

This project is provided for educational, demonstration, and portfolio purposes.
