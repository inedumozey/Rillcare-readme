<style>
.primary-text { color: #005691; }
.secondary-text { color: #4DC7C3; }
.accent-text { color: #FF7A00; }
.swatch {
display: inline-block;
width: 20px;
height: 20px;
border-radius: 4px;
margin-right: 8px;
vertical-align: middle;
border: 1px solid #1F2937;
}
</style>

<span class="primary-text">RillCare: Modern Hospital Management System (HMS) UI/UX Design Brief</span>

This document serves as the comprehensive brief for the UI/UX design team, outlining the requirements, aesthetics, and functionality for the Figma mockups across all three major RillCare systems: the Public Landing Site, the Hospital Tenant Application, and the Internal Admin System.

<span class="accent-text">1. Project Overview and Aesthetic Guidelines</span>

1.1 Core Aesthetic Mandates

The design must convey trust, professionalism, clarity, and modern efficiency.

Component

Style Mandate

Details

Color Palette

Defined Hex Codes added below (See 1.1.1). Primary colors must evoke trust and healthcare.

The palette must be consistent across all three systems.

Typography

Clean, highly legible, and modern sans-serif font family. Excellent contrast is mandatory.

Priority on readability for data-heavy dashboards and EMR forms.

Visual Style

Clean, spacious, and data-focused. Use rounded corners, soft shadows, and subtle gradients. Avoid heavy or cluttered interfaces.

Mobile-First Design is mandatory for all pages and dashboards. All elements must be fully responsive.

Icons

Modern, scalable vector icons (e.g., Lucide or Font Awesome equivalent). Consistent line weight and style.

1.1.1 Defined Color Palette

The following Hex codes must be used to establish brand consistency:

Primary Brand Color (Medical Blue): <span class="swatch" style="background-color: #005691;"></span>#005691 (Used for main navigation, primary actions, and branding)

Secondary Color (Aqua/Teal): <span class="swatch" style="background-color: #4DC7C3;"></span>#4DC7C3 (Used for accents, progress bars, and calm status indicators)

Accent/CTA Color (Vibrant Orange): <span class="swatch" style="background-color: #FF7A00;"></span>#FF7A00 (Used exclusively for Call-to-Action buttons, alerts, and key highlights)

Background (Light Gray): <span class="swatch" style="background-color: #F7F9FC; border: 1px solid #ccc;"></span>#F7F9FC (Used for content panels and the main application background for a soft, clean look)

Text/Icons (Dark Slate): <span class="swatch" style="background-color: #1F2937;"></span>#1F2937 (Used for body text and primary icons to ensure maximum readability)

1.2 System-Wide UX Principles

Accessibility: Ensure high contrast and logical tab order.

Speed: Design must feel fast and responsive (prioritize low visual clutter).

Feedback: All interactive actions (e.g., button clicks, form submissions) must have clear success, error, or loading states.

Dark Mode (Optional, but preferred for Dashboards): Consider a clean, accessible dark mode for extended use in clinical settings.

<span class="accent-text">2. System I: Public Landing Pages</span>

Goal: Attract hospitals, showcase RillCare’s value, and drive tenant account creation.
URL: https:xxxxxxxx.com

2.1 Home Page (Single Page, Smooth Scroll)

Section

Content Requirement & Design Note

Navigation Bar

Must be sticky/fixed. Links: Home, Services, About Us, Partners, Feedback, Packages, CTA: Login / Get Started.

Hero Section

Strong, attractive visual/image (modern hospital or abstract data security). Clear headline and a strong Value Proposition (e.g., "The Future of Hospital Management"). Prominent CTA: Create Tenant Account.

Services Section

Use cards or grid layout to detail key benefits (e.g., EMR, Financial Efficiency, Data Security). Use professional, thematic icons.

About Us

Brief text on the company's mission and vision. Use professional imagery (e.g., team photo or abstract professionalism).

Partners Section

Horizontal slider or grid displaying Partner Logos. Include a small text overlay or description showing "Joined:

$$Month YYYY$$

" for each partner.

Feedback Section

Carousel or grid displaying 3-5 professional-looking Testimonials (name, hospital/title).

Footer

Standard links (Privacy Policy, Terms), social media, and contact details.

2.2 Auxiliary Pages

Package Page:

Comparison table format for EMR Package vs. HMS Package.

Clear toggles for Monthly and Yearly pricing.

Features: List features clearly. The main difference (e.g., HMS includes Financial/HR modules, EMR is clinical only) must be visually obvious.

Primary CTA: Select

$$Package Name$$

and Start Registration.

Contact Us: Standard form (Name, Email, Subject, Message) and company contact details (Address, Phone, Email).

Staff Training Booking: A simple form interface to book a session (Name, Hospital, Contact, Preferred Date/Time).

2.3 Tenant Authentication & Registration Flow

Design Priority: Simplicity and high conversion rate.

Page

Requirement

Tenant Creation Page (Multi-Step Form)

Step 1: Basic Info (Email, Hospital Name, Subdomain Choice). Step 2: Location/Contact (Country, State, Address, Logo Upload). Step 3: Patient Metrics (Total Registered, Avg. Monthly).

OTP Verification Page

Clean input field for the 6-digit OTP. Clear instructions and a visible timer for resending the code.

Login / Forgot Password / Reset Password

Standard, secure authentication interfaces.

<span class="accent-text">3. System II: Hospital Tenant Application (Subdomain App)</span>

Goal: Provide an efficient, secure, and professional interface for hospital staff to manage operations and patient data.

3.1 Layout and Navigation

Layout: Use a standard application shell: Fixed Left Sidebar Navigation and a Header Bar for global actions/notifications.

Header: Must display Hospital Name/Logo, a Notifications Bell, and a User Profile/Settings Menu.

3.2 Tenant Financial & Status Pages

Page

Key Data Points and Interaction

Dashboard (Initial View)

Prominent Status Card: Must clearly display the current account status: PENDING (with countdown timer for 24-48 hours), ACTIVE, or BLOCKED. Include the message: "Contact management if status takes longer than 48 hours."

Dashboard (Active View)

Key Hospital Metrics (e.g., Active Patients, Today’s Appointments, Revenue Snapshot). Must display the direct App URL (https://[subdomain].xxxxxx.com).

Subscription Page

Status: (Active, Pending, Exhausted). Details: Package Name (HMS/EMR), Start Date, Expiry Date, Remaining Days. Primary CTA: Renew Subscription / Upgrade.

Wallet Page

Virtual Account Number: Must be large and easily copiable. Shows current Balance. Action: Button/section for "Deposit Funds."

Transaction History

Table view with filters and pagination: Date, Type (Deposit/Payment), Description, Amount, Status.

Tenant Settings

Form fields to edit editable info: Hospital Name, Address, Contact Info, Logo upload.

Database Backup

Prominent button: "Initiate Database Backup." Clear status text showing the last backup date and size.

3.3 HMS/EMR Modules (Placeholder/Structure)

The EMR and HMS modules should be structured as navigable sub-sections.

Structure Requirement: Design a unified, collapsible sidebar navigation structure that will house modules like:

Patient Registration

Appointments

Clinical Notes / Documentation (EMR Core)

Billing / Pharmacy / HR (HMS Core)

<span class="accent-text">4. System III: Admin Webpages</span>

Goal: Provide internal staff with tools for server monitoring, tenant management, and communication.
URL: https://admin.xxxxxxx.com

4.1 Admin Dashboard

Design Priority: Data visualization and clear system status.

Top-Level Metrics: Large, clear cards for Total Number of Tenants, Server Health Status.

System Usage Graphs: Mock up interactive graphs for Server Usage (RAM, CPU, Database Load) over time.

Recent Activity: Table listing the 10 Most Recent Tenant Registrations (Name, Subdomain, Status).

Package Comparison Map/Chart: A prominent visualization (e.g., a donut chart or map visualization) that visually compares the ratio of tenants choosing the HMS vs. EMR package.

4.2 Tenant Management

Tenant List Page:

Data Table: Displays key tenant data (Logo, Hospital Name, Subdomain, Contact Email, Package, Status: Active/Inactive/Blocked).

Mandatory Features: Search bar, Filters, Pagination, and a "Create Tenant" button (modal form).

Tenant Detail Page:

Overview Section: All hospital registration details (Logo, Name, Patient metrics, Address).

Status Panel: Large toggle/button pair to BLOCK / UNBLOCK the tenant.

Financial Tab: Shows Wallet Balance, Virtual Account Number, and Subscription History table.

Subscription History Tab: Shows every past and current subscription status.

4.3 Admin Tools & Settings

Admin Management Page (Super Admin Only): Table for managing internal admin users (Name, Email, Role, Last Login). Actions: Add New Admin, Edit Role (Admin/Super Admin).

Email Marketing Page:

Section for Individual Email (Tenant Search Field, Subject, Body).

Section for Bulk Email (Recipient Filter options, Subject, Body). Use a rich text editor placeholder.

Admin Profile & Settings: Standard profile viewing and password reset forms for internal users.

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
