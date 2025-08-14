# TESDA-ICTO Asset Inventory & Lifespan Tracking System

## 📌 Overview

The **TESDA-ICTO Asset Inventory & Lifespan Tracking System** is a centralized platform for managing ICT-related assets within TESDA.  
It ensures **accurate tracking, accountability, and lifecycle monitoring** of assets — from acquisition to disposal — improving transparency, compliance, and operational efficiency.

---

## 🎯 Objectives

- **Centralized Asset Database** – Maintain accurate, real-time ICT asset records.
- **Utilization & Maintenance Tracking** – Support allocation decisions, preventive maintenance, and timely replacements.
- **Regulatory Compliance** – Align with COA, DBM, DICT, and internal TESDA audit requirements.
- **Accountability** – Assign custodians and track movement across locations.

---

## 👥 Stakeholders

| Type      | Stakeholder                        | Role & Responsibility                    |
| --------- | ---------------------------------- | ---------------------------------------- |
| Primary   | TESDA Employees                    | View/update assigned assets              |
| Primary   | Procurement Division Encoder       | Register/update asset details            |
| Primary   | ICTO – ITOD System Administrator   | Manage system, users, and asset database |
| Secondary | ICTO – Programmer                  | Develop and maintain the system          |
| Secondary | ICTO – Information Systems Analyst | Document processes and manuals           |
| Tertiary  | COA / DBM / DICT                   | Compliance report access                 |
| Tertiary  | TESDA EXECOM & Board               | Dashboard and summary report access      |

---

## 🛠 Features

- **Role-Based Access Control** (Admin, Encoder, Employee)
- **Asset Registration** with QR/Barcode Tagging
- **Automated Lifespan Calculation** & Maintenance Alerts
- **Location & Accountability Tracking**
- **Advanced Search & Filtering**
- **Photo Attachments for Asset Records**
- **Repair & Maintenance History**
- **Replacement & Warranty Alerts**
- **Reporting & Analytics Dashboard**
- **Mobile & Desktop Compatibility**

---

## 📋 In Scope

- ICT Asset Registration & Classification
- Location & Custodian Tracking
- Lifecycle & Depreciation Monitoring
- Repair & Maintenance History Logging
- Condition & Status Updates
- Alerts & Preventive Maintenance Notifications
- Role-Based Access Control
- Reporting & Analytics

### 🚫 Out of Scope

- Tracking of non-ICT assets
- Procurement process automation
- Disposal approval workflows

---

## 🖥 User Roles

- **System Administrator** – Full access, configuration, and maintenance.
- **Encoder** – Register and update asset records.
- **Employee/User** – View and give feedback on assigned assets.
- **Auditor/External Agency** – Read-only access for compliance checks.

---

## 📜 Forms & Templates

- **ICT Materials Accountability Agreement** (ICTO-ITOD F01)
- **Asset Transfer Request Form** (ICTO-ITOD F02)

---

## 🛠 Development & Planning Process

The project follows TESDA ICTO’s **10-Step Project Planning Process**:

1. Review Initiation Deliverables
2. Define Project Scope
3. Requirements Gathering & Analysis
4. Identify Resources & Roles
5. Develop Work Breakdown Structure (WBS)
6. Create Project Schedule
7. Risk Assessment & Mitigation
8. Budget Planning
9. Communication & Governance Plan
10. Planning Sign-Off

---

## 📂 Repository Structure

```plaintext
.
├── docs/                # Documentation and manuals
├── src/                 # Application source code
├── database/            # Migrations, seeders, and schema
├── public/              # Public assets (images, scripts)
├── tests/               # Automated tests
└── README.md            # Project documentation
```
