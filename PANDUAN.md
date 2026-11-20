# e-Panitia Sejarah: penyelenggaraan

Portal awam responsif; tiada pelayan, kata laluan atau pangkalan data sulit. Jangan simpan data peribadi dalam mana-mana fail GitHub, termasuk sejarah commit. Indeks awam kosong dengan sengaja sehingga dokumen awam yang diluluskan dibekalkan. Penyegerakan Drive atau rekod bersama belum dihubungkan.

## Arkib kekal

- `data/years.json` mendaftarkan tahun 2026 dan 2027.
- `data/2026.json` dan `data/2027.json` ialah indeks berasingan, dijejak dalam sejarah Git.
- Tambah `data/2028.json` dengan `{"year":2028,"records":[]}` dan tambah 2028 kepada senarai `years`; tetapkan `defaultYear` jika perlu. Jangan gantikan fail tahun lama.
- Setiap dokumen awam menggunakan medan `id`, `title`, `section`, `date` (YYYY-MM-DD), `description`, `url` (HTTPS), `visibility` (`public`). Bahagian sah: standard, takwim, mesyuarat, program, pentaksiran, inovasi, laporan.
- Indeks menyimpan pautan, bukan salinan fail. Kekalkan fail sebenar dan sandaran dalam storan sekolah. Pautan yang dipadam di Drive tidak boleh dipulihkan oleh portal.
- Hanya metadata dan dokumen yang diluluskan untuk orang awam boleh ditambah. Untuk rekod sulit, gunakan folder Drive terhad yang dikongsi terus kepada guru. Jangan komit URL atau metadata sulit ke repositori ini.

## Senarai semak

29 item asal Standard 1–5 dikekalkan. Tanda semak 2027 versi terdahulu dibaca tanpa memadam kunci asal. Tanda semak diasingkan mengikut tahun dan disimpan pada pelayar sahaja. Menu Panduan menyediakan eksport/import JSON bertahun; eksport setiap tahun secara berasingan. Simpan fail sandaran ke Drive terhad. Tiada jaminan kekal jika data pelayar dipadam tanpa sandaran.

## GitHub Pages dan Google Sites

Dalam repositori ini sahaja: Settings → Pages → Deploy from a branch → main → / (root) → Save. Tunggu Pages build selesai. Buka https://teacherziela.github.io/e-panitia-sejarah-2027/?year=2027 dan semak 2026 juga.

Dalam Google Sites: Sisipkan → Benam → URL tersebut; gunakan halaman penuh atau tinggi sekitar 1000px. Terbitkan Google Sites. Pembatasan akses Google Sites tidak menjadikan GitHub Pages peribadi. Akses fail Drive mesti dikawal di Drive sendiri.

## Sandaran dan pemulihan

`backups/index-before-archive.html` mengekalkan halaman asal. Commit sebelum perubahan: `ccd59b2a8ea1c70a6f4ff76ca957c4a753f8a7cc`. Untuk kembali, pulihkan index.html daripada sandaran atau revert commit kemas kini; jangan padam sejarah, arkib atau repositori lain.

Logo `school.jpeg` disalin tanpa pengubahsuaian daripada lampiran asal SEK(5).jpeg. SHA-256: 347f33701dfcb0b3ab8f0cfec473eb2083a6cb1ab11106b2395b840ca5484bb8.

Semakan penerimaan: tukar 2026/2027; tanda semak kekal berasingan; muat semula; eksport/import tahun sepadan; tolak tahun berbeza; uji carian dan penapis; buka aplikasi lama; semak telefon dan papan kekunci. Tambah dokumen sebenar hanya selepas semakan privasi.
