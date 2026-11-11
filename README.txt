SAMZ MARKET — SOLUSI DIGITAL TANPA RIBET
========================================

ISI WEBSITE
-----------
- index.html                 Halaman utama dan seluruh bagian website
- style.css                 Desain responsif, animasi, dan komponen tampilan
- script.js                 Katalog, pencarian, checkout, perhitungan harga, dan WhatsApp
- assets/images/            Ilustrasi SVG original untuk setiap kategori
- vercel.json               Konfigurasi deployment Vercel

MENJALANKAN SECARA LOKAL
------------------------
1. Ekstrak ZIP ke sebuah folder.
2. Buka folder samz-market.
3. Klik dua kali index.html untuk membukanya di browser.
4. Untuk pengalaman pengembangan yang lebih baik, jalankan server lokal
   (misalnya ekstensi Live Server di Visual Studio Code).

Tidak diperlukan npm, database, atau API untuk fitur katalog dan checkout dasar.

HARGA VPS
---------
1GB / 1Core    Rp15.000
2GB / 1Core    Rp20.000
2GB / 2Core    Rp25.000
4GB / 2Core    Rp35.000
8GB / 2Core    Rp45.000
8GB / 4Core    Rp50.000
16GB / 4Core   Rp60.000
16GB / 8Core   Rp80.000
32GB / 8Core   Rp100.000
Masa aktif seluruh paket VPS: 30 hari.

Fasilitas VPS yang dicantumkan: pilihan region; pilihan OS dan version;
bantuan instalasi Pterodactyl Panel; instalasi Node/Wings; instalasi Node.js
Egg; Cloudflare Verification; dan pilihan nama subdomain.

MENAMBAHKAN QRIS ASLI
---------------------
1. Siapkan file gambar QRIS asli dari pemilik toko/merchant.
2. Jangan mengedit, menggambar ulang, memotong bagian kode, atau mengubah pola QR.
3. Simpan salinan gambar asli dengan nama: qris-samz-store.png
4. Letakkan di folder: assets/images/qris-samz-store.png
5. Muat ulang website dan lakukan pemeriksaan visual sebelum dipublikasikan.

QRIS tidak disertakan karena file asli belum diberikan. Website tidak membuat QR
pengganti. Nama merchant pada gambar QRIS tetap mengikuti gambar sumber.
Pembayaran tidak diverifikasi otomatis. Pembeli mengirim bukti melalui WhatsApp
untuk diperiksa secara manual oleh admin.

ALUR PEMESANAN
--------------
1. Pilih paket/produk berharga tetap dan tekan Pesan Sekarang.
2. Isi nama, nomor WhatsApp, dan kebutuhan tambahan.
3. Periksa total dan ringkasan pesanan.
4. Lanjut ke instruksi pembayaran.
5. Setelah membayar melalui QRIS asli yang telah dipasang, kirim bukti ke
   WhatsApp SAMZ MARKET: https://wa.me/62895371030339

Produk yang belum memiliki harga tetap diarahkan ke WhatsApp untuk menanyakan
harga dan ketersediaan; website tidak mengarang harga.

DEPLOY KE VERCEL
----------------
Cara melalui dashboard:
1. Ekstrak ZIP.
2. Masuk ke https://vercel.com/ dan login.
3. Pilih Add New > Project.
4. Hubungkan repository GitHub yang berisi isi folder ini, atau gunakan Vercel
   CLI dari folder proyek.
5. Untuk proyek HTML/CSS/JS statis, pilih Other sebagai Framework Preset.
6. Build Command: kosongkan / None.
7. Output Directory: . (root folder).
8. Deploy. Vercel akan menerbitkan URL website.

Cara melalui Vercel CLI:
1. Instal Node.js dan Vercel CLI: npm i -g vercel
2. Buka terminal di folder proyek.
3. Jalankan: vercel
4. Ikuti instruksi login dan deployment.
5. Untuk deployment produksi: vercel --prod

CATATAN DAN BATASAN
-------------------
- Website ini menggunakan HTML, CSS, dan JavaScript sisi browser.
- Pemesanan mengirim ringkasan ke WhatsApp; tidak ada database pesanan.
- Tidak ada payment gateway atau verifikasi pembayaran otomatis.
- Harga VPS merupakan harga yang diberikan untuk proyek ini. Harga produk lain
  yang belum ditentukan perlu dikonfirmasi kepada admin.
- Ketersediaan layanan, region, OS, spesifikasi panel/cloud, dan promo harus
  dikonfirmasi sebelum pembayaran.
- Gambar kategori adalah ilustrasi SVG original yang dibuat khusus untuk
  website ini, bukan foto produk fisik atau bukti afiliasi resmi penyedia.
- Website menggunakan Google Fonts jika internet tersedia; font fallback lokal
  tetap disediakan oleh browser.

IDENTITAS TOKO
--------------
Nama       : SAMZ MARKET
Slogan     : Solusi Digital Tanpa Ribet
WhatsApp Admin 1 : 0895371030339
Link Admin 1     : https://wa.me/62895371030339
WhatsApp Admin 2 : 082334292520
Link Admin 2     : https://wa.me/6282334292520
Checkout         : Pembeli dapat memilih Admin 1 atau Admin 2 untuk menerima ringkasan pesanan dan bukti pembayaran.
