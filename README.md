# Cahaya AI — PABWE P2

Website studi kasus perusahaan jasa **Artificial Intelligence (AI)** untuk praktikum PABWE.

## Identitas Proyek

- **Nama proyek:** `cahaya-pabwe-p2`
- **Nama aplikasi/brand:** Cahaya AI
- **Tema:** Jasa Artificial Intelligence
- **Bahasa:** Bahasa Indonesia
- **Tahun:** 2026

## Struktur Folder

```text
cahaya-pabwe-p2/
├── index.html
├── blog.html
├── blog-detail.html
├── cv.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── img/
```

## Halaman

### 1. Landing Page — `index.html`

Menggunakan:
- Semantic HTML5
- CSS murni
- External CSS: `assets/css/style.css`
- CSS Variables
- Flexbox
- CSS Grid
- Hover dan transition
- Media query untuk responsive
- Google Fonts

Tidak menggunakan Bootstrap, Tailwind, atau framework CSS lain.

Bagian utama:
- Navbar
- Hero
- Layanan
- Tentang
- Kontak
- Footer

### 2. Daftar Blog — `blog.html`

Menggunakan:
- Bootstrap 5.3.8
- Bootstrap Icons
- Navbar
- Container
- Row dan Column
- Card
- Badge
- Footer
- Responsive layout

Terdapat 4 artikel bertema AI.

### 3. Detail Blog — `blog-detail.html`

Menggunakan:
- Bootstrap 5.3.8
- Bootstrap Icons
- Cover artikel
- Meta informasi
- Isi artikel minimal 3 paragraf
- Blockquote
- Alert
- List
- Form komentar

Semua judul artikel pada `blog.html` mengarah ke `blog-detail.html`.

### 4. Curriculum Vitae — `cv.html`

Menggunakan:
- Tailwind CSS 4 melalui Play CDN
- Utility class
- `@theme` untuk token warna
- Flexbox
- Grid
- Responsive prefix
- Hover dan transition

## Integrasi Navigasi

Semua halaman saling terhubung:

```text
index.html
   ├── blog.html
   └── cv.html

blog.html
   ├── index.html
   ├── cv.html
   └── blog-detail.html

blog-detail.html
   ├── index.html
   ├── blog.html
   └── cv.html

cv.html
   ├── index.html
   └── blog.html
```

## Cara Menjalankan

Tidak membutuhkan server khusus.

1. Buka folder `cahaya-pabwe-p2` di VS Code.
2. Pastikan struktur folder sesuai README.
3. Buka `index.html` menggunakan browser.
4. Untuk pengalaman pengembangan yang lebih nyaman, dapat menggunakan extension **Live Server** di VS Code.
5. Pastikan koneksi internet tersedia karena Bootstrap, Bootstrap Icons, Tailwind Play CDN, Google Fonts, dan gambar blog menggunakan sumber eksternal.

## Catatan

- Gambar blog menggunakan URL publik dari Unsplash.
- Form kontak dan komentar merupakan tampilan frontend dan belum terhubung ke backend.
- Data CV dapat disesuaikan dengan data mahasiswa sebelum dikumpulkan.
- Email, GitHub, LinkedIn, dan informasi profil pada `cv.html` sebaiknya diganti dengan data asli jika diperlukan.

## Checklist Studi Kasus

- [x] Landing page dengan external CSS
- [x] Tidak menggunakan framework CSS pada landing page
- [x] Minimal 3 layanan AI
- [x] Responsive desktop dan mobile
- [x] Blog list menggunakan Bootstrap 5
- [x] Bootstrap Icons digunakan
- [x] Minimal 4 artikel AI
- [x] Judul artikel membuka `blog-detail.html`
- [x] Detail blog memiliki minimal 3 paragraf
- [x] CV menggunakan Tailwind CSS 4
- [x] Semua halaman memiliki navigasi
- [x] Identitas Cahaya AI konsisten
- [x] README tersedia
