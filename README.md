# SaveBux-Public-
Official public repository for SaveBux — Mindful budgeting and personal finance app by Faith-Bros with zero cloud financial telemetry and 100% on-device SQLite storage.


# SaveBux 💳🌱

> **Mindful Budgeting & Expense Tracking with Zero Cloud Financial Storage.**  
> Built by **Faith-Bros** — Engineering privacy-first financial wellness.

[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-2E7D32?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![Architecture](https://img.shields.io/badge/Storage-100%25%20On--Device%20SQLite-0277BD?style=for-the-badge&logo=sqlite)](https://sqlite.org)
[![Privacy](https://img.shields.io/badge/Privacy-Zero%20Cloud%20Telemetry-00897B?style=for-the-badge)](https://github.com/Faith-Bros/savebux-public/blob/main/PRIVACY_POLICY.md)
[![License](https://img.shields.io/badge/License-Proprietary-455A64?style=for-the-badge)](#license)

---

## 🌟 Overview

Most budgeting applications require users to link their bank accounts or upload sensitive financial statements to remote cloud servers for monetization and ad-targeting. 

**SaveBux** takes a radically different approach: **Privacy-First Personal Finance**. 

Every transaction, scanned bill, bank statement, and category breakdown is stored **exclusively in encrypted SQLite storage on your physical device**. Your financial history never touches any remote database or third-party analytics network.

---

## ✨ Key Features

### 1. 💡 Live Daily Spendable Limit
* Replaces complex monthly budgeting spreadsheets with one clear daily number: *"How much can I safely spend today?"*
* Dynamically recalibrates based on your monthly income, fixed recurring bills, and savings target.
* Rollover calculations ensure saving today gives you more freedom tomorrow.

### 2. 🧾 Smart Receipt & Statement Ingestion
* **On-Device Optical Character Recognition (OCR):** Point your camera at paper bills or restaurant receipts. Powered by Google ML Kit running 100% offline on your hardware with Latin and Devanagari script support.
* **Bank & UPI Statement Import:** Import CSV statements from banks (SBI, HDFC, ICICI, etc.) with automated column detection, interactive preview, and multi-row selection.
* **Android System Share Sheet Integration:** Share receipt screenshots or payment confirmation text directly into SaveBux from **Google Pay**, **PhonePe**, or **Paytm**.

### 3. 👥 Split & Credit Allocations
* Group dining or roommate expenses? Split transactions equally or by custom percentages.
* Clearly demarcates personal spending versus recoverable amounts so shared expenses don't skew your personal budget.

### 4. 📊 Mindful Spending Insights & Trends
* Category breakdown with visual charts and month-over-month trend indicators.
* Fast full-text transaction search with custom date range filters.
* Calendar-based spending view to pinpoint heavy spending days.

### 5. 🎨 Dual Neumorphic Design System
* **Midnight Oceanic Mode:** Deep slate-navy aesthetic (`#0A0F1D`) with subtle cyan and emerald neon accents for OLED displays.
* **Clean Light Mode:** Minimalist paper-white theme with soft neumorphic shadows and high-contrast typography.

### 6. ⏰ Scheduled Daily Recap Notifications
* Optional end-of-day summary delivered at your preferred evening time.
* Scheduled entirely on-device via native alarms without cloud push notifications.

---

## 🛡️ Privacy & Security Architecture

| Guarantee | How SaveBux Enforces It |
| :--- | :--- |
| **Zero Cloud Financial Storage** | Drift + SQLite stores all transactions on-device within the sandboxed app container. |
| **No Telemetry / Data Monetization** | No third-party ad networks, tracking SDKs, or data brokers are integrated. |
| **Secure Authentication** | Firebase Authentication is strictly used to identify user sessions. No transactions are uploaded. |
| **CSV Formula Injection Defense** | Cell contents starting with `=`, `+`, `-`, or `@` are automatically sanitized. |
| **Complete Data Ownership & Wipe** | Single-tap **Delete Account & Data** permanently clears local SQLite tables and Firebase authentication records. |

---

## 🛠️ Technology Stack

* **Framework:** Flutter 3.x (Dart 3)
* **Local Database:** [Drift](https://drift.simonbinder.eu/) + [SQLite3](https://sqlite.org) (`sqlite3_flutter_libs`)
* **State Management:** Provider pattern with reactive streams
* **On-Device AI / ML:** Google ML Kit Text Recognition (Devanagari + Latin)
* **Authentication:** Firebase Authentication & Google Sign-In
* **Scheduled Tasks:** Flutter Local Notifications (`timezone` aware)

---

## 📱 Supported Platforms

* **Android:** Android 7.0 (API level 24) and higher.
* **iOS:** iOS 13.0 and higher.

---

## 📜 Legal & Policies

* [Privacy Policy & Terms of Service](https://github.com/Faith-Bros/savebux-public/blob/main/PRIVACY_POLICY.md)
* For inquiries regarding privacy or compliance: [support@savebux.app](mailto:support@savebux.app)

---

## 🏢 About the Developer

**SaveBux** is proudly designed and maintained by **Faith-Bros**.  
* **GitHub Organization:** [Faith-Bros](https://github.com/Faith-Bros)  
* **Contact:** [support@savebux.app](mailto:support@savebux.app)

---

## ⚖️ License

Copyright © 2026 Faith-Bros. All rights reserved.  
SaveBux is proprietary software. The source code of the main application is private.
