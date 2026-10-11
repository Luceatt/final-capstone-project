# TripTally

TripTally adalah prototipe aplikasi web untuk merencanakan perjalanan, mengelola teman yang ikut, dan mencatat patungan biaya (split bill).

## Tujuan

Project ini dibuat sebagai latihan Capstone Workshop (Track IBM Bob, Hacktiv8) untuk melatih penyusunan prompt 3 lapisan (Role & Context, Task & Requirements, Constraints & Output).

## Fitur

- **Itinerary:** Pengguna dapat melihat daftar perjalanan beserta aktivitas per tanggal, lengkap dengan checkbox "Selesai" dan progress bar.
- **Teman & Peserta:** Pengguna dapat melihat daftar teman, mengundang teman ke sebuah perjalanan, dan mengeluarkan peserta dari perjalanan tersebut.
- **Split Bill:** Setiap perjalanan menampilkan daftar pengeluaran yang dibagi rata, dengan checkbox "Sudah bayar" dan badge "Lunas" yang muncul otomatis saat semua peserta sudah membayar.

## Batasan

- Hanya memakai HTML5 dan CSS3, tanpa JavaScript, framework, atau library eksternal.
- Hanya terdiri dari dua file: `index.html` dan `style.css`.
- Ini adalah prototipe UI, sehingga data bersifat statis dan tidak tersimpan setelah halaman di-refresh.
- Form tambah, edit, dan hapus hanya berupa tampilan dan tidak benar-benar mengubah data.
- Angka ringkasan split bill tidak berubah otomatis saat checkbox dicentang.
- Fitur "Undang Teman" hanya simulasi, tanpa pengiriman email asli.
- Membutuhkan browser modern yang mendukung `:has()` (Chrome 105+, Safari 15.4+, Firefox 121+).

## Cara Menjalankan

Simpan kedua file dalam satu folder, lalu buka `index.html` di browser.
