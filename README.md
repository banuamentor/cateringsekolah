# Catering Sekolah MVP

Prototype webapp statis untuk mengatur catering beberapa sekolah.

## Fitur
- Dashboard jumlah sekolah, total porsi, menu terjadwal, kesiapan distribusi.
- Multi-sekolah dan jumlah porsi per sekolah.
- Menu harian: jenis makan, karbohidrat, lauk, sayur, buah/tambahan, catatan dapur.
- Menu dapat diterapkan ke beberapa sekolah sekaligus.
- Kebutuhan khusus/alergi per sekolah.
- Status persiapan / siap kirim per sekolah.
- Kalender menu 7 hari.
- Rekap dan export CSV.
- Data tersimpan di localStorage browser.

## Menjalankan
Cukup buka `index.html` di browser.

## Deploy
Karena statis, folder ini bisa langsung di-deploy ke Netlify, Vercel, GitHub Pages, atau hosting biasa.

## Catatan untuk versi produksi
Untuk penggunaan multi-user dan lintas perangkat, migrasikan penyimpanan ke database (misalnya Supabase/PostgreSQL), lalu tambahkan login, role, audit trail, data siswa/alergi yang aman, stok bahan baku, purchase planning, delivery tracking, dan laporan biaya.
