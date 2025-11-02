# 🏥 **RillCare: Modern Hospital Management System (HMS) — UI/UX Design Brief**

This document provides a complete specification for the **UI/UX design team** to develop the **Figma mockups** across all major RillCare platforms:

- 🌍 **Public Landing Site**
- 🏢 **Hospital Tenant Application**
- 🛠️ **Internal Admin System**

---

## 🎯 **1. Project Overview & Aesthetic Guidelines**

### 🧭 1.1 Core Aesthetic Mandates

The design must communicate **trust**, **professionalism**, **clarity**, and **modern efficiency**.

| **Component**        | **Style Mandate**                                       | **Details**                                                           |
| -------------------- | ------------------------------------------------------- | --------------------------------------------------------------------- |
| 🎨 **Color Palette** | Use consistent medical-grade colors across all systems. | Must evoke **trust and healthcare reliability**.                      |
| ✍️ **Typography**    | Clean, modern **sans-serif** font.                      | High contrast, readability for **data-heavy dashboards & EMR forms**. |
| 🧩 **Visual Style**  | Clean, **spacious**, and **data-focused**.              | Rounded corners, soft shadows, subtle gradients. **Avoid clutter.**   |
| 📱 **Mobile-First**  | Design for mobile first, scale up to desktop.           | All elements must be **fully responsive**.                            |
| 🔣 **Icons**         | Vector-based (Lucide / Font Awesome).                   | Maintain **consistent line weight & style**.                          |

---

### 🎨 1.1.1 **Defined Color Palette**

| **Purpose**           | **Color Name** | **Hex Code** | **Usage**                            |
| --------------------- | -------------- | ------------ | ------------------------------------ |
| 🩵 Primary Brand Color | Medical Blue   | `#005691`    | Navigation, branding, buttons        |
| 🧊 Secondary Color    | Aqua / Teal    | `#4DC7C3`    | Accents, calm indicators, highlights |
| 🧡 Accent / CTA       | Vibrant Orange | `#FF7A00`    | Call-to-Action buttons, alerts       |
| ⚪ Background         | Light Gray     | `#F7F9FC`    | Panel backgrounds, app body          |
| ⚫ Text / Icons       | Dark Slate     | `#1F2937`    | Primary text, icons                  |

---

### ⚙️ 1.2 **System-Wide UX Principles**

- ♿ **Accessibility:** High contrast, logical tab order, screen-reader friendly.
- ⚡ **Speed:** Minimize visual clutter; ensure fast page load feel.
- 🔁 **Feedback:** Clear loading, success, and error states for all interactions.
- 🌙 **Dark Mode (Optional):** Clean, contrast-optimized mode for dashboards.

---

## 🌐 **2. System I — Public Landing Pages**

**Goal:** Attract hospitals, showcase RillCare’s value, and drive **tenant account creation**.  
**URL:** `https://xxxxxxxx.com`

---

### 🏠 2.1 Home Page (Single-Scroll Layout)

| **Section**             | **Content Requirements**                                                      | **Design Notes**                                                                                                  |
| ----------------------- | ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| 🔝 **Navigation Bar**   | Fixed bar with links: Home, Services, About Us, Partners, Feedback, Packages. | CTA: **Login / Get Started**.                                                                                     |
| 💡 **Hero Section**     | Strong visual (hospital/data security).                                       | Headline + Value Proposition (“**The Future of Hospital Management**”). Prominent CTA: **Create Tenant Account**. |
| 🩺 **Services Section** | Grid or card layout highlighting benefits (EMR, Financial, Security).         | Use thematic icons & hover effects.                                                                               |
| 👥 **About Us**         | Short company mission & vision.                                               | Use clean imagery or illustration.                                                                                |
| 🤝 **Partners Section** | Grid or carousel with logos.                                                  | Each shows “**Joined: Month YYYY**”.                                                                              |
| 💬 **Feedback Section** | 3–5 testimonials in carousel.                                                 | Name, hospital/title.                                                                                             |
| ⚓ **Footer**           | Links: Privacy, Terms, Contact, Socials.                                      | Minimal, clean layout.                                                                                            |

---

### 📦 2.2 Auxiliary Pages

| **Page**              | **Purpose**             | **Key Design Features**                                                                      |
| --------------------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| 💼 **Package Page**   | Compare **EMR vs HMS**. | Table layout, toggle Monthly/Yearly pricing, CTA: “**Select Package & Start Registration**”. |
| 📞 **Contact Us**     | Contact RillCare.       | Form: Name, Email, Subject, Message + company details.                                       |
| 🎓 **Staff Training** | Book training sessions. | Simple booking form: Name, Hospital, Contact, Preferred Date/Time.                           |

---

### 🔐 2.3 Tenant Authentication & Registration Flow

| **Page**                            | **Steps / Requirements**                                                                                                       | **Design Notes**                   |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------- |
| 🧩 **Tenant Creation (Multi-Step)** | **Step 1:** Email, Hospital Name, Subdomain<br>**Step 2:** Country, State, Address, Logo Upload<br>**Step 3:** Patient Metrics | Progress bar at top; clean layout. |
| 🔢 **OTP Verification**             | Single 6-digit field + resend timer.                                                                                           | Simple, centered UI with feedback. |
| 🔑 **Login / Reset Password**       | Standard secure forms.                                                                                                         | Use password visibility toggle.    |

---

## 🏥 **3. System II — Hospital Tenant Application**

**Goal:** Enable hospital staff to manage **operations & patient data** efficiently.  
Each hospital operates under its **unique subdomain** (e.g. `https://myhospital.xxxxx.com`).

---

### 🧭 3.1 Layout & Navigation

| **Area**          | **Design Requirements**                                                |
| ----------------- | ---------------------------------------------------------------------- |
| 🧱 **Layout**     | Fixed **Left Sidebar Navigation** + **Top Header Bar**.                |
| 🧩 **Header Bar** | Display Hospital Name/Logo, Notifications Bell, User Profile dropdown. |

---

### 💳 3.2 Tenant Financial & Status Pages

| **Page**                   | **Key Data Points**                                              | **Visual Design Elements**                      |
| -------------------------- | ---------------------------------------------------------------- | ----------------------------------------------- |
| 📊 **Dashboard (Initial)** | Tenant Status: `PENDING / ACTIVE / BLOCKED`                      | Use **status card** + countdown (for pending).  |
| 📈 **Dashboard (Active)**  | Active Patients, Today’s Appointments, Revenue Snapshot, App URL | Use **metric cards + mini charts**.             |
| 💰 **Subscription Page**   | Package Name, Start/End Date, Remaining Days                     | CTA: **Renew / Upgrade**.                       |
| 💳 **Wallet Page**         | Virtual Account Number (copyable), Balance                       | CTA: **Deposit Funds**.                         |
| 📜 **Transaction History** | Date, Type, Description, Amount, Status                          | Table view + pagination.                        |
| ⚙️ **Tenant Settings**     | Editable fields (Name, Address, Contact, Logo)                   | Include save confirmation feedback.             |
| 💾 **Database Backup**     | Initiate Backup Button + Last Backup Info                        | Prominent visual feedback (e.g., progress bar). |

---

### 🧬 3.3 HMS / EMR Module Structure

| **Module Group**            | **Examples / Submodules**                                 |
| --------------------------- | --------------------------------------------------------- |
| 🧑‍⚕️ **Clinical (EMR)**       | Patient Registration, Appointments, Clinical Notes        |
| 💼 **Administrative (HMS)** | Billing, Pharmacy, HR, Inventory                          |
| 🗂️ **Navigation Structure** | Collapsible sidebar with unified icons & nested sections. |

---

## 🛡️ **4. System III — Admin Webpages**

**Goal:** Provide internal RillCare staff with tools for **server monitoring, tenant management, and communications**.  
**URL:** `https://admin.xxxxxxx.com`

---

### 📊 4.1 Admin Dashboard

| **Component**                | **Requirement**                                             |
| ---------------------------- | ----------------------------------------------------------- |
| 🧾 **Top Metrics**           | Total Tenants, Server Health Status, Database Load.         |
| 📈 **Usage Graphs**          | Interactive charts (RAM, CPU, DB Usage over time).          |
| 📋 **Recent Activity**       | Table of 10 most recent tenant registrations.               |
| 🗺️ **Package Visualization** | Donut or map chart comparing HMS vs EMR package selections. |

---

### 🧮 4.2 Tenant Management

| **Page**                  | **Key Features**                                                   |
| ------------------------- | ------------------------------------------------------------------ |
| 🧾 **Tenant List**        | Data Table: Logo, Name, Subdomain, Email, Package, Status.         |
| 🔍 **Search & Filters**   | Search bar + Filter options + Pagination.                          |
| ➕ **Create Tenant**      | Modal form for adding new tenant.                                  |
| 🏥 **Tenant Detail Page** | Overview (Logo, Address, Metrics) + Financial & Subscription Tabs. |
| 🚫 **Status Controls**    | Toggle to **BLOCK / UNBLOCK** tenant.                              |

---

### ⚙️ 4.3 Admin Tools & Settings

| **Tool / Page**                 | **Functionality**                                                          |
| ------------------------------- | -------------------------------------------------------------------------- |
| 👤 **Admin Management**         | Manage internal admins (Name, Email, Role, Last Login). Actions: Add/Edit. |
| ✉️ **Email Marketing**          | Individual & Bulk email sections with rich text editor.                    |
| 🔐 **Admin Profile & Settings** | Profile view + password reset options.                                     |

---

## 🧾 **5. Summary**

RillCare aims to deliver a **modern, responsive, and trustworthy digital ecosystem** for hospitals.  
The UI/UX must be consistent, intuitive, and scalable — from the **public landing site** to **tenant operations** and **admin oversight**.

---

### 🖋️ **Design Principles Recap**

✅ Consistency across systems  
✅ Accessibility and readability  
✅ Minimalist and data-focused layout  
✅ Mobile-first and responsive  
✅ Clear interactive feedback  
✅ Clean typography & strong color hierarchy

---

### 🧠 **Design Tools & Assets**

- **Figma** (Main design tool)
- **Lucide Icons / Font Awesome**
- **TailwindCSS design alignment (preferred)**
- **RillCare Branding Colors** (See palette above)

---

> **© 2025 RillCare. All rights reserved.**
