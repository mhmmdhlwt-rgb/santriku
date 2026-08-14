# Pesantrenku - Portal Wali Santri (PWA)

Aplikasi Web Progressive (PWA) Portal Silaturahmi Wali Santri Pondok Pesantren, siap di-deploy langsung ke **Vercel** dan di-install di Android, iOS, maupun Desktop.

## 🚀 Fitur Utama
- **Siap PWA (Installable)**: Dapat dipasang langsung ke Home Screen HP tanpa melalui Play Store/App Store.
- **Support Service Worker & Offline**: Aplikasi tetap berjalan lancar walaupun koneksi internet tidak stabil.
- **Multi-Pesantren & Multi-Sesi**: Login wali dengan NIS & PIN, serta portal admin pengurus.
- **3D Islamic Design System**: UI modern dengan tema emerald & gold.
- **Akademik & Catatan Kedisiplinan / Pelanggaran**: Tampilan rapi, responsif, dan lancar di-scroll pada semua layar.

## 📦 Struktur File Project
```
├── index.html              # Aplikasi utama (HTML/CSS/JS)
├── manifest.json           # Web App Manifest untuk PWA
├── sw.js                   # Service Worker untuk caching & offline support
├── vercel.json             # Konfigurasi Deployment Vercel
├── package.json            # Manifest paket Node.js
├── icon.svg                # Icon aplikasi vektor
├── icon-192.png            # Icon PWA 192x192
├── icon-512.png            # Icon PWA 512x512
├── icon-512-maskable.png   # Icon PWA Maskable (Android)
├── apple-touch-icon.png    # Icon Home Screen iOS (180x180)
├── favicon-32x32.png       # Favicon browser 32x32
├── favicon-16x16.png       # Favicon browser 16x16
└── favicon.ico             # Standard ICO favicon
```

## 🌐 Cara Deploy ke Vercel
1. Buka terminal di folder project ini.
2. Jalankan command:
   ```bash
   npx vercel
   ```
3. Ikuti instruksi di layar. Selesai!

## 📱 Cara Menginstall di HP (Android & iOS)
- **Android (Chrome)**: Buka URL -> klik tombol "Install" pada banner atau pilih "Tambahkan ke Layar Utama".
- **iOS (Safari)**: Buka URL -> klik tombol Share -> pilih "Add to Home Screen".
