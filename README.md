# project-documentation
Central repository for all project documents: SRS, Test Plan, Design Documents, etc.

## Project

**Restaurant Management System** — a web-based application for managing table bookings, food ordering, and menu management for a single restaurant outlet.

- **Backend:** Python (Django REST Framework)
- **Real-time layer:** Node.js (WebSocket / Socket.io) for live order-status updates
- **Author:** Abhay Dubey H (PES1UG24CS551), Dept. of Computer Science and Engineering, PES University

## Repository Structure

```
project-documentation/
├── SRS/
│   └── SRS - Restaurant Management System.docx
├── Test-Plan/
├── Design-Documents/
└── README.md
```

## Documents

| Document | Status | Description |
|---|---|---|
| Software Requirements Specification (SRS) | ✅ Added | Functional & non-functional requirements, system features (Table Booking, Menu Management, Ordering & Tracking, Auth), and requirement traceability matrix. |
| Test Plan | 🔲 Pending | Test strategy, test cases, and acceptance criteria mapped to SRS requirements (REQ-1 → REQ-14). |
| Design Documents | 🔲 Pending | Architecture diagram, ER diagram, and API/interface specifications. |

## Conventions

- **File naming:** `<Document Type> - <Project Name>.<ext>` (e.g. `SRS - Restaurant Management System.docx`).
- **Revision history:** every document should carry its own Revision History table for tracked changes.
- **Traceability:** requirement IDs introduced in the SRS (`REQ-1` … `REQ-14`) should be reused as-is in the Test Plan and Design Documents so items stay traceable across all three.
- **Format:** `.docx` for formal deliverables; `.md` acceptable for lighter-weight or working documents.

## Status

| Milestone | Status |
|---|---|
| SRS drafted and reviewed | ✅ Complete |
| Test Plan | 🔲 Not started |
| Design Documents | 🔲 Not started |
