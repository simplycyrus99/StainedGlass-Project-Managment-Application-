# Gamberini Stained Glass Restoration Workflow System

[![Project Status: Documentation Phase](https://shields.io)](#)
[![Tech Stack: Flask + SQLite/Postgres](https://shields.io)](#)
[![License: Educational](https://shields.io)](#)

## 📌 Project Overview
A comprehensive software engineering project to design and implement a digital workflow management system for a 3rd-generation stained glass restoration studio in Bologna, Italy. This repository serves as the central documentation hub for the project's planning, requirements engineering, and design phases, replacing an inefficient paper-based workshop process with a structured, web-based application.

The system was engineered for the **"European Heritage Innovation" call (Grant Agreement No. CE-2026-DH-0123)** to ensure traceability, minimize administrative overhead, and fulfill rigorous EU reporting obligations.

---

## 🖼️ User Interface Preview
*(Uncomment the line below and update the path once the file is uploaded to your repo)*
<!-- ![Gamberini Main Dashboard Mockup](8.2%20UI.drawio.png) -->

---

## 📂 Repository Contents
This repository contains all major deliverables created during the Software Development Lifecycle (SDLC) planning phase:

| File Name | Category | Description |
| :--- | :--- | :--- |
| 📄 **`1. full_project_charter_complete.docx`** | Management | Formal project charter outlining scope, deliverables, budget (€48,000), risk analysis, WBS, and resource allocation. |
| 📄 **`3. SRS_Gamberini_StainedGlass.docx`** | Requirements | Software Requirements Specification (SRS) defining functional (REQ-01 to REQ-11) and non-functional (REQ-12) requirements. |
| 📊 **`3. Gamberini_Gantt_Chart.xlsx`** | Scheduling | 24-week (6-month) software development lifecycle schedule from requirements gathering to final delivery. |
| 📊 **`3.1stained_glass_restoration_gantt.xlsx`** | Operations | Operational physical workflow schedule (site inspection, restoration, re-installation) that the software manages. |
| 📄 **`5. Sample use case.docx`** | Design | Detailed use case (`UC_02: Record damage assessment`) showcasing actor actions, system responses, and business rules. |
| 📄 **`7. Testing_Methodology_and_Test_Cases.docx`** | Quality | Testing strategy and sample test cases (e.g., `TC-EU-01` for EU grant report validation). |
| 📄 **`8.1User manual.docx`** | Documentation | Step-by-step user manual draft for the "Record Damage Assessment" module, optimized for restorers. |
| 🎨 **`8.2 UI.drawio.png`** | Design | Interface mockup showcasing order lists, search, filtering, and responsive UI layouts. |

---

## 🚀 Key System Features
*   **Order Management:** Create, track, and close restoration orders with detailed physical object descriptions.
*   **Damage Assessment:** Record structured damage logs (cracks, lead fatigue, paint loss) with up to 5 photographic uploads.
*   **Automated Inventory:** Real-time consumption tracking of workshop materials (glass, lead, solder) deducted automatically per order.
*   **Role-Based Access Control (RBAC):** Strict permission separation between `admin` and `restorer` roles.
*   **EU Compliance Reporting:** One-click CSV generation capturing cost breakdowns (materials and labor) required for Creative Europe auditing.
*   **Client Deliverables:** Automated PDF exports summarizing order details and restoration lifecycles for clients.

---

## 🛠️ Planned Technology Stack
*   **Backend:** Python 3.x / Flask Framework
*   **Database:** SQLite (Local Development) / PostgreSQL (Production)
*   **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5 (Tablet-first responsive layout for workshop environments)
*   **Architecture:** Multi-tier client-server application deployed **on-premise** to comply fully with GDPR guidelines.

---

## 📈 Quantified Business Impact
*   **70% reduction** in manual administrative paperwork per restoration order.
*   **100% data traceability** of historic objects from initial workshop intake to final delivery.
*   **Zero-friction compliance** via automated generation of EU-mandated cost-utilization reports.
*   **Accessible design** engineered for low digital literacy, optimized for tablet interaction directly on the restoration bench.

---

## 🎓 Academic Context & Metadata
*   **Institution:** DHDK (Digital Humanities and Knowledge), University of Bologna
*   **Course:** B1874 — Project Management and Software Engineering for Cultural Heritage
*   **Author:** Kourosh "Cyrus" Shahbazi
*   **Date:** May 2026

## 📜 License
This repository is compiled strictly for educational review and project evaluation. Commercial reproduction, distribution, or deployment of these planning artifacts without explicit permission is prohibited.
