RUPIAH — PERSONAL FINANCE PWA

Isi:
- index.html: aplikasi
- manifest.json: konfigurasi Home Screen
- sw.js: cache/offline app shell
- icon.svg: ikon aplikasi

FITUR:
- Saldo awal + pemasukan - pengeluaran
- Tambah/edit/hapus transaksi
- Kategori, metode pembayaran, tanggal, catatan
- Budget bulanan dan ringkasan kategori
- Ekspor JSON, ekspor CSV, impor JSON
- Penyimpanan lokal di browser

PENTING:
- Ini adalah versi awal tanpa koneksi bank/e-wallet.
- Data browser bisa hilang; lakukan ekspor JSON secara rutin.
- Jangan simpan PIN, password, atau OTP.
- Untuk pemasangan sebagai PWA, host folder ini melalui HTTPS. GitHub Pages bisa digunakan untuk hosting statis gratis.

CARA PUBLISH DENGAN GITHUB PAGES:
1. Buat akun/login di GitHub jika belum punya.
2. Buat repository baru bernama rupiah-pwa.
3. Upload semua file dari folder ini (index.html, manifest.json, sw.js, icon.svg, README.txt) ke root repository.
4. Buka Settings > Pages.
5. Pada Build and deployment, pilih Deploy from a branch, branch main, folder /(root), lalu Save.
6. Tunggu sampai URL Pages muncul. Buka URL itu di Safari iPhone.
7. Di Safari tekan Share > Add to Home Screen. Pastikan Open as Web App aktif, lalu Add.

DATA LOKAL:
Transaksi disimpan pada browser origin tempat aplikasi diakses. Jangan berganti URL/domain tanpa mengekspor cadangan lebih dahulu. Mode offline mulai tersedia setelah aplikasi dibuka online dan cache terpasang.
