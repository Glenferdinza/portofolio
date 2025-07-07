# Halaman Piagam Kejuaraan - Portfolio

## Deskripsi
Halaman web responsif untuk menampilkan detail piagam kejuaraan yang telah diraih. Dibuat dengan HTML, CSS, dan JavaScript untuk memberikan pengalaman pengguna yang menarik dan informatif dalam memamerkan pencapaian kompetisi.

## Fitur Utama

### 🏆 Tampilan Piagam
- Header dengan gradient emas-oranye yang elegan
- Ikon trophy dengan animasi glow
- Badge juara yang mencolok
- Informasi lengkap tentang lomba dan pencapaian

### 📱 Responsive Design
- Tampilan optimal di desktop, tablet, dan mobile
- Navigation bar yang dapat collapsed di mobile
- Layout grid yang adaptif
- Touch-friendly interface

### ✨ Animasi & Interaktivitas
- Fade-in animations untuk semua elemen
- Hover effects pada achievement badges
- Smooth scrolling untuk navigasi
- Interactive trophy dengan scale effect
- Transition effects yang halus

### 📄 Informasi Lengkap
- **Deskripsi Lomba**: Penjelasan detail tentang kompetisi
- **Kategori & Pencapaian**: Skill yang diuji dan dikuasai
- **Soal yang Diselesaikan**: Detail 5 soal dengan skor dan waktu
- **Informasi Piagam**: Data lengkap lomba dan penyelenggara
- **Hadiah & Penghargaan**: Daftar hadiah yang diterima
- **Teknologi**: Bahasa pemrograman dan tools yang digunakan

## Struktur File

```
piagam-kejuaraan.html
├── HTML Structure
│   ├── Navigation Bar
│   ├── Breadcrumb
│   ├── Header Section
│   ├── Main Content
│   │   ├── Piagam Details (2/3 width)
│   │   └── Sidebar (1/3 width)
│   └── Footer
├── CSS Styling
│   ├── Tailwind CSS (CDN)
│   ├── Font Awesome Icons
│   └── Custom Styles
└── JavaScript
    ├── Mobile Menu Toggle
    ├── Animation Initialization
    ├── Smooth Scrolling
    └── Interactive Effects
```

## Teknologi yang Digunakan

### Frontend Framework & Libraries
- **HTML5**: Struktur semantic dan modern
- **Tailwind CSS**: Utility-first CSS framework
- **Font Awesome 6.0**: Icon library
- **JavaScript (Vanilla)**: Interaktivitas dan animasi

### CDN Dependencies
- Tailwind CSS: `https://cdn.tailwindcss.com`
- Font Awesome: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css`

## Instalasi & Penggunaan

### Langkah 1: Download
```bash
# Download atau copy file HTML
# Simpan sebagai: piagam-kejuaraan.html
```

### Langkah 2: Buka di Browser
```bash
# Buka file di browser
# Atau gunakan live server untuk development
```

### Langkah 3: Kustomisasi
- Edit konten sesuai piagam yang dimiliki
- Sesuaikan warna tema jika diperlukan
- Tambahkan/ubah informasi personal

## Kustomisasi

### Mengubah Informasi Piagam
```html
<!-- Edit bagian header -->
<h1 class="text-3xl font-bold mb-2">Juara 1 Lomba Coding Competition</h1>
<p class="text-orange-100 text-lg">Universitas Indonesia Tech Festival 2024</p>
<p class="text-orange-100">Diraih: 20 Maret 2024</p>
```

### Mengubah Warna Tema
```css
/* Edit di bagian CSS */
.gradient-bg {
    background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
}
.piagam-bg {
    background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
}
```

### Menambah Soal/Pencapaian
```html
<!-- Tambahkan di bagian "Soal yang Diselesaikan" -->
<div class="border-l-4 border-green-500 pl-4">
    <h3 class="text-lg font-semibold text-gray-800">Judul Soal</h3>
    <p class="text-gray-600 mb-2">Deskripsi soal</p>
    <div class="flex flex-wrap gap-2">
        <span class="bg-green-100 text-green-800 px-2 py-1 rounded text-sm">✓ Selesai</span>
        <!-- badges lainnya -->
    </div>
</div>
```

## Fitur Interaktif

### Navigation
- **Breadcrumb**: Navigasi hierarkis
- **Mobile Menu**: Hamburger menu untuk mobile
- **Back Button**: Kembali ke halaman achievement

### Action Buttons
- **Bagikan**: Untuk membagikan piagam
- **Unduh PDF**: Download piagam dalam format PDF
- **Lihat Piagam Asli**: Link ke sumber asli

### Animations
- **Fade-in**: Animasi masuk bertahap
- **Hover Effects**: Efek saat cursor hover
- **Trophy Glow**: Animasi berkedip pada trophy
- **Scale Effects**: Efek pembesar saat hover

## Browser Support
- ✅ Chrome (80+)
- ✅ Firefox (75+)
- ✅ Safari (13+)
- ✅ Edge (80+)
- ✅ Mobile browsers

## Performance
- **Lightweight**: Menggunakan CDN untuk dependencies
- **Fast Loading**: Optimized CSS dan JavaScript
- **Smooth Animations**: Hardware-accelerated transitions
- **SEO Friendly**: Semantic HTML structure

## Lisensi
File ini dapat digunakan dan dimodifikasi untuk keperluan personal maupun komersial.

## Kontak
Untuk pertanyaan atau dukungan:
- Email: asyadda05@gmail.com

---
