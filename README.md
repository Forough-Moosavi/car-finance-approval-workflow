# Car Finance Approval Workflow

## Overview

This project demonstrates an end-to-end business process automation solution built using Microsoft Power Platform.

The workflow automates the vehicle finance application process from submission to final approval or rejection, reducing manual effort, improving tracking, and providing a structured approval process.

The solution integrates Microsoft Forms, Power Automate, REST APIs, Excel Online, Outlook, Approval Actions, and Power BI into a single automated workflow.

---

## Business Scenario

Many finance application processes rely on manual data entry, email communication, and spreadsheet tracking, which can lead to:

* Processing delays
* Human errors
* Poor visibility of application status
* Inconsistent approval procedures
* Difficult reporting and auditing

This solution automates the entire process and creates a centralized workflow for managing finance applications.

---

## Solution Architecture

```text
Applicant Submission
        ↓
Microsoft Forms
        ↓
Power Automate
        ↓
Generate Application ID
        ↓
REST API Request
        ↓
Parse JSON Response
        ↓
Store in Excel Online
        ↓
Email Notification
        ↓
Approval Request
        ↓
Approve / Reject Decision
        ↓
Update Application Status
        ↓
Power BI Reporting
```

---

## Workflow Features

### Application Intake

Applicants submit requests through a Microsoft Form.

Collected information includes:

* Applicant Name
* Email Address
* Vehicle Model
* Requested Finance Amount

### Automatic Application ID Generation

Each application receives a unique identifier for tracking.

Example:

```text
APP-20260605-145453
```

### REST API Integration

Power Automate sends an HTTP request to an external API to retrieve additional user information.

The API response is returned in JSON format and automatically processed.

Retrieved fields include:

* Office Location
* User Email
* Surname
* User Profile Information

### JSON Parsing

API responses are parsed using the Parse JSON action, allowing structured extraction of required fields.

### Excel Online Database

Applications are automatically stored and updated in Excel Online.

Stored information includes:

* Application ID
* Applicant Details
* Finance Amount
* Status
* Priority
* Notes
* API Data

### Automated Email Notifications

Email notifications are automatically sent throughout the process.

Examples:

* Application submitted
* Application approved
* Application rejected

### Approval Workflow

Applications are routed to an approver using Microsoft Approval Actions.

Approvers can:

* Review application details
* Approve applications
* Reject applications
* Provide comments

### Conditional Processing

The workflow uses decision-based branching to perform different actions based on approval outcomes.

Examples:

* Approval email notification
* Rejection email notification
* Status update in Excel
* Audit trail creation

### Power BI Reporting

Application data can be visualized through Power BI dashboards to monitor:

* Application volumes
* Approval rates
* Rejection rates
* Total requested finance amounts
* Processing performance

---

## Technologies Used

| Technology       | Purpose                    |
| ---------------- | -------------------------- |
| Microsoft Forms  | Application collection     |
| Power Automate   | Workflow automation        |
| REST API         | Data enrichment            |
| Parse JSON       | Structured data extraction |
| Excel Online     | Application database       |
| Outlook          | Email notifications        |
| Approval Actions | Decision management        |
| Power BI         | Reporting and dashboards   |

---

## Screenshots

### Workflow Overview

End-to-end Power Automate workflow.

### Approval Dashboard

Approval and rejection management interface.

### Excel Database

Automated application tracking and status management.

### Power BI Dashboard

Reporting and business analytics.

---

## Skills Demonstrated

* Business Process Automation
* Microsoft Power Automate
* REST API Integration
* HTTP Requests
* JSON Parsing
* Excel Online Integration
* Outlook Automation
* Approval Workflows
* Conditional Logic
* Data Management
* Process Design
* Business Reporting
* Power BI Dashboard Development

---

## Future Enhancements

Potential improvements include:

* Multi-level approval workflows
* AI-assisted application assessment
* Risk scoring engine
* SharePoint integration
* Dataverse integration
* Automated fraud detection
* Applicant self-service portal
* Advanced Power BI analytics

---

## Author

**Forough Moosavi**

Data Analyst | Business Intelligence | Process Automation

LinkedIn:
https://www.linkedin.com/in/forough-s-moosavi

---

## License

This project is provided for educational and portfolio purposes.
