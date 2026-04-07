# Web Merchant Integration System & Auto Batch Processing

## Note on Source Code Availability
This project is a proprietary enterprise application developed for a fintech organization. Due to confidentiality and intellectual property restrictions, the source code cannot be made public. This repository is intended to present the system design, architecture, and business impact.

---

## Overview
This project involved the complete migration and redesign of a legacy fintech system previously built on .NET 4.6.

The original system was unstable, difficult to maintain, and lacked flexibility for banking operations. I redesigned and rebuilt the platform from scratch using .NET 8, introducing a modern architecture, improved performance, and enhanced configurability.

The system is currently deployed in production and used by multiple banking partners for daily operational workflows.

---

## Impact

- Replaced a legacy system with a stable and scalable .NET 8 architecture  
- Eliminated recurring production issues and improved system reliability  
- Reduced operational workload through improved UI and faster processing  
- Enabled dynamic configurations that were not possible in the previous system  
- Implemented compliance-focused workflows required for banking systems  

---

## Core Features

### Maker-Checker Workflow
- Multi-level approval system (four-eyes principle)  
- Actions must be authorized before execution  

### Role-Based Access Control
- Dynamic user creation and management  
- Granular permission handling  
- Hierarchical role structure  

### Entity Management
- Full lifecycle management for:
  - Auto Batch Services  
  - Merchants and participants  

### Audit Logging
- Complete tracking of system activity  
- Includes user actions, timestamps, and status  
- Export support (CSV/TXT) for compliance  

### Data Validation & Integration
- Real-time validation against AS400 DB2  
- Fail-safe mechanisms for critical operations  

---

## Architecture

The system follows a clean, layered architecture:

- Core / Domain Layer  
- Infrastructure Layer  
- Web Layer (UI)  

Designed for scalability, maintainability, and separation of concerns.

---

## Tech Stack

Backend:
- C# / .NET 8  
- ASP.NET Core (MVC / Razor Pages)  

Database:
- Microsoft SQL Server  
- IBM DB2 (AS400)  

Data Access:
- Stored Procedures  
- Repository Pattern  

---

## Responsibilities

- Led full system redesign and migration from .NET 4.6 to .NET 8  
- Designed application architecture and data flow  
- Implemented backend services and business logic  
- Built user interface and management modules  
- Integrated legacy AS400 DB2 systems with modern architecture  
- Developed security, validation, and audit mechanisms  

---

## Summary
This project demonstrates experience in modernizing legacy enterprise systems, designing scalable architectures, and building secure, production-grade fintech applications.

---

## Disclaimer
This repository is intended for demonstration purposes only. No proprietary source code is included.
