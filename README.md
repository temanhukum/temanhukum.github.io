# ⚖️ Teman Hukum UMKM

> **Platform Penjadwalan Edukasi & Pendampingan Hukum Praktis untuk Pelaku Usaha Mikro, Kecil, dan Menengah (UMKM) Indonesia.**

---

## 👤 Inisiator & Penanggung Jawab Layanan
* **Nama:** Bunga Tesalonika Lempang
* **NIM:** B011251165
* **Fakultas:** Fakultas Ilmu Hukum

Inisiatif ini dirancang untuk memberikan literasi hukum yang aplikatif, mudah dipahami, dan ramah bagi pelaku UMKM agar memiliki fondasi legalitas yang kokoh tanpa rasa cemas.

---

## 📁 Struktur Folder Proyek

```text
temanhukum/
├── assets/
│   ├── icons/                 # Favicon dan ikon web multi-ukuran
│   │   ├── favicon.svg        # Ikon vektor resolusi tinggi
│   │   ├── favicon.png        # Ikon browser 512x512
│   │   ├── favicon-32x32.png  # Ikon tab browser 32x32
│   │   └── apple-touch-icon.png # Ikon homescreen smartphone 192x192
│   └── images/
│       └── og-image.png       # Banner Open Graph 1200x630 (WhatsApp/Social Share)
│
├── backend/
│   └── google-apps-script.js  # Kode API Google Apps Script & Integrasi Google Sheets
│
├── index.html                 # Landing Page Publik & Sistem Reservasi Klien
├── admin.html                 # Portal Admin (Autentikasi Sheet & Manajemen Sesi)
└── README.md                  # Dokumentasi Proyek
```

---

## ✨ Fitur Utama

1. **Landing Page Edukatif (`index.html`)**:
   - Kurikulum topik hukum (NIB OSS, Merek Dagang DJKI, Kontrak Bisnis, Sertifikasi Halal, Pajak UMKM).
   - Profil resmi petugas pendamping hukum.
   - Section **Jadwal Edukasi & Klien Terdaftar** yang memuat jadwal terkonfirmasi secara real-time.
   - Sistem reservasi online interaktif dengan ringkasan tiket dan nomor kode booking unik.

2. **Database Serverless (Google Spreadsheet & Apps Script)**:
   - **Tab `akun`**: Tempat penyimpanan data autentikasi login pengelola (Username & Password).
   - **Tab `reservasi`**: Menampung data reservasi masuk dari klien.
   - Menggunakan Google Apps Script sebagai REST API tanpa biaya server (100% gratis).

3. **Portal Admin (`admin.html`)**:
   - Sistem login terautentikasi langsung ke Google Spreadsheet.
   - Dashboard analitik ringkasan reservasi.
   - Filter topik, pencarian data klien, dan tombol kontak langsung via WhatsApp.
   - **Modal Atur Jadwal & Link Meeting**: Admin dapat menetapkan tautan Google Meet / Zoom dan mempublikasikan statusnya ke halaman publik.

4. **Keamanan & Privasi Data**:
   - Nomor WhatsApp dan Email klien disembunyikan dari halaman publik, hanya inisial nama dan nama brand usaha yang ditampilkan pada jadwal terbuka.
   - Open Graph Media Tags (`og-image.png`) untuk pratinjau tautan WhatsApp/Medsos yang memukau.

---

## 🚀 Panduan Hosting di GitHub Pages

1. Buat repositori baru di GitHub dengan nama `temanhukum`.
2. Unggah seluruh isi folder ini ke repositori tersebut.
3. Masuk ke tab **Settings** > **Pages**.
4. Pada bagian **Branch**, pilih `main` / `root`, lalu klik **Save**.
5. Website Anda akan aktif di alamat: `https://<username>.github.io/temanhukum/`.

---

© 2026 Teman Hukum UMKM. Seluruh Hak Cipta Dilindungi.
