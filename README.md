# 🌙 Ramadhan Space 2026 - Portal Ibadah Digital

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://ramadan-c6-ra-ma-dan-portal.vercel.app/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

**Ramadhan Space** adalah portal ibadah digital modern yang dirancang untuk menemani perjalanan spiritual umat Muslim selama bulan suci Ramadhan 1447 H / 2026 M. Platform ini menyediakan berbagai fitur terlengkap dalam satu halaman, mulai dari jadwal imsakiyah real-time, kumpulan doa, penghitung zikir, kalkulator zakat, hingga artikel islami inspiratif.

Dibangun dengan pendekatan *mobile-first* dan desain antarmuka yang estetis, Ramadhan Space bertujuan membuat ibadah menjadi lebih terorganisir, konsisten, dan khusyuk.

---

## ✨ Fitur Utama

### Dashboard & Navigasi
- **Desain Responsif:** Tampilan optimal di Desktop, Tablet, dan Mobile.
- **Dark Mode:** Mode gelap yang nyaman untuk ibadah malam (Tarawih & Sahur).
- **Navigasi Intuitif:** Menu sidebar dan navbar yang mudah diakses.

###  Jadwal Imsakiyah
- Jadwal sholat dan imsak otomatis berdasarkan lokasi.
- Countdown menuju waktu sholat berikutnya.
- Indikator hari keberapa puasa saat ini.

### Fitur Ibadah
- **Kumpulan Doa:** Doa sahur, buka puasa, dan doa harian lengkap dengan Arab, Latin, dan Arti.
- **Digital Tasbih (Zikir):** Penghitung zikir interaktif dengan target harian.
- **Kalkulator Zakat:** Menghitung zakat fitrah dan zakat maal secara otomatis sesuai nisab.
- **Ibadah Tracker mencatat ibadah harian anda untuk memantau progress

### Konten & Edukasi
- **Artikel Islami:** Artikel tentang keutamaan Ramadhan, tips kesehatan saat puasa, dan kisah teladan sahabat.
- **Tips Kesehatan:** Panduan menjaga stamina tubuh selama berpuasa.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan teknologi web standar yang ringan dan cepat:

- **HTML5:** Struktur semantik untuk SEO yang baik.
- **CSS3:** Styling custom dengan variabel CSS, Flexbox, Grid, dan animasi halus.
- **JavaScript (Vanilla):** Logika interaktif untuk countdown, dark mode, kalkulator, dan penyimpanan lokal (LocalStorage).
- **Font Awesome & Bootstrap Icons:** Ikon vektor untuk elemen visual.
- **Google Fonts:** Tipografi modern (Poppins & Amiri).
- **Vercel:** Platform hosting untuk deployment yang cepat dan stabil.

---


### 2. Buka File
Anda tidak perlu menginstall server khusus. Cukup buka file `index.html` langsung di browser Anda (Chrome, Firefox, Edge, dll).

Atau jika menggunakan VS Code, gunakan ekstensi **Live Server**:
1. Klik kanan pada `index.html`.
2. Pilih "Open with Live Server".

### 3. Struktur Folder
```text
ramadhan-space/
├── assets/             # Gambar dan ikon
├── css/                # File stylesheet (jika dipisah)
├── js/                 # File script (jika dipisah)
├── page/               # File script (jika dipisah)
    └──jadwal.html      # Halaman jadwal imsakiyah
    └──doa.html         # Halaman kumpulan doa
    └──zikir.html       # Halaman penghitung zikir
    └──kalkulator-zakat.html # Halaman kalkulator
    └── artikel.html     # Halaman daftar artikel
    └── artikel-detail/  #  daftar halaman artikel
├── index.html       # Halaman utama
└── README.md        # Dokumentasi proyek
```

---

## 🎨 Desain & UI/UX

Proyek ini mengutamakan pengalaman pengguna yang tenang dan fokus:
- **Palet Warna:** Dominasi hijau emerald (`#10b981`) dan emas (`#f59e0b`) yang melambangkan ketenangan dan kemuliaan Ramadhan.
- **Animasi:** Efek *hover* halus, animasi floating pada kartu, dan transisi warna saat ganti tema.
- **Aksesibilitas:** Kontras warna yang terjaga dan ukuran font yang mudah dibaca.


##  Penulis

Dikembangkan dengan ❤️ oleh:

**Reni Kartika Suwandi**
- Instagram: [@xyzhunnn_](https://www.instagram.com/xyzhunnn_/)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah lisensi **MIT**. Silakan digunakan untuk tujuan pembelajaran atau pengembangan pribadi.

---

## 🙏 Dukungan

Jika proyek ini bermanfaat bagi Anda, silakan berikan ⭐ **Star** pada repository ini untuk mendukung pengembangan selanjutnya!

> *"Semoga ibadah Ramadhan kita tahun ini diterima oleh Allah SWT dan menjadi Ramadhan terbaik dalam hidup kita."*
```

### Tips Tambahan untuk Anda:
1.  **Screenshot:** Ambil tangkapan layar website Anda (tampilan desktop dan mobile), simpan di folder `assets`, lalu update bagian `![Light Mode]...` di atas dengan nama file gambar yang benar.
2.  **Link GitHub:** Ganti `https://github.com/username-anda/ramadhan-space.git` dengan link repository GitHub asli Anda jika sudah ada.
3.  **Deploy:** Karena Anda sudah memiliki link Vercel, pastikan setiap kali ada perubahan kode, Anda melakukan *push* ke GitHub agar Vercel melakukan update otomatis (jika terhubung).
