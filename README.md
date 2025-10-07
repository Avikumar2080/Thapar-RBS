<div align="center">

# 🏛️ Thapar Room Booking System (RBS)

### 🎓 A Secure & Scalable Room Reservation Platform for Thapar Institute of Engineering & Technology

</div>

---

## 📘 Overview

The **Thapar Room Booking System (RBS)** is a full-stack platform built to simplify and digitize the process of booking lecture halls and classrooms across Thapar University.

Traditionally, room scheduling required physical registers and manual approval from administrative staff — leading to delays, double-bookings, and lack of transparency.

RBS transforms that workflow with a **real-time, intelligent, and role-based web system** accessible to all authorized Thapar faculty and departments.

> 🏫 **Hosted at:** [`rbs.thapar.edu`](https://rbs.thapar.edu)  
> 🔒 **Access:** Restricted to Thapar University's secure Wi-Fi network for privacy and data protection.  
> 👩‍🏫 **Used by:** All teaching & administrative departments.

---

## ⚙️ Tech Stack

| Layer                 | Technologies Used     |
| --------------------- | --------------------- |
| 💻 **Frontend**       | JavaScript, React.js  |
| 🧠 **Backend**        | Node.js, Express.js   |
| 🗄️ **Database**       | PostgreSQL            |
| 🔐 **Authentication** | JSON Web Tokens (JWT) |
| 📧 **Mail Server**    | Gmail (SMTP)          |

---

## 🚀 Features

✨ **Role-Based Access Control**

> Secure login for Admins, Professors, Society Heads, and Security Personnel via JWT tokens.

📅 **Smart Timetable Mapping**

> Converts calendar dates into weekdays automatically for dynamic timetable access.

⚡ **Conflict-Free Booking**

> Real-time slot validation prevents double bookings using database constraints and time logic.

🗂️ **Centralized Room Database**

> Stores room capacity, projector availability, and building details.

📧 **Automated User Onboarding**

> Admins can add users who receive email-based OTPs and activation links through Gmail integration.

🧾 **Privacy-Preserving View Access**

> Faculty can see _why_ a room is booked — not _who_ booked it.

📊 **Admin Dashboard**

> Manage users, view logs, and track booking patterns.

💬 **Planned:** Real-time notifications for confirmations and cancellations.

---

## 🧠 Use Cases

| User Role             | Privileges                                                                        |
| --------------------- | --------------------------------------------------------------------------------- |
| 👨‍💼 **Admin**          | Add/approve users, approve or cancel bookings, manage inventory, full visibility. |
| 👩‍🏫 **Professor**      | Book rooms, view own bookings, and check available rooms for classes/quizzes.     |
| 🧑‍🎓 **Society Head**   | Reserve spaces for events, manage club activities scheduling.                     |
| 🛡️ **Security Staff** | Validate active bookings via booking ID for real-time verification.               |

---

## 🔮 Future Scope

- 🏨 **Guest Room Booking System**

- 📱 **Mobile-Friendly & App Integration**

- 📊 **Analytics & Insights Dashboard**

- 🔔 **Real-Time Notifications**

- ☁️ **Scalability & Cloud Deployment**

- 🤝 **Integration with Other Thapar Systems**

---
