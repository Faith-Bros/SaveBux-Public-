# SaveBux Privacy Policy & Terms of Service

**Last Updated:** September 14, 2026  
**Effective Date:** September 14, 2026  

Welcome to **SaveBux**. We are committed to protecting your personal information and your right to privacy. This Privacy Policy explains how SaveBux collects, uses, and safeguards your information when you use our mobile application.

---

## 1. On-Device First & Zero Cloud Storage Architecture
SaveBux is built from the ground up with **Privacy First** engineering:
* **Zero Cloud Transaction Storage:** All financial transactions, imported bank/UPI statements (SMS, PDFs, CSVs, Paytm, PhonePe, Google Pay), scanned bills, category allocations, and monthly budget targets are stored **exclusively in encrypted local SQLite storage on your device**.
* **No Remote Analytics or Selling of Data:** We do not track, upload, synchronize, sell, or monetize your financial statements, transaction history, or spending habits with any third-party advertising or analytics networks.

---

## 2. Authentication & Account Information
* **Sign-In Options:** SaveBux allows you to sign in using Google Sign-In or Email and Password.
* **Authentication Processing:** Account authentication is processed securely by **Google Firebase Authentication**. SaveBux only accesses your public display name, email address, and unique user identifier (UID) to personalize your local session.
* **Guest / Offline Mode:** You can use SaveBux offline. However, signing in enables user profile personalization.

---

## 3. Device Permissions & How They Are Used
SaveBux requests only permissions strictly necessary for user-initiated actions:
1. **Camera (`NSCameraUsageDescription`)**: Used only when you choose to scan a physical bill or paper receipt. Camera frames are processed entirely on-device using on-device optical character recognition (OCR) and are never transmitted to cloud servers.
2. **Photos / Photo Library (`NSPhotoLibraryUsageDescription`)**: Used when you choose to import an existing receipt image from your gallery or photo album.
3. **Notifications (`POST_NOTIFICATIONS` / `SCHEDULE_EXACT_ALARM`)**: Used solely on your device to deliver your optional nightly spending recap and mindful budget insights at your preferred reminder time.
4. **Files / Storage**: Used when you export your transactions to an Excel/CSV file or import a bank statement file.

---

## 4. User Data Ownership, Export & Deletion
You retain complete, 100% ownership over all data created in SaveBux:
* **Data Export:** You can export your entire transaction history to standard CSV at any time via the Profile & Settings screen.
* **In-App Account & Data Deletion:** In compliance with Google Play and Apple App Store policies, you can permanently delete your account and all associated data at any time:
  1. Open SaveBux and navigate to **Profile**.
  2. Tap **Delete Account & Data**.
  3. Confirm **Delete Forever**.
  This immediately purges all SQLite transactions, item breakdowns, and settings from your device and permanently deletes your authentication record from Firebase.

---

## 5. Security
We implement strict industry-standard technical measures:
* Local database storage is sandboxed within your operating system's protected application sandbox.
* All authentication requests use TLS/SSL encryption via Google Firebase.

---

## 6. Children's Privacy
SaveBux does not knowingly collect or solicit personal information from anyone under the age of 13.

---

## 7. Terms of Service
By using SaveBux, you agree to the following terms:
1. **Budgeting Tool Disclaimer:** SaveBux is an informational personal budgeting and expense tracking utility. It is not a bank, financial institution, or licensed financial advisor.
2. **User Responsibility:** You are responsible for ensuring the accuracy of manual entries and imported data.
3. **License:** SaveBux grants you a personal, non-transferable, revocable license to use the app in accordance with these terms.

---

## 8. Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:
* **Email:** support@savebux.app
* **Developer:** Faith-Bros / SaveBux Team  
* **Public Repository:** [https://github.com/Faith-Bros/savebux-public](https://github.com/Faith-Bros/savebux-public)
