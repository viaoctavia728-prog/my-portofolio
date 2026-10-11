# Portofolio Digital - Neha Anggreany Octavia

Website portofolio digital profesional untuk posisi **Backend Developer & Software Engineer**.
Dibangun menggunakan **HTML5**, **Tailwind CSS**, dan **Vanilla JavaScript** (ringan, responsif di perangkat mobile, dan tanpa dependensi rumit).

---

## 🚀 Cara Melihat Portofolio di Browser

### Opsi 1: Langsung Klik Dua Kali
Cukup klik dua kali file [`index.html`](file:///d:/protofolio/index.html) di file explorer Anda, file akan otomatis terbuka di browser favorit Anda (Chrome, Edge, Firefox, dll).

### Opsi 2: Menggunakan Local Server (Python)
Buka terminal / PowerShell di direktori ini (`d:\protofolio`) dan jalankan:
```bash
python -m http.server 8000
```
Lalu buka browser di alamat: [http://localhost:8000](http://localhost:8000).

---

## ✏️ Panduan Edit Manual (Yang Perlu Anda Isi)

Semua bagian yang perlu Anda isi secara manual sudah diberi tanda komentar khusus di dalam [`index.html`](file:///d:/protofolio/index.html). Anda cukup tekan `Ctrl + F` di editor kode dan cari kata kunci `EDIT MANUAL`:

1. **Email:**
   - Cari ID `email-text` (sekitar baris 417), ganti `email@domain.com` dengan alamat email aktif Anda.
2. **LinkedIn:**
   - Cari bagian `LINKEDIN` (sekitar baris 429), ganti `href="#"` dengan tautan profil LinkedIn Anda.
3. **GitHub:**
   - Cari bagian `GITHUB` (sekitar baris 448), ganti `href="#"` dan nama akun dengan link profil GitHub Anda.
4. **WhatsApp:**
   - Cari bagian `WHATSAPP` (sekitar baris 467), ganti `href="#"` dengan format link WhatsApp: `https://wa.me/628xxxxxxxxxx`.
5. **Repository SI-BANSOS JATIM:**
   - Cari teks `Featured Project` di bagian proyek (sekitar baris 250), ganti `href="#"` dengan tautan repositori GitHub proyek tersebut.
6. **File CV PDF:**
   - Simpan file CV Anda di folder ini (misal: `cv-neha.pdf`), lalu ubah tombol navbar `href="#contact"` menjadi `href="cv-neha.pdf" download`.

---

## ➕ Cara Menambah Proyek Backend Baru Nanti

Ketika Anda ingin memasukkan proyek backend kedua (misal proyek Express.js atau PHP), Anda cukup menyalin blok proyek pendukung di dalam `<section id="projects">` dan mengisi:
- Judul Proyek
- Tech Stack Badges
- Problem & Solution
- Link GitHub

---

## 🌐 Cara Deploy Gratis ke GitHub Pages

1. Buat repositori baru di GitHub dengan nama: `<username-kamu>.github.io` atau `portfolio`.
2. Push file `index.html` dan `README.md` ke branch `main`.
3. Buka tab **Settings** di GitHub repo -> masuk ke menu **Pages** -> pilih Source: **Deploy from a branch (main)**.
4. Website portofolio Anda langsung aktif online dalam beberapa menit!
