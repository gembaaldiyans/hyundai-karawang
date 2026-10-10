PAKET WEBSITE FULLSTACK — SALES HYUNDAI KARAWANG

Isi:
- public/index.html: landing page responsive untuk HP/desktop
- public/admin.html: dashboard lead dan status follow-up
- server.js: backend API untuk menerima dan menyimpan lead
- data/leads.json: penyimpanan demo
- package.json: konfigurasi aplikasi Node.js

Yang tersedia:
Beranda, pilihan model, promo, tentang sales, kalkulator angsuran perkiraan, form prospek ke WhatsApp, backend penyimpanan leads, dan dashboard admin di /admin.html.

Nomor WhatsApp sudah disetel ke 0817-9177-767.
Password admin lokal default: GantiPasswordIni123! — WAJIB diganti melalui environment variable ADMIN_PASSWORD sebelum dipublikasikan.

PENTING:
- Foto mobil adalah ilustrasi sementara; ganti dengan foto resmi unit.
- Harga tidak ditulis sebagai harga resmi karena perlu dikonfirmasi ke dealer.
- Kalkulator memakai asumsi bunga flat 7% per tahun untuk estimasi awal, bukan rumus leasing resmi.
- Penyimpanan JSON bisa hilang di hosting yang filesystem-nya sementara. Untuk produksi, gunakan persistent disk atau database.
- Saya belum menerbitkan website ini ke internet. ZIP ini adalah sumber website, bukan URL live.

JALANKAN:
1. Install Node.js 18+
2. Ekstrak ZIP
3. Jalankan npm install
4. Jalankan npm start
5. Buka http://localhost:3000
6. Dashboard: http://localhost:3000/admin.html

Jika hanya menggunakan HP, unggah proyek ke GitHub lalu deploy di layanan hosting yang mendukung Node.js. Atur ADMIN_PASSWORD di pengaturan hosting dan pilih penyimpanan persisten sebelum memakai data pelanggan sungguhan.
