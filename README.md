# 🌐 Personal Portfolio — Putri Alya

Website portofolio pribadi yang dirancang untuk menampilkan profil, keahlian, proyek, latar belakang pendidikan, serta informasi kontak secara sederhana dan profesional.

Website ini dikembangkan menggunakan **HTML5, CSS3, dan Bootstrap 5** sebagai bagian dari penugasan mata kuliah **Workshop Web Desain**.

Desain website mengadaptasi konsep **Clean, Warm, dan Modern** dengan mempertahankan palet warna *earthy tones* dari project sebelumnya, seperti Cream, Caramel, Coffee, dan Brown.

## 📌 Deskripsi

Website ini merupakan pengembangan dari website profil dan portofolio yang telah dibuat pada tugas sebelumnya.

Pada versi ini, struktur halaman dikembangkan menggunakan **Bootstrap 5** untuk membantu membangun layout yang responsif serta menyediakan berbagai komponen antarmuka.

Selain Bootstrap, website juga menggunakan **CSS custom** untuk mempertahankan identitas visual serta menerapkan berbagai efek seperti *rounded corners*, *gradients*, *shadow effects*, dan *2D transforms*.

Website ini juga dirancang agar dapat digunakan sebagai personal portfolio yang dapat ditampilkan melalui berbagai platform seperti GitHub, LinkedIn, maupun media sosial.

## 🎯 Tujuan

Project ini dibuat untuk memenuhi tugas praktikum mata kuliah **Workshop Web Desain** dengan kriteria utama:

* Menggunakan minimal 5 komponen Bootstrap.
* Menerapkan CSS Rounded Corners pada elemen website.
* Menerapkan CSS Gradients pada background dan button.
* Menerapkan CSS Shadow Effects pada card dan gambar.
* Menerapkan CSS 2D Transforms pada elemen saat hover.
* Menerapkan Tooltip menggunakan Bootstrap.
* Menerapkan CSS Box Sizing untuk mengatur ukuran elemen.
* Membuat tampilan website yang responsif pada perangkat desktop maupun mobile.

## 🛠️ Teknologi yang Digunakan

* **HTML5** — digunakan untuk membangun struktur dan konten halaman website.

* **CSS3** — digunakan untuk styling custom, variabel warna, rounded corners, gradients, shadow effects, hover effects, 2D transforms, box sizing, serta responsive design.

* **Bootstrap 5** — digunakan untuk membangun komponen antarmuka dan layout responsif, termasuk Navbar, Grid, Card, Button, Badge, dan Tooltip.

* **Google Fonts** — menggunakan font `Inter` dan `Poppins` untuk memberikan tampilan tipografi yang modern dan konsisten.

## 📂 Struktur Project

```text
Personal-Portfolio/

├── .gitignore
├── index.html
├── LICENSE
├── README.md
├── style.css
└── assets/
    ├── Logo.png
    ├── my-photo.JPG
    └── Putri_Alya-CV.pdf
```

## ✨ Fitur & Komponen

### 🧭 Navbar

Navbar responsif yang digunakan sebagai navigasi utama menuju beberapa bagian website seperti Tentang, Keahlian, Proyek, Pendidikan, dan Kontak.

Navbar memanfaatkan komponen **Bootstrap Navbar** dan dapat menyesuaikan tampilan pada perangkat dengan ukuran layar yang berbeda.

### 👤 Profil & About

Bagian profil menampilkan foto, nama, status pendidikan, serta deskripsi singkat mengenai latar belakang dan ketertarikan pada bidang teknologi.

Informasi biodata juga ditampilkan dalam bentuk **Bootstrap Card** agar lebih terstruktur.

### 💻 Keahlian

Bagian keahlian menampilkan beberapa teknologi yang pernah dipelajari, seperti:

* HTML
* CSS
* PHP
* Laravel
* Git
* JavaScript

Setiap keahlian ditampilkan menggunakan **Bootstrap Grid** dan **Card**.

### 📁 Proyek

Bagian proyek digunakan untuk menampilkan beberapa project yang pernah dibuat atau dikembangkan selama proses pembelajaran.

Project ditampilkan menggunakan **Bootstrap Card** dengan efek *shadow*, *rounded corners*, serta transform ketika elemen disentuh oleh pointer.

### 🎓 Pendidikan

Bagian pendidikan menampilkan latar belakang pendidikan, mulai dari SMK Rekayasa Perangkat Lunak hingga pendidikan D3 Teknik Informatika.

### 📄 Curriculum Vitae

CV dapat diakses melalui tombol **Lihat CV** pada bagian hero dan dibuka dalam halaman/tab baru menggunakan file PDF yang tersedia di folder `assets`.

### 🔗 Kontak & Media Sosial

Bagian kontak menyediakan akses menuju beberapa platform seperti:

* GitHub
* LinkedIn
* Instagram

Tombol sosial juga dilengkapi dengan **Bootstrap Tooltip** yang memberikan informasi ketika pointer diarahkan ke tombol.

### 🎨 CSS Visual Effects

Website menerapkan beberapa efek CSS sebagai bagian dari penugasan, yaitu:

* **Rounded Corners** menggunakan `border-radius`.
* **CSS Gradient** menggunakan `linear-gradient()`.
* **Shadow Effects** menggunakan `box-shadow`.
* **2D Transform** menggunakan `scale()` dan `translateY()`.
* **Hover Transition** menggunakan `transition`.
* **Box Sizing** menggunakan `box-sizing: border-box`.

### 📱 Responsive Design

Layout website menggunakan sistem **Bootstrap Grid** serta CSS media queries sehingga tampilan dapat menyesuaikan ukuran layar desktop, tablet, maupun mobile.

## 🖥️ Cara Menjalankan

1. Clone repository ini ke komputer:

```bash
git clone <URL_REPOSITORY>
```;

2. Masuk ke folder project:

```bash
cd Personal-Portfolio
```;

3. Buka file `index.html` menggunakan browser.

Website dapat dijalankan secara langsung tanpa server karena menggunakan HTML, CSS, dan Bootstrap melalui CDN.

## 👤 Pembuat

**Putri Alya**

Mahasiswi D3 Teknik Informatika

Project ini dibuat untuk keperluan akademik pada mata kuliah **Workshop Web Desain** sekaligus dikembangkan sebagai personal portfolio.

---

> 📚 *Academic project & personal portfolio — Workshop Web Desain*
