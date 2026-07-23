# 📚 Prephooks

> An adaptive educational quiz and exam preparation platform designed to help students master academic subjects through intelligent practice metrics and interactive study feeds.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 About Prephooks

**Prephooks** goes beyond static past question archives. It is a full-stack platform that delivers interactive, adaptive quiz sessions to help students study smarter. By tracking performance metrics and utilizing dynamic caching, Prephooks provides real-time feedback, step-by-step progress setups, and tailored practice feeds.

---

## ✨ Key Features

- **⚡ Adaptive Question Feeds:** Smart question delivery based on progress metrics and active topic focus.
- **📊 Performance Tracking:** Integrated performance gauge indicators, score tracking, and spaced retention logic.
- **🔄 Smart Caching:** Disk and session-based local memory caching to ensure fast, low-latency question scrolling and offline resilience.
- **🎯 Custom Quiz Wizard:** Step-by-step wizard allowing users to tailor quiz length, subjects, and difficulty parameters.
- **📱 Dynamic UI:** Fully responsive interface featuring micro-animations and smooth fluid visual components.

---

## 🛠️ Tech Stack

### Web & Mobile Frontend
- **Frameworks:** React / Flutter
- **UI & Motion:** Custom Widgets, Framer Motion keyframe animations, Material Design 3

### Backend & Database
- **Runtime:** Node.js, Express.js
- **ORM / DB:** Sequelize ORM, Relational SQL
- **Authentication:** Secure JWT authentication and session controllers

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Git](https://git-scm.com/)
- [Flutter SDK](https://flutter.dev/) *(if running the mobile client)*

### Environment Setup
Create a `.env` file in the backend root directory and configure your environment:

```env
PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_jwt_secret_key
CORS_ORIGIN=http://localhost:3000
