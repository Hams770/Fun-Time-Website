# 🎢 Fun Time Website: Software Engineering & UI/UX Design

**Fun Time** is a platform for discovering and booking adventure and recreational activities (skydiving, hiking, tree climbing, paragliding and more) for **Kids**, **Adults** and adrenaline-seeking **Fun Players**. This repository holds the full **software engineering analysis and design**: requirements, UML diagrams, use cases, project plan, and a complete **mobile UI/UX prototype**.

> Software Engineering course project CS3151 (December 2024), Effat University. Team: **Hams Aljohani**, Amalya Hdaddi, Duaa Suroor, Howyna Ahmed. Supervised by **Dr. Passent Elkafrawy**.

![UI showcase](ui-design/showcase.png)

---

## 📌 Project Scope

- User registration, login, password recovery and profile management
- Browsing and filtering activities by age group, location and activity type
- Booking activities and paying securely (Apple Pay, Visa, vouchers)
- Notifications for booking confirmations, reminders, offers and cancellations
- Ratings and reviews for activities
- Admin dashboard to manage users, events, bookings and reports

---

## 📋 Requirements

### Functional
1. Registration and login with credential validation and error feedback (98% secure-access success rate).
2. Account management with encrypted passwords, password reset and account deactivation.
3. Search and filter by age group and preferences, with results in under 2 seconds.
4. Secure booking and payment processing (99% completion without errors).
5. Users can update their preferences and profile, with changes shown immediately.
6. Reminder notifications, 95% delivered at least 24 hours before the activity.
7. Admins upload and manage activity descriptions and images (load time under 2 seconds).
8. Ratings and reviews shown instantly (under 1 second), moderated by admins.

### Non-functional
**Performance** · **Security** (SSL, secure storage) · **Availability** (multi-language and multi-currency) · **Accessibility** (all devices and screen sizes) · **Maintainability**

### Stakeholders and user classes
Kids (through parents) · Adults · Fun Players · Activity providers · System administrators · Testers · Third-party payment services

---

## 🧩 System Design

| Context diagram | ER diagram |
|---|---|
| ![Context](diagrams/context-diagram.png) | ![ER](diagrams/er-diagram.png) |

| Class diagram | ER diagram 2 |
|---|---|
| ![Class](diagrams/class-diagram.png) | ![ER 2](diagrams/er-diagram-2.png) |

**Traceability matrix:** links each requirement to the use cases that cover it.
<img src="diagrams/traceability-matrix.png" width="420" alt="Traceability matrix">

---

## 🎯 Use Cases

Each use case is documented with actors, pre- and post-conditions, constraints, the main success scenario and alternate flows, plus **use case**, **sequence** and **state** diagrams.

| # | Use case | Actor | Goal |
|---|---|---|---|
| UC-1 | User Authentication & Management | User | Log in or create an account |
| UC-2 | Search & Filtering | User | Find events that match given criteria |
| UC-3 | Booking & Purchasing | User, payment gateway | Book and pay for an activity with no unnecessary steps |
| UC-4 | Event Details | User, event providers | View the details of a selected event |
| UC-5 | Admin Management | Admin | Manage events, users, bookings and reports |

| UC-3 Booking: use case | UC-3 Booking: sequence | UC-3 Booking: state |
|---|---|---|
| ![](diagrams/use-cases/uc3-booking-use-case.png) | ![](diagrams/use-cases/uc3-booking-sequence.png) | ![](diagrams/use-cases/uc3-booking-state.png) |

All 16 use-case, sequence and state diagrams are in [`diagrams/use-cases`](diagrams/use-cases).

---

## 🗓️ Project Plan

![Gantt chart](diagrams/gantt-chart.png)

---

## 🎨 UI/UX Prototype (14 screens)

| Home | Login | Create account | Forgot password | Explore |
|---|---|---|---|---|
| ![](ui-design/screens/01-home.jpg) | ![](ui-design/screens/02-login.jpg) | ![](ui-design/screens/03-create-account.jpg) | ![](ui-design/screens/04-forgot-password.jpg) | ![](ui-design/screens/09-explore-search.jpg) |

| Activities | Activity details | Booking & payment | Ratings & reviews | Profile |
|---|---|---|---|---|
| ![](ui-design/screens/14-activities.jpg) | ![](ui-design/screens/13-activity-details.jpg) | ![](ui-design/screens/08-booking-payment.jpg) | ![](ui-design/screens/11-ratings-reviews.jpg) | ![](ui-design/screens/10-user-profile.jpg) |

| Notifications | Admin dashboard | About us | Contact us |
|---|---|---|---|
| ![](ui-design/screens/07-notifications.jpg) | ![](ui-design/screens/12-admin-dashboard.jpg) | ![](ui-design/screens/05-about-us.jpg) | ![](ui-design/screens/06-contact-us.jpg) |

---

## 📁 Repository Structure

```
Fun-Time-Website/
├── docs/
│   ├── Software-Engineering-Report.pdf   # Full SE report (requirements, UML, use cases, Gantt, UI)
│   ├── UI-UX-Design.pdf                  # All prototype screens
│   └── Presentation.pdf                  # Project presentation
├── diagrams/
│   ├── context-diagram.png, er-diagram*.png, class-diagram.png
│   ├── traceability-matrix.png, gantt-chart.png
│   └── use-cases/                        # Use case, sequence and state diagrams for UC-1 to UC-5
└── ui-design/
    ├── showcase.png
    └── screens/                          # 14 mobile screens
```

📄 [Software engineering report](docs/Software-Engineering-Report.pdf) · 🎨 [UI/UX design](docs/UI-UX-Design.pdf) · 🎞️ [Presentation](docs/Presentation.pdf)

---

## 👩‍💻 Team

- **Hams Aljohani**
- Amalya Hdaddi
- Duaa Suroor
- Howyna Ahmed

Supervisor: Dr. Passent Elkafrawy
