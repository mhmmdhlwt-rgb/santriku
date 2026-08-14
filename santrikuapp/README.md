# Santriku - Portal Silaturahmi & Informasi Wali Santri

Aplikasi Web Progresif (PWA) untuk portal wali santri pondok pesantren, terintegrasi langsung dengan database absensi dan kegiatan santri.

## Fitur Utama
- **Beranda (Dashboard)**: Informasi status santri, kehadiran harian, pengumuman terbaru, tagihan administrasi, galeri dokumentasi, dan 4 tombol akses cepat Informasi Pesantren.
- **Akademik & Catatan**: Evaluasi berkala, target hafalan, dan catatan santri (prestasi, kesehatan, kedisiplinan).
- **Galeri Dokumentasi**: Format Bento Masonry Grid yang mempertahankan rasio asli foto (potret, lanskap, persegi) secara proporsional, dilengkapi pratinjau Lightbox layar penuh.
- **Pusat Info & Layanan**: Pengumuman umum, agenda pondok, customer service WhatsApp, dan peraturan resmi pondok pesantren.
- **Profil & Riwayat**: Identitas digital santri & wali santri, rekap kehadiran bulanan, dan linimasa absensi lengkap.
- **Panel Pengurus**: Kelola agenda, pengumuman, peraturan/dokumen, kontak pengurus, galeri foto, dan PIN admin.
- **PWA & Offline Ready**: Dapat diinstal ke homescreen Android & iOS dengan nama **Santriku**.

## Cara Deploy ke Vercel

### Opsi 1: Lewat Dashboard Vercel / GitHub
1. Buat repository baru di GitHub (misal: `santriku-pwa`).
2. Upload seluruh file proyek ke repository GitHub tersebut.
3. Buka [Vercel Dashboard](https://vercel.com/new).
4. Import repository GitHub tersebut.
5. Klik **Deploy** (Framework Preset: *Other*).

### Opsi 2: Lewat Vercel CLI
```bash
npm i -g vercel
vercel
```
