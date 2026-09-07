# Catering Sekolah MVP

Prototype webapp statis untuk mengatur catering beberapa sekolah secara efisien, lengkap dengan laporan rekapitulasi dan ekspor PDF.

## Fitur Utama
- **Dashboard Operasional**: Ringkasan jumlah sekolah aktif, total porsi harian, menu terjadwal, kesiapan distribusi, dan kebutuhan bahan masak harian.
- **Multi-Sekolah & Kebutuhan Khusus**: Pengaturan porsi rutin per sekolah, kontak PIC, dan catatan alergi/diet khusus siswa.
- **Menu Harian Dinamis**: Input jenis makan (Makan Siang, Sarapan, Snack), karbohidrat, lauk utama, sayur, buah/tambahan, dan catatan dapur. Satu menu dapat diterapkan ke beberapa sekolah sekaligus.
- **Status Kesiapan Distribusi**: Toggle status persiapan vs siap kirim per sekolah secara real-time.
- **Kalender Menu 7 Hari**: Tampilan jadwal menu mingguan interaktif.
- **Rekapitulasi & Download PDF**:
  - **Filter Fleksibel**: Pilih sekolah tertentu atau seluruh sekolah, serta tentukan rentang tanggal (Mulai s/d Selesai) dengan shortcut preset (*Hari Ini*, *7 Hari ke Depan*, *Bulan Ini*, *Semua*).
  - **Download PDF Rekap Resmi**: Laporan berformat PDF vektor rapi (via jsPDF & AutoTable) lengkap dengan kop dokumen, info sekolah & PIC, catatan alergi khusus, tabel rincian menu harian, total akumulasi porsi, ringkasan kebutuhan bahan dapur, penomoran halaman, dan kolom tanda tangan verifikasi.
  - **Export CSV & Cetak Langsung**: Opsi ekspor ke spreadsheet dan print langsung dari browser.
- **Penyimpanan Lokal**: Semua data tersimpan otomatis di `localStorage` browser.

## Menjalankan
Cukup buka file `index.html` di browser (Chrome, Edge, Firefox, Safari).

## Deploy
Karena statis tanpa backend wajib, aplikasi ini dapat langsung di-deploy ke Netlify, Vercel, GitHub Pages, Cloudflare Pages, atau web hosting standar.

