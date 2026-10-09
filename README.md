# ARCANA — Tarot 3D

Game tarot interaktif berbahasa Indonesia oleh Dapur Kreatif. Pilih tema, kocok kartu, dan buka tiga kartu untuk refleksi diri.

## Fitur
- Meja dan kartu dengan transformasi CSS 3D; meja bisa diputar dengan mouse atau sentuhan.
- 22 Major Arcana dengan makna tegak dan terbalik berdasarkan ringkasan Liz Dean.
- Animasi hasil 3D, percikan bintang, kilau, dan detail simbol kartu.
- Tema perjalanan diri, cinta, dan karier. Tanpa kolom pertanyaan.
- Pola Masa Lalu · Kini · Masa Depan dan pola refleksi kreatif.
- Riwayat browser, suara opsional, dan cetak / Simpan sebagai PDF.
- Layout responsif dan dukungan pengaturan kurangi gerakan.

## Jalankan lokal
Buka `index.html` di browser modern. Tidak memerlukan instalasi, database, API key, atau build. Untuk penyimpanan riwayat yang konsisten, gunakan GitHub Pages atau server lokal; beberapa browser membatasi penyimpanan file lokal.

## Upload melalui website GitHub
1. Buat repository baru bernama `arcana-tarot-3d`, pilih Public.
2. Ekstrak ZIP ini.
3. Pada repository, pilih Add file → Upload files.
4. Upload isi folder: `index.html`, `README.md`, dan `PANDUAN_GITHUB.txt` langsung di root repository. File `.nojekyll` juga boleh disertakan.
5. Klik Commit changes. Jangan upload ZIP-nya saja dan jangan letakkan index.html di subfolder.
6. Buka Settings → Pages → Build and deployment.
7. Source: Deploy from a branch. Branch: main. Folder: /(root). Klik Save.
8. Tunggu proses deployment selesai. URL ditampilkan di halaman Pages.

Contoh URL bila akun GitHub adalah artesiannest:
https://artesiannest.github.io/arcana-tarot-3d/

Panduan resmi:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Pembaruan
Upload ulang index.html ke repository yang sama lalu Commit changes. GitHub Pages menerbitkan pembaruan setelah deployment selesai. Bila versi lama masih tampil, tekan Ctrl+Shift+R.

## Sumber dan ruang lingkup
Liz Dean (2015). The Ultimate Guide to Tarot: A Beginner’s Guide to the Cards, Spreads, and Revealing the Mystery of the Tarot. Fair Winds Press.
- Bab 3: pola bacaan tiga kartu.
- Bab 4: 22 Major Arcana, makna upright dan reversed (hlm. 30–117).
- Aplikasi ini memakai ringkasan singkat bahasa Indonesia, bukan terjemahan lengkap.
- Minor Arcana belum termasuk. Pola Situasi · Tantangan · Saran dan pertanyaan refleksi adalah adaptasi kreatif aplikasi.
- Ilustrasi simbolik adalah desain aplikasi; gambar serta PDF buku tidak disertakan.

Tarot di sini digunakan untuk hiburan dan refleksi, bukan kepastian tentang masa depan.

## Verifikasi
Sintaks JavaScript dan alur kocok → pilih tiga kartu → hasil → riwayat → mulai ulang telah diperiksa. Tampilan belum diuji langsung melalui browser HP.
