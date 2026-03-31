# SpeakUp Coach - iPhone App (PWA)

AI English speaking coach yang berjalan sebagai app di iPhone.

## Files
- `index.html` - Main app
- `manifest.json` - PWA manifest
- `sw.js` - Service worker (offline support)
- `icon-192.png` - App icon 192x192
- `icon-512.png` - App icon 512x512
- `apple-touch-icon.png` - iOS home screen icon

## Deploy Gratis ke GitHub Pages (5 menit)

### 1. Buat GitHub Repository
- Buka https://github.com/new
- Nama repo: `speakup-coach` (atau apapun)
- Set **Public**
- Klik **Create repository**

### 2. Upload Files
- Di halaman repo, klik **Add file** > **Upload files**
- Drag semua file dari folder ini (index.html, manifest.json, sw.js, semua icon)
- Klik **Commit changes**

### 3. Aktifkan GitHub Pages
- Buka **Settings** > **Pages**
- Source: pilih **Deploy from a branch**
- Branch: pilih **main**, folder **/ (root)**
- Klik **Save**
- Tunggu 1-2 menit

### 4. Akses App
- URL: `https://[username].github.io/speakup-coach/`
- Buka URL ini di **Safari** di iPhone

### 5. Install di iPhone
- Di Safari, tap tombol **Share** (kotak dengan panah ke atas)
- Scroll ke bawah, tap **Add to Home Screen**
- Beri nama "SpeakUp Coach"
- Tap **Add**
- App icon akan muncul di home screen seperti native app

## Cara Pakai
1. Buka app, masukkan API key dari console.anthropic.com/settings/keys
2. Masukkan nama student dan pilih level (B1/B2/C1)
3. Pilih skenario atau Free Talk
4. Coach Alex akan bicara duluan
5. Tap **Start** untuk mulai bicara, tap **Stop** ketika selesai
6. Coach akan merespons dengan koreksi dan saran
7. Ulangi sampai session selesai

## Biaya
- Hosting: GRATIS (GitHub Pages)
- API: ~$0.01-0.02 per sesi (Claude Sonnet)
- Top-up $5 di Anthropic cukup untuk ratusan sesi latihan

## Troubleshooting
- **Mic tidak jalan**: Pastikan izin microphone diberikan di Settings > Safari > Microphone
- **Voice tidak keluar**: Cek volume iPhone, pastikan tidak dalam silent mode
- **API error**: Cek API key valid dan ada credit di console.anthropic.com
