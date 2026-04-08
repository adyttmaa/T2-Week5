Kode ini menggunakan bantuan framework bootstrap untuk membantu mempermudah dalam merancang
design web dengan css dan fungsi interaktif agar web lebih responsif dengan js yang sudah 
tersedia pada framework bootstrap tersebut

Penggunaan external css sudah diterapkan, dimana terdapat file style.css yang diletakkan berbeda dengan 
atau dipisah dari file html.

Implementasi box model, untuk mengatur foto profile menggunakan border border: 5px solid white; untuk
memberikan bingkai visual. Padding digunakan untuk memberi ruang atau jarak di antara konten elemen, contoh padding-top: 80px untuk elemen #home.hero padding ini digunakan untuk mencegah agar konten "Halo, Saya Adiyatma Putra" tidak tertutup atau terpotong oleh navbar saat halaman pertama kali dimuat. Margin, penggunaan mb-4 dan ms-auto pada elemen-elemen Bootstrap mengatur jarak antar komponen agar tidak saling menempel.

Flexbox, bagian Hero (#home.hero) dan Section menggunakan display: flex dan align-items: center untuk memastikan teks dan gambar sejajar secara vertikal di tengah. Bootstrap Grid, struktur tata letak utama menggunakan sistem Grid Bootstrap (row dan col-lg-*) yang berbasis Flexbox untuk membagi kolom secara proporsional.

Menggunakan 5 kelas berbeda 
.nav-link:hover (Navigasi).

.project-card (Kartu Proyek bagian karya&proyek).

.profile-pic (Foto Profil).

.social-icon-dark (Ikon yang berda pada Footer).

.hero (Bagian Utama).

Memiliki Navbar, Hero Section, Content, dan Footer
Navbar: Navigasi gelap (bg-dark) dengan fitur sticky-top.

Hero Section: Bagian perkenalan dengan judul besar, deskripsi, dan foto profil.

Content: Terdiri dari bagian "Tentang Saya" dan galeri "Karya & Proyek Saya".

Footer: Penutup berwarna hitam yang berisi informasi dan tautan sosial media.

