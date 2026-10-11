<div align="center">

# ⚡ Originate Command
### **Unified Operations, Task Board & Instruction Management System**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://fuad2e3.github.io/Originate-Command)
[![Language](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Standard](https://img.shields.io/badge/Spec-OM_SRS_001-purple?style=for-the-badge)](docs/)
[![Architecture](https://img.shields.io/badge/Architecture-Modular_SPA-green?style=for-the-badge)](assets/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**An enterprise operations hub combining live daily todo execution with company policy instructions and automated escalation.**

---

[Explore Features](#-key-features) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Originate Command** is a centralized operations management system built to the **OM SRS 001** enterprise specification. Tailored for agency environments, it bridges the gap between fast-paced daily task execution and high-level corporate governance. By combining a real-time Todo board on the left with an active Instruction/Notice dispatch system on the right, Originate Command ensures that team execution aligns directly with organizational protocol.

---

## ✨ Key Features

- 📋 **Unified Dual-Panel Board:** Simultaneous visibility into actionable daily Todos and mandatory operational Instructions.
- 🏢 **Multi-Department Hierarchy:** Granular Role-Based Access Control (RBAC) across 6 organizational tiers (Leadership, Ops, Marketing, Dev, Creative, Support).
- 🔁 **Automated Task Recurrence:** Automatic regeneration of recurring daily/weekly checklists upon sign-off.
- 🚨 **Automated Incident Escalation:** Smart overdue watchdog that automatically escalates stalled deliverables up the management chain.
- 👥 **Client & Cross-Functional Groups:** Segment workflows by client account and assign multi-department squads.
- 📜 **Immutable Audit Trail:** Comprehensive activity logging tracking creation, state transitions, edits, and supervisor approvals.

---

## 📁 Project Structure

```text
Originate-Command-Demo/
├── assets/
│   ├── css/                    # Glassmorphism tokens & responsive themes
│   └── js/
│       ├── core/               # State management, pub-sub & event bus
│       ├── modules/
│       │   ├── todos/          # Task Kanban, priority scoring & recurrence
│       │   ├── instructions/   # Company notice board & acknowledgments
│       │   └── audit/          # Immutable change logging engine
│       └── utils/              # Storage helpers, date formatting & toasts
├── docs/                       # OM SRS 001 specification & compliance documents
├── index.html                  # Main operations board interface
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend UI** | HTML5, Modern CSS3 Custom Properties, Vanilla ES6+ | High-performance zero-build responsive web app |
| **State Engine** | Custom Reactive Event Store | Fast in-memory state with persistence |
| **Persistence** | LocalStorage API / IndexedDB | Offline resilient caching and local data storage |
| **Typography** | Google Fonts (Inter, Plus Jakarta Sans) | Executive readability and enterprise polish |
| **Architecture** | Component-Driven Modular Vanilla JS | Clean separation of business logic and presentation |

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
