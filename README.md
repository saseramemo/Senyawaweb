# Senyawaweb 🌐

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-success?logo=github)](https://github.com/saseramemo/Senyawaweb)
[![HTML5](https://img.shields.io/badge/Tech-HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/Tech-CSS3-1572B6?logo=css3&logoColor=white)](#)

Repositori ini berisi kode sumber untuk situs web resmi **Senyawa Enthusiastic**. Dibangun menggunakan fondasi HTML dan CSS statis untuk memastikan performa yang ringan, akses yang cepat, serta kemudahan dalam pemeliharaan konten komunitas.

## 📂 Struktur Direktori & Navigasi

Situs ini terdiri dari beberapa halaman utama yang dirancang untuk memfasilitasi berbagai aktivitas dan karya komunitas:

```text
Senyawaweb/
├── assets/             # Penyimpanan aset gambar, ikon, dan berkas media
├── 404.html            # Halaman penanganan galat (Page Not Found)
├── CNAME               # Konfigurasi Custom Domain untuk GitHub Pages
├── fanart.html         # Galeri pameran karya seni / Fanart komunitas
├── index.html          # Beranda / Halaman Utama portal
├── ocditerima.html     # Arsip dan basis data Original Character (OC) yang tervalidasi
├── project.html        # Etalase portofolio dan rilis proyek komunitas
├── store.html          # Halaman toko, penawaran merchandise, atau jalur donasi
└── style.css           # Pengaturan gaya visual dan tata letak (CSS utama)
```

## ✨ Fitur Utama
 * **Kinerja Optimal**: Menggunakan *native* HTML5 dan CSS3 tanpa ketergantungan *framework* berat, menghasilkan waktu muat (*loading*) yang sangat instan.
 * **Pusat Informasi Terintegrasi**: Menggabungkan rilis proyek, apresiasi kreator (*fanart*), dan validasi karakter (*OC*) ke dalam satu portal terpusat.
 * **Dukungan Custom Error Page**: Dilengkapi halaman 404.html mandiri agar navigasi pengguna tetap terjaga saat terjadi kesalahan tautan.
## 🚀 Pemasangan & Pengembangan Lokal
Untuk menjalankan atau memodifikasi situs ini di komputer lokal, ikuti langkah-langkah berikut:
 1. **Kloning Repositori**
   ```bash
   git clone [https://github.com/saseramemo/Senyawaweb.git](https://github.com/saseramemo/Senyawaweb.git)
   cd Senyawaweb
   
   ```
 2. **Menjalankan Situs**
   Karena berbasis statis, kamu bisa langsung membuka berkas index.html menggunakan peramban web (*browser*). Untuk pengalaman pengembangan yang lebih baik (mendukung *hot-reload*), disarankan menggunakan ekstensi **Live Server** di Visual Studio Code.
 3. **Modifikasi Konten**
   * Tambahkan atau perbarui gambar/media di dalam folder assets/.
   * Sesuaikan tata letak dan palet warna di style.css.
   * Edit struktur konten langsung pada berkas .html yang relevan.
     
## 📦 Deployment
Situs ini di-host secara otomatis menggunakan **GitHub Pages**. Setiap kali ada *commit* atau *push* baru ke *branch* main, perubahan akan langsung diterapkan ke situs *live* sesuai dengan alamat domain yang terdaftar pada berkas CNAME.
## 🤝 Kontribusi
Bagi pengurus atau pengembang yang ingin memperbarui halaman:
 1. Pastikan selalu melakukan *pull* mandiri dari *branch* main sebelum mengedit berkas.
 2. Jaga konsistensi penamaan kelas (*class naming*) pada berkas HTML agar sejalan dengan kaidah yang sudah ada di style.css.
 3. Kompresi ukuran gambar sebelum dimasukkan ke folder assets/ agar beban pemuatan web tetap ringan.
**Senyawa Enthusiastic** — *Membangun ekosistem kreatif yang solid dan antusias.*


### Analisis Struktur Berkas
 * **index.html**: Halaman utama (beranda) yang menjadi pintu masuk informasi komunitas.
 * **project.html**: Halaman khusus untuk menampilkan portofolio atau daftar proyek yang sedang/telah dikembangkan.
 * **fanart.html**: Galeri apresiasi untuk menampilkan karya seni (*fanart*) dari anggota komunitas maupun pendukung.
 * **ocditerima.html**: Halaman pencatatan/arsip khusus untuk daftar *Original Character* (OC) yang telah divalidasi atau diterima dalam semesta/kegiatan komunitas.
 * **store.html**: Akses menuju etalase toko, layanan komisi, atau jalur dukungan/donasi resmi.
 * **404.html**: Halaman galat kustom agar pengunjung tetap mendapatkan navigasi yang seragam saat mengakses tautan yang tidak ditemukan.
 * **style.css**: Berkas *stylesheet* utama yang mengontrol tata letak dan antarmuka visual seluruh halaman.
 * **CNAME**: Berkas penentu *custom domain* agar perutean domain utama mengarah tepat ke GitHub Pages repositori ini.
 * **assets/**: Direktori penyimpanan sumber daya visual seperti logo, gambar proyek, ikon, dan karya seni.

### 💡 Tips Tambahan untuk Repositori
1. **Optimasi Aset**: Mengingat adanya halaman berbasis visual yang padat seperti `fanart.html` dan `ocditerima.html`, pastikan gambar yang diunggah ke folder `assets/` dikonversi ke format web modern (seperti `.webp` atau `.avif`) untuk menghemat *bandwidth*.
2. **Pengujian Responsivitas**: Pastikan berkas `style.css` telah mengimplementasikan *media queries* (`@media`) dengan baik agar navigasi dari proyek, detail OC, hingga tautan *store* tetap nyaman diakses lewat perangkat seluler.
