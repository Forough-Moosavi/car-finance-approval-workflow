# Car Finance Approval & Reporting Workflow

An end-to-end car finance approval and reporting solution built using Microsoft Power Platform components.

## Overview

This project demonstrates how Microsoft Forms, Power Automate, Excel Online, Outlook, and Power BI can be integrated to automate and monitor a complete car finance approval process.

The solution collects finance applications, generates unique application IDs, routes requests for approval, updates records automatically, notifies applicants of decisions, and provides management reporting through an interactive Power BI dashboard.

---

## Technologies Used

* Microsoft Forms
* Power Automate
* Excel Online
* Outlook
* Approval Actions
* Power BI

---

## Workflow

1. A customer submits a finance application through Microsoft Forms.
2. Power Automate retrieves the submitted response.
3. A unique Application ID is generated automatically.
4. The application is stored in Excel Online.
5. An approval request is sent to the reviewer.
6. The reviewer approves or rejects the application.
7. Excel is updated automatically with:

   * Status
   * Decision Date
8. The applicant receives an automated email notification containing the final decision.
9. Power BI provides real-time reporting and analytics based on application data.

---

## Features

* Automatic Application ID generation
* Excel-based application tracking
* Approval and rejection workflow
* Automated email notifications
* Decision date logging
* End-to-end automation without coding
* Power BI reporting dashboard
* Approval rate monitoring
* Application status analytics
* Priority distribution analysis
* Finance amount reporting

---

## Power BI Dashboard

The project includes an interactive Power BI dashboard connected to the finance application dataset.

### Dashboard KPIs

* Total Finance Amount
* Total Applications
* Approved Applications
* Rejected Applications
* Approval Rate (%)

### Dashboard Visualizations

* Finance Amount by Status
* Application Count by Status
* Application Count by Priority
* Interactive Status Filters
* Interactive Priority Filters

The dashboard provides real-time visibility into application performance, approval trends, and business metrics.

---

## Screenshots

### Application Form

![Application Form](screenshots/application-form.png)

### Power Automate Workflow

![Workflow](screenshots/workflow.png)

### Approval Request Email

![Approval Email](screenshots/approval-email.png)

### Excel Database

![Excel Output](screenshots/excel-output.png)

### Approved Notification

![Approved Email](screenshots/approved-email.png)

### Rejected Notification

![Rejected Email](screenshots/rejected-email.png)

### Power BI Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Business Value

This solution demonstrates how low-code technologies can be used to automate business processes, reduce manual work, improve decision tracking, and provide management visibility through real-time reporting.

---

## Future Improvements

* AI-assisted risk assessment
* Multi-level approval workflow
* Dataverse integration
* Customer portal integration
* Power Apps front-end
* Advanced reporting and forecasting

---

## Author

**Forough S. Moosavi**

---

## Repository Purpose

This repository was created as a portfolio project to demonstrate practical skills in:

* Business Process Automation
* Power Automate
* Microsoft Forms
* Excel Online
* Outlook Integration
* Approval Workflows
* Power BI Reporting
* Low-Code Solutions
