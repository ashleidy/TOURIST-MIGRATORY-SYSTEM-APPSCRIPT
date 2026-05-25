# Tourist Information Collection System

This project is a **Tourist Information Collection System** developed as a custom **Google Apps Script Web Application** designed for promoters and operational staff working at transit entry points such as airports and docks. The platform enables the controlled registration, validation, and management of tourist arrival information directly through **Google Sheets** as a cloud-based backend infrastructure.

The system was created to optimize the collection of tourism statistics, reduce manual registration errors, improve operational control, and provide secure role-based access for field personnel and administrators.

---

# System Architecture

The application follows a **client-server architecture** based on the Google Apps Script ecosystem:

- **Frontend Layer (JavaScript):**  
  Handles dynamic interfaces, input validation, modal workflows, UI state management, session tracking, and interactive user controls.

- **Backend Layer (Google Apps Script):**  
  Executes server-side operations through `google.script.run`, processes data, validates users, manages permissions, and performs CRUD operations directly inside Google Sheets.

- **Cloud Data Layer (Google Sheets):**  
  Functions as the operational database storing:
  - Tourist records
  - User accounts
  - System catalogs
  - Cities and countries
  - Lodging references
  - Operational logs

---

# Main Features

## Tourist Registration Workflow
- Two-step controlled registration process
- Arrival context validation (airport or dock)
- Batch tourist registration system
- Real-time field validation
- Session-based tourist accumulation

## Security & Authentication
- SHA-256 client-side password hashing
- Role-based access control
- Secure session management
- User permission segregation
- Administrative account controls

## Operational Modules
- Tourist registration and monitoring
- Personal daily activity logs
- Administrative dashboards
- Multi-role operational views
- Dynamic catalog verification
- Country and city validation systems

## Dynamic UI Logic
- Conditional forms based on nationality
- Automatic field visibility management
- Input restrictions and validation
- Real-time catalog filtering
- Interactive modal interfaces

---

# Roles & Permissions

| Role | Access Level | Capabilities |
|---|---|---|
| ADMIN | Full System Access | User administration, visibility control, account management |
| ADMIN-INVITADO | Extended Access | Operational supervision and profile modifications |
| USUARIO | Restricted Access | Tourist registration and personal activity review |

---

# Technologies Used

- Google Apps Script
- JavaScript
- HTML/CSS
- Google Sheets API
- Web Crypto API (SHA-256)
- Google Script Run API

---

# Purpose of the Project

The main objective of this system is to digitalize and standardize tourism information collection processes at transit checkpoints while maintaining data consistency, operational traceability, and secure cloud-based storage.

The platform was specifically designed to improve:
- Tourism statistics collection
- Data validation processes
- Operational efficiency
- Registration reliability
- Administrative visibility
- Real-time data centralization

---

# Additional Notes

This application is a custom operational solution developed specifically for tourism control workflows and checkpoint registration environments. The system prioritizes lightweight cloud infrastructure, accessibility, and real-time synchronization using Google Workspace technologies instead of traditional database servers.
