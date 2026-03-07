# 💰 Friendzon – Financial Management System

## 📌 Project Overview

**Friendzon** is a comprehensive **financial management and loan servicing desktop application** designed to manage the complete lifecycle of micro-finance and lending operations.

The system is built using a **hybrid JavaFX + Spring Boot architecture**, combining a modern desktop UI with a powerful backend service layer.

Friendzon helps financial organizations efficiently manage:

* Customers and agents
* Loan origination and lifecycle
* EMI schedules and collections
* Partner investments and deals
* Expenses and company balances
* Employee salaries
* Payment transactions
* Profit and loss reporting
* SMS notifications and OTP services
* Backup and operational utilities

The project follows **enterprise-level architecture practices** including layered design, modular services, and reusable utility frameworks.

⚠️ **Important Notice**

This repository is intended to showcase the **system architecture, features, and screenshots** of the application.

The **complete production source code is maintained in a private repository** to protect the intellectual property and proprietary implementation.

---

# 🖥️ Application Screenshots

Screenshots below illustrate different modules of the Friendzon system.

*(You can replace or add more screenshots as new modules evolve.)*

## Login Screen

<img src="screenshots/login.png" width="650">

Secure authentication interface supporting encrypted passwords and role-based access.

---

## Dashboard Overview

<img src="screenshots/dashboard.png" width="700">

The dashboard provides a quick overview of the entire financial system including:

* Loan statistics
* Customer counts
* Financial summaries
* System status indicators

---

## Customer Management

<img src="screenshots/customer.png" width="700">

Customer management allows administrators to maintain customer profiles and address records.

---

## Loan Management

<img src="screenshots/loan.png" width="700">

Loan management handles loan creation, editing, lifecycle control, and loan state tracking.

---

## EMI Management

<img src="screenshots/loan-emi.png" width="700">

The EMI module tracks repayment schedules, overdue payments, and EMI reporting.

---

## Partner Management

<img src="screenshots/partner.png" width="700">

Partners and investment stakeholders can be managed through the partner module.

---

## Payment Transactions

<img src="screenshots/payment-transaction.png" width="700">

All financial transactions including collections and settlements are recorded here.

---

## Reports

<img src="screenshots/reports.png" width="700">

The reporting system generates operational and financial insights.

---

# 🚀 Core Functional Modules

Friendzon includes a large set of enterprise-level features covering financial operations.

## 🔐 Authentication & Security

* Secure login screen
* BCrypt password hashing
* Role-driven access flow (Admin / Agent)
* Change password functionality
* Profile management dialog

---

## 🏠 System Navigation

* Home screen navigation
* Dashboard overview screen
* Dashboard card widgets
* Modular screen routing via controllers

---

## 👥 Customer & Agent Management

* Customer management module
* Customer add/edit operations
* Customer search and listing
* Customer address dialog management
* Agent management module
* Agent session handling

---

## 💰 Loan Management

* Loan creation / origination
* Loan edit and update workflows
* Loan lifecycle management
* Active / Closed / Defaulted loan states
* Loan report summaries
* Loan settlement management
* Loan default handling dialog
* Settlement utilities support

---

## 📆 EMI & Repayment Management

* EMI schedule generation
* Loan EMI management screen
* EMI report generation
* Overdue EMI report generation
* Monthly loan report generation
* Collection amount reporting

---

## 💳 Transaction & Payment Management

* Payment transaction management
* Payment method tracking
* Payment status tracking
* Transaction type classification
* Collection management

---

## 🏦 Financial Management

* Company balance management
* Backdated balance calculation control
* Expense management module
* Expense form workflow
* Expense type classification
* Employee salary management
* Salary dialog workflow
* Investment management module
* Investment reporting

---

## 🤝 Partner & Investment Management

* Partner management module
* Partner deal management
* Partner deal workflow
* Down-payment migration utilities

---

## 📊 Reporting & Analytics

* Profit and loss reporting
* Account reporting screen
* Consolidated financial reports
* EMI reports
* Overdue reports
* Monthly loan reports

---

# 📤 Export & Print Features

* PDF export support (iText)
* Excel export support (Apache POI)
* Print/export utilities
* Header and footer injection for reports
* Printable financial reports

---

# 💬 SMS & Notification System

Friendzon includes a built-in SMS infrastructure.

Features include:

* SMS sending service
* SMS HTTP client integration
* SMS request builder pipeline
* SMS scheduler for background tasks
* Failed SMS retry mechanism
* OTP service support
* Redis integration for OTP/SMS storage

---

# 💾 Backup & Data Management

* Backup service implementation
* Configurable backup system
* Backup configuration utilities
* Scheduled data protection support

---

# 🧠 Technical Architecture

Friendzon uses a **hybrid desktop architecture** combining Spring Boot with JavaFX.

```
JavaFX UI (FXML)
       ↓
Controller Layer
       ↓
Service Layer
       ↓
Repository Layer (Spring Data JPA)
       ↓
SQLite Database
```

This architecture ensures:

* clean separation of concerns
* maintainable modular code
* scalable business logic

---

# 🧩 Technical Features & Infrastructure

The system includes multiple infrastructure-level capabilities.

## Application Core

* Spring context integration with JavaFX
* Spring-aware FXML loader
* Centralized application constants
* Application startup database initialization

---

## Persistence Layer

* Embedded SQLite database
* Hibernate SQLite dialect configuration
* Externalized database path support
* Spring Data JPA repositories

---

## Utility Framework

* Shared date utilities
* Custom date picker utilities
* Dialog utility framework
* TableView utility framework
* Editable table column helpers
* Default button behavior utilities
* Database exception utilities
* Data change tracking utilities
* Audit helper utilities

---

## Workflow & Domain Utilities

* Enum-based loan action workflows
* Standardized reporting contracts
* Settlement workflow helpers
* Partner migration utilities

---

## Infrastructure Utilities

* Async processing configuration
* Scheduler configuration
* SMS status repository
* SMS status domain model
* Repository layers for each financial domain

---

## UI System

* CSS-based JavaFX styling
* Modular FXML screen structure
* Dialog-driven UI architecture

---

# 🛠 Technology Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Hibernate

### Desktop UI

* JavaFX
* FXML
* CSS

### Database

* SQLite

### Messaging

* SMS HTTP API
* Redis (OTP and SMS state)

### Reporting

* iText (PDF export)
* Apache POI (Excel export)

### Build System

* Maven
* Maven Wrapper

---

# 📂 Screenshot Folder Structure

Create a folder inside the repository:

```
/screenshots
```

Example structure:

```
Friendzon
 ├── README.md
 └── screenshots
      ├── login.png
      ├── dashboard.png
      ├── dashboard-cards.png
      ├── customer.png
      ├── customer-form.png
      ├── agent.png
      ├── loan.png
      ├── loan-emi.png
      ├── overdue-emi.png
      ├── partner.png
      ├── partner-deal.png
      ├── investment.png
      ├── expense.png
      ├── reports.png
      └── profit-loss.png
```

Recommended **15 screenshot names**:

```
login.png
dashboard.png
dashboard-cards.png
customer.png
customer-form.png
agent.png
loan.png
loan-emi.png
overdue-emi.png
partner.png
partner-deal.png
investment.png
expense.png
reports.png
profit-loss.png
```

---

# 👨‍💻 Author

**Rezaul Karim Khan**

Software Engineer
Java • Spring Boot • Full Stack Development

🌐 Portfolio
https://rezaul.online

💻 GitHub
https://github.com/rezaul-code

🔗 LinkedIn
https://linkedin.com/in/rezaul-khan

---

# 💼 Commercial Availability

Friendzon is available for **commercial licensing and deployment**.

For business inquiries, custom development, or deployment assistance, please contact the author.

---

# ⭐ Support

If you find this project interesting, please **star the repository** ⭐
