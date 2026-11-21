# Catering Pagi Sore

Website promosi dan katalog layanan **Catering Pagi Sore** yang dibuat sebagai proyek mata kuliah Pemrograman Web 1. Website ini menampilkan menu makanan, informasi layanan, testimoni pelanggan, profil tim, dan informasi kontak.

## Fitur Utama

- Halaman beranda dengan hero section dan menu unggulan
- Daftar menu catering beserta harga dan deskripsi
- Notifikasi pesanan ketika tombol **Pesan Sekarang** ditekan
- Keranjang belanja tampilan statis
- Form pencarian dan navigasi responsif untuk layar kecil
- Slider testimoni pelanggan
- Halaman profil layanan dan anggota tim
- Informasi kontak, tautan media sosial, dan lokasi pada peta

## Teknologi

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Font Awesome
- Google Fonts
- Google Maps Embed

## Struktur Halaman

```text
.
├── index.html              # Halaman utama / beranda
├── beranda.html            # Versi halaman beranda
├── beranda.css
├── beranda.js
├── img/                    # Gambar beranda
├── menu catering/
│   ├── menu.html
│   ├── menu.css
│   ├── menu.js
│   └── img/
├── testimoni/
│   ├── testimoni.html
│   ├── testimoni.css
│   ├── testimoni.js
│   └── img/
└── about us/
    ├── about.html
    ├── about.css
    ├── about.js
    └── img/
```

## Cara Menjalankan

Proyek ini tidak memerlukan instalasi package atau proses build.

1. Buka folder proyek.
2. Jalankan `index.html` langsung melalui browser, atau
3. Jalankan server lokal agar navigasi dan aset dapat dimuat dengan lebih konsisten.

Contoh menggunakan Python:

```bash
python -m http.server 8000
```

Kemudian buka:

```text
http://localhost:8000
```

Jika menggunakan Visual Studio Code, ekstensi **Live Server** juga dapat digunakan untuk membuka proyek.

## Akses Halaman

- Beranda: `index.html`
- Menu: `menu catering/menu.html`
- Testimoni: `testimoni/testimoni.html`
- Tentang Kami: `about us/about.html`

## Catatan Pengembangan

- Website saat ini merupakan proyek frontend statis.
- Tombol pesanan dan keranjang hanya menampilkan interaksi antarmuka; belum terhubung ke sistem pembayaran atau database.
- Form pencarian, newsletter, dan form kontak belum memiliki proses pengiriman data ke backend.
- Beberapa pustaka, ikon, font, dan peta membutuhkan koneksi internet.

## Tim Pengembang

Proyek ini dibuat oleh Kelompok 1 untuk mata kuliah Pemrograman Web 1.
