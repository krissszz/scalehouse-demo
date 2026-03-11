# ScaleHouse Management System (Demo)

## Overview

The **ScaleHouse Management System** is a weighbridge management platform designed to handle truck weighing operations, dispatch monitoring, and reporting.

This project demonstrates a **simplified demo version** of a real-world system used to manage truck arrivals, weight measurements, and operational workflows in a weighbridge or scalehouse environment.

⚠️ **Note:**
This repository contains a **demo implementation only**. The original production system includes proprietary business logic and integrations that cannot be publicly shared.

---

## Features

### Truck Weighing Management

* Record **gross weight**, **tare weight**, and **net weight**
* Track incoming and outgoing trucks
* Store truck and driver information

### Dispatch Monitoring

* Manage dispatch records
* Track deliveries and loading status
* Associate trucks with dispatch operations

### Dashboard Monitoring

* Visualize truck arrivals
* Display operational statistics
* Track daily activity

### Reporting

* Generate basic operational reports
* View transaction history
* Export data for analysis

### QR Code Slip Printing (Demo)

* Generate printable slips with QR codes
* Encode transaction references for quick lookup

---

## Demo Scope

This repository demonstrates:

* System architecture
* Frontend interface concepts
* Backend API structure
* Simplified weighing logic
* Mock database records

The following are **intentionally excluded**:

* Internal company APIs
* Authentication systems used in production
* Proprietary business rules and formulas
* Real database schemas
* Production deployment configuration

---

## Tech Stack

**Backend**

* Python
* Django
* REST API

**Frontend**

* HTML
* Bootstrap
* JavaScript
* AJAX

**Database**

* PostgreSQL (Demo schema)

**Other Tools**

* QR Code generation
* Chart dashboards
* API integration examples

---

## Example Workflow

1. Truck arrives at the scalehouse
2. Operator records the **gross weight**
3. Truck unloads or loads cargo
4. Operator records the **tare weight**
5. System calculates **net weight**
6. Transaction is stored and a **QR slip** can be printed

Example simplified logic:

```
Net Weight = Gross Weight - Tare Weight
```

---

## Screenshots

### Dashboard

Shows truck activity and operational statistics.

*(Add screenshot here)*

### Weighing Interface

Form used to record truck weight transactions.

*(Add screenshot here)*

### Dispatch Module

Tracks dispatch operations and truck assignments.

*(Add screenshot here)*

---

## Project Structure (Demo)

```
scalehouse-demo/
│
├── backend/
│   ├── api/
│   ├── models/
│   └── views/
│
├── frontend/
│   ├── dashboard/
│   ├── weighing/
│   └── dispatch/
│
├── screenshots/
│
└── README.md
```

---

## Purpose of This Repository

This repository is intended to demonstrate:

* System design for operational management systems
* Backend and frontend integration
* Dashboard data visualization
* Practical workflow implementation

The goal is to showcase **software architecture and development approach** rather than replicate the full production system.

---

## Future Improvements (Demo)

Planned additions for the demo version:

* Sample API endpoints
* Mock data generator
* Demo dashboard charts
* Example report exports

---

## Author

Developed by **Kristine Venesse Anunsawon**

Background:

* Analyst / Programmer
* Experience building operational systems including:

  * ScaleHouse Management Systems
  * Medical Record Systems
  * Dashboard and reporting tools
  * Data-driven web applications

---

## License

This repository is provided for **portfolio and demonstration purposes only**.
