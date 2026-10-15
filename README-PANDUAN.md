# Paket siap unggah: Teman Belajar PAUD – Kenal Hewan

## Isi paket

| Berkas | Fungsi |
|---|---|
| `index.html` | Aplikasinya. Satu berkas, semua gambar, suara, dan huruf sudah tertanam. Tidak memanggil situs lain |
| `privacy.html` | Kebijakan privasi (wajib untuk Play Store). **Masih ada bagian yang harus Anda isi** |
| `manifest.webmanifest`, `icons/` | Membuat aplikasi bisa dipasang di layar utama HP |
| `sw.js` | Membuat aplikasi tetap jalan tanpa internet setelah dibuka sekali |
| `_headers` | Pengaturan keamanan dasar untuk Netlify dan Cloudflare Pages |
| `FONT-LICENSE.txt` | Catatan lisensi huruf. Jangan dihapus |

## Langkah 1. Isi data Anda di `privacy.html`

Buka dengan Notepad atau editor teks, lalu cari tulisan berlatar kuning dalam kurung siku:

- `[NAMA PENGEMBANG ATAU USAHA]`
- `[EMAIL KONTAK]` (muncul 2 kali)
- `[NAMA PENYEDIA HOSTING ...]`

Ganti semuanya dengan data asli. Email ini akan tampil publik. Pakai email khusus usaha jika tidak ingin email pribadi terlihat.

## Langkah 2. Unggah ke hosting

Hosting statis gratis yang cocok untuk paket ini: Netlify, Cloudflare Pages, atau GitHub Pages. Tampilan menu mereka bisa berubah, jadi ikuti petunjuk di situsnya.

1. Ekstrak zip ini menjadi satu folder.
2. Buat akun di salah satu layanan di atas.
3. Unggah **isi folder** (bukan zip-nya). Di Netlify, pakai fitur unggah folder (drag and drop). Di Cloudflare Pages, pilih unggah langsung (direct upload).
4. Anda akan mendapat alamat web. Catat alamat itu.
5. Buka alamat itu di HP.

Alamat yang diperoleh bisa diganti dengan nama sendiri (domain) belakangan.

## Langkah 3. Uji di HP

1. Buka alamat di Chrome Android. Pilih menu ⋮ lalu "Instal aplikasi" atau "Tambahkan ke layar utama". Di iPhone (Safari): tombol bagikan lalu "Tambah ke Layar Utama".
2. Coba semua layar, terutama suara. Pastikan volume media menyala.
3. Matikan internet lalu buka lagi aplikasinya. Seharusnya tetap bisa dibuka.
4. Minta 3–5 orang tua mencoba bersama anaknya.

## Penting sebelum menjual

**Versi web ini bisa dibuka siapa saja yang tahu alamatnya**, dan kodenya bisa disalin. Jika ingin menjual akses, pilih salah satu:

- Jual lewat Play Store (pembayaran lewat Google). Lihat Langkah 4.
- Pakai fitur proteksi kata sandi atau login di layanan hosting. Biasanya ini fitur berbayar, cek paket yang tersedia.
- Jual paket cetak PDF-nya, dan jadikan versi web sebagai bonus.

**Cek hak atas isinya:**

- **Gambar hewan:** pastikan Anda berhak memakainya secara komersial. Jika dibuat dengan AI, baca syarat layanan yang dipakai.
- **Suara hewan:** pastikan sumbernya boleh dipakai komersial. Suara dari paket gratis generator AI, CapCut, atau video YouTube biasa umumnya tidak boleh.
- **Huruf:** Poppins berlisensi OFL, boleh dipakai komersial. Jangan hapus `FONT-LICENSE.txt`.
- **Ikon:** ikon bawaan hanya contoh (kepala singa). Ganti dengan desain sendiri jika ingin tampil lebih khas.

## Langkah 4 (opsional). Play Store

Play Store menerima aplikasi web yang dibungkus (misalnya lewat PWABuilder atau Bubblewrap). Garis besarnya:

1. Unggah dulu ke hosting (Langkah 2) dan pastikan alamat `privacy.html` bisa dibuka publik.
2. Buat akun Google Play Console. Ada biaya pendaftaran sekali bayar, dan akun pribadi baru bisa diwajibkan menjalankan uji tertutup dengan sejumlah penguji sebelum rilis. **Cek syarat terbaru di situs Google**, karena sering berubah.
3. Bungkus aplikasi dengan PWABuilder (pwabuilder.com): masukkan alamat web Anda, lalu pilih paket Android dan unduh berkas paketnya.
4. Isi data toko: nama, deskripsi, tangkapan layar, ikon 512×512, dan alamat kebijakan privasi.
5. Isi formulir **Keamanan data (Data safety)** sesuai perilaku aplikasi ini:
   - Mengumpulkan data pengguna: **Tidak**
   - Membagikan data ke pihak lain: **Tidak**
   - Iklan: **Tidak ada**
   - Akun atau login: **Tidak ada**
6. Pilih sasaran usia anak. Aplikasi untuk anak tunduk pada kebijakan khusus Google Play untuk anak dan keluarga. **Baca kebijakan itu sebelum mengirim.**
7. Atur harga atau gratis. Untuk pembelian digital di dalam aplikasi, Play Store biasanya mewajibkan sistem pembayaran Google. Cek ketentuan terbaru.

Jika ada perubahan pada aplikasi (misalnya menambah akun, iklan, atau pembelian), perbarui `privacy.html` dan formulir Keamanan data sebelum merilis.

## Mengganti isi di kemudian hari

Jika Anda mengganti `index.html`, naikkan angka `VERSI` di `sw.js` (misalnya `tbp-v2`) supaya HP pengguna mengambil versi baru.

## Catatan hukum

Kebijakan privasi ini ditulis mengikuti cara kerja aplikasi saat ini. Aplikasi bukan pengganti nasihat hukum. Jika berencana menjual secara luas, sebaiknya kebijakan ini dibaca oleh orang yang paham hukum perlindungan data di Indonesia.
