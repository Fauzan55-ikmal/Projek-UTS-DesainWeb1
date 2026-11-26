# MAPAY BANDUNG — Project Overview

## Ringkasan
MAPAY BANDUNG adalah website panduan perjalanan bertema pariwisata untuk memperkenalkan suasana, tempat, dan cerita di kawasan Bandung Raya. Desain menggunakan gaya editorial dengan perpaduan warna hijau, warna netral hangat, tipografi serif untuk judul, dan sans-serif untuk teks isi.

## Tujuan
- Menyajikan inspirasi perjalanan di Bandung Raya.
- Menampilkan destinasi melalui gambar dan deskripsi singkat.
- Menyediakan halaman artikel, diskusi, dan form login demo.
- Menyusun lima halaman dengan karakter visual berbeda tetapi tetap dalam satu identitas.

## Teknologi
- HTML5 untuk struktur dan konten.
- CSS3 untuk layout, responsif, navigasi, efek visual, filter kategori sederhana, dan pergantian artikel.
- Tidak menggunakan JavaScript, JSON, framework, atau library.

## Lima halaman
1. `index.html` — beranda sinematik dengan video latar yang berjalan tanpa suara dan pemutar ambience opsional menggunakan kontrol audio bawaan browser.
2. `artikel.html` — artikel utama yang dapat diganti menggunakan radio button HTML dan CSS.
3. `destinasi.html` — kartu destinasi, ringkasan `<details>`, dan filter kategori berbasis radio + CSS.
4. `wilayah.html` — route file untuk ruang Diskusi, berisi form contoh dan posting contoh statis.
5. `login.html` — desain form masuk dengan validasi bawaan HTML; belum terhubung ke autentikasi.

## Cakupan
Termasuk: visual perjalanan Bandung Raya, gambar, deskripsi, navigasi ant halaman, form HTML, artikel, kartu destinasi, dan layout responsif.

Tidak termasuk: pencarian teks dinamis, autentikasi nyata, pengiriman dan penyimpanan diskusi, database, chat real-time, booking, pembayaran, dan pengelolaan konten dinamis.

## Catatan implementasi
Konten ditulis langsung pada HTML. Data destinasi dan artikel tidak diambil dari file JSON. Fitur yang memerlukan pemrosesan dinamis sengaja tidak disertakan untuk mematuhi batasan tugas.
