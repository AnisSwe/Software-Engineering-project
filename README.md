# 🌾 AgriConnect — Connecting Micro Entrepreneurs With Farmers

![Platform](https://img.shields.io/badge/Platform-Web-green)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![University](https://img.shields.io/badge/University-AIUB-blue)
![Semester](https://img.shields.io/badge/Semester-Spring%202024--25-yellowgreen)

> A web-based agricultural marketplace that eliminates middlemen by directly connecting farmers, consumers, and micro-entrepreneurs — empowering rural communities through technology.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [User Roles](#user-roles)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Project Planning](#project-planning)
- [Team](#team)

---

## 🧩 About the Project

**AgriConnect** is a full-stack web platform designed to revolutionize agricultural commerce in Bangladesh. It gives farmers a direct channel to sell produce, purchase farming supplies, and access expert agricultural advice — all without intermediaries. Consumers can browse fresh produce, place orders, track deliveries, and rate products. Admins oversee platform integrity through user verification, product pricing controls, and financial reporting.

The platform is built for scalability and rapid iteration based on user feedback, with the core mission of making farming more profitable and efficient for everyone involved.

---

## ✨ Key Features

### 🔐 Authentication
- Secure user registration with OTP verification
- Role-based login (Farmer / Consumer / Admin)
- Password reset via registered email or phone
- "Remember Me" persistent session support

### 🛒 Consumer Module
- Browse categorized agricultural products with images, prices, and availability
- Keyword search and filter-based product discovery
- Shopping cart with quantity management
- Multi-payment checkout: Cash on Delivery, bKash/Nagad/Rocket, Online Banking (DBBL)
- Order tracking, invoice generation, and order cancellation
- Star-based product rating and written review system

### 🌱 Farmer Module
- Personal dashboard with at-a-glance metrics (orders, earnings, pending payments)
- Order management: place, track, and manage supply orders
- Product listing: list agricultural produce for direct sale to consumers
- Transaction history with filtering by date and type
- Expert support request booking (consultation slot scheduling)
- Marketplace access for seeds, fertilizers, and farming supplies

### 🛠️ Admin Module
- Dashboard with platform-wide statistics (users, transactions, top products)
- User management: search, filter, and verify farmer/consumer accounts (NID-based)
- Product management: set minimum price and quantity limits per category
- Financial report generation and Excel export
- Role-based admin creation (Director, GM, Collector) with permission assignment

---

## 👥 User Roles

| Role | Description |
|------|-------------|
| **Farmer** | Lists produce, buys supplies, books expert consultations |
| **Consumer** | Browses products, places orders, rates purchases |
| **Admin** | Manages users, products, reports, and platform settings |
| **Expert** | Provides agricultural advice to farmers (via support system) |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Server-side web framework |
| Database | Relational Database (structured schema) |
| Payments | bKash API, DBBL Nexus Gateway |
| Testing | Black-Box Testing methodology |
| Version Control | Git |

---

## 🗂️ System Architecture

The WBS (Work Breakdown Structure) covers 7 major phases:

```
AgriConnect
├── 1.1 Project Planning       (Goals, Requirements, Budget, Risk, Schedule)
├── 1.2 Design                 (Auth, Prototype, Architecture, DB Schema, UI/UX, OOAD)
├── 1.3 Development            (Features, Backend, Frontend, DB Connection, Security)
├── 1.4 Testing                (Requirement Analysis, Test Cases, Execution, Reports)
├── 1.5 Integration            (Deployment, Handover, Feedback, Documentation, Patches)
├── 1.6 Marketing              (Market Analysis, Social Media, Email, Demo Videos)
└── 1.7 Support                (Feedback Analysis, Maintenance, Training)
```

---

## 📊 Project Planning

### COCOMO Estimation

| Metric | Value |
|--------|-------|
| Source Lines of Code (estimated) | 5,000 SLOC |
| Effort (PM) | **13.00 person-months** |
| Development Time (DM) | **6.63 months** |
| Required Staff | **~2 people** |

### Earned Value Analysis (EVA)

| Metric | Value |
|--------|-------|
| BAC (Budget at Completion) | 521 person-days |
| BCWS (Planned Value) | 457 |
| BCWP (Earned Value) | 443 |
| ACWP (Actual Cost) | 451 |
| **SPI** (Schedule Performance Index) | **0.97** |
| **CPI** (Cost Performance Index) | **0.98** |
| Schedule Variance (SV) | -14 person-days |
| Cost Variance (CV) | -8 person-days |
| % Work Scheduled | 87.71% |
| % Work Completed | 85.02% |

### Project Timeline (Gantt)

| Phase | Period |
|-------|--------|
| Project Planning | May 2025 |
| Design | June 2025 |
| Development | July – August 2025 |
| Testing | September 2025 |
| Integration | September – October 2025 |
| Marketing | October 2025 |
| Support | November 2025 |

### Key Risks Identified

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| Customer changes requirements | 80% | Medium | Agile methods + change control process |
| Lack of training on tools | 80% | High | Early training + mentors |
| Test coverage insufficient | 75% | High | TDD + coverage benchmarks |
| Improper auth & access control | 70% | Medium | Secure coding + penetration testing |
| Less reuse than planned | 70% | Medium | Identify reusable components early |

---

## 👨‍💻 Team

| Name | Student ID | Contributions |
|------|------------|---------------|
| Ishan, Ibnul Ishtiak | 22-49545-3 | UI/UX (Admin), Test Cases, WBS, Gantt Chart, EVA |
| Siddique, Md Abu Bakar | 22-48322-3 | UI/UX (Auth), Test Cases, COCOMO, EVA, Risk Management |
| Md. Ibtihazaman | 22-49153-3 | UI/UX (Consumer), Test Cases, Gantt Chart, EVA, Risk Management |
| Md. Anisur Rahman | 22-49553-3 | UI/UX (Farmer), Test Cases, Gantt Chart, COCOMO, Risk Management |

---

## 🏫 Academic Info

- **University:** American International University-Bangladesh (AIUB)
- **Department:** Computer Science, Faculty of Science & Technology
- **Course Outcome:** CO4 — Software Project Management
- **Semester:** Spring 2024–25 | Section H | Group 01

---

> *"Empowering Farmers, Connecting Communities"*
