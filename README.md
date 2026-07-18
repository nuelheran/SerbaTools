# 🧰 SerbaTools

**Kumpulan 12 tools gratis untuk keperluan sehari-hari — bilingual (ID/EN), tanpa daftar akun, dan 100% berjalan di browser.**

Free everyday tools in one place. No signup, no server — everything runs in your browser.

## ✨ Fitur

| Tool | Deskripsi |
|---|---|
| 📝 Penghitung Kata | Kata, karakter, kalimat, paragraf, estimasi waktu baca |
| 🔠 Case Converter | UPPERCASE, lowercase, Title Case, camelCase, snake_case, kebab-case |
| 🔐 Generator Password | Password acak kuat (crypto-secure), dibuat di perangkat Anda |
| 📱 QR Code Generator | Ubah link/teks jadi QR, unduh sebagai PNG |
| 📏 Konverter Satuan | Panjang, berat, suhu, ukuran data |
| 💯 Kalkulator Persen | Persentase, proporsi, harga diskon |
| 🧾 Split Bill | Bagi tagihan + pajak + service charge |
| ⚖️ Kalkulator BMI | Indeks massa tubuh (kategori WHO) |
| 🎂 Kalkulator Usia | Usia tepat hingga hitungan hari + countdown ulang tahun |
| 🎲 Undian Nama | Pilih pemenang acak — cocok untuk giveaway |
| 🍅 Pomodoro Timer | Timer fokus 25/5 untuk produktivitas |
| 🏦 Kalkulator Cicilan | Estimasi cicilan bulanan (bunga anuitas) |

**Keunggulan lain:**

- 🌐 Bilingual Indonesia/English dengan toggle satu klik (tersimpan di browser)
- 🔒 Privat — tidak ada data yang dikirim ke server manapun
- 🎨 Desain liquid glass (glassmorphism)
- 🔗 Tiap tool punya URL sendiri (mis. `#/splitbill`) sehingga mudah dibagikan
- ⚡ Satu file HTML, tanpa build step, tanpa dependency lokal

## 🚀 Demo

> `https://serbatools.netlify.app/`

## 📦 Cara Deploy

### GitHub Pages (gratis)

1. Push repo ini ke GitHub.
2. Buka **Settings → Pages** di repo Anda.
3. Pada **Source**, pilih **Deploy from a branch** → branch `main` → folder `/ (root)` → **Save**.
4. Tunggu 1–2 menit. Situs online di `https://<username>.github.io/<nama-repo>/`.

### Netlify

1. Buka [app.netlify.com/drop](https://app.netlify.com/drop), lalu drag & drop folder ini — atau connect repo GitHub Anda untuk auto-deploy setiap push.

### Vercel

1. Di dashboard [Vercel](https://vercel.com): **Add New → Project → Import** repo GitHub ini.
2. Framework preset: **Other**, tanpa build command. Deploy.

## 🛠️ Menjalankan Secara Lokal

Tidak perlu install apa pun — cukup buka `index.html` di browser.

## 🎨 Kustomisasi

- **Link donasi Trakteer**: cari `trakteer.id/manuelnicholas` di `index.html` (2 tempat: tombol embed di atas dan link di footer).
- **Warna aksen**: ubah `--accent` dan `--accent-deep` di bagian `:root` pada CSS.
- **Nama situs**: ganti `SerbaTools` di `<title>`, `.brand`, dan meta description.

## 🧱 Teknologi

HTML + CSS + Vanilla JavaScript dalam satu file. Dependency eksternal hanya via CDN: [qrcodejs](https://cdnjs.com/libraries/qrcodejs) untuk QR code dan Google Fonts (Inter).

## ☕ Dukungan

Jika tools ini bermanfaat, Anda bisa memberikan dukungan sukarela:

[![Trakteer](https://img.shields.io/badge/Trakteer-Traktir%20saya%20kopi%20☕-be1e2d)](https://trakteer.id/manuelnicholas)

## 📄 Lisensi

All Rights Reserved

This code is proprietary and confidential. 
Unauthorized copying, modification, or use is prohibited.
