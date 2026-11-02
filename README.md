# UnitedCeres

<p align="center">
  <img src="assets/app-logo.png" width="120" alt="UnitedCeres">
</p>

<p align="center">
  <strong>United Ceres College Student Mobile Application</strong><br>
  A production mobile application built for United Ceres College students.
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=sg.edu.unitedceres.app">
    <img src="https://img.shields.io/badge/Google%20Play-Live-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play">
  </a>
  <a href="https://apps.apple.com/pk/app/united-ceres/id6761606105">
    <img src="https://img.shields.io/badge/App%20Store-Live-000000?style=for-the-badge&logo=apple&logoColor=white" alt="App Store">
  </a>
</p>

> **Company Project · Client Project · Production Application**
>
> UnitedCeres is a company project completed **solo by me at VirtueNetz** for **United Ceres College**. The client provided the backend/ERP system and APIs. My responsibility was the complete mobile-side implementation, including ERP API integration, application UI/UX implementation, local storage and state handling, device-side functionality, and production delivery.

---

## About the Project

**UnitedCeres** is a mobile application developed for **United Ceres College students**.

The application provides students with convenient mobile access to important academic and college-related information and services through a single application.

This repository is a **public project showcase**. The production source code and private client infrastructure are intentionally not included because this is a company/client project.

---

## My Role

I completed the mobile application **solo as a Flutter Developer at VirtueNetz**.

The backend/ERP system was provided by the client. My work focused on the complete mobile application and its integration with the client's existing ERP/backend services.

### Responsibilities

- Complete Flutter mobile application development
- UI/UX implementation
- ERP/backend API integration
- API request and response handling
- Authentication and session handling
- Local storage implementation
- Local application state handling
- Secure device-side data handling
- Push notification integration
- Biometric authentication
- PDF/document related functionality
- Device and platform integrations
- Error and crash handling
- Android and iOS application preparation
- Production release and store delivery
- Ongoing frontend-side improvements and fixes

The project was delivered as a production application for both **Android and iOS**.

---

## Key Features

The application provides students with access to areas such as:

- Student profile
- Academic information
- Class schedules and timetables
- Attendance
- Assessment results
- Failure reports
- Leave-related information
- Invoices
- Payment receipts
- College announcements
- Notifications
- Helpdesk/support
- Documents and PDF-related information
- Secure authentication
- Biometric authentication
- Local data persistence

The exact functionality available to a student depends on the services and information exposed by the client's ERP/backend system.

---

## Technology

### Mobile Application

- **Flutter**
- **Dart**
- **GetX**
- **Dio**
- **Socket.IO**
- **Firebase**
- **Flutter Secure Storage**
- **Local Auth**
- **PDF / Printing**
- **WebView**
- **Lottie**
- **SVG**

### Backend Integration

The application integrates with the **client-provided ERP/backend APIs**.

The backend itself is **not part of this repository**.

---

## High-Level Architecture

```text
                    ┌──────────────────────────┐
                    │      UnitedCeres App     │
                    │       Flutter / Dart     │
                    └────────────┬─────────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
       ┌──────▼──────┐    ┌──────▼──────┐    ┌──────▼──────┐
       │ UI / Screens │    │ App State   │    │ Local Data  │
       │ & Widgets    │    │ & Services  │    │ & Storage   │
       └──────┬──────┘    └──────┬──────┘    └──────┬──────┘
              │                  │                  │
              └──────────────────┼──────────────────┘
                                 │
                         ┌───────▼────────┐
                         │ ERP API Layer  │
                         │ Client Backend │
                         └────────────────┘
```

This is intentionally a **high-level representation**. Private backend architecture, endpoints, credentials, and infrastructure are not published.

---

## Project Scope

| Area                       | Responsibility                 |
| -------------------------- | ------------------------------ |
| Mobile Application         | Solo implementation            |
| Flutter Frontend           | Solo implementation            |
| UI / UX                    | Solo implementation            |
| ERP API Integration        | Solo implementation            |
| API Handling               | Solo implementation            |
| Local Storage              | Solo implementation            |
| Local State                | Solo implementation            |
| Device-side Features       | Solo implementation            |
| Client ERP / Backend       | Provided by client             |
| Production Mobile Delivery | Handled as part of the project |

---

## Production Platforms

The application has been delivered and published for:

- **Android**
- **iOS**

### Google Play

[**View UnitedCeres on Google Play**](https://play.google.com/store/apps/details?id=sg.edu.unitedceres.app)

### Apple App Store

[**View United Ceres on the App Store**](https://apps.apple.com/pk/app/united-ceres/id6761606105)

---

## About the Company Project

This project was completed as part of my professional work at **VirtueNetz**.

UnitedCeres was a **client project**, and the client provided the ERP/backend infrastructure. I independently handled the mobile application side, including the frontend, ERP API integration, local storage, application state, and related mobile functionality.

The project was completed as a production application and published on both major mobile platforms.

---

## Repository Structure

```text
unitedceres/
├── assets/
│   └── app-logo.png
├── docs/
│   ├── ARCHITECTURE.md
│   └── PROJECT.md
├── CHANGELOG.md
├── NOTICE.md
├── SECURITY.md
├── .gitignore
└── README.md
```

---

## Project Documentation

- [Project Overview](docs/PROJECT.md)
- [High-Level Architecture](docs/ARCHITECTURE.md)
- [Changelog](CHANGELOG.md)
- [Copyright & Usage Notice](NOTICE.md)
- [Security](SECURITY.md)

---

## Project Status

**Status: Completed · Production · Published**

UnitedCeres is a completed client project delivered through **VirtueNetz**.

This public repository exists only as a professional project showcase and does not contain the production implementation.

---

## Credits

**Developer:** Mubashir Sikander  
**Role:** Flutter Developer  
**Company:** VirtueNetz  
**Client:** United Ceres College  
**Project:** UnitedCeres

<p align="center">
  <sub>Company/client project · Production application · Source code private</sub>
</p>
