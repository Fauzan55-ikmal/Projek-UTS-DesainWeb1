# Test Plan

## 1. Navigasi
- Buka setiap halaman dari menu desktop.
- Uji menu mobile menggunakan `<details>`.
- Pastikan tautan logo kembali ke Beranda.
- Pastikan ikon Login membuka `login.html`.

## 2. Beranda
- Pastikan video latar tampil dan berjalan muted.
- Uji kontrol audio native dengan menekan Play dan Volume.
- Pastikan hero tidak terpotong pada desktop dan mobile.

## 3. Artikel
- Pilih setiap artikel dari panel samping.
- Pastikan artikel yang dipilih tampil dan artikel lain tersembunyi.
- Uji pilihan artikel menggunakan keyboard.

## 4. Destinasi
- Buka dan tutup ringkasan setiap kartu.
- Pilih Semua Tempat, Alam, Kota & Budaya, dan Ruang Publik.
- Pastikan kartu yang sesuai kategori tampil.

## 5. Diskusi dan Login
- Pastikan label terhubung dengan input yang tepat.
- Uji validasi email dan kolom wajib melalui browser.
- Pastikan tombol kirim demo tidak dapat digunakan dan keterangan batasan terlihat.

## 6. Responsivitas dan aksesibilitas
- Uji lebar 360 px, 768 px, 1024 px, dan 1440 px.
- Pastikan tidak ada horizontal overflow.
- Uji tab order, focus indicator, dan skip link.
- Uji gambar yang gagal dimuat; alt text harus tetap menjelaskan konteks gambar.

## 7. Pemeriksaan teknologi
- Pastikan tidak ada file `.js` dan `.json`.
- Pastikan tidak ada tag `<script>`.
- Pastikan setiap halaman menghubungkan stylesheet yang benar.
