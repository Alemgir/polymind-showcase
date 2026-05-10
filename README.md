# Polymind - Yapay Zeka Destekli Dil Öğrenme Ekosistemi 🌍🧠

👉 **[Read in English (İngilizce Versiyon İçin Tıklayın)](README_EN.md)** 👈

[![App Store](https://img.shields.io/badge/Download_on-App_Store-black?style=for-the-badge&logo=apple)](https://apps.apple.com/us/app/polymind/id6757526614)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)

> **⚠️ Not:** Bu depo yalnızca **portfolyo ve sergileme amaçlıdır**. Polymind ekosistemine ait (Mobil, Backend, Admin, Web) tüm kaynak kodlar, fikri mülkiyeti ve sistem güvenliğini korumak amacıyla gizli (private) depolarda tutulmaktadır.

## 🚀 Proje Hakkında
Polymind, yeni bir dil öğrenme sürecini doğal, sürükleyici ve yapay zeka destekli hale getirmek için sıfırdan geliştirilmiş devasa bir eğitim ekosistemidir. Şu an App Store'da yayında olan sistem; ileri düzey konuşma tanıma, aralıklı tekrar algoritmaları ve mini oyunları harmanlayarak dil eğitimine yeni bir standart getirmektedir.

## 📸 Ekosistem Görselleri

### 🏠 Ana Ekran (Home Page)
*(Not: Portfolio için `assets` klasörüne `home_page.png` isimli resminizi eklediğinizde burada tam boyutuyla harika gözükecektir.)*
<div align="center">
  <img src="assets/home_page.png" width="300" alt="Yakında Eklenecek"/>
</div>

### 📝 App Store Mağaza Görünümü
<div align="center">
  <img src="assets/app_store_da_görünüşü.png" width="800" alt="App Store"/>
</div>

### 🎯 Öğrenci Seviye Belirleme Sınavı
<div align="center">
  <img src="assets/seviye_belirleme_sınavı.png" width="300" alt="Seviye Belirleme"/>
</div>

### 📅 Günlük Görevler ve İlerleyiş
<div align="center">
  <img src="assets/günlük_görev.png" width="300" alt="Günlük Görev"/>
</div>

### 👤 Kullanıcı Profil Ekranı
<div align="center">
  <img src="assets/profil ekran.png" width="300" alt="Profil Ekranı"/>
</div>

### 🎮 İnteraktif Mini Oyunlar (Flame Engine)
<div align="center">
  <img src="assets/oyunlar.png" width="800" alt="Oyunlar"/>
</div>

### 💻 CMS / Admin Yönetim Paneli
<div align="center">
  <img src="assets/admin_panel.png" width="800" alt="Admin Panel"/>
</div>

### 🌐 Mobil Uygulama Tanıtım (Landing) Sayfası
<div align="center">
  <img src="assets/website.png" width="800" alt="Website"/>
</div>

---

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