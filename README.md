<h1 align="center">Budget Picker JKT</h1>

<p align="center"><strong>Cari makan dan minum di Jakarta sesuai budget.</strong></p>
<p align="center">Aplikasi web statis: HTML, CSS, dan JavaScript saja. Tanpa build step, tanpa server, tanpa dependensi.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  <a href="#fitur">Fitur</a> &middot;
  <a href="#struktur">Struktur</a> &middot;
  <a href="#cara-menjalankan">Cara Menjalankan</a> &middot;
  <a href="#dukungan">Dukungan</a>
</p>

## Fitur

- Cari kuliner Jakarta berdasarkan budget yang dimasukkan.
- Filter berdasarkan wilayah, langsung dari halaman Jelajah.
- Favorit: simpan kuliner favorit (tersimpan di `localStorage`) beserta total harganya.
- Halaman detail tiap kuliner, lengkap dengan tautan "Lihat di peta".
- Halaman Kontak berisi tautan dukungan (Saweria dan Trakteer).

## Struktur

Satu file HTML per halaman, satu `style.css`, satu `script.js`. Data kuliner
menyatu di dalam `script.js` (tidak ada file `data.js` terpisah).

```
index.html      Beranda + panel budget
jelajah.html    Jelajah kuliner + filter wilayah
favorit.html    Daftar favorit + total harga
detail.html     Detail tiap kuliner
tentang.html    Tentang proyek
kontak.html     Kontak + dukungan
style.css       Satu-satunya stylesheet (palet 8 warna per tema)
script.js       Data + seluruh logika
src/            Foto kuliner
```

## Cara Menjalankan

```bash
git clone https://github.com/senshiner/budget-picker-jkt.git
cd budget-picker-jkt
```

Buka `index.html` di browser. Tidak perlu server atau build step.

## Dukungan

Dukungan untuk proyek ini ada di halaman Kontak: Saweria dan Trakteer.
