# ☢️ Project E.M.P - Blackridge Facility

> *"Kumpulkan bukti. Temukan 3 kunci utama. Cari jalan keluar lain. Dan apa pun yang terjadi... Bersembunyilah jika dia mendekat."*

**Project E.M.P** adalah sebuah purwarupa antarmuka *Web-Based Escape Room / Horror Game* yang berlatar di Laboratorium Riset Blackridge—sebuah fasilitas yang ditinggalkan akibat rumor gelap tentang eksperimen tak manusiawi. Pemain ditantang untuk meretas sistem, memecahkan teka-teki, dan bertahan hidup dari apa pun yang terkurung di dalam kegelapan.

Proyek ini merupakan hasil *revamp* dari HTML/JS/CSS vanilla menjadi **Single Page Application (SPA)** modern untuk memastikan performa yang lebih mulus dan pengalaman pengguna yang lebih imersif.

---

## 🛠️ Tech Stack & Architecture

Proyek ini dibangun menggunakan teknologi *frontend* modern:

* **Framework:** Next.js (App Router)
* **Library:** React (State Management & Hooks)
* **Styling:** Tailwind CSS v4
* **Design Trend:** Glassmorphism UI & Sci-Fi Dashboard Aesthetics

---

## ✨ Key Features

* **Modern SPA Navigation:** Perpindahan antar layar (Home, Settings, Credits, Loading) terjadi secara instan tanpa memuat ulang (*reload*) *browser*, diatur menggunakan `useState` React.
* **Auto-Scaling Engine:** Menggunakan utilitas `aspect-video` dari Tailwind untuk memastikan tampilan *game* selalu mempertahankan rasio 16:9 (1920x1080) di berbagai ukuran layar secara natural tanpa mengorbankan performa JS.
* **Immersive Glassmorphism UI:** Panel pengaturan dan menu dibuat dengan efek kaca transparan (*backdrop-blur*) yang menyatu dengan *background* beresolusi tinggi.
* **Optimized Memory Management:** Efek *Typewriter* (mengetik) dan *Loading Bar* diisolasi menggunakan `useEffect` dengan fungsi *cleanup* yang ketat untuk mencegah *memory leak*.
* **Interactive Settings:** Slider kustom untuk *Brightness*, *Volume*, dan *Music*, serta *toggle* status *Hint* yang reaktif.

---

## 🚀 How to Run Locally

Jika kamu ingin menjalankan proyek ini di komputermu sendiri, ikuti langkah-langkah berikut:

**1. Clone Repository**
\`\`\`bash
git clone https://github.com/username-kamu/project-emp-next.git
cd project-emp-next
\`\`\`

**2. Install Dependencies**
Pastikan kamu sudah menginstal [Node.js](https://nodejs.org/). Kemudian jalankan:
\`\`\`bash
npm install
\`\`\`

**3. Run Development Server**
\`\`\`bash
npm run dev
\`\`\`
Buka [http://localhost:3000](http://localhost:3000) di *browser* pilihanmu untuk melihat hasilnya.

---

## 👥 Development Team (Group 5)

* **Fhatur Aziz Gustiyana** - Game Director, UI/UX Designer, Lead Programmer
* **Falatehan Ramadhan Fahmi** - Game Idea
* **Jekki Hatigoran Hutabarat** - Production Support
* **Januari Putra Mulyono** - General Member
* **M. Calvin Alfarisi** - General Member

**Special Thanks To:** * **Resa Pramudita, S.Pd., M.T.**
* **Gemini AI** (Co-Programmer)
* **ChatGPT / DALL-E** (Visual Assets)

---
*© 2026 Project E.M.P - Blackridge Facility. All Rights Reserved.*