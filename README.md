# **StuntFree \- Landing Page Edukasi Stunting**

Ini adalah *submission* untuk Lomba Desain Frontend, berupa *landing page* edukasi interaktif tentang stunting. Proyek ini dibangun dengan fokus pada desain yang responsif, visual yang "meriah" (penuh animasi), dan interaktivitas tinggi untuk memberikan pengalaman pengguna yang tak terlupakan.

Semua *resource* (CSS/JS) dimuat menggunakan CDN dan seluruh proyek dibundel dalam satu file index.html untuk portabilitas.

## **✨ Fitur Utama**

Proyek ini tidak hanya statis, tetapi hidup dengan berbagai animasi dan interaksi:

* **Desain Responsif Penuh:** Dibangun dengan pendekatan *mobile-first* menggunakan Tailwind CSS, memastikan tampilan sempurna di semua perangkat, dari ponsel hingga desktop.  
* **Animasi "Meriah" (AOS):** Setiap elemen *section* memiliki animasi *fade-up*, *zoom-in*, atau *slide* saat di-*scroll* menggunakan *library* Animate on Scroll (AOS).  
* **Latar Belakang Gradien Animasi:** *Section* "Statistik" dan "CTA" memiliki latar belakang gradien animasi yang "rich" dan bergerak dinamis untuk menarik perhatian.  
* **Statistik Interaktif (CountUp.js):** Angka pada *section* "Fakta Kunci" beranimasi menghitung naik saat terlihat di layar.  
* **Kartu Statistik "Glassmorphism":** Kartu di *section* statistik menggunakan efek transparan (bg-white/10) dan *backdrop-blur* untuk menciptakan tampilan "kaca" yang mewah di atas gradien animasi.  
* **Slider Mitos vs Fakta (Swiper.js):** Konten Mitos vs Fakta disajikan dalam *carousel* interaktif yang dapat digeser (swipe).  
* **Kartu Solusi Interaktif (CSS Hover):** Tiga kartu solusi di *section* "Teknologi" menggunakan efek *hover* CSS murni untuk menampilkan deskripsi dengan animasi geser yang halus.  
* **Navigasi Cerdas:**  
  * *Header* "mengecil" (shrink) saat halaman di-*scroll* ke bawah.  
  * Menu *mobile* (hamburger) berfungsi penuh dengan animasi *dropdown* yang halus.  
  * Tombol "Back to Top" muncul saat pengguna meng-*scroll* jauh ke bawah.  
* **Animasi Hero:** Gambar ilustrasi di *hero section* memiliki animasi "float" (naik-turun) yang halus.

## **🛠️ Tumpukan Teknologi (Semua via CDN)**

* **HTML5**  
* **Tailwind CSS** (via CDN)  
* **JavaScript (ES6+)** (untuk fungsionalitas menu, header, dan *scroll*)  
* **AOS.js (Animate on Scroll)** (via CDN)  
* **Swiper.js** (via CDN, untuk *carousel*)  
* **CountUp.js** (via CDN, untuk statistik)  
* **Font Awesome** (via CDN, untuk ikon)  
* **Google Fonts (Inter)**

## **🚀 Cara Menjalankan**

Tidak ada proses instalasi atau *build* yang diperlukan.

1. Pastikan Anda memiliki koneksi internet (untuk memuat *resource* CDN).  
2. Cukup buka *file* index.html di *browser* modern apa pun (Chrome, Firefox, Safari, Edge).

## **📂 Struktur File**

Proyek ini sengaja dibuat dalam **satu file tunggal** untuk memenuhi kriteria portabilitas.

./  
└── index.html

Seluruh CSS kustom (termasuk animasi gradien dan kartu) dan JavaScript kustom (termasuk logika menu dan *smooth scroll*) berada di dalam *file* index.html.

## **📄 Lisensi**

Proyek ini dilisensikan di bawah Lisensi MIT.