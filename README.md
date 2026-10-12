# Nexora IT Service Desk & Asset Management System

An enterprise-style IT service desk solution built with Microsoft Power Apps, Dataverse and Power Automate to manage IT support tickets, track assets and automate service workflows.

## Project Overview

Nexora simulates an organisation's internal IT support environment. Employees can raise support tickets, IT agents can manage and resolve incidents, and managers can monitor ticket activity through an operational dashboard.

## Business Objectives

- Centralise IT support requests and ticket management.
- Track IT assets and their allocation to employees.
- Automate ticket creation, assignment and resolution notifications.
- Standardise ticket handling through a Business Process Flow.
- Improve visibility of ticket priorities, statuses and unassigned work.
- Organise business data using related Dataverse tables.

## Key Features

- **Ticket Management:** Track tickets through New, Triage, Assigned, In Progress, Resolved and Closed.
- **Asset Management:** Maintain IT asset records, asset types, serial numbers and assignment details.
- **Automated Notifications:** Send email notifications for new tickets, assignments and resolutions.
- **Business Process Flow:** Guide ticket progression through defined stages.
- **Security Roles:** Configure separate Employee, IT Agent and IT Manager roles.
- **Operational Dashboard:** Display tickets by status and priority, active tickets, unassigned tickets, and high- or critical-priority tickets.

## Technology Stack

- Microsoft Power Apps — model-driven application
- Microsoft Dataverse — relational data storage
- Microsoft Power Automate — workflow automation and email notifications
- Business Process Flows — structured ticket lifecycle
- GitHub — project documentation and portfolio presentation

## Data Model

The solution uses seven core Dataverse tables:

1. Department
2. Employee
3. Asset Type
4. IT Asset
5. Ticket Category
6. IT Ticket
7. Ticket Update

Relationships connect employees to departments, tickets to requesters and assigned agents, assets to asset types and employees, and tickets to their updates.

## Dashboard

The Nexora IT Operations Dashboard includes:

- Tickets by Status
- Tickets by Priority
- Active IT Tickets
- Unassigned IT Tickets
- High/Critical Priority IT Tickets

Screenshots and supporting documentation will be added to this repository.

## Project Documentation

The repository will include an overview of the architecture, data model, automation flows, business process flow, security configuration and testing evidence.

## Testing and Limitations

Core notification flows and the ticket lifecycle were tested in the development environment. Some lifecycle stages and role-based access scenarios still require additional verification. Independent testing with separate user accounts has not been fully completed.

This project is a portfolio simulation using fictional company and employee data. It is not a production IT service management deployment.

## Author

**Abayomi Ali**

Power Platform | Business Applications | Process Automation

