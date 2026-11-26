# Technical Architecture — Static HTML/CSS

## 1. Prinsip
MAPAY BANDUNG menggunakan arsitektur multi-page static website. Setiap halaman berupa file HTML terpisah dan menggunakan stylesheet bersama.

## 2. Teknologi
- HTML5: struktur dokumen, semantic landmarks, navigasi, gambar, video, audio, form, radio control, dan disclosure widget.
- CSS3: reset, variabel warna, layout, grid, flexbox, media query, hover/focus, transition, keyframes, dan state berdasarkan radio `:checked`.
- Tidak ada JavaScript, JSON, framework, library, bundler, atau proses build.

## 3. Pola halaman
Setiap file HTML menghubungkan `src/css/main.css`. File utama tersebut mengimpor stylesheet dasar, layout, komponen, dan halaman menggunakan CSS `@import`.

## 4. Navigasi
Navigasi desktop menggunakan elemen `<nav>` dan tautan biasa. Navigasi mobile memakai `<details>` dan `<summary>` sehingga tidak memerlukan script.

## 5. Interaksi CSS-only
- Pemilihan artikel memanfaatkan input radio dan selector `:checked`.
- Filter kategori destinasi menggunakan radio dan general sibling selector `~`.
- Kartu destinasi memakai `<details>`.
- Audio menggunakan kontrol native HTML.

## 6. Form
Form Diskusi dan Login menggunakan label, tipe input, `required`, `minlength`, dan `maxlength` untuk demonstrasi serta validasi dasar browser. Tanpa endpoint/server, form tidak mengirim maupun menyimpan informasi.

## 7. Media
Video latar diputar muted agar kebijakan autoplay browser terpenuhi. Pengunjung dapat memutar audio ambience terpisah melalui kontrol audio bawaan. Foto, video, audio, dan font tertentu berasal dari layanan eksternal, sehingga membutuhkan koneksi internet.

## 8. Batasan
Tidak ada API, localStorage, pencarian teks dinamis, akun, autentikasi, database, atau pengiriman diskusi. Batasan tersebut disengaja untuk mengikuti ketentuan tugas HTML dan CSS saja.
