# Personal Portfolio Website - Salman Yusuf

Portfolio website statis yang modern dan responsif dengan dominasi warna abu-abu dan animasi yang halus.

## 📁 Struktur File

```
portfolio/
│
├── index.html          # Halaman utama
├── profile.html        # Halaman profil
├── work-exp.html       # Halaman pengalaman kerja
├── education.html      # Halaman pendidikan & sertifikasi
├── skills.html         # Halaman keahlian
├── contact.html        # Halaman kontak
│
├── style.css           # File CSS utama
├── script.js           # File JavaScript
│
├── assets/             # Folder untuk aset
│   ├── profile-photo.jpg   # Foto profil Anda
│   └── cv.pdf              # File CV dalam format PDF
│
└── README.md           # File dokumentasi
```

## 🚀 Cara Menggunakan

### 1. Setup Awal

1. Buat folder baru untuk project Anda
2. Buat semua file HTML, CSS, dan JS sesuai struktur di atas
3. Buat folder `assets/` di dalam folder project

### 2. Menambahkan Foto dan CV

**Foto Profil:**
- Simpan foto profil Anda di `assets/profile-photo.jpg`
- Ukuran recommended: 500x500 pixels atau lebih
- Format: JPG, PNG, atau WebP

**File CV:**
- Simpan file CV PDF Anda di `assets/cv.pdf`
- Pastikan nama file adalah `cv.pdf` atau update path di HTML

### 3. Kustomisasi Konten

Jika ingin mengubah konten, edit file HTML yang sesuai:
- **Informasi pribadi**: Edit `profile.html`
- **Pengalaman kerja**: Edit `work-exp.html`
- **Pendidikan**: Edit `education.html`
- **Keahlian**: Edit `skills.html`
- **Kontak**: Edit `contact.html`

### 4. Deploy ke GitHub Pages

1. **Buat Repository GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push ke GitHub:**
   ```bash
   git remote add origin https://github.com/username/repository-name.git
   git branch -M main
   git push -u origin main
   ```

3. **Aktifkan GitHub Pages:**
   - Buka repository di GitHub
   - Pergi ke Settings > Pages
   - Pilih branch `main` dan folder `/ (root)`
   - Klik Save
   - Website Anda akan tersedia di: `https://username.github.io/repository-name/`

## 🎨 Fitur

- ✅ **Multi-halaman** dengan navigasi yang smooth
- ✅ **Desain modern** dengan dominasi warna abu-abu
- ✅ **Animasi halus** pada scroll dan hover
- ✅ **Responsive design** untuk mobile dan desktop
- ✅ **Download CV** langsung dari website
- ✅ **Section terpisah** untuk setiap informasi
- ✅ **Pure HTML/CSS/JS** - tidak perlu build process

## 🎯 Kustomisasi Warna

Jika ingin mengubah skema warna, edit file `style.css`:

```css
/* Warna utama */
--primary-color: #2563eb;    /* Biru */
--gray-dark: #1f2937;        /* Abu-abu gelap */
--gray-medium: #6b7280;      /* Abu-abu medium */
--gray-light: #f9fafb;       /* Abu-abu terang */
```

## 🔧 Troubleshooting

**Foto tidak muncul:**
- Pastikan path foto benar: `assets/profile-photo.jpg`
- Cek nama file sama persis (case-sensitive)

**CV tidak bisa di-download:**
- Pastikan file CV ada di `assets/cv.pdf`
- Cek console browser untuk error

**Animasi tidak berjalan:**
- Pastikan file `script.js` sudah ter-load
- Buka browser console untuk cek error

## 📱 Browser Support

Website ini kompatibel dengan:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## 📝 Lisensi

© 2025 Salman Yusuf. All rights reserved.

---

**Dibuat dengan HTML, CSS, dan JavaScript** ❤️