# UI/UX Design Specification

## Arah visual
Gaya editorial yang hangat, modern, dan dekat dengan anak muda serta traveler. Visual destinasi menjadi fokus, tetapi teks tetap mudah dibaca.

## Palet warna
| Nama | HEX | Kegunaan |
|---|---|---|
| Pine Green | `#214F40` | Identitas dan tombol utama |
| Deep Green | `#15392F` | Latar gelap dan overlay |
| Soft Sage | `#DDE8DC` | Aksen latar |
| Mint | `#EEF3ED` | Permukaan pendukung |
| Warm Ivory | `#F7F7F1` | Latar utama |
| Apricot | `#E6A36B` | Aksen dan penekanan |

## Tipografi
- DM Serif Display untuk judul besar dan judul artikel.
- DM Sans untuk navigasi, paragraf, label, dan tombol.
- Jika font online tidak tersedia, browser menggunakan Georgia dan Arial sebagai fallback.

## Layout
- Container terpusat dengan gutter responsif.
- Flexbox untuk navigasi dan alignment sederhana.
- CSS Grid untuk susunan kartu dan layout dua kolom.
- Media query untuk tablet dan mobile.

## Interaksi tanpa JavaScript
- Mobile navigation: `<details>` / `<summary>`.
- Artikel: radio button + CSS untuk mengganti artikel yang tampil.
- Destinasi: radio button + CSS untuk menyaring kategori.
- Ringkasan destinasi: `<details>` / `<summary>`.
- Tombol, link, hover, focus, dan animasi: CSS.
- Audio ambience: kontrol asli elemen `<audio>`.

## Catatan UX
Form Diskusi dan Login tetap disediakan untuk memenuhi kebutuhan tampilan form. Keduanya tidak mengirim data karena website ini tidak menggunakan backend.
