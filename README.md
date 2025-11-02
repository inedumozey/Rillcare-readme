# 🏥 **RillCare: Modern Hospital Management System (HMS) — UI/UX Design Brief**

This document provides a comprehensive guide for the **UI/UX design team** to develop the **Figma mockups** for the three main RillCare systems:

- 🌍 **Public Landing Site**
- 🏢 **Hospital Tenant Application**
- 🛠️ **Internal Admin System**

---

## 🎯 **1. Project Overview**

RillCare is a modern hospital management system designed to bring **efficiency, trust, and simplicity** to healthcare operations.  
The UI/UX should emphasize **clarity**, **accessibility**, and **seamless navigation** across all system modules.

---

## ⚙️ **2. System-Wide UX Principles**

| **Principle**               | **Guideline**                                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------------------------- |
| ♿ **Accessibility**        | Ensure high contrast, logical tab order, and screen-reader support.                                        |
| ⚡ **Speed**                | Prioritize fast, lightweight layouts with minimal visual clutter.                                          |
| 🔁 **Feedback**             | Every interaction (clicks, form submissions, actions) should have clear success, error, or loading states. |
| 🌙 **Dark Mode** | Consider a dark mode variant for dashboards, especially for long clinical use.                             |

---

## 🌐 **3. System I — Public Landing Pages**

**Goal:** Attract hospitals, showcase RillCare’s value, and drive **tenant account creation**.  
**URL:** `https://xxxxxxxx.com`

---

### 🏠 3.1 Home Page (Single-Scroll Layout)

| **Section**             | **Content Requirements**                                                              | **Design Notes**                                |
| ----------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------- |
| 🔝 **Navigation Bar**   | Sticky navigation with links: Home, Services, About Us, Partners, Feedback, Packages. | Include prominent CTA: **Login / Get Started**. |
| 💡 **Hero Section**     | Headline and Value Proposition.                                                       | Prominent CTA: **Create Tenant Account**.       |
| 🩺 **Services Section** | Highlight system benefits (EMR, Financial Efficiency, Data Security).                 | Use consistent iconography.                     |
| 👥 **About Us**         | Brief mission and vision statement.                                                   | Include team or professional imagery.           |
| 🤝 **Partners Section** | Grid or carousel displaying partner logos.                                            | Optionally show “Joined: Month YYYY”.           |
| 💬 **Feedback Section** | 3–5 testimonials from hospitals or users.                                             | Include name and title.                         |
| ⚓ **Footer**           | Standard footer with legal links and contact info.                                    | Include social media handles.                   |

---

### 📦 3.2 Auxiliary Pages

| **Page**              | **Purpose**                                      | **Design Notes**                                            |
| --------------------- | ------------------------------------------------ | ----------------------------------------------------------- |
| 💼 **Package Page**   | Compare **EMR vs HMS** offerings.                | Display feature list and pricing toggle (Monthly/Yearly).   |
| 📞 **Contact Us**     | Provide contact and support details.             | Include form for inquiries (Name, Email, Subject, Message). |
| 🎓 **Staff Training** | Allow hospitals to book staff training sessions. | Form fields: Name, Hospital, Contact, Date/Time.            |

---

### 🔐 3.3 Tenant Authentication & Registration Flow

| **Page**                            | **Steps / Requirements**                                                                                              | **Design Notes**                                            |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| 🧩 **Tenant Creation (Multi-Step)** | **Step 1:** Email, Hospital Name, Subdomain<br>**Step 2:** Address, Logo, Contact Info<br>**Step 3:** Patient Metrics | Use a clean multi-step form with progress indicator.        |
| 🔢 **OTP Verification**             | 6-digit OTP entry with resend option.                                                                                 | Simple centered design with clear guidance.                 |
| 🔑 **Login / Reset Password**       | Secure standard authentication forms.                                                                                 | Include password visibility toggle and validation feedback. |

---

## 🏢 **4. System II — Hospital Tenant Application**

**Goal:** Enable hospital staff to manage **patients, appointments, billing, and data** efficiently.  
Each hospital has a dedicated subdomain (e.g. `https://myhospital.xxxxx.com`).

---

### 🧭 4.1 Layout & Navigation

| **Area**          | **Requirement**                                                   |
| ----------------- | ----------------------------------------------------------------- |
| 🧱 **Layout**     | Fixed **Left Sidebar Navigation** and **Top Header Bar**.         |
| 🧩 **Header Bar** | Display Hospital Name/Logo, Notifications Bell, and Profile Menu. |

---

### 💳 4.2 Tenant Financial & Status Pages

| **Page**                   | **Key Data Points**                              | **Notes**                                     |
| -------------------------- | ------------------------------------------------ | --------------------------------------------- |
| 📊 **Dashboard (Initial)** | Tenant Status: Pending, Active, or Blocked       | Include countdown for pending activation.     |
| 📈 **Dashboard (Active)**  | Active Patients, Appointments, Revenue, App URL  | Present as data cards and mini charts.        |
| 💰 **Subscription Page**   | Package, Start Date, Expiry Date, Remaining Days | Include CTA: **Renew / Upgrade**.             |
| 💳 **Wallet Page**         | Virtual Account Number, Balance, Deposit Action  | Enable “Copy” and “Deposit” buttons.          |
| 📜 **Transaction History** | Date, Type, Description, Amount, Status          | Use paginated table layout.                   |
| ⚙️ **Tenant Settings**     | Editable hospital info fields                    | Include save success feedback.                |
| 💾 **Database Backup**     | Backup button and last backup status             | Display backup progress and last backup time. |

---

### 🧬 4.3 HMS / EMR Module Structure

| **Module Group**            | **Submodules / Example Pages**                     |
| --------------------------- | -------------------------------------------------- |
| 🧑‍⚕️ **Clinical (EMR)**       | Patient Registration, Appointments, Clinical Notes |
| 💼 **Administrative (HMS)** | Billing, Pharmacy, HR, Inventory                   |
| 🗂️ **Sidebar Navigation**   | Collapsible structure with clear module grouping.  |

---

## 🛡️ **5. System III — Admin Webpages**

**Goal:** Provide internal RillCare staff with tools for **system monitoring, tenant management, and communication.**  
**URL:** `https://admin.xxxxxxx.com`

---

### 📊 5.1 Admin Dashboard

| **Component**              | **Functionality**                                    |
| -------------------------- | ---------------------------------------------------- |
| 🧾 **Top-Level Metrics**   | Total Tenants, Server Health, Database Load.         |
| 📈 **System Usage Graphs** | Interactive charts for RAM, CPU, and DB performance. |
| 📋 **Recent Activity**     | Table showing 10 most recent tenant registrations.   |
| 🗺️ **Package Insights**    | Visual representation of HMS vs EMR package usage.   |

---

### 🧮 5.2 Tenant Management

| **Page**               | **Features**                                          |
| ---------------------- | ----------------------------------------------------- |
| 🧾 **Tenant List**     | Data table with filters, search, and pagination.      |
| ➕ **Create Tenant**   | Modal form for new tenant registration.               |
| 🏥 **Tenant Details**  | Overview of hospital info, metrics, and subscription. |
| 🚫 **Status Controls** | Toggle between Active, Inactive, Blocked.             |

---

### ⚙️ 5.3 Admin Tools & Settings

| **Page**                | **Purpose**                                             |
| ----------------------- | ------------------------------------------------------- |
| 👤 **Admin Management** | Manage internal admins (Name, Role, Last Login).        |
| ✉️ **Email Marketing**  | Send individual or bulk emails with a rich text editor. |
| 🔐 **Admin Profile**    | Profile viewing and password reset.                     |

---

## 🧾 **6. Summary**

RillCare’s UI/UX design should reflect **trust, professionalism, and usability**.  
The system must be **responsive, intuitive, and consistent** across all modules — ensuring smooth experiences for hospitals, patients, and internal staff alike.

---

### 🖋️ **Design Team Responsibilities**

- Develop **responsive Figma mockups** for all three systems.
- Ensure **user journey consistency** across the platform.
- Propose final **color palette, typography, and iconography** aligned with healthcare design standards.
- Present **interactive prototypes** for stakeholder review before development.

---

> **© 2025 RillCare. All rights reserved.**
