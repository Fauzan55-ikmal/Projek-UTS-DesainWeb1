# MAPAY BANDUNG

**Website Panduan Perjalanan Bandung Raya**  
**UTS Desain Web 1 — Politeknik TEDC Bandung**

MAPAY BANDUNG adalah website bertema pariwisata yang dibuat untuk memperkenalkan berbagai suasana dan destinasi di kawasan Bandung Raya. Website ini dirancang sebagai panduan perjalanan sederhana dengan gaya visual editorial, foto dan video sebagai elemen utama, serta informasi yang disajikan melalui lima halaman dengan susunan berbeda.

Proyek ini dikembangkan sebagai tugas kelompok Ujian Tengah Semester mata kuliah **Desain Web 1**. Implementasinya mengikuti batasan teknologi pada soal, yaitu **HTML5 dan CSS3**, tanpa JavaScript, JSON, framework, maupun library tambahan.

---

## Identitas Kelompok

| Identitas | Keterangan |
|---|---|
| Nama Anggota 1 | **Fauzan Fauzia Fauzi** |
| NIM | D112521003 |
| Nama Anggota 2 | **Muhammad Tsaqofa Ahsan** |
| NIM | D112521008 |
| Nama Anggota 3 | **Rizky Natakusumah** |
| NIM | D112521009 |
| Kelas | IFK-25 |
| Program Studi | Sarjana Terapan Teknik Informatika (D4) |
| Institusi | Politeknik TEDC Bandung |
| Mata Kuliah | Desain Web 1 |
| Tema Website | Pariwisata — Panduan Perjalanan Bandung Raya |

---

## Tujuan Proyek

MAPAY BANDUNG dibuat untuk:

- Memperkenalkan tempat dan suasana perjalanan di kawasan Bandung Raya.
- Menyajikan informasi wisata melalui gambar, deskripsi, dan artikel singkat.
- Menampilkan lima halaman dengan struktur dan tujuan yang berbeda, tetapi tetap konsisten dalam satu identitas desain.
- Menerapkan materi HTML5 dan CSS3 yang dipelajari pada mata kuliah Desain Web 1.
- Melatih penyusunan halaman web yang rapi, menarik, responsif, dan mudah digunakan.

## Halaman Website

Website memiliki **lima halaman utama** sebagai berikut.

| Halaman | File | Fungsi dan Isi |
|---|---|---|
| **Beranda** | `index.html` | Landing page sinematik dengan video latar, pengenalan MAPAY BANDUNG, navigasi utama, serta tombol menuju Destinasi dan Diskusi. Audio ambience tersedia secara opsional melalui pemutar bawaan browser. |
| **Artikel** | `artikel.html` | Halaman editorial untuk membaca artikel perjalanan. Pengunjung dapat memilih artikel lain melalui radio button HTML; konten berganti menggunakan CSS tanpa berpindah halaman. |
| **Destinasi** | `destinasi.html` | Menampilkan kartu destinasi dengan gambar, kategori, judul, dan deskripsi. Filter kategori menggunakan radio button dan CSS, sedangkan ringkasan setiap destinasi menggunakan elemen `<details>` dan `<summary>`. |
| **Diskusi** | `wilayah.html` | Halaman berisi formulir diskusi dan contoh posting statis. Nama file `wilayah.html` dipertahankan, tetapi fungsi dan label navigasinya adalah **Diskusi**. |
| **Login** | `login.html` | Halaman formulir masuk sebagai demonstrasi desain antarmuka. Form menggunakan tipe input HTML yang sesuai dan validasi dasar browser, tetapi belum terhubung ke sistem akun. |

Setiap halaman menggunakan struktur yang disesuaikan dengan isi. Beranda berfokus pada visual, Artikel menggunakan susunan editorial, Destinasi menggunakan kartu, sedangkan Diskusi dan Login menggunakan tata letak formulir.

---

## Teknologi dan Implementasi

| Teknologi | Penggunaan |
|---|---|
| **HTML5** | Struktur dokumen, semantic elements, navigasi, gambar, video, audio, form, radio button, `<details>`, dan `<summary>`. |
| **CSS3** | Pengaturan warna, tipografi, layout, Flexbox, Grid, responsive design, hover, focus, transition, keyframes, serta perubahan tampilan berdasarkan state HTML. |
| **SVG** | Ilustrasi dan elemen grafis yang digunakan sebagai aset gambar. |

### Batasan Teknologi

Sesuai instruksi UTS, project final ini:

- Tidak menggunakan JavaScript.
- Tidak menggunakan file JSON.
- Tidak menggunakan framework atau library.
- Tidak menggunakan template website siap pakai.
- Menggunakan HTML5 dan CSS3 sebagai teknologi implementasi.

### Interaksi yang Tetap Bisa Dilakukan

Beberapa interaksi dibuat menggunakan fitur HTML dan CSS:

- Menu navigasi mobile menggunakan `<details>` dan `<summary>`.
- Pergantian artikel menggunakan radio button dan selector CSS.
- Filter kategori destinasi menggunakan radio button dan CSS.
- Ringkasan destinasi dibuka dan ditutup menggunakan `<details>`.
- Efek hover, focus, transisi, dan animasi dibuat menggunakan CSS.
- Pemutar video dan audio menggunakan elemen media bawaan HTML.
- Form menggunakan atribut HTML seperti `required`, `type`, `minlength`, dan `maxlength` sesuai kebutuhan.

---

## Batasan Fitur

Karena project hanya menggunakan HTML5 dan CSS3 tanpa JavaScript maupun backend, beberapa bagian merupakan demonstrasi tampilan dan bukan layanan interaktif penuh.

| Bagian | Batasan |
|---|---|
| **Pencarian Destinasi** | Pencarian bebas berdasarkan kata kunci tidak tersedia. Pengunjung dapat menggunakan filter kategori yang dibuat dengan CSS. |
| **Diskusi** | Form dan contoh posting ditampilkan sebagai rancangan antarmuka. Pengunjung belum dapat mengirim, menyimpan, atau membagikan posting. |
| **Login** | Halaman hanya berupa rancangan form. Tidak ada proses registrasi, autentikasi, verifikasi kata sandi, atau penyimpanan akun. Jangan memasukkan kredensial pribadi. |
| **Artikel** | Pergantian artikel terbatas pada konten yang sudah ditulis di HTML dan dikendalikan oleh radio button serta CSS. |
| **Destinasi** | Informasi destinasi ditulis langsung di HTML, bukan diambil dari database atau JSON. |
| **Media** | Video, audio, foto, atau font yang menggunakan sumber eksternal memerlukan koneksi internet dan ketersediaan layanan sumbernya. |

Pengembangan seperti diskusi multi-pengguna, login sungguhan, pencarian dinamis, dan penyimpanan data memerlukan teknologi di luar ruang lingkup tugas ini.

---

## Struktur Direktori

```text
mapay-bandung/
│
├── assets/
│   ├── fonts/                  # Font lokal jika digunakan
│   ├── icons/                  # Ikon dan identitas visual
│   ├── images/
│   │   ├── articles/           # Gambar untuk artikel
│   │   ├── destinations/       # Gambar destinasi
│   │   ├── general/            # Gambar umum dan hero
│   │   └── regions/            # Ilustrasi wilayah
│   └── videos/                 # Video lokal jika tersedia
│
├── docs/                       # Dokumentasi project
│   ├── 01-project-overview.md
│   ├── 02-srs.md
│   ├── 03-ui-ux-design.md
│   ├── 04-technical-architecture.md
│   ├── 05-content-inventory.md
│   ├── 06-test-plan.md
│   ├── 07-asset-sources.md
│   ├── 08-wireframe-homepage.md
│   └── 09-ui-revision.md
│
├── src/
│   └── css/
│       ├── base/               # Reset, variabel warna, dan tipografi
│       ├── components/         # Button, card, form, dan navigasi
│       ├── layout/             # Header, footer, container, dan responsive
│       ├── pages/              # CSS khusus setiap halaman
│       └── main.css            # File CSS utama
│
├── index.html                  # Beranda
├── artikel.html                # Artikel
├── destinasi.html              # Destinasi
├── wilayah.html                # Diskusi
├── login.html                  # Login
├── README.md                   # Dokumentasi utama
├── LICENSE
└── .gitignore
```

---

## Cara Menjalankan Project

Project merupakan website statis. Cara termudah untuk melihatnya adalah menggunakan Visual Studio Code dan ekstensi Live Server.

### Menggunakan Visual Studio Code

1. Clone repository atau unduh source code project.
2. Ekstrak project apabila diunduh dalam bentuk ZIP.
3. Buka folder `mapay-bandung` melalui Visual Studio Code.
4. Pastikan ekstensi **Live Server** sudah terpasang.
5. Klik kanan file `index.html`.
6. Pilih **Open with Live Server**.
7. Website akan terbuka melalui browser.

### Alternatif Menggunakan Python

Jika Python sudah terpasang, jalankan perintah berikut dari folder utama project:

```bash
python -m http.server 8000
```

Kemudian buka alamat berikut di browser:

```text
http://localhost:8000
```

Karena project tidak menggunakan Fetch API atau JSON, halaman dasarnya juga dapat dibuka langsung melalui browser. Namun, penggunaan local server tetap disarankan agar proses pengujian lebih konsisten.

---

## Repository

Source code project dapat diakses melalui repository GitHub kelompok:

```text
https://github.com/Fauzan55-ikmal/Projek-UTS-DesainWeb1
```

Untuk melakukan clone melalui terminal:

```bash
git clone https://github.com/Fauzan55-ikmal/Projek-UTS-DesainWeb1.git
```

---

## Aset dan Sumber Media

Beberapa elemen visual menggunakan gambar, video, audio, atau font dari sumber eksternal. Daftar sumber dan catatan penggunaan media dicatat dalam dokumen:

```text
docs/07-asset-sources.md
```

Ketersediaan media eksternal bergantung pada koneksi internet dan layanan penyedia. Penggunaan ulang media harus tetap mengikuti ketentuan lisensi masing-masing sumber.

---

## Kesesuaian dengan Soal UTS

| Ketentuan Tugas | Penerapan pada MAPAY BANDUNG |
|---|---|
| Memilih satu tema website | Pariwisata — panduan perjalanan Bandung Raya. |
| Memiliki lima halaman | Beranda, Artikel, Destinasi, Diskusi, dan Login. |
| Memiliki gambar, deskripsi, dan form | Gambar dan deskripsi tersedia di Beranda, Artikel, dan Destinasi; form tersedia di Diskusi dan Login. |
| Struktur halaman bervariasi dalam satu tema | Setiap halaman memiliki komposisi visual sesuai fungsi, dengan identitas MAPAY BANDUNG yang konsisten. |
| Memperhatikan tata letak dan jarak | Menggunakan sistem warna, tipografi, container, spacing, serta layout yang konsisten. |
| Hanya menggunakan HTML/HTML5 dan CSS/CSS3 | Tidak ada JavaScript, JSON, framework, atau library. |
| Tidak menggunakan template siap pakai | Tampilan disusun khusus untuk identitas MAPAY BANDUNG. |
| Membuat video presentasi hasil website | Video presentasi disiapkan sebagai berkas pengumpulan terpisah dari source code. |

---

## Penutup

MAPAY BANDUNG merupakan hasil kerja kelompok dalam menerapkan materi Desain Web 1 melalui pembuatan website bertema pariwisata. Kami berusaha menggabungkan tampilan yang menarik, variasi struktur halaman, navigasi yang jelas, dan penggunaan HTML5 serta CSS3 sesuai batasan tugas.

Kami berharap website ini dapat menjadi media pengenalan sederhana untuk menemukan inspirasi perjalanan dan mengenal lebih banyak tempat menarik di Bandung Raya.

---

© 2026 **MAPAY BANDUNG**  
Dibuat oleh Kelompok IFK-25 untuk UTS Desain Web 1 — Politeknik TEDC Bandung.
