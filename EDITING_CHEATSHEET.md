# 📝 EDITING CHEAT SHEET - Quick Reference Guide

## 🎯 Editing Website dengan Mudah

Buka file `index.html` dengan text editor (Notepad++, VS Code, Sublime, dll) dan gunakan panduan ini.

---

## 🔤 MENGUBAH TEKS

### Headline Hero Section
**Lokasi:** Cari `<h1>Solusi Teknologi Terpadu untuk`

```html
<!-- SEBELUM -->
<h1>Solusi Teknologi Terpadu untuk <span class="highlight">Bisnis Modern</span></h1>

<!-- SESUDAH (Contoh) -->
<h1>Platform Digital Terdepan untuk <span class="highlight">Kesuksesan Anda</span></h1>
```

### Deskripsi Singkat
**Lokasi:** Cari `<p>Kami menyediakan layanan IT komprehensif`

```html
<!-- SEBELUM -->
<p>Kami menyediakan layanan IT komprehensif dengan standar internasional...</p>

<!-- SESUDAH -->
<p>Solusi teknologi terpercaya untuk mengakselerasi transformasi digital bisnis Anda...</p>
```

### Section Heading
**Lokasi:** Cari `<h2>` di setiap section

```html
<!-- CONTOH: Tentang CV SEMASA HIDUP -->
<h2>Tentang CV SEMASA HIDUP</h2>

<!-- UBAH MENJADI -->
<h2>Tentang Perusahaan Kami</h2>
```

---

## 📞 MENGUBAH KONTAK

### Nomor Telepon
**Cari semua kemunculan dan ganti:**

```html
<!-- SEBELUM -->
089532559611

<!-- SESUDAH -->
0812-3456-7890
```

### Email
**Cari:**
```html
<!-- SEBELUM -->
cvsemasahidup@gmail.com

<!-- SESUDAH -->
email@perusahaananda.com
```

### Alamat
**Lokasi:** Cari `<p>Jl. Cikoko Timur II`

```html
<!-- SEBELUM -->
Jl. Cikoko Timur II No.28, Pancoran, Jakarta Selatan, DKI Jakarta 12770

<!-- SESUDAH -->
Jl. Nama Jalan No.XX, Kelurahan, Kecamatan, Kota, Provinsi
```

### Rekening Bank
**Lokasi:** Cari `Mandiri: 1030012913121`

```html
<!-- SEBELUM -->
Mandiri: 1030012913121

<!-- SESUDAH -->
BCA: 0123456789 atau Nomor Rekening Anda
```

---

## 🎨 MENGUBAH WARNA

### Warna Brand Utama (Biru)
**Lokasi:** Cari `--primary: #1a4d7a;` (di bagian `:root {}`)

```css
/* SEBELUM - Biru tua */
--primary: #1a4d7a;

/* SESUDAH - Ganti dengan hex color pilihan Anda */
--primary: #003d82;    /* Biru lebih terang */
--primary: #1e3a8a;    /* Biru indigo */
--primary: #064e3b;    /* Hijau gelap */
```

### Warna Accent (Oranye)
**Lokasi:** Cari `--secondary: #e8931f;`

```css
/* SEBELUM - Oranye */
--secondary: #e8931f;

/* SESUDAH */
--secondary: #ff6b35;   /* Oranye lebih cerah */
--secondary: #f97316;   /* Oranye elegan */
--secondary: #ca8a04;   /* Amber */
```

### Warna Accent (Cyan/Biru Muda)
**Lokasi:** Cari `--accent: #00b4d8;`

```css
/* SEBELUM - Cyan */
--accent: #00b4d8;

/* SESUDAH */
--accent: #06b6d4;      /* Cyan lebih cerah */
--accent: #0891b2;      /* Cyan tua */
--accent: #0ea5e9;      /* Sky blue */
```

### Warna Background Light
**Lokasi:** Cari `--light: #f8f9fa;`

```css
/* SEBELUM */
--light: #f8f9fa;

/* SESUDAH */
--light: #f0f9ff;       /* Sky light */
--light: #faf5ff;       /* Purple light */
--light: #faf9f6;       /* Cream light */
```

---

## 🔘 MENGUBAH BUTTONS

### Button Text
**Cari button dengan text yang ingin diubah:**

```html
<!-- SEBELUM -->
<button class="btn-primary">Mulai Sekarang</button>

<!-- SESUDAH -->
<button class="btn-primary">Konsultasi Gratis</button>
```

### Button Action
**Cari `onclick="showPage(...)"` dan ubah nama halaman:**

```html
<!-- SEBELUM - Ke halaman profile -->
<button onclick="showPage('profile')">Pelajari Lebih Lanjut</button>

<!-- SESUDAH - Ke halaman contact -->
<button onclick="showPage('contact')">Hubungi Kami Sekarang</button>
```

Halaman yang tersedia:
- `home` - Beranda
- `profile` - Profile Lengkap
- `legality` - Legalitas & Dokumentasi
- `contact` - Kontak

---

## 🖼️ MENGGANTI LOGO

### Cara Simpel
1. Siapkan file logo baru (PNG atau JPG)
2. Rename menjadi `logo.png` (PENTING: nama harus sama)
3. Letakkan di folder yang sama dengan `index.html`
4. Reload browser - logo otomatis muncul! ✅

### Cara Advanced (Ubah Nama File)
Jika ingin nama file berbeda, cari semua `<img src="logo.png"`:

```html
<!-- SEBELUM -->
<img src="logo.png" alt="CV SEMASA HIDUP">

<!-- SESUDAH (jika file bernama logo_baru.png) -->
<img src="logo_baru.png" alt="CV SEMASA HIDUP">
```

---

## 📝 MENGUBAH SERVICE/LAYANAN

### Menambah Service Card Baru
**Lokasi:** Cari `<div class="services-grid">`

```html
<!-- Template untuk menambah service baru -->
<div class="service-card">
    <h3>🆕 Icon & Nama Layanan</h3>
    <p>Deskripsi layanan Anda dalam 1-2 kalimat singkat</p>
</div>
```

### Mengubah Service Existing
**Cari service yang ingin diubah:**

```html
<!-- SEBELUM -->
<div class="service-card">
    <h3>🖥️ Infrastruktur IT</h3>
    <p>Penyediaan dan pemeliharaan infrastruktur teknologi...</p>
</div>

<!-- SESUDAH -->
<div class="service-card">
    <h3>☁️ Cloud Solutions</h3>
    <p>Solusi cloud computing terintegrasi untuk bisnis modern...</p>
</div>
```

---

## 📊 MENGUBAH STATISTICS/KPI

### Mengubah Angka & Label
**Cari `<div class="stats-grid">`:**

```html
<!-- SEBELUM -->
<div class="stat-item">
    <div class="stat-number">15+</div>
    <div class="stat-label">Bidang Usaha</div>
</div>

<!-- SESUDAH -->
<div class="stat-item">
    <div class="stat-number">50+</div>
    <div class="stat-label">Klien Puas</div>
</div>
```

---

## 👥 MENGUBAH TEAM MEMBERS

### Menambah/Mengubah Team Member
**Cari `<div class="team-grid">`:**

```html
<!-- SEBELUM -->
<div class="team-member">
    <div class="team-member-avatar">👔</div>
    <div class="team-member-info">
        <h3>Husni Thamrin</h3>
        <p>Direktur Utama</p>
    </div>
</div>

<!-- SESUDAH -->
<div class="team-member">
    <div class="team-member-avatar">💼</div>
    <div class="team-member-info">
        <h3>Nama Baru</h3>
        <p>Posisi Baru</p>
    </div>
</div>
```

---

## 📄 MENGUBAH DOKUMEN/LEGALITAS

### Mengubah Dokumen Card
**Lokasi:** Cari `<div class="document-card">`

```html
<!-- SEBELUM -->
<div class="document-card">
    <div class="document-header">
        <div class="document-icon">🎖️</div>
        <h3>Perizinan Berusaha</h3>
        <p>Risiko Berbasis</p>
    </div>
    <div class="document-body">
        <ul>
            <li>Izin Operasional Lengkap</li>
            <li>15 Kode KBLI Terverifikasi</li>
        </ul>
    </div>
</div>

<!-- SESUDAH - Ubah content sesuai kebutuhan -->
```

---

## 🎯 MENGUBAH FORM PLACEHOLDER

### Form Fields
**Cari `<input type="text" placeholder=`:**

```html
<!-- SEBELUM -->
<input type="text" placeholder="Nama Lengkap" required>

<!-- SESUDAH -->
<input type="text" placeholder="Nama & Marga Lengkap" required>
```

---

## 🔗 MENGUBAH INTERNAL LINKS

### Navigation Links
**Cari `onclick="showPage(`:**

```html
<!-- Format standar -->
<a onclick="showPage('home')">Beranda</a>
<a onclick="showPage('profile')">Profile Lengkap</a>
<a onclick="showPage('legality')">Legalitas</a>
<a onclick="showPage('contact')">Kontak</a>
```

---

## 🎨 MENGUBAH FONT

### Font Family
**Lokasi:** Cari `font-family:` di bagian `body {}`

```css
/* SEBELUM */
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

/* SESUDAH - Gunakan Google Fonts */
font-family: 'Poppins', sans-serif;
font-family: 'Raleway', sans-serif;
font-family: 'Outfit', sans-serif;
```

### Cara Pakai Google Fonts
1. Buka fonts.google.com
2. Cari font yang disukai
3. Copy link dan paste di `<head>`
4. Gunakan di CSS

---

## 📱 RESPONSIVE BREAKPOINT

### Untuk Mobile Customization
**Cari `@media (max-width: 768px)`:**

```css
@media (max-width: 768px) {
    /* Edit CSS untuk mobile di sini */
    .hero-content h1 {
        font-size: 1.8rem; /* Ubah ukuran */
    }
}
```

---

## 🔍 FIND & REPLACE TIPS

Gunakan fitur Find & Replace (Ctrl+H) untuk:

### Ganti Semua Nama Perusahaan
```
Find:    CV SEMASA HIDUP
Replace: CV Perusahaan Baru
```

### Ganti Semua Email
```
Find:    cvsemasahidup@gmail.com
Replace: email@perusahaanbaru.com
```

### Ganti Nomor Telepon
```
Find:    089532559611
Replace: 0812-3456-7890
```

---

## ⚠️ SAFETY TIPS

### Sebelum Edit:
- ✅ Backup file original `index.html`
- ✅ Gunakan text editor yang tepat (VS Code, Notepad++)
- ✅ Jangan hapus struktur HTML penting
- ✅ Hati-hati dengan quotes dan brackets

### Tag & Element Penting (JANGAN HAPUS):
```html
<!-- Struktur page utama -->
<div id="home" class="page active">...</div>
<div id="profile" class="page">...</div>
<div id="legality" class="page">...</div>
<div id="contact" class="page">...</div>

<!-- Navigation function -->
<nav>...</nav>

<!-- JavaScript untuk navigasi -->
<script>
    function showPage(pageId) { ... }
</script>
```

---

## 🚀 COMMON EDITS SUMMARY

| Tugas | Lokasi | Contoh |
|------|--------|---------|
| Ubah headline | Hero section `<h1>` | "Solusi Terpadu" |
| Ubah email | Search `@gmail.com` | "newemail@domain.com" |
| Ubah no telp | Search `0895` | "0812-3456-7890" |
| Ubah warna utama | `:root { --primary` | `#003d82` |
| Tambah service | `.services-grid` | Copy & modify card |
| Ubah team | `.team-grid` | Update nama & posisi |
| Ganti logo | Rename file & update | `<img src="logo.png">` |
| Tambah halaman | Duplikasi page `<div>` | Buat id halaman baru |

---

## 💾 SAVE & TEST

### Setiap Selesai Edit:
1. **Save** file (Ctrl+S)
2. **Refresh** browser (F5)
3. **Check** hasilnya
4. Jika ada error, undo (Ctrl+Z)
5. Cek browser console (F12) untuk error messages

---

## 📚 RESOURCES

- **Hex Color Picker:** colorpicker.com
- **Google Fonts:** fonts.google.com
- **Emoji List:** emojipedia.org
- **HTML Validator:** validator.w3.org
- **CSS Validator:** jigsaw.w3.org/css-validator

---

**Happy Editing! 🎉**

*Save ini sebagai bookmark untuk referensi cepat*
