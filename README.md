# 🔊 Sound Box

**Sound Box** is a QR-based anonymous feedback, suggestion, and complaint system designed for apartments, gyms, offices, hospitals, and public spaces.

Users scan a QR code, submit feedback anonymously (or with contact details if they choose), and the organization manages everything through a clean dashboard with status tracking.

---

## 🚀 Live Demo

🔗 **Submission Page (QR Target):**  
[https://insuki180.github.io/sound-box/]

📊 **Admin Dashboard:**  
(Private – powered via Google Apps Script)

---

## 🧠 Problem Statement

Traditional suggestion boxes and internal forms fail because:
- People fear retaliation
- Handwriting or login exposes identity
- Feedback is ignored due to poor tracking

As a result, organizations lose honest input.

---

## 💡 Solution

Sound Box solves this by:
- Being **anonymous by default**
- Being maintained by a **third-party system**
- Requiring **no login, no app**
- Providing a **live dashboard** with status updates

This creates psychological safety and accountability.

---

## ✨ Key Features

- 📱 QR-based mobile-first submission
- 🔒 Anonymous by default (optional identification)
- 📝 Complaint / Suggestion / Feedback categories
- 📊 Admin dashboard with:
  - Monthly / yearly views
  - Status filtering (New / In Progress / Resolved)
  - Live metrics
- 🔁 Status write-back to database
- ☁️ Serverless backend (Google Apps Script + Sheets)

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Backend:** Google Apps Script (Web App)
- **Database:** Google Sheets
- **Hosting:** GitHub Pages
- **Deployment:** Serverless (no paid infrastructure)

---

## 🧩 System Architecture

QR Code
↓
GitHub Pages (Submission Page)
↓
Google Apps Script (API)
↓
Google Sheets (Database)
↓
Dashboard (HTML served by Apps Script)


---

## 🔐 Privacy & Trust Model

- No login required
- No IP or device tracking
- Identity stored **only if user provides it**
- Backend enforces anonymity even if frontend fails

---

## 📈 Use Cases

- Apartment complexes
- Gyms & fitness centers
- Offices & co-working spaces
- Hospitals & clinics
- Colleges & hostels

---

## 📌 Project Status

✅ Core system complete  
🔜 Multi-client scaling  
🔜 Automated weekly reports  
🔜 Client-specific branding  

---

## 👤 Author

**Kiran Suresh**  
Software Engineer | Product Builder  

This project is part of my hands-on portfolio focused on building real, deployable systems.

