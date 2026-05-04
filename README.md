# co.bold
# co.bold space — Landing Page

Landing page untuk kedai kopi **co.bold space**. Dibangun dengan HTML, CSS, dan Vanilla JavaScript murni — 100% kompatibel dengan GitHub Pages.

---

## 📁 Struktur File

```
cobold-space/
├── index.html     ← Struktur & konten halaman
├── style.css      ← Semua styling & animasi
├── script.js      ← Interaktivitas & efek
└── README.md      ← Panduan ini
```

---

## 🚀 Deploy ke GitHub Pages

### Langkah-langkah:

1. **Buat repository baru di GitHub**
   - Pergi ke [github.com](https://github.com) → New Repository
   - Nama repo: `cobold-space` (atau sesuai keinginan)
   - Set ke **Public**

2. **Upload semua file**
   ```bash
   git init
   git add .
   git commit -m "first commit: co.bold space landing page"
   git branch -M main
   git remote add origin https://github.com/USERNAME/cobold-space.git
   git push -u origin main
   ```

3. **Aktifkan GitHub Pages**
   - Buka tab **Settings** di repo
   - Scroll ke bagian **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` → folder `/root`
   - Klik **Save**

4. **Akses landing page**
   - URL: `https://USERNAME.github.io/cobold-space`
   - Biasanya aktif dalam 1–3 menit

---

## 🎨 Kustomisasi

### Ganti teks & konten
Edit langsung di `index.html`:
- **Tagline hero** → cari `<h1 class="hero-title">`
- **Menu & harga** → cari section `<div class="menu-tab-content">`
- **Alamat & jam** → cari section `<section class="visit">`
- **Nomor telepon & Instagram** → cari `.visit-val`

### Ganti warna
Edit variabel di `style.css`:
```css
:root {
  --gold:    #c9a84c;  /* Warna aksen utama */
  --black:   #0a0907;  /* Background gelap */
  --brown:   #3d2e1e;  /* Coklat tua */
  --cream:   #f0e6d0;  /* Teks terang */
}
```

### Tambah foto nyata
Ganti div placeholder dengan tag `<img>`:
```html
<!-- Contoh di gallery -->
<div class="gallery-item g1">
  <img src="foto-interior.jpg" alt="Interior co.bold space" />
  <div class="gallery-overlay"><p>Main Hall</p></div>
</div>
```

### Embed Google Maps
Di section `visit`, ganti div `.map-placeholder` dengan:
```html
<iframe
  src="https://www.google.com/maps/embed?pb=YOUR_EMBED_URL"
  width="100%"
  height="450"
  style="border:0; border-radius: 12px;"
  allowfullscreen=""
  loading="lazy">
</iframe>
```

---

## ✨ Fitur yang Sudah Ada

- ✅ Custom cursor (gold dot + trail)
- ✅ Navbar sticky dengan scroll effect
- ✅ Hamburger menu untuk mobile
- ✅ Hero section dengan animasi teks
- ✅ Marquee/ticker animasi
- ✅ Reveal on scroll (semua section)
- ✅ Counter animasi (stats)
- ✅ Menu tabs (Espresso / Manual / Signature / Bites)
- ✅ Gallery dengan tilt effect hover
- ✅ Parallax pada background circles
- ✅ Map placeholder (siap di-embed)
- ✅ Footer lengkap
- ✅ Full responsive (mobile/tablet/desktop)

---

## 📦 Dependencies

Tidak ada npm / framework — semua external hanya:
- **Google Fonts** (Bebas Neue, Cormorant Garamond, DM Mono) → via CDN
- Tidak ada jQuery, Bootstrap, atau library lain

100% kompatibel dengan GitHub Pages static hosting.

---

*Built for co.bold space — Where Bold Meets Brew.*
