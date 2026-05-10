# Polymind - AI-Powered Language Learning Ecosystem

👉 **[Türkçe Versiyon İçin Tıklayın (Read in Turkish)](README.md)** 👈

[![App Store](https://img.shields.io/badge/Download_on-App_Store-black?style=for-the-badge&logo=apple)](https://apps.apple.com/us/app/polymind/id6757526614)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)

> **Note:** This repository is intended **strictly for portfolio and showcase purposes**. The source code for the Polymind ecosystem (Mobile App, Backend, Admin Panel, and App Landing) is maintained in private enterprise repositories to protect proprietary intellectual property and business logic.

## About The Project
Polymind is not just a mobile application; it is a full-fledged language learning ecosystem designed to make language acquisition natural, immersive, and AI-supported. Currently live on the App Store, it combines advanced speech recognition, spaced repetition algorithms, and minigames to redefine the educational experience.

## Ecosystem Showcase

### App Store Presentation
<div align="center">
  <img src="assets/app_store_da_görünüşü.png" width="800" alt="App Store"/>
</div>

### Mobile App Screens
<div align="center">
  <img src="assets/home_page.png" width="350" alt="Home Page"/>
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="assets/seviye_belirleme_sınavı.png" width="350" alt="Placement Test"/>
</div>
<br>
<div align="center">
  <img src="assets/günlük_görev.png" width="350" alt="Daily Tasks"/>
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="assets/profil ekran.png" width="350" alt="Profile Screen"/>
</div>

### Interactive Mini Games
<div align="center">
  <img src="assets/oyunlar.png" width="400" alt="Games"/>
</div>

### CMS / Admin Dashboard
<div align="center">
  <img src="assets/admin_panel.png" width="800" alt="Admin Panel"/>
</div>

### Mobile App Landing Website
<div align="center">
  <img src="assets/website.png" width="800" alt="Website"/>
</div>

---

## Technical Architecture & Tech Stack

The architecture is distributed into 4 main decoupled micro-applications, built with the latest enterprise-level standards.

### 1. Mobile Application (iOS/Android)
Developed to deliver a highly interactive 60fps+ native experience.
* **Core:** Flutter SDK, Dart
* **State Management & Routing:** Riverpod, GoRouter
* **Engines & UI:** Flame (for in-app 2D games), Lottie (Animations), Liquid Swipe
* **Integrations:** RevenueCat (In-App Purchases), Firebase Suite (Core, Analytics, Crashlytics, Perf), AdMob
* **AI & Hardware:** Speech-to-Text & Flutter TTS for vocal language corrections.

### 2. High-Performance API Backend
A robust, scalable RESTful API handling business logic, user data, and real-time syncing.
* **Core:** Node.js, Fastify (High-throughput framework)
* **Databases & ORM:** SQL + Prisma ORM for type-safe database queries.
* **AI Integration:** Groq SDK for AI-generated personalized language content.
* **Security & Auth:** JWT, Bcrypt, Fastify Rate Limit, Helmet. Cloudinary for secure asset storage.

### 3. CMS / Admin Dashboard
A deeply customized React application to manage the entire mobile app's content remotely.
* **Core:** React 19, TypeScript, Vite
* **Routing & Requests:** React Router DOM, Axios
* **Purpose:** Allows real-time addition of lessons, flashcards, words, and user management without needing to push App Store updates.

### 4. Marketing Website & Landing
A perfectly SEO-optimized, blazing fast landing page to funnel user acquisitions.
* **Core:** Next.js 16, React 19, TypeScript
* **Styling & Animations:** Tailwind CSS v4, Framer Motion, Lenis (Smooth Scrolling).

---
*Developed & Maintained By [Alemgir](https://github.com/alemgir) - View on [App Store](https://apps.apple.com/us/app/polymind/id6757526614)*