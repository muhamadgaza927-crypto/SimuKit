# 🛠️ SimuKit - Simulasi Merakit

**SimuKit** adalah sebuah sistem manajemen pembelajaran untuk siswa dan guru dengan fitur simulasi merakit pc yang embedded dan terintegrasi dengan LMS nya untuk mendukung pembelajaran

---

## Fitur & Halaman yang Tersedia

Saat ini, pengembangan antarmuka meliputi beberapa halaman utama:

1. **Landing Page (`landing_page.html`)**
   - Tampilan pembuka dengan tata letak *split-screen* (kiri: navigasi role, kanan: *background pattern*).
   - Pemilihan akses peran pengguna (**Siswa** dan **Guru**).

2. **Halaman Login Siswa (`login_siswa.html`)**
   - Form input untuk Username/Email dan Password.
   - Tombol **Login** (terintegrasi langsung ke halaman Dashboard Siswa).
   - Tombol **Register** untuk pendaftaran akun baru.

3. **Dashboard Siswa (`dashboard_siswa.html`)**
   - *Header Navbar* responsif dengan logo, judul dashboard, dan ikon profil.
   - Tampilan *empty state* yang menginformasikan status kelas siswa beserta tombol **Buka Profil**.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik halaman web.
- **CSS3**: Tata letak kustom (Flexbox, CSS Grid, Responsive Design).
- **Google Fonts**: Tipografi menggunakan font `Poppins`.

---

##  Struktur Folder Proyek

```text
SimuKit/
│
├── assets/                  # Folder aset gambar, logo, dan pattern
│   ├── logo.png
│   ├── iconsiswa.png
│   └── pattern.png
│
├── landing_page.html               # Landing Page (Pilihan Role)
├── landing_page.css                # Styling untuk Landing Page
│
├── login_siswa.html         # Halaman Login Siswa
├── login_siswa.css          # Styling untuk Halaman Login Siswa
│
├── dashboard_siswa.html     # Halaman Dashboard Siswa
├── dashboard_siswa.css      # Styling untuk Dashboard Siswa
│
└── README.md                # Dokumentasi Proyek
