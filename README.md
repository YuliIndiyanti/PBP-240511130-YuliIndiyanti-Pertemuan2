# Praktikum Pemrograman Berbasis Platform - Pertemuan 2

Repository ini berisi hasil pengerjaan **Lembar Kerja Praktikum 2A (LKP 2A)**: *Halaman Profil Pribadi dengan HTML5 & CSS Dasar*.

---

## Identitas Mahasiswa
- **Nama:** Yuli Indiyanti
- **NIM:** 240511130
- **Program Studi:** S1 Teknik Informatika
- **Perguruan Tinggi:** Universitas Muhammadiyah Cirebon
- **Mata Kuliah:** Pemrograman Berbasis Platform
- **Tahun Akademik:** 2026

---

## Struktur Folder & Berkas
```text
PERTEMUAN 2/
├── README.md                      # Dokumentasi praktikum
└── lpk-2a/
    ├── assets/
    │   └── foto.jpg               # Foto profil mahasiswa
    ├── index.html                 # Struktur dokumen HTML5 semantik
    ├── style.css                  # Berkas styling CSS tema Strawberry Matcha
    └── screenshot-halaman.png     # Tangkapan layar hasil tampilan di browser
```

---

## Penjelasan Komponen Implementasi

### 1. Struktur HTML5 Semantik (`index.html`)
- Menggunakan tag semantik standar HTML5 untuk mempermudah pembacaan mesin (SEO & aksesibilitas):
  - `<header>`: Memuat avatar profil (`<img>`), nama lengkap (`<h1>`), dan identitas mahasiswa (`<p>`).
  - `<nav>`: Menu navigasi tautan internal berbasis anchor (`#tentang`, `#keahlian`, `#kontak`).
  - `<main>`: Membungkus konten utama halaman profil:
    - `<section id="tentang">`: Ringkasan profil dan latar belakang keilmuan.
    - `<section id="keahlian">`: Daftar keahlian teknis dalam bentuk kartu (HTML & CSS, JavaScript, Java, Kotlin).
    - `<section id="kontak">`: Tautan surel (`mailto:`) dan profil GitHub.
  - `<footer>`: Informasi hak cipta (*copyright*).

### 2. Styling & Layout Modern (`style.css`)
- **Tema Warna Strawberry Matcha:**
  - **Strawberry Pink (Dominan):** Merah muda strawberry (`#9e2f4b`, `#c94668`, `#e36a88`) dan latar lembut (`#fff8fa`).
  - **Matcha Green (Aksen):** Hijau matcha untuk border aksen dan efek hover (`#527850`, `#6e996b`, `#eef5ed`).
- **Layout Flexbox (`nav`):** Mengatur posisi tautan navigasi horizontal secara terpusat (`justify-content: center`).
- **Layout CSS Grid (`.cards`):** Menampilkan daftar keahlian secara responsif (`repeat(auto-fit, minmax(180px, 1fr))`).
- **Interaktivitas:** Efek hover lembut (*scale* pada foto profil, elevasi bayangan kartu, dan pil merah muda pada tautan menu).

---

## Cara Menjalankan Halaman
Buka file `lpk-2a/index.html` langsung pada browser web atau melalui terminal:
```powershell
start lpk-2a/index.html
```
