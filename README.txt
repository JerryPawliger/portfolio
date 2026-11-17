JERRY PORTFOLIO 2027 — RESPONSIVE / OPTIMIZED

Isi:
- index.html : seluruh HTML, CSS, dan JavaScript
- assets/ : 31 gambar WebP (1 foto profil + 30 karya)
- PANDUAN_GITHUB.txt : langkah publikasi

Pembaruan desain:
1. Introduce Jerry berada di hero paling awal, dengan foto asli.
2. Hierarki tipografi editorial yang konsisten pada desktop, tablet, dan mobile.
3. Bento grid proyek yang menyesuaikan lebar layar tanpa horizontal overflow.
4. Maja Group Investama membuka Instagram langsung.
5. Raja Esports, PWLGR Studio, Flazz Arceus, NGID Esports, dan Other Design punya galeri masing-masing (6 gambar).
6. Filter proyek Corporate / Esports / Independent.
7. Galeri dengan tombol next/previous, thumbnail, tombol close, Escape, dan swipe di layar sentuh.
8. AI workflow ChatGPT dan Claude tetap ditampilkan.
9. Animasi judul berbasis CSS transform/opacity, reveal berbasis IntersectionObserver, tanpa canvas berat.
10. Mendukung prefers-reduced-motion dan lazy-loading gambar karya.

Performa:
- Semua gambar lokal menggunakan format WebP.
- Tidak memakai library JavaScript eksternal.
- Tidak memakai canvas yang berjalan pada setiap frame.
- Menggunakan dua font (Space Grotesk dan DM Sans) dari Google Fonts, dengan fallback standar.

Pengujian:
- Ukuran layar 1440, 820, 390, dan 320 piksel.
- Tidak ditemukan horizontal overflow atau error JavaScript.
- Filter dan semua galeri berhasil diuji.
- Akurasi tautan Instagram dan keberadaan seluruh file gambar diperiksa.

Catatan: Website ini belum diunggah otomatis ke GitHub. Ganti file index.html dan folder assets pada branch main.
