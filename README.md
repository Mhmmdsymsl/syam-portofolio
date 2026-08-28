# Portfolio — Muhammad Syamsul Muarif

Website portfolio statis, responsive, dan siap hosting. Tidak memerlukan proses build atau instalasi paket apa pun.

Versi ini sudah menggunakan tujuh kelompok proyek asli: desain feed F&B, animated business icons, animated healthcare icons, abstract pattern animations, iklan produk, koleksi logo aplikasi, dan biometric dashboard motion.

## Sebelum dipublikasikan

1. Buka `index.html` dan ganti `hello@yourdomain.com` dengan email aktif.
2. Ganti semua tautan sosial `href="#"` dengan URL Instagram, Behance, LinkedIn, dan Dribbble.
3. Sesuaikan deskripsi proyek atau angka statistik bila diperlukan.
4. Semua media proyek berada di `assets/projects`. Detail, tools, dan daftar media setiap proyek berada di `assets/script.js`.

## Preview lokal

Klik dua kali `index.html` untuk membukanya langsung di browser. Semua filter, navigasi, animasi, dan modal detail dapat berjalan tanpa server.

## Hosting di Cloudflare Pages

1. Masuk ke Cloudflare Dashboard → **Workers & Pages**.
2. Pilih **Create application** → **Pages** → **Upload assets**.
3. Beri nama project, lalu unggah folder ini atau file ZIP-nya.
4. Pilih **Deploy site**. Tidak perlu build command atau environment variable.

## Hosting di GitHub Pages

1. Buat repository baru lalu unggah seluruh isi folder ini ke root repository.
2. Buka **Settings** → **Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu simpan.

## Struktur

```text
muhammad-syamsul-portfolio/
├── index.html
├── README.md
└── assets/
    ├── styles.css
    └── script.js
```

Font menggunakan Google Fonts dan memerlukan internet saat pertama kali dimuat. Bila offline, website otomatis memakai font sistem sebagai fallback.
