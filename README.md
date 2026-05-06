# 🌐 CV SEMASA HIDUP - Website Profesional & Multi-Halaman

## 📋 Daftar Isi
1. [Deskripsi](#deskripsi)
2. [Fitur Utama](#fitur-utama)
3. [Struktur Halaman](#struktur-halaman)
4. [Petunjuk Penggunaan](#petunjuk-penggunaan)
5. [Integrasi Logo](#integrasi-logo)
6. [Customization](#customization)
7. [Dukungan Teknis](#dukungan-teknis)

---

## 🎯 Deskripsi

Website ini adalah **Single Page Application (SPA)** profesional yang menampilkan CV SEMASA HIDUP sebagai perusahaan teknologi terpadu. Menggunakan teknologi HTML5, CSS3, dan JavaScript murni (tanpa framework eksternal), website ini menawarkan pengalaman pengguna yang lancar dan responsif.

**File Utama:**
- `index.html` - File HTML lengkap dengan semua halaman terintegrasi
- `logo.png` - Logo resmi perusahaan CV SEMASA HIDUP

---

## ✨ Fitur Utama

### 1. **Sistem Multi-Halaman (SPA)**
Navigasi antar halaman tanpa refresh dengan animasi yang smooth:
- 🏠 **Halaman Beranda (Home)** - Presentasi utama perusahaan
- 📄 **Profile Lengkap** - Informasi detail perusahaan & manajemen
- ✅ **Legalitas & Dokumentasi** - Semua bukti legalitas & sertifikasi
- 📞 **Kontak** - Form komunikasi & informasi kontak

### 2. **Desain Responsif**
- ✓ Mobile-first approach
- ✓ Tablet compatible
- ✓ Desktop optimized
- ✓ Dinamis untuk semua ukuran layar

### 3. **Integrasi Logo Profesional**
- Logo terintegrasi di navbar
- Responsif dan berkualitas tinggi
- Clickable untuk kembali ke beranda

### 4. **Dokumentasi Lengkap**
Menampilkan semua aspek legalitas:
- ✓ NIB (Nomor Induk Berusaha)
- ✓ NPWP (Nomor Pokok Wajib Pajak)
- ✓ Akta Pendirian Notaris
- ✓ Registrasi Kementerian Hukum
- ✓ SPPL (Izin Lingkungan)
- ✓ Status Wajib Pajak

### 5. **Animasi & Interaktivitas**
- Fade-in effects pada halaman
- Hover animations pada cards
- Smooth scrolling
- Loading states yang elegant

### 6. **SEO & Aksesibilitas**
- Meta tags lengkap
- Semantic HTML5
- Accessible form elements
- Mobile viewport configured

---

## 🗂️ Struktur Halaman

### **Halaman 1: HOME (Beranda)**
```
├── Hero Section
│   ├── Headline utama
│   ├── CTA buttons
│   └── Feature cards
├── Company Info
│   ├── Legalitas terjamin
│   ├── Lokasi strategis
│   └── Struktur organisasi
├── Services Section
│   └── 6 layanan utama
├── Statistics
│   └── 4 KPI penting
└── Footer
```

### **Halaman 2: PROFILE LENGKAP**
```
├── Header dengan Logo
├── Identitas Perusahaan
│   ├── Nama resmi
│   ├── NIB & NPWP
│   └── Tanggal terdaftar
├── Lokasi & Kontak
├── Struktur Manajemen (Timeline)
│   ├── Direktur Utama
│   ├── Direktur
│   └── Tim Komisaris
├── 15 Bidang Usaha (Business Grid)
└── Sertifikasi & Status
```

### **Halaman 3: LEGALITAS & DOKUMENTASI**
```
├── Legality Badges
│   ├── NIB
│   ├── NPWP
│   ├── Akta Pendirian
│   ├── Registrasi Hukum
│   ├── SPPL
│   └── Status Pajak
├── Dokumentasi Lengkap (Document Grid)
│   ├── Perizinan Berusaha
│   ├── Struktur Organisasi
│   ├── Status Pajak
│   ├── Lokasi & Fasilitas
│   ├── Komitmen Lingkungan
│   └── Sertifikasi
├── Timeline Registrasi
└── Ringkasan Kelengkapan
```

### **Halaman 4: KONTAK**
```
├── Informasi Kontak
│   ├── Alamat
│   ├── Telepon
│   ├── Email
│   ├── Rekening Bank
│   └── Data Perusahaan
├── Contact Form
│   ├── Nama
│   ├── Email
│   ├── Telepon
│   ├── Nama Perusahaan
│   └── Pesan
├── Jam Operasional
└── Footer dengan Link Cepat
```

---

## 🚀 Petunjuk Penggunaan

### **1. Setup Awal**

#### Option A: Direct File Opening
```bash
# Buka di browser favorit Anda
- Double-click file `index.html`
- Atau drag & drop ke browser
- Atau klik kanan → Open with Browser
```

#### Option B: Local Server (Recommended)
```bash
# Menggunakan Python 3
python -m http.server 8000

# Menggunakan Python 2
python -m SimpleHTTPServer 8000

# Menggunakan Node.js (dengan http-server)
npx http-server

# Menggunakan PHP
php -S localhost:8000
```

Kemudian akses di browser: `http://localhost:8000`

### **2. Navigasi Antar Halaman**

**Dari Navbar:**
- Klik logo untuk ke Beranda
- Klik menu items (Beranda, Profile Lengkap, Legalitas, Kontak)
- Klik tombol "Hubungi Kami"

**Dari Halaman:**
- Klik tombol "Pelajari Lebih Lanjut" di Hero
- Klik tombol "Kembali ke Beranda" di atas halaman
- Klik link di footer

**Navigasi Halaman:**
```javascript
// Di background, semua halaman dimuat dalam satu HTML
// Navigasi menggunakan JavaScript:
showPage('home')     // Ke halaman Beranda
showPage('profile')  // Ke Profile Lengkap
showPage('legality') // Ke Legalitas
showPage('contact')  // Ke Kontak
```

### **3. Form Kontak**

Pengisian form:
1. Masukkan Nama Lengkap
2. Masukkan Email yang valid
3. Masukkan Nomor Telepon
4. Masukkan Nama Perusahaan
5. Tulis pesan/kebutuhan Anda
6. Klik tombol "Kirim Pesan"

Untuk integrasi email sebenarnya, hubungkan dengan service seperti:
- Formspree
- Netlify Forms
- EmailJS
- Backend API sendiri

---

## 🎨 Integrasi Logo

### **Cara Kerja Logo:**

Logo terintegrasi di:
1. **Navbar** - Kiri atas (clickable)
2. **Profile Page** - Header section
3. **Footer** - Tersirat dalam branding

### **File Logo:**
- Nama file: `logo.png`
- Format: PNG dengan transparent background
- Ukuran: Fleksibel (auto-scale)
- Lokasi: Sama folder dengan `index.html`

### **Cara Mengganti Logo:**

1. Siapkan file logo baru (format PNG, JPG, atau SVG)
2. Rename menjadi `logo.png` (atau sesuaikan nama di HTML)
3. Ganti di line HTML:
```html
<img src="logo.png" alt="CV SEMASA HIDUP">
```

### **Optimasi Logo:**

Untuk performa lebih baik, gunakan:
```html
<!-- Format WebP dengan fallback PNG -->
<picture>
    <source srcset="logo.webp" type="image/webp">
    <img src="logo.png" alt="CV SEMASA HIDUP">
</picture>
```

---

## 🛠️ Customization

### **1. Mengubah Warna Brand**

Edit variable CSS di awal `<style>`:
```css
:root {
    --primary: #1a4d7a;    /* Biru gelap */
    --secondary: #e8931f;   /* Oranye */
    --accent: #00b4d8;      /* Cyan */
    --dark: #0f2a3d;        /* Hitam */
    --light: #f8f9fa;       /* Abu-abu muda */
    --text: #1a1a1a;        /* Teks */
    --border: #e0e0e0;      /* Border */
}
```

### **2. Mengubah Konten Teks**

Setiap section dapat diedit langsung di HTML:

```html
<!-- Mengubah headline hero -->
<h1>Solusi Teknologi Terpadu untuk <span class="highlight">Bisnis Modern</span></h1>

<!-- Mengubah deskripsi -->
<p>Kami menyediakan layanan IT komprehensif...</p>

<!-- Mengubah informasi kontak -->
<p>089532559611</p>
<p>cvsemasahidup@gmail.com</p>
```

### **3. Menambah/Mengurangi Section**

Contoh menambah service card baru:

```html
<div class="service-card">
    <h3>🆕 Service Baru</h3>
    <p>Deskripsi service baru Anda</p>
</div>
```

### **4. Mengubah Font**

Default menggunakan Segoe UI. Untuk mengubah:

```css
body {
    font-family: 'Nama Font Baru', fallback, sans-serif;
}
```

---

## 📱 Responsive Design

### **Breakpoints:**
- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

### **Testing Responsive:**

Gunakan browser DevTools:
1. Tekan `F12` atau `Ctrl+Shift+I`
2. Klik toggle device toolbar
3. Pilih device yang ingin ditest

---

## 🎯 Call-to-Action (CTA) Buttons

Website menggunakan beberapa CTA:

1. **Primary Button** (Oranye gradient)
   - "Mulai Sekarang"
   - "Pelajari Lebih Lanjut"
   - "Kirim Pesan"

2. **Secondary Button** (White border)
   - "Hubungi Kami"
   - "Kembali ke Beranda"

3. **Link Buttons** (Dalam teks)
   - Di footer sections
   - Di navigation

---

## 🔐 Data & Privacy

### **Data yang Ditampilkan:**
Semua data yang ditampilkan adalah:
- ✓ Data publik resmi perusahaan
- ✓ Informasi dari dokumen legal
- ✓ Contact info yang ingin dipublikasikan
- ✓ Tidak ada data pribadi pemilik yang sensitif

### **GDPR & Privacy:**
Jika menambahkan form pengumpulan data:
- Tambahkan Privacy Policy
- Tambahkan Terms & Conditions
- Implementasikan cookie consent
- Compliance dengan regulasi lokal

---

## 🚀 Deployment

### **Option 1: GitHub Pages** (FREE)
```bash
# 1. Push files ke GitHub
git add .
git commit -m "Deploy website"
git push origin main

# 2. Di GitHub settings → Pages
# 3. Select main branch
# 4. Website siap di: username.github.io/repo-name
```

### **Option 2: Netlify** (FREE)
```bash
# 1. Drag & drop folder ke Netlify
# 2. Website otomatis live dengan SSL
# 3. URL: site-name.netlify.app
```

### **Option 3: Hosting Berbayar**
- Bluehost
- Hostinger
- DreamHost
- AWS
- DigitalOcean

---

## 📊 Performance

### **Metrics:**
- **Page Load:** < 2 detik
- **LCP:** < 2.5 detik
- **CLS:** < 0.1

### **Optimasi:**
- ✓ Minifikasi CSS/JS
- ✓ Compress images
- ✓ Lazy loading
- ✓ Caching strategy

---

## 🐛 Troubleshooting

### **Logo tidak tampil?**
- Cek nama file `logo.png` (case-sensitive)
- Pastikan file ada di folder yang sama
- Cek console browser (F12) untuk error

### **Halaman tidak berpindah?**
- Refresh browser
- Cek JavaScript console untuk error
- Pastikan JavaScript enabled di browser

### **Form tidak bekerja?**
- Form hanya menampilkan alert di demo
- Untuk submit sebenarnya, integrasikan dengan backend atau service

### **Styling berubah?**
- Clear cache browser (Ctrl+Shift+Delete)
- Atau gunakan Hard Refresh (Ctrl+Shift+R)

---

## 📞 Dukungan & Support

### **Kontak Teknis:**
- **Email:** cvsemasahidup@gmail.com
- **Telepon:** 089532559611
- **Alamat:** Jl. Cikoko Timur II No.28, Jakarta Selatan

### **Social Media:**
- Website di-update secara berkala
- Follow untuk informasi terbaru

---

## 📄 License & Rights

Website ini merupakan properti CV SEMASA HIDUP.

**© 2025 CV SEMASA HIDUP**

---

## 🎓 Panduan Pengembang

### **Struktur File:**
```
project/
├── index.html          # File utama (ALL IN ONE)
├── logo.png            # Logo perusahaan
└── README.md           # Dokumentasi ini
```

### **Cara Extend Functionality:**

**Menambah Halaman Baru:**
```html
<!-- 1. Tambah di HTML -->
<div id="page-baru" class="page">
    <!-- Konten halaman -->
</div>

<!-- 2. Tambah di Navigation -->
<li><a onclick="showPage('page-baru')">Page Baru</a></li>
```

**Menambah Form Validation:**
```javascript
function validateEmail(email) {
    const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    return regex.test(email);
}
```

---

## ✅ Checklist Sebelum Go-Live

- [ ] Cek semua link dan navigasi
- [ ] Test di mobile & tablet
- [ ] Verifikasi semua informasi akurat
- [ ] Test form kontak
- [ ] Setup Google Analytics (optional)
- [ ] Setup SSL/HTTPS
- [ ] Backup files
- [ ] Test loading speed
- [ ] SEO basic setup
- [ ] Social media sharing setup

---

## 🎉 Selesai!

Website profesional CV SEMASA HIDUP siap untuk dipublikasikan!

Untuk bantuan lebih lanjut atau customization, hubungi tim development kami.

**Made with ❤️ for CV SEMASA HIDUP**
