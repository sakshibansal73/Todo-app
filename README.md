# GeoVolt — Smart Task Management Platform

GeoVolt is a cross-platform Flutter application that provides a modern task management experience backed by Firebase services. The application combines secure authentication, cloud synchronization, and an intuitive user interface to help users efficiently organize and manage their daily tasks.

The project demonstrates the integration of Flutter with Firebase Authentication, Cloud Firestore, and Firebase Storage while following a modular and scalable application architecture.

---

## Overview

GeoVolt is designed as a cloud-enabled productivity application that enables users to securely manage personal tasks from any device. By leveraging Firebase as the backend infrastructure, the application provides real-time synchronization, authentication, and persistent cloud storage.

The project follows Flutter's widget-based architecture, allowing reusable UI components, simplified maintenance, and future scalability.

---

## Core Features

| Module | Description |
|---------|-------------|
| Authentication | Secure Email, Google and Phone authentication |
| Task Management | Create, edit and delete personal tasks |
| Cloud Sync | Real-time synchronization using Firebase |
| User Profile | Manage account information |
| Persistent Storage | Cloud-based task storage |
| Cross Platform | Android and iOS support |

---

## Repository Structure

```text
GeoVolt/
├── android/
├── ios/
├── lib/
│   ├── models/
│   ├── screens/
│   ├── services/
│   ├── widgets/
│   ├── utils/
│   └── main.dart
├── assets/
├── test/
├── pubspec.yaml
└── README.md
```

---

## System Architecture

```text
                 User
                   │
                   ▼
          Flutter Application
                   │
      ┌────────────┴────────────┐
      │                         │
 Presentation Layer       Business Logic
      │                         │
      └────────────┬────────────┘
                   │
           Firebase Services
                   │
 ┌─────────────────┼─────────────────┐
 │                 │                 │
Authentication   Firestore      Cloud Storage
```

---

## Technology Stack

| Layer | Technology |
|--------|------------|
| Framework | Flutter |
| Language | Dart |
| Backend | Firebase |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| Storage | Firebase Storage |
| IDE | Android Studio / VS Code |

---

## Application Flow

```text
Authentication
        │
        ▼
Dashboard
        │
        ▼
Task Management
        │
 ┌──────┼─────────────┐
 │      │             │
 ▼      ▼             ▼
Create  Update     Delete
        │
        ▼
Cloud Synchronization
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/<your-username>/GeoVolt.git
```

### Install Dependencies

```bash
flutter pub get
```

### Configure Firebase

Create a Firebase project and add the required platform configuration files.

Android

```
android/app/google-services.json
```

iOS

```
ios/Runner/GoogleService-Info.plist
```

### Run

```bash
flutter run
```

---

## Dependencies

| Package | Purpose |
|----------|----------|
| firebase_auth | User Authentication |
| cloud_firestore | Cloud Database |
| firebase_storage | File Storage |
| provider | State Management |
| google_sign_in | Google Authentication |

---

## Future Enhancements

| Feature | Status |
|----------|--------|
| Push Notifications | Planned |
| Offline Synchronization | Planned |
| Dark Theme | Planned |
| Task Categories | Planned |
| Calendar Integration | Planned |
| Productivity Analytics | Planned |

---

## Design Principles

- Modular Architecture
- Reusable Widgets
- Clean User Interface
- Cloud-first Design
- Responsive Performance
- Maintainable Codebase

---

## License

This project is intended for educational and learning purposes.
