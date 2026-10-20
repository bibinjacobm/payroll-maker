# Payroll Maker

[![Platform](https://img.shields.io/badge/Platform-Windows-blue.svg)](#system-requirements)
[![Release](https://img.shields.io/badge/Release-v3.6.3-brightgreen.svg)](https://github.com/bibinjacobm/payroll-maker/releases)
[![License](https://img.shields.io/badge/License-Freeware-orange.svg)](#licence)
[![Privacy](https://img.shields.io/badge/Data%20Privacy-100%25%20Offline-success.svg)](#data-privacy--security)

**Payroll Maker** is a comprehensive, production-grade desktop payroll and statutory compliance solution designed for Indian institutions, businesses, and accounting professionals. It handles end-to-end salary processing, multi-firm consolidations, Indian statutory registers, and tax reporting—while keeping your financial data completely offline and secure.

---

## 🚀 Key Highlights

* **100% Offline & Private:** Data stays strictly on your computer in encrypted `.pmk` files. No cloud dependency, no telemetry, no subscription fees.
* **Statutory Compliance Ready:** Pre-configured for EPF, ESIC, Code on Social Security 2020, state-wise minimum wage checks, and TDS (both Old & New Regimes).
* **Multi-Firm Management:** Run standalone firm payrolls or manage multiple entities under a parent organisation with unified reporting.
* **Accounting Integration:** Generates direct salary journals formatted for **TallyPrime / Tally ERP**, eliminating manual reconciliation.
* **Zero-Touch Updates:** Built-in update manager with automated SHA-256 checksum verification for both installed and portable editions.

---

## 📋 Comprehensive Feature Tour

### 1. Core Payroll Processing
* **Flexible Attendance & Time-Tracking:** Import records directly via Excel, CSV, or biometric system exports.
* **Dynamic Adjustments:** Robust handling of Loss of Pay (LOP), salary advances, salary holds, and retroactive arrears.
* **Audit & Reversals:** Step-by-step undo functionality and month-by-month discrepancy verification for every pay change.
* **Pay History & Scaling:** Maintain full pay history with effective dates, handle individual or bulk pay revisions, and firm-wide Dearness Allowance (DA) adjustments.

### 2. Statutory Compliance (India)
* **Provident Fund (EPF / MP Act):** Wage ceiling calculations with support for mid-month changes; exports ready-to-upload **EPF ECR** files.
* **ESIC Compliance:** Automatic eligibility screening, contribution computation, and standard ESIC portal upload files.
* **Code on Social Security 2020:** Built-in wage restructuring and 50% wage rules.
* **Minimum Wage Alerts:** Cross-verifies pay against state-specific minimum wage thresholds with real-time discrepancy alerts.
* **TDS & Taxation:** Dual-regime TDS computation (Old vs. New tax regimes) on salaries, along with Section-wise TDS for contractual/professional payments.
* **Gratuity & Leave Encashment:** Automatic actuarial-style liability statements, with combined cross-firm gratuity tracking.

### 3. Statutory Registers & Export Packs
* Standard **Register of Wages** & **Register of Employees**.
* **Form IV:** Register of deductions and advances.
* **Tally Salary Journal:** Clean export format ready for instant import into Tally.
* **Compliance Calendar:** Alerts and tracking for monthly, quarterly, and annual statutory filing deadlines.
* Comprehensive **Month-End** and **Year-End** audit and archiving packs.

### 4. Custom Document & Report Generation
Print or export high-resolution, branded PDFs and documents using your organization’s logo and letterhead:
* **Salary Slips & Yearly Statements** (with ready-to-email standardized filenames)
* **Salary Certificates, CTC Breakups, & Increment / Revision Letters**
* **Form 16 / Form 130** and TDS Certificates
* **Bank Transfer Advices** formatted for direct corporate banking submission
* Print previews and pre-configured output naming for seamless administrative distribution.

### 5. Multi-Entity & Enterprise Features
* **Parent Organization Architecture:** View multiple branches or subsidiary firms side by side.
* **Consolidated Operations:** Generate single, combined ECR, ESIC, TDS, and bank transfer sheets for group entities.
* **Productivity & Security:** Global quick search (`Ctrl + K`), bulk edit utilities, setup wizards, and detailed user audit trails.
* **Cloud-Drive Safe:** Protection logic prevents file corruption when storing firm files on sync engines like Microsoft OneDrive.

---

## 🔒 Data Privacy & Security

Your payroll records contain sensitive financial and personal information. Payroll Maker adheres to a strict zero-knowledge architecture:

* **Local Storage Only:** Firm files (`.pmk`) reside exclusively where you choose to save them on your local drive or private network share.
* **AES-256 Encryption:** Protect sensitive firm databases with robust AES-256 password encryption. *(Note: Encryption keys are never transmitted; passwords cannot be recovered if forgotten).*
* **Zero Telemetry:** The application operates completely offline. Network access is restricted purely to checking official release tags when the user requests an update check.

---

## 💻 Editions & Installation

Payroll Maker is distributed in two packaging formats:

| Edition | Details | Best For |
| :--- | :--- | :--- |
| **Installed (`.msi`)** | Standard Windows installer deploying to `Program Files`. Includes automated in-place upgrades. | Dedicated workstations & permanent accounting PCs. |
| **Portable (`.zip`)** | No installation required. Run directly from a folder, USB drive, or secure shared drive. | Multi-PC usage, restricted-privilege environments, or external drives. |

### Upgrading to New Versions
Starting in **Version 3.6**, Payroll Maker includes an integrated **Update Manager**:
* Check for updates via the sidebar or **Help > About**.
* Automatically detects the latest verified release, displays the release notes, and confirms package checksums before applying.
* **Installed copies** upgrade in-place.
* **Portable copies** safely extract into a parallel directory while seamlessly transferring existing configurations, user preferences, and automated backups.

---

## ⚙️ System Requirements

* **Operating System:** Windows 10, Windows 11, or Windows Server 2016+ (64-bit recommended)
* **Storage:** 150 MB free disk space for the core program (plus space for your `.pmk` firm databases and automated backups)
* **Office Integration:** Microsoft Excel / OpenOffice / LibreOffice (optional, for viewing exported `.xlsx` and `.csv` sheets)

---

## 📄 Licence

**Payroll Maker — Freeware Licence**  
*Copyright © 2026 Bibin Jacob. All rights reserved.*

1. **Free of charge:** You may download, install, and use Payroll Maker free of charge for personal, institutional, and commercial payroll work on any number of computers.
2. **Distribution & Sharing:** You may copy and share the application freely, provided it is shared unmodified, free of charge, and with this licence and the credit *"Crafted by Bibin Jacob"* intact.
3. **Not for Sale:** You may not sell, rent, lease, or charge for the application itself, or remove or alter its branding and credits.
4. **Your Data:** Firm files (`.pmk`) and every report generated belong entirely to you. The application stores data solely where you direct it and transmits nothing over the internet.
5. **No Warranty:** The application is provided "as is", without warranty of any kind. Statutory rates, wage ceilings, tax slabs, and electronic portal formats change periodically; users are responsible for verifying computational outputs against current statutory rules prior to releasing salary payments or filing regulatory returns.

---

### Author & Credits
Crafted with precision by **Bibin Jacob**.  
For release issues, feedback, or compliance feature discussions, feel free to submit an issue via the repository tracker.

```
