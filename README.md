# Mathpreneur F&B Online - Pertemuan 1

Folder ini adalah paket raw template-style untuk di-upload ke GitHub Pages. Mulai dari `index.html` sebagai hub utama.

Update terbaru: logo Kalananti sudah dihilangkan dari template, dan teks pada spin wheel tetap terbaca normal setelah roda diputar.

## File Utama

- `index.html` - hub utama guru.
- `teacher-deck-day1-online.html` - deck guru versi HTML.
- `math-champs-fnb-online-day1-teacher-deck.pdf` - PDF cadangan deck.
- `spin-wheel-day1.html` - spin wheel bahan utama.
- `pre-test-day1.html` - pre-test online siswa.
- `post-test-day1.html` - post-test online siswa.
- `results-spreadsheet-day1.html` - halaman hasil guru dan export CSV.
- `answer-key-day1.html` - soal dan kunci jawaban guru.
- `pre-test-day1-questions.pdf` - PDF soal pre-test.
- `post-test-day1-questions.pdf` - PDF soal post-test.

## Cara Upload ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload semua isi folder ini ke root repository, termasuk `index.html`.
3. Buka `Settings > Pages`.
4. Pilih `Deploy from a branch`, branch `main`, folder `/root`.
5. Setelah aktif, hub utama akan bisa dibuka di `https://USERNAME.github.io/NAMA-REPO/`.

## Cara Edit Dropdown Guru

Buka file `pre-test-day1.html` dan `post-test-day1.html`, lalu cari bagian ini:

```js
// EDIT DI SINI: ganti daftar nama guru sesuai kelas Holiday Program.
const TEACHER_OPTIONS = ["Guru 1", "Guru 2", "Guru 3"];
```

Ganti daftar nama guru sesuai kebutuhan.

## Catatan Hasil Test

Pre-test dan post-test tetap menyimpan hasil ke backend online yang sudah dibuat. GitHub Pages hanya menjadi tempat hosting file HTML, sementara hasil siswa tetap bisa dilihat dari halaman `results-spreadsheet-day1.html`.
