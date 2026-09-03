# Portofolio Resmi Kelompok 6 — PTI '24 (Semester 5)

Website portofolio kelompok statis satu halaman (*single-page portfolio*) yang dirancang dengan standar antarmuka modern, tipografi bersih, dark mode *slate-950*, dan layout responsif untuk memamerkan proyek rekayasa perangkat lunak mahasiswa Pendidikan Teknologi Informasi '24.

---

## 🌟 Fitur Utama Website

1. **Sticky Glassmorphism Navigation Bar**:
   - Branding logo lencana eksklusif kelompok.
   - Navigasi internal smooth scroll (`#hero`, `#projects`, `#team`, `#contact`).
   - Tautan langsung ke repositori GitHub tim.
   - Menu hamburger responsif untuk perangkat mobile.

2. **Hero Section High-Impact**:
   - Headline terstruktur: Baris atas `"PORTOFOLIO"` dan baris bawah `"KELOMPOK 6"` dengan aksen teks berkilau.
   - Subheadline ringkas mengenai identitas tim pengembang PTI '24 Semester 5.
   - Tombol Call-to-Action ganda: *"Lihat Proyek"* dan *"Tentang Tim"*.
   - Baris metrik cepat (2 Pilar, 100% Responsif, Modular Full-Stack, Standar Produksi PTI).

3. **Dual-Project Showcase (Split 2 Kolom Berdampingan)**:
   - **Kolom Kiri — Pilar Sektor Industri / Enterprise**:
     - Aksen tema **Amber / Orange** (`amber-500`, border khusus, dan glow saat kursor diarahkan).
     - Proyek: *ProTrack ERP — Sistem Manajemen Aset & Logistik Terpadu*.
     - Mockup UI interaktif berbasis CSS/SVG dengan live metric dashboard status server & efisiensi.
     - Ringkasan eliminasi bottleneck persetujuan dan pelacakan inventaris real-time.
     - Tech stack badges: Laravel 11, MySQL 8.0, RESTful API, Tailwind CSS, Redis Cache, Docker.
     - Tombol aksi: *"Live Demo"* (modal simulasi interaktif) dan *"Dokumentasi / Kode"*.
   - **Kolom Kanan — Pilar Sektor Pendidikan / EdTech**:
     - Aksen tema **Cyan / Sky** (`cyan-400`, border khusus, dan glow saat kursor diarahkan).
     - Proyek: *EduQuest LMS — Platform Pembelajaran Interaktif & Tergamifikasi*.
     - Mockup UI interaktif berbasis CSS/SVG dengan Student HUD, skill tree, dan progress quest.
     - Fokus media & metode edukatif: pedagogi *micro-learning* dan *gamification engine*.
     - Tech stack badges: Next.js / React, Node.js, WebSockets, Tailwind CSS, PostgreSQL, Canvas API.
     - Tombol aksi: *"Live Demo"* (modal simulasi interaktif) dan *"Dokumentasi / Kode"*.

4. **Team Showcase Responsif**:
   - Grid 4 profil anggota tim dengan avatar inisial modern beraksen gradasi neon.
   - Spesialisasi peran (Project Lead & System Architect, Frontend & UI/UX Specialist, Backend & Database Engineer, Systems Analyst & QA Engineer).
   - Penjabaran kontribusi spesifik pada masing-masing pilar (Pilar Industri & Pilar Pendidikan).
   - Tautan profil profesional (GitHub dan LinkedIn).

5. **Footer & Kontak Terintegrasi**:
   - Formulir kontak cepat terhubung langsung ke aplikasi email (`mailto`).
   - Informasi institusi Pendidikan Teknologi Informasi '24.
   - Hak cipta semester 5 dan navigasi *Kembali ke Atas*.

---

## 🛠️ Tech Stack & Spesifikasi

- **Markup**: Pure Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`)
- **Styling**: Tailwind CSS CDN + Google Fonts (*Inter* & *JetBrains Mono*)
- **Theme**: Dark Modern Palette (`slate-950`, `slate-900`, `slate-800`, `amber-500`, `cyan-400`)
- **Script**: Vanilla JavaScript modern (tanpa dependensi eksternal) untuk menu toggle, simulasi modal demo, dan form handler.

---

## 🚀 Cara Menjalankan Secara Lokal

Website ini berformat murni statis tanpa perlu proses build atau instalasi dependensi NPM:

### Opsi 1: Menggunakan Python Built-in Server (Rekomendasi)
Buka terminal pada direktori proyek ini, lalu jalankan:
```bash
python -m http.server 8080
```
Buka peramban (browser) di alamat: [http://localhost:8080](http://localhost:8080)

### Opsi 2: Buka Langsung File HTML
Cukup klik dua kali (*double click*) file `index.html` pada File Explorer untuk membukanya langsung di browser favorit Anda.

