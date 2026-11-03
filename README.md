# KCRA — Knowledge Commercialization Readiness Assessment

## Isi paket
- `index.html`: aplikasi assessment
- `manifest.webmanifest`: konfigurasi agar dapat diinstal sebagai PWA
- `sw.js`: cache/offline dasar
- `icon.svg`: ikon aplikasi

## Publikasi gratis melalui GitHub Pages
1. Buat repository publik baru di GitHub, misalnya `kcra-assessment`.
2. Unggah keempat file ini ke root repository (bukan folder di dalamnya).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`, folder `/ (root)`, lalu Save.
6. Tunggu proses publikasi. GitHub akan memberikan URL `https://USERNAME.github.io/kcra-assessment/`.
7. Bagikan URL tersebut. PWA dan service worker memerlukan HTTPS; GitHub Pages menyediakan HTTPS.

## Instalasi
- Android/Chrome: buka URL, pilih menu browser → Install app / Add to Home screen.
- Desktop Chrome/Edge: buka URL, pilih ikon Install di address bar atau menu browser.
- iPhone/iPad: buka di Safari → Share → Add to Home Screen.

## Catatan metodologis
Versi 1.0 memakai empat dimensi dengan bobot sama. Skor total = (jumlah skor dimensi / 20) × 100.
Kategori sementara: 80–100 = Siap; 60–79 = Siap dengan perbaikan; di bawah 60 = Belum siap.
Ambang dan rubrik perlu divalidasi melalui expert judgement dan uji coba sebelum digunakan untuk keputusan resmi. Aplikasi ini berjalan di browser; data tidak dikirim ke server. Hasil dapat dicetak/disimpan sebagai PDF atau diunduh sebagai JSON.
