# Software Requirements Specification (SRS)

## 1. Tujuan
Dokumen ini mendefinisikan kebutuhan MAPAY BANDUNG untuk proyek UTS Desain Web 1. Website dibuat sebagai panduan wisata statis Bandung Raya.

## 2. Pengguna
Pengunjung umum yang ingin melihat inspirasi destinasi dan membaca informasi perjalanan.

## 3. Kebutuhan Fungsional

| ID | Kebutuhan | Implementasi |
|---|---|---|
| FR-01 | Pengunjung dapat berpindah halaman | Link HTML pada navigasi |
| FR-02 | Pengunjung dapat melihat identitas dan pengantar wisata | Hero pada Beranda |
| FR-03 | Pengunjung dapat melihat gambar dan deskripsi destinasi | Kartu HTML statis |
| FR-04 | Pengunjung dapat membuka ringkasan destinasi | Elemen `<details>` dan `<summary>` |
| FR-05 | Pengunjung dapat memilih kategori destinasi | Radio button dan CSS sibling selector |
| FR-06 | Pengunjung dapat memilih artikel | Radio button dan CSS sibling selector |
| FR-07 | Pengunjung dapat mengisi form diskusi demo | Form HTML dengan validasi bawaan |
| FR-08 | Pengunjung dapat mengisi form login demo | Input email dan password dengan atribut HTML |
| FR-09 | Pengunjung dapat memutar ambience | Elemen `<audio controls>` |

## 4. Kebutuhan Nonfungsional
- Tampilan konsisten dengan identitas MAPAY BANDUNG.
- Layout menyesuaikan layar desktop, tablet, dan mobile.
- Navigasi dapat digunakan dengan keyboard.
- Gambar memiliki teks alternatif.
- Tidak menggunakan library atau framework.
- Tidak menggunakan JavaScript atau JSON.
- Struktur file dan penamaan mudah dipahami mahasiswa pemula.

## 5. Batasan dan Asumsi
- Konten bersifat statis dan ditulis langsung pada file HTML.
- Filter kategori hanya mengubah tampilan kartu yang sudah ada.
- Form Diskusi hanya contoh tampilan; tidak mengirim atau menyimpan posting.
- Form Login hanya contoh tampilan; tidak memverifikasi akun.
- Media eksternal memerlukan koneksi internet.
- Tidak ada backend maupun database.

## 6. Acceptance Criteria
- Terdapat tepat lima halaman HTML.
- Semua halaman memiliki navigasi yang konsisten.
- Setiap halaman memiliki susunan konten yang berbeda tetapi satu tema.
- Destinasi menampilkan gambar dan deskripsi.
- Artikel dapat berganti melalui pilihan radio.
- Filter destinasi dapat digunakan tanpa JavaScript.
- Form memiliki label dan tipe input yang sesuai.
- Tidak terdapat file `.js` atau `.json` pada project.
