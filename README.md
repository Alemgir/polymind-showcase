# Polymind - AI-Powered Language Learning Ecosystem 🌍🧠
[![App Store](https://img.shields.io/badge/Download_on-App_Store-black?style=for-the-badge&logo=apple)](https://apps.apple.com/us/app/polymind/id6757526614)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)

*You can find the Turkish version below. / Türkçe versiyonu aşağıdadır.*

> **⚠️ Note:** This repository is intended **strictly for portfolio and showcase purposes**. The source code for the Polymind ecosystem (Mobile App, Backend, Admin Panel, and App Landing) is maintained in private enterprise repositories to protect proprietary intellectual property and business logic.

## 🚀 About The Project
Polymind is not just a mobile application; it is a full-fledged language learning ecosystem designed to make language acquisition natural, immersive, and AI-supported. Currently live on the App Store, it combines advanced speech recognition, spaced repetition algorithms, and minigames to redefine the educational experience.

## 📸 Sneak Peek (Ecosystem Showcase)

<div align="center">
  <img src="assets/app_store_da_go%CC%88ru%CC%88nu%CC%88s%CC%A7u%CC%88.png" width="800" alt="App Store"/><br>
  <i>Live on the App Store</i>
</div>
<br>

<div align="center">
  <img src="assets/seviye_belirleme_s%C4%B1nav%C4%B1.png" width="250" alt="Placement Test"/>
  <img src="assets/gu%CC%88nlu%CC%88k_go%CC%88rev.png" width="250" alt="Daily Tasks"/>
  <img src="assets/profil%20ekran.png" width="250" alt="Profile Screen"/>
</div>
<br>

<div align="center">
  <img src="assets/oyunlar.png" width="800" alt="Interactive Games"/><br>
  <i>Built-in minigames powered by Flame Engine</i>
</div>
<br>

<div align="center">
  <img src="assets/website.png" width="400" alt="Website"/>
  <img src="assets/admin_panel.png" width="400" alt="Admin Panel"/>
</div>

---

## 🏗️ Technical Architecture & Tech Stack

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
---

# Türkçe Versiyon 🇹🇷

> **⚠️ Not:** Bu depo yalnızca **portfolyo ve sergileme amaçlıdır**. Polymind ekosistemine ait (Mobil, Backend, Admin, Web) tüm kaynak kodlar, fikri mülkiyeti ve sistem güvenliğini korumak amacıyla gizli (private) depolarda tutulmaktadır.

## 🚀 Proje Hakkında
Polymind, yeni bir dil öğrenme sürecini doğal, sürükleyici ve yapay zeka destekli hale getirmek için sıfırdan geliştirilmiş devasa bir eğitim ekosistemidir. Şu an App Store'da yayında olan sistem; ileri düzey konuşma tanıma, aralıklı tekrar algoritmaları ve mini oyunları harmanlayarak dil eğitimine yeni bir standart getirmektedir.

## 🏗️ Teknik Mimari ve Teknoloji Yığını

Polymind, son teknoloji kurumsal standartlar baz alınarak birbirinden bağımsız 4 farklı projeden oluşmaktadır.

### 1. Mobil Uygulama (iOS/Android)
60fps+ "native" deneyim sunması için optimize edilmiştir.
* **Altyapı:** Flutter SDK, Dart
* **State Management (Durum Yönetimi):** Riverpod, GoRouter
* **Oyun & Animasyon:** Flame Engine (uygulama içi 2D oyunlar için), Lottie, Liquid Swipe
* **Entegrasyonlar:** RevenueCat (Uygulama İçi Satın Alma), Firebase (Analytics, Crashlytics, vb.), Google AdMob.
* **AI & Donanım:** Sesli okuma ve kullanıcının telaffuzunu ölçmek için Speech-to-Text & TTS altyapısı.

### 2. Gelişmiş API Backend (Sunucu)
İş mantığını, kullanıcı verilerini ve anlık veri aktarımlarını inanılmaz bir hızda işleyen mimari.
* **Altyapı:** Node.js, Fastify (Yüksek performanslı sunucu)
* **Veritabanı & ORM:** SQL + Prisma DB
* **AI Entegrasyonu:** Groq SDK kullanılarak yapay zekanın kullanıcılara kişiselleştirilmiş içerik üretmesi.
* **Güvenlik:** JWT, Bcrypt, Fastify Rate Limit. Medya yönetimi için Cloudinary.

### 3. Yönetim & Admin Paneli
Mobil uygulamadaki içeriklerin dışarıdan dinamik olarak yönetilebilmesi için tasarlanmış panel.
* **Altyapı:** React 19, TypeScript, Vite
* **Özellik:** Derslerin, flashcard'ların ve kullanıcıların yönetilmesi. Mobil tarafı güncellemeden saniyeler içinde yeni ders eklenebilmesini sağlayan CMS mimarisi.

### 4. Web Sitesi
Kusursuz SEO puanlarına sahip, kullanıcı edinim (acquisition) hunisi için geliştirilmiş açılış sayfası.
* **Altyapı:** Next.js 16, React 19, TypeScript
* **Tasarım:** Tailwind CSS v4, Framer Motion, Lenis (Pürüzsüz kaydırma/Smooth scroll).

---
*Developed & Maintained By [Alemgir](https://github.com/alemgir) - View on [App Store](https://apps.apple.com/us/app/polymind/id6757526614)*