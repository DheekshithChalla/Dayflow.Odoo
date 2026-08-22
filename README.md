# Dayflow.Odoo
# 🏢 Dayflow — Human Resource Management System (HRMS)
> *"Every workday, perfectly aligned."*

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Status: Production-Ready](https://img.shields.io/badge/Status-Production--Ready-emerald.svg)]()
[![Platform: Web](https://img.shields.io/badge/Platform-Web-blue.svg)]()

**Dayflow HRMS** is a modern, responsive, and full-featured Human Resource Management System designed to digitize and streamline core HR operations including onboarding, profile management, attendance tracking, leave requests & approval workflows, and payroll visibility.

---

## ✨ Key Modules & Capabilities

### 🔐 1. Authentication & Role-Based Access Control (RBAC)
- **Sign In & Sign Up**: Role-based onboarding for **Employees** and **Admin / HR Officers**.
- **⚡ 1-Click Fast Demo Login**: Switch roles seamlessly between HR Admin and Employee to test workflows instantly.
- **Session & Role Persistence**: Stateful storage with real-time UI adaptation based on active privileges.

### 📊 2. Dual Dedicated Dashboards
- **Employee Dashboard**:
  - Quick-action cards: My Profile, Attendance Timesheet, Leave Requests, and Salary Slip.
  - Live clock-in / clock-out status with active working session timer.
  - Weekly hours tracked interactive bar chart.
  - Leave balances overview (Paid, Sick, Casual).
- **Admin / HR Officer Dashboard**:
  - Organization KPI metrics (Total Workforce, Present Today %, Pending Approvals, Monthly Payroll).
  - Live pending leave requests queue with 1-click **Approve** (with confetti celebration 🎉) and **Reject** (with reason prompt).
  - Real-time workforce attendance feed across departments.
  - **Employee Context Switcher**: Inspect any employee's profile, attendance, and salary details.

### 👤 3. Employee Profile Management
- **Personal Details**: Full Name, Email, Phone, Residential Address, Emergency Contact, Date of Birth.
- **Job Details**: Employee ID, Designation, Department, Reporting Manager, Employment Type, Joining Date.
- **Salary Structure**: Detailed breakdown of Basic Pay, HRA, Special Allowance, PF deduction, Tax TDS, and Net Take-Home.
- **Verified Documents**: PDF document repository for Employment Contracts, ID proofs, and Tax forms.
- **Permission Matrix**:
  - *Employees*: Can edit contact info (Phone, Address, Emergency Contact, Profile Photo).
  - *Admin / HR*: Full modification rights across all organizational, job, and compensation fields.

### ⏱️ 4. Attendance & Time Tracking
- **Interactive Punch Clock**: Real-time Check-In / Check-Out toggle with automatic duration calculation.
- **Weekly Timesheet & Daily Log Views**: Comprehensive Monday–Sunday shift breakdowns and status tags (`Present`, `Late`, `Half-day`, `Leave`, `Weekend`).
- **CSV Export**: 1-click export of workforce attendance data for administrative records.

### 🌴 5. Leave & Time-Off Management
- **Leave Application Engine**: Support for Paid Leave, Sick Leave, Casual Leave, and Unpaid Leave with date range pickers and duration counters.
- **Automated Approvals Workflow**: Admin approval updates employee records and attendance status in real time.

### 💰 6. Payroll & Salary Administration
- **Organization Salary Registry**: Overview of gross earnings, statutory deductions, and net payouts.
- **Authentic Printable Pay Slip**:
  - Company header, employee data, detailed earnings vs. deductions table, and net amount in words.
  - Integrated **Print / Save as PDF** support.

### 📈 7. Analytics & Notification Center
- **Visual Analytics**: Interactive Chart.js graphs for 6-month attendance trends and department salary budget distribution.
- **Real-time Alert Hub**: Interactive notification tray with unread counters and animated toast alerts.

---

## 🔑 Demo Credentials

| Role | Email | Password | Pre-Configured Access |
|---|---|---|---|
| 👑 **Admin / HR Officer** | `admin@dayflow.io` | `password123` | Full HR administrative control & approvals |
| 💻 **Senior Engineer** | `alex@dayflow.io` | `password123` | Employee self-service & timesheet |
| 🎨 **Design Lead** | `priya@dayflow.io` | `password123` | Employee self-service & timesheet |
| ⚡ **DevOps Architect** | `marcus@dayflow.io` | `password123` | Employee self-service & timesheet |
| 🧪 **QA Specialist** | `elena@dayflow.io` | `password123` | Employee self-service & timesheet |

---

## 🚀 Running Locally or in GitHub Codespaces

### 1. Run with Node.js
```bash
# Start the built-in server
node server.js