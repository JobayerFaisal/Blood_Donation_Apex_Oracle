<div align="center">

# 🩸 Heart2Blood
### Emergency Blood Donation Management System

*Connecting blood donors with recipients — saving lives, one request at a time.*

![Oracle APEX](https://img.shields.io/badge/Oracle-APEX-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-Database-336791?style=for-the-badge&logo=oracle)
![License](https://img.shields.io/github/license/JobayerFaisal/Blood_Donation_Apex_Oracle?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/JobayerFaisal/Blood_Donation_Apex_Oracle?style=for-the-badge)

</div>

---

## 📋 Table of Contents
- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [System Architecture](#-system-architecture)
- [Demo](#-demo)
- [Getting Started](#-getting-started)
- [Database Schema](#-database-schema)
- [Project Report](#-project-report)
- [Team](#-team)

---

## 🔎 About

**Heart2Blood** is a web-based Blood Donation Management System built on **Oracle APEX** and **Oracle Database (PL/SQL)**. The platform bridges the gap between blood donors and recipients by enabling real-time donor discovery, blood requests, and emergency coordination.

Developed as a CSE347 (Information System Analysis & Design) project at **East West University**, Fall 2024.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔐 **Authentication** | Secure sign-up, login, and logout with role-based access |
| 🔍 **Donor Search** | Search donors by blood group and geographic area |
| 🩸 **Rare Blood Tracker** | Dedicated section for rare blood type donors |
| 🏥 **Blood Bank & Hospital Directory** | Browse nearby blood banks and hospitals with contact info |
| 📋 **Blood Request System** | Submit, track, and manage blood requests with patient profiles |
| ⭐ **Donor Rating & Feedback** | Rate and review donors after interactions |
| 💳 **Payment Gateway** | Support for transportation fees and fund donations (credit card & bKash) |
| 🔔 **Notifications** | Automated alerts for blood requests and emergencies |
| 👥 **Social Organizations** | View blood donation events from social organizations |
| 📞 **Contact & Helpline** | In-app helpline, email, and social media integration |

---

## 🛠 Tech Stack

- **Frontend/UI:** Oracle APEX (Application Express)
- **Backend:** PL/SQL, Oracle Database
- **Modeling:** UML (Use Case, Class, Sequence, State Machine, Activity Diagrams)
- **Architecture:** Multi-tier web application with role-based access control

---

## 🏗 System Architecture

The system follows a three-tier architecture:

User Device (Browser/Mobile)
↓
Application Server (Oracle APEX)
↓
Application Database (Oracle DB)


Three roles are supported: **Donor**, **General User (Recipient)**, and **Admin** — each with distinct access controls and capabilities.

---

## 🎬 Demo

> 📹 A full **12-minute walkthrough** of the system — covering all major features including authentication, donor search, blood requests, payment, and admin management.

[▶ Watch Full Project Demo](https://drive.google.com/file/d/1PG_3vc8WyON3YcedBxCF4MlWxc0ytlMM/view?usp=drive_link)

---

## 🚀 Getting Started

### Prerequisites
- Oracle Database 19c or later (or Oracle XE)
- Oracle APEX 22.x or later
- A web browser

### Installation

1. **Clone the repository**
```bash
  git clone https://github.com/JobayerFaisal/Blood_Donation_Apex_Oracle.git
  cd Blood_Donation_Apex_Oracle
  
  2. **Import the SQL schema**
     - Open Oracle SQL Developer or SQL*Plus
     - Connect to your Oracle database
     - Run the SQL script:
```sql
@Blood_Donation.sql

----
```

3. **Set up Oracle APEX**
   - Log in to your APEX workspace
   - Import the application file (if provided) via **App Builder → Import**
   - Configure your database connection

4. **Launch the app**
   - Navigate to your APEX instance URL
   - Register as a Donor or General User to get started

---

## 🗃 Database Schema

Key entities in the system:

- `UserInfo` — Core user table (donors and recipients)
- `DonorInfo` — Donor-specific data (blood group, location, contacts)
- `DonorHealthInfo` — Health status and eligibility tracking
- `PatientInfo` — Patient profiles for blood requests
- `RecepientInfo` — Recipient user details
- `DonationStatus` — Tracks donation events and feedback
- `Notification` — System notifications
- `Feedback` — Ratings and reviews
- `Location` — Area/district data for search

---

## 📄 Project Report

The full Software Requirements Specification (SRS) report covers:
- Inception & stakeholder analysis
- Requirements elicitation (QFD, usage scenarios)
- Use case diagrams (18 use cases)
- Class diagram, DFD, State Machine, Sequence diagrams
- Deployment architecture

[📎 View Full SRS Report (PDF)](https://drive.google.com/file/d/1sTAJQdCi93AgrCPnUt_J739GSYmt6nZP/view?usp=sharing)
---

## 👨‍💻 Team

| Name | Student ID |
|---|---|
| Jobayer Faisal Fahim | 2022-2-60-130 |
| Shafiqul Islam Fahim | 2022-2-60-085 |
| Akash Saha | 2022-2-60-084 |
| Abrar Hossain Zahin | 2022-2-60-040 |
| Sadman Riyan | 2021-2-60-107 |

**Supervised by:** Anika Tabassum, Lecturer, Dept. of CSE, East West University

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ by Team Heart2Blood — East West University, Fall 2024
</div>









