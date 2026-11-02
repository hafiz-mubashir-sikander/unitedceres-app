# UnitedCeres — High-Level Architecture

This document provides a non-confidential overview of the mobile application's architecture.

## System Overview

```text
┌─────────────────────────────────────────┐
│          UnitedCeres Mobile App         │
│               Flutter / Dart            │
├─────────────────────────────────────────┤
│ UI / Screens / Widgets                  │
│ Student Workflows                       │
├─────────────────────────────────────────┤
│ State / Controllers / Services           │
├─────────────────────────────────────────┤
│ API Integration / Authentication         │
│ Local Storage / Device Services          │
└────────────────────┬────────────────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │ Client ERP / Backend │
          │   APIs & Services    │
          └──────────────────────┘
```

## Mobile Layer

The mobile application was implemented using Flutter and Dart.

The mobile layer includes:

- Presentation/UI
- Navigation
- Application state
- API integration
- Authentication
- Local persistence
- Secure storage
- Device capabilities
- Notifications
- PDF/document functionality

## ERP Integration

The application communicates with the **client-provided ERP/backend APIs**.

The API integration was handled on the mobile side, including:

- API requests
- Response processing
- Authentication/session handling
- Data mapping
- Error handling
- Integration with local application state

## Local Storage

Local storage was implemented on the mobile side for application data and secure device-side information where appropriate.

## Confidentiality Boundary

The public repository does not expose:

- Client backend source code
- Private endpoints
- Credentials
- API keys
- Firebase production configuration
- Signing credentials
- Client data
- Internal infrastructure

The architecture shown here is intentionally simplified for portfolio documentation.
