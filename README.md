# Panduan Website Link in Bio

Template website "link in bio" yang bersih dan modern, dibangun dengan HTML, TailwindCSS, dan JavaScript.

## 🔗 Demo

[Link in Bio Demo](https://aqid191161.github.io/Link-in-Bio/index.html)



## 🚀 Memulai

1. Buka file `index.html` di editor kode (seperti Visual Studio Code)
2. Cari bagian yang ingin disesuaikan
3. Simpan file setelah melakukan perubahan
4. Buka di browser untuk melihat hasilnya

## 📝 Cara Menyesuaikan

### Mengubah Informasi Profil

Temukan Bagian Profil di `index.html`:

```html
<div class="text-center mb-12">
    <!-- Gambar Profil -->
    <div class="mx-auto rounded-full overflow-hidden shadow-2xl mb-8 profile-img">
        <img src="URL-GAMBAR-ANDA" 
             alt="Foto Profil" 
             class="h-full w-full object-cover">
    </div>
    <!-- Nama dan Deskripsi -->
    <h1 class="text-4xl font-bold mb-3 name-title">Nama Anda</h1>
    <p class="text-gray-600 text-lg font-light leading-relaxed">Deskripsi Anda di sini</p>
</div>
```

- Ganti `URL-GAMBAR-ANDA` dengan URL foto profil Anda
- Ubah `Nama Anda` dengan nama Anda
- Edit teks deskripsi sesuai kebutuhan

### Memperbarui Link Media Sosial

Temukan bagian Ikon Media Sosial:

```html
<div class="flex justify-center space-x-4 mt-4">
    <a href="#" class="text-gray-500 hover:text-gray-700 social-icon">
        <i class="fab fa-instagram text-xl"></i>
    </a>
    <!-- Ikon media sosial lainnya... -->
</div>
```

Ganti `#` dengan URL profil media sosial Anda:
- Instagram: `https://instagram.com/namapengguna`
- Twitter: `https://twitter.com/namapengguna`
- GitHub: `https://github.com/namapengguna`
- LinkedIn: `https://linkedin.com/in/namapengguna`

## 🎨 Mengubah Warna

Edit variabel root di bagian CSS:

```css
:root {
    --primary-color: #8B5CF6;    /* Warna aksen utama */
    --secondary-color: #EC4899;  /* Warna aksen sekunder */
    --bg-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 🎨 Kustomisasi Gaya Lanjutan

### Mengubah Efek Animasi

```css
.profile-img {
    transition: transform 0.6s cubic-bezier(0.33, 1, 0.68, 1);
    /* ...kode yang ada... */
}

.profile-img:hover {
    transform: scale(1.05) rotate(2deg);  /* Sesuaikan nilai scale dan rotasi */
}
```

### Pilihan Gradien Latar Belakang

```css
:root {
    /* Ungu ke Merah Muda */
    --bg-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    
    /* Biru Laut */
    --bg-gradient: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    
    /* Oranye Senja */
    --bg-gradient: linear-gradient(135deg, #f6d365 0%, #fda085 100%);
    
    /* Hijau Hutan */
    --bg-gradient: linear-gradient(135deg, #00b09b 0%, #96c93d 100%);
}
```

## 💡 Tips Penyuntingan

1. Jaga panjang teks agar tetap seimbang
2. Gunakan gambar profil berkualitas tinggi
3. Periksa semua tautan setelah diperbarui
4. Jaga konsistensi spasi dalam kode
5. Tinjau perubahan di desktop dan mobile
6. Gunakan gaya ikon yang serupa

## 🔍 Menguji Perubahan

1. Simpan semua perubahan di `index.html`
2. Buka file di browser
3. Uji semua tautan dan efek hover
4. Periksa tampilan responsif menggunakan dev tools (F12)

## 📱 Perintah Pengujian Mobile

```bash
# Menggunakan python untuk membuat server lokal
python3 -m http.server 8000
```

Kemudian buka `http://localhost:8000` di perangkat mobile Anda (pastikan kedua perangkat berada dalam jaringan yang sama).

## ⚠️ Masalah Umum

- Jika ikon tidak muncul, periksa koneksi internet (Font Awesome membutuhkan internet)
- Jika animasi tidak mulus, pastikan JavaScript diaktifkan
- Jika gradien rusak, pastikan variabel CSS didefinisikan dengan benar

## 📝 Kredit

- [Font Awesome](https://fontawesome.com/) untuk ikon (v6.4.0)
- [TailwindCSS](https://tailwindcss.com/) untuk styling
- Google Fonts: [Poppins](https://fonts.google.com/specimen/Poppins) & [Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Unsplash](https://unsplash.com/) untuk gambar sampel
