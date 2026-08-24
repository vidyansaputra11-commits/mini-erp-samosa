MINI ERP PRODUKSI & PENJUALAN - PWA SIAP PAKAI
================================================

FITUR UTAMA
- Rekap order masuk
- Jenis order REGULER / RESELLER dengan harga berbeda
- Print struk order
- Pembelian & pemakaian Raw Material
- Pembelian & pemakaian Packaging INNER / OUTER
- Input hasil produksi & reject
- Stok Raw Material, Packaging, Finish Good
- Outstanding produksi otomatis dari order aktif vs stok FG
- Laporan penjualan
- Laporan HPP & profit kotor
- Print laporan
- Backup / restore data JSON
- Offline-first setelah pertama kali dibuka melalui HTTPS

CARA TRIAL DI LAPTOP
1. Ekstrak ZIP.
2. Buka folder MINI_ERP_WEBAPP_READY.
3. Klik dua kali index.html.
4. Input master produk, raw material, dan packaging pada menu Master.
CATATAN: mode file lokal bisa dipakai untuk trial, tetapi fitur install/offline PWA penuh membutuhkan HTTPS.

CARA PAKAI DI ANDROID SEPERTI APLIKASI
1. Upload seluruh isi folder ini ke hosting HTTPS (contoh: Netlify / GitHub Pages).
2. Buka URL hasil hosting memakai Chrome di Android.
3. Tekan tombol INSTALL di bagian atas aplikasi, atau menu Chrome > Tambahkan ke layar utama / Install app.
4. Setelah terpasang, aplikasi muncul di Home Screen.

DATA
- Data tersimpan lokal di browser/perangkat yang digunakan.
- Lakukan Backup Data secara berkala melalui menu Master.
- Jika ganti HP/browser, lakukan Restore dari file backup JSON.
- Versi ini belum memakai database cloud/multi-user.

URUTAN PEMAKAIAN YANG DISARANKAN
1. Master: sesuaikan produk dan harga Reguler/Reseller.
2. Master: tambah Raw Material dan Packaging.
3. Raw Material / Packaging: input pembelian awal agar stok tersedia.
4. Order: input pesanan pelanggan.
5. Dashboard: lihat outstanding produksi.
6. Produksi: input hasil produksi.
7. Order: klik Selesai setelah stok FG cukup, lalu Print Struk.
8. Laporan: filter periode dan Print Laporan.
9. Master: Backup Data secara berkala.

VERSI
Ready Trial v2 - 24 Agustus 2026
