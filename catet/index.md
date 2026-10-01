# Privacy Policy — CATET

**Last Updated: September 2026** • **Organization: LuwengStudio**

LuwengStudio is fully committed to safeguarding and respecting your personal privacy rights. This document outlines our data protection, encryption, and telematics management standards for the application **CATET: Financial & Mobility Intelligence** (`com.luwengstudios.catet`).

---

### 1. Privacy-by-Design & Zero-Knowledge Architecture
CATET operates on an absolute *Offline-First* foundation. All financial logs, cashflow ledgers, daily trip records, vehicle service journals, and savings goals are stored locally on your device within encrypted storage.

We never upload, copy, analyze, sell, or trade your financial records, location trails, or personal profile data to our central servers or any third-party brokers.

---

### 2. Google Identity Authentication
To authenticate account ownership and secure cloud backup operations:
* **Verified Public Profile:** We receive basic verified identity attributes (Full Name, Registered Email, Firebase UID, and Profile Picture).
* We never request, access, or store your Google account password.

---

### 3. Location Permissions & GNSS Doppler Speedometer
We strictly request essential device permissions activated intentionally by the user:
* **Precise GPS Location (Fine & Coarse):** Utilized for the **Fuel Radar** utility to calculate direct proximity to official Pertamina fuel stations, and **Driving Mode** to calculate instantaneous GNSS Doppler speed and accumulated distance (KM). Coordinates are processed in volatile device memory and are never persisted as tracking history on any remote server.
* **Foreground Service with Persistent Notification:** Runs when *Driving Mode* or the *Floating Speedometer Widget* is active to ensure continuous metric calculation while using navigation apps. Terminates immediately via the notification "Stop" action.
* **Google Drive AppData Silent Backup:** Automated cloud backups store AES-256-GCM encrypted `.ctt` archives directly into your personal Google Drive hidden partition (`appDataFolder`). LuwengStudio has zero access to your Google Drive content.

---

### 4. User Rights & Data Deletion
In accordance with Google Play Developer Policy 2026, GDPR (Article 17), and Indonesian UU PDP No. 27/2022:
* Instant local data wipe via the *Reset All Data* menu inside CATET.
* Permanent cloud account erasure requests by contacting **luwengstudio@gmail.com** or our official Telegram desk.

---

### 5. Official Contacts
* **Organization:** LuwengStudio
* **Lead Developer:** Darmawan Aditya (KepalaLuweng)
* **Official Email:** luwengstudio@gmail.com
* **Official Telegram Support:** [t.me/luwengtechofficial](https://t.me/luwengtechofficial)
* **Official Updates Channel:** [t.me/luwengtechsupport](https://t.me/luwengtechsupport)
