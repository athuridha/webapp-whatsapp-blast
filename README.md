﻿# 🚀 WA Blast WebApp

Aplikasi web untuk mengirim pesan WhatsApp massal (blast) dengan fitur lengkap, mudah digunakan, dan cocok untuk kebutuhan promosi, notifikasi, atau komunikasi bisnis.

---

## ✨ Fitur Utama
- **Kirim Pesan Blast** ke banyak kontak sekaligus
- **Kirim Media** (gambar, video, PDF) ke banyak nomor
- **Import Kontak** dari file Excel/CSV (template tersedia)
- **Generate Nomor WhatsApp Random** (hanya yang terdaftar/terverifikasi WhatsApp)
- **Export Nomor ke Excel** hasil generate
- **Riwayat Pengiriman** lengkap & bisa dihapus massal
- **Auto Reply** WhatsApp
- **Pengaturan Jeda & Batas Blast** (termasuk tanpa batas)
- **Login Admin** (proteksi akses)
- **Logout & Proteksi Session**

---

## 📦 Struktur Project
- `src/` — Frontend React (UI, pages, components)
- `server/` — Backend Node.js/Express (API, WhatsApp automation)
- `template_kontak.xlsx` — Template import kontak

---

## ⚡️ Cara Menjalankan Lokal
1. **Clone repo & install dependencies**
   ```powershell
   git clone https://github.com/athuridha/webapp-blast.git
   cd webapp-blast
   npm install
   cd server
   npm install
   ```
2. **Jalankan backend**
   ```powershell
   node index.js
   ```
3. **Jalankan frontend**
   ```powershell
   cd ..
   npm run dev
   ```
4. **Akses di browser:**
   - Frontend: [http://localhost:5173](http://localhost:3000)
   - Backend API: [http://localhost:5000](http://localhost:5000)

---

## 🛠️ Deploy
- Deploy backend di VPS/Cloud (Node.js, Chrome/Chromium harus tersedia)
- Deploy frontend (build) di hosting static (Vercel, Netlify, atau server sendiri)
- Gunakan PM2 untuk menjaga backend tetap berjalan

---

## 📄 Template Import Kontak
Download: [template_kontak.xlsx](./template_kontak.xlsx)

---

## 📤 Export Nomor WhatsApp
- Hasil generate nomor WhatsApp random dapat diexport langsung ke file Excel (.xlsx) melalui tombol "Export ke Excel" di halaman Generate Number.
- Nomor yang diexport hanya yang sudah terverifikasi terdaftar di WhatsApp.

---

## 👨‍💻 Kontribusi & Lisensi
- Pull request & issue sangat diterima!
- Lisensi: MIT

---

