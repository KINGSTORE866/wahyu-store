# WAHYU STORE

Website toko sederhana, responsif untuk HP dan komputer. Dibuat menggunakan HTML, CSS, dan JavaScript biasa sehingga bisa di-host gratis di Vercel.

## Isi folder
- `index.html` — seluruh website dalam satu file.

## Sebelum dipublikasikan
1. Buka `index.html`.
2. Cari `const WHATSAPP_NUMBER = "6289538212429";` lalu ganti jika nomor WhatsApp tokomu berbeda. Format: kode negara + nomor, tanpa `+`, spasi, atau strip.
3. Cari bagian `const PRODUCTS = [...]` untuk mengganti nama produk, kategori, harga, deskripsi, dan ikon.
4. Harga yang tampil sekarang hanya contoh teks seperti "Hubungi admin". Sesuaikan dengan daftar harga toko sebelum website dibuka untuk umum.

## Cara upload ke Vercel dari HP
1. Buat akun atau masuk ke https://vercel.com/.
2. Siapkan folder project ini di perangkat.
3. Cara termudah: buat repository baru di https://github.com/ lalu upload `index.html` ke repository tersebut.
4. Di Vercel, pilih **Add New → Project**, lalu hubungkan repository GitHub tadi.
5. Untuk project HTML statis ini, pilih pengaturan default. Tidak perlu framework atau build command. Jika diminta, biarkan Build Command kosong dan Output Directory kosong.
6. Tekan **Deploy**. Setelah selesai, Vercel memberikan alamat website `.vercel.app`.

## Catatan
- Tombol pesan membuka WhatsApp dengan teks pesanan yang sudah diisi otomatis.
- Website ini belum memproses pembayaran otomatis, belum memiliki database, dan belum memiliki dashboard admin. Produk dan harga diedit langsung di bagian `PRODUCTS` pada file `index.html`.
- Jangan memasukkan password, kode OTP, atau data rahasia pelanggan ke dalam website.
