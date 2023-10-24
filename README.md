Laporan Tugas Pemrograman Web SRS 

Disusun oleh:

  1. Albiona Qhalbu Shouki       : 22091397076
  2. Ageng Kurniawan             : 22091387077
  3. Danar Adrian Ridho Nugroho  : 22091397087

Program Studi D4 Manajemen Informatika Fakultas Vokasi Universitas Negeri Surabaya 2023

1. Tujuan

    Dokumen ini bertujuan untuk menyediakan spesifikasi persyaratan perangkat lunak yang lebih
rinci untuk pembuatan website profil perusahaan “Smart Parking System”. Website ini bertujuan
untuk secara profesional dan mendalam memperkenalkan perusahaan kepada publik, melalui
informasi tentang visi, misi, produk, dan layanan. Dokumen ini akan menjadi panduan bagi tim
pengembangan dalam merancang dan mengimplementasikan situs web.
   
2. Lampiran
   
   A. Flowchart

   ![Flowchart (1)](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/ac99ad84-5d38-4488-9cc7-6567f0ee9ac9)
   
   - Start: Ini adalah titik awal dari navigasi di website profil perusahaan. Ketika pengguna pertama kali mengakses website, mereka akan memulai dari sini.
   
   - Halaman Utama: Setelah pengguna memulai dari "Start," mereka akan diarahkan ke halaman utama atau homepage perusahaan. Halaman utama biasanya berisi informasi ringkas tentang perusahaan dan tautan menu ke bagian-bagian lain dari website.
   
   - Tentang Perusahaan: Pengguna memiliki opsi untuk mengklik tautan "Tentang Kami" di halaman utama, yang akan membawa mereka ke halaman yang memberikan rincian tentang perusahaan, sejarah, dan nilai-nilai.
   
   - Produk/Layanan: Pengguna juga dapat memilih untuk mengeksplorasi produk atau layanan yang ditawarkan oleh perusahaan. Ini mungkin mencakup deskripsi produk, spesifikasi, dan lainnya.
   
   - Sign In: Selain itu, jika pengguna ingin masuk ke akun mereka atau mengakses area yang memerlukan otentikasi, mereka dapat memilih "Sign In."
   
   - Kontak: Pengguna dapat mencari informasi kontak perusahaan, seperti alamat, nomor telepon, atau formulir kontak di halaman "Kontak."
   
   - Media Sosial: Jika perusahaan aktif di media sosial, pengguna dapat mengeklik tautan ke halaman media sosial perusahaan di mana mereka dapat mengikuti atau berinteraksi dengan perusahaan di platform tersebut.
   
   - End: Flowchart diakhiri dengan "End," yang menunjukkan akhir dari navigasi pengguna. Pengguna dapat kembali ke halaman utama atau keluar dari website.   

   B. UseCase Diagram

   ![Use Case](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/5ad985df-b6b7-439c-843a-756b407349e8)

  1. View Homepage (Melihat Halaman Depan):

      • Aktor Utama: Pengguna customer.
     
      • Deskripsi: Pengguna mengunjungi situs web dan melihat halaman depan (homepage) untuk mendapatkan informasi umum tentang bisnis atau layanan
yang ditawarkan.

      • Langkah-langkah:
     
         1) Pengguna membuka peramban web.
     
         2) Pengguna memasukkan URL situs web.
     
         3) Halaman depan situs web dimuat.
     
         4) Pengguna melihat konten halaman depan, seperti gambar, teks, dan mungkin tautan ke halaman lain.

2. View About Us (Melihat Halaman Tentang Kami):

     • Aktor Utama: Pengguna customer.
   
     • Deskripsi: Pengguna tertarik untuk memahami lebih lanjut tentang perusahaan atau
individu yang berdiri di balik situs web tersebut.

     • Langkah-langkah:
   
        1) Dari halaman depan, pengguna menemukan tautan "About Us" atau
sejenisnya.

        2) Pengguna mengklik tautan "About Us."
        
        3) Halaman "About Us" dimuat.
        
        4) Pengguna membaca informasi tentang perusahaan atau individu tersebut.\
        
3. View Contact Us (Melihat Halaman Kontak Kami)

     • Aktor Utama: Pengguna customer.

     • Deskripsi: Pengguna ingin menghubungi perusahaan atau individu yang terkait dengan situs web tersebut.

     • Langkah-langkah:
      
        1) Dari halaman depan atau halaman "About Us," pengguna menemukan tautan "Contact Us" atau sejenisnya.
      
        2) Pengguna mengklik tautan "Contact Us."
      
        3) Halaman "Contact Us" dimuat.
      
        4) Pengguna melihat informasi kontak, seperti alamat email, nomor telepon, atau formulir kontak.

4. Register (Mendaftar):\
   
     • Aktor Utama: Pengguna customer.

     • Deskripsi: Pengguna ingin mendaftar atau membuat akun di situs web tersebut untuk mengakses fitur atau layanan tambahan.

     • Langkah-langkah:
    
        1) Dari halaman depan atau dari tautan khusus "Register" di menu, pengguna memilih opsi "Register" atau "Sign Up."
      
        2) Pengguna diarahkan ke halaman pendaftaran.
      
        3) Pengguna mengisi formulir pendaftaran dengan informasi yang diperlukan, seperti nama, alamat email, kata sandi, dan data pribadi lainnya.
      
        4) Pengguna mengklik tombol "Submit" atau sejenisnya untuk menyelesaikan pendaftaran.

5. Login (Masuk):

     • Aktor Utama: Pengguna admin.

     • Deskripsi: Pengguna admin perlu masuk ke akun admin mereka untuk mengakses kontrol dan fitur administratif di situs web.

     • Langkah-langkah:
      
        1) Pengguna admin membuka halaman login di situs web.
      
        2) Pengguna admin memasukkan nama pengguna (username) dan kata sandi (password) mereka.
      
        3) Sistem memverifikasi informasi login.
      
        4) Jika informasi login valid, pengguna admin diizinkan untuk mengakses akun admin mereka.
      
6. View Customer on the Web (Melihat Data Customer di Situs Web):

     • Aktor Utama: Pengguna admin.

     • Deskripsi: Pengguna admin ingin melihat data dan informasi terkait dengan pengguna customer yang terdaftar di situs web.

     • Langkah-langkah:
    
        1) Setelah masuk, pengguna admin mengakses panel administratif.
      
        2) Pengguna admin memilih opsi "View Customers" atau "Lihat Data Customer."
      
        3) Sistem menampilkan daftar pengguna customer yang terdaftar beserta detailnya, seperti nama, alamat email, informasi kontak, dan riwayat transaksi.

7. Edit Web (Mengedit Situs Web):

     • Aktor Utama: Pengguna admin.

     • Deskripsi: Pengguna admin bertanggung jawab untuk mengedit konten dan pengaturan situs web, seperti mengubah teks, gambar, atau konfigurasi situs.

     • Langkah-langkah:
      
        1) Setelah masuk, pengguna admin mengakses panel administratif.
      
        2) Pengguna admin memilih opsi "Edit Website" atau "Edit Konten" atau sejenisnya.
      
        3) Pengguna admin dapat mengganti teks, gambar, atau mengkonfigurasi berbagai aspek situs web, seperti tampilan, tema, dan pengaturan lainnya.
      
        4) Pengguna admin menyimpan perubahan yang telah dibuat.

8. Logout (Keluar):

     • Aktor Utama: Pengguna admin.

     • Deskripsi: Pengguna admin ingin keluar dari akun admin mereka untuk menjaga keamanan dan privasi informasi di situs web.

     • Langkah-langkah:
      
        1) Pengguna admin yang telah selesai melakukan tugas administratif memilih opsi "Logout" atau "Keluar" di panel administratif atau pada halaman akun mereka.
      
        2) Sistem mengakhiri sesi login pengguna admin dan mengarahkannya kembali ke halaman login atau halaman depan situs web
   
4. Penjelasan Code
   
   A. HTML

index.html
     ![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/fb7bfa1e-b126-4006-9137-b20bbd0ff511)

    ![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/df2e6b40-4223-49cb-a544-497d7b962b7a)

 ![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/dffc7a5a-b8dd-47f0-9305-a4f87798db7e)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/549391ef-9ce1-43ce-bc37-28373ca11074)

1.	<!DOCTYPE html>: Deklarasi tipe dokumen (DTD) yang menunjukkan bahwa halaman ini adalah dokumen HTML. Ini digunakan untuk menginformasikan browser bahwa halaman ini mengikuti standar HTML5.

2.	<html lang="id">: Elemen ini mendefinisikan awal dari dokumen HTML. Atribut lang="id" menandakan bahwa bahasa yang digunakan dalam halaman ini adalah bahasa Indonesia.

3.	<head>: Elemen kepala dokumen HTML yang berisi informasi-informasi meta dan pengaturan yang tidak ditampilkan kepada pengguna. Ini termasuk pengaturan karakter, pengkodean, judul halaman, dan file eksternal yang digunakan.

4.	<meta charset="UTF-8">: Elemen ini mendefinisikan pengkodean karakter UTF-8 untuk halaman. Ini digunakan untuk mendukung karakter internasional dalam halaman web.

5.	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Elemen <meta> ini digunakan untuk mengatur tampilan halaman pada perangkat seluler. Ini memastikan bahwa lebar halaman sesuai dengan lebar perangkat dan faktor skala awalnya diatur ke 1.0.

6.	<title>Smart Parking System</title>: Elemen ini mendefinisikan judul halaman web yang akan ditampilkan di tab atau jendela browser. Judul ini akan membantu pengguna mengidentifikasi konten halaman.

7.	<link rel="stylesheet" type="text/css" href="model.css">: Elemen <link> ini digunakan untuk memuat file stylesheet eksternal "model.css" yang digunakan untuk mengatur tampilan halaman dengan mengaplikasikan gaya dan tata letak.

8.	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">: Elemen <link> ini memuat stylesheet eksternal dari Font Awesome, yang memberikan akses ke ikon-ikon kustom yang dapat digunakan dalam halaman web.

9.	<body>: Elemen ini merupakan area utama di mana konten halaman web ditampilkan. Semua elemen yang terlihat oleh pengguna, seperti teks, gambar, dan tautan, ditempatkan di dalam elemen <body>.

10.	<header>: Elemen ini digunakan untuk menyusun bagian kepala halaman, yang biasanya berisi elemen-elemen seperti logo, menu navigasi, dan judul halaman.

11.	<nav>: Elemen ini digunakan untuk membuat bagian navigasi halaman web. Biasanya berisi tautan menu ke halaman-halaman terkait.

12.	<section class="about-us">: Elemen ini menandai awal dari bagian "Tentang Kami" di halaman. Ini digunakan untuk mengelompokkan konten yang berkaitan dengan informasi tentang produk atau layanan yang ditawarkan.

13.	<a>: Elemen ini digunakan untuk membuat tautan ke halaman lain. Pada contoh ini, digunakan untuk menghubungkan gambar ke file "Gambar 6.jpg"".

14.	"<img src="Gambar 6.jpg" alt="gambar 6>": Elemen ini digunakan untuk menampilkan gambar di halaman web. Atribut src menentukan sumber gambar, sementara atribut alt memberikan teks alternatif jika gambar tidak dapat dimuat.

15.	"<h1>Transformasi Parkir dengan Teknologi Canggih</h1>": Elemen ini digunakan untuk menampilkan judul besar yang menyoroti topik "Tentang Kami" di halaman.

16.	"<p>": Elemen ini digunakan untuk menampilkan paragraf teks. Digunakan untuk menjelaskan informasi tentang produk "Smart Parking System."

17.	"<div class="team">": Elemen ini digunakan untuk mengelompokkan konten tentang "Tim Kami" yang termasuk h1, dan elemen-elemen lainnya.

18.	"<ul>": Elemen ini digunakan untuk membuat daftar yang berisi informasi tentang anggota tim, termasuk gambar dan teks terkait.

19.	"<footer>": Elemen ini digunakan untuk membuat bagian bawah halaman web yang biasanya berisi informasi kontak dan tautan ke media sosial.

20.	"<i class="fab fa-facebook-f icon"></i>": Elemen ini digunakan untuk menampilkan ikon media sosial dari Font Awesome.

21.	"<form>": Elemen ini digunakan untuk membuat formulir yang pengguna dapat gunakan untuk berlangganan newsletter.

22.	"<script src="script.js"></script>": Elemen ini memuat script JavaScript eksternal yang digunakan untuk meningkatkan fungsionalitas halaman web.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/85dbf500-9968-4358-bfe1-86cf6204814c)
Service.html

1.  "<section class="services">": Ini adalah elemen HTML yang mendefinisikan sebuah bagian dari halaman web dengan kelas "services." Bagian ini tampaknya didedikasikan untuk menampilkan berbagai layanan yang ditawarkan oleh Smart Parking System.

2.  "<h1+>/*Services<///**/h1>": Ini adalah judul bagian "Services.+" Biasanya digunakan untuk memberikan judul atau pengenalan singkat tentang isi bagian tersebut.

3.  "<ul>": Ini adalah elemen yang digunakan untuk membuat daftar tak terurut, yang akan berisi berbagai layanan Smart Parking System.

Item Layanan Pertama:

4.  "<li>": Ini adalah elemen daftar dalam daftar tak terurut.

5.  "<a target="_blank" href="Gambar 2.jpg*">": Ini adalah tautan ke gambar (Gambar 2.*) yang membuka gambar dalam tab atau jendela baru (target="_blank").
   Biasanya, gambar ini digunakan untuk menggambarkan layanan tersebut.

6.  "<h1+>Solusi Parkir Cerdas</*+h1>": Ini adalah judul layanan pertama, yaitu "+Solusi Parkir Cerdas."

7.  "<p>"Solusi Parkir Cerdas kami/...: Ini adalah paragraf atau deskripsi singkat dari layanan "Solusi Parkir Cerdas." Ini memberikan gambaran umum tentang layanan ini.

8.  "<button onclick="toggleText('text1', this)">Read More</button>: Ini adalah tombol "Read More" yang memicu suatu fungsi JavaScript ketika diklik. Tombol ini digunakan untuk memperluas deskripsi layanan saat diklik.

9.  "<div id="text1" class="hidden-content">": Ini adalah div yang mengandung deskripsi lebih lanjut tentang "Solusi Parkir Cerdas." Saat tombol "Read More" diklik, konten di dalam div ini akan ditampilkan. Kelas "hidden-content" mungkin digunakan untuk awalnya menyembunyikan kontennya.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/d560b011-04a5-44d8-b549-19509fc5a2d5)

1.)	<section class="about-us">: Ini adalah elemen HTML yang mendefinisikan sebuah bagian dari halaman web dengan kelas "about-us." Bagian ini tampaknya didedikasikan untuk memberikan informasi tentang perusahaan, khususnya mengenai bagaimana mereka menggunakan teknologi canggih dalam solusi parkir mereka.

2.)	<a target="_blank" href="Gambar 6.jpg">: Ini adalah tautan ke gambar (Gambar 6.jpg) yang membuka gambar dalam tab atau jendela baru (target="_blank"). Gambar ini mungkin digunakan untuk mengilustrasikan konsep teknologi canggih yang digunakan dalam solusi parkir perusahaan.

3.)	<h1>Transformasi Parkir dengan Teknologi Canggih</h1>: Ini adalah judul yang menjelaskan tentang transformasi parkir dengan teknologi canggih yang disediakan oleh perusahaan.

4.)	<p>: Ini adalah paragraf atau deskripsi yang menjelaskan penggunaan teknologi canggih dalam solusi parkir perusahaan. Ini termasuk penggunaan Internet of Things (IoT), machine learning, dan webcam dalam mengoptimalkan penggunaan tempat parkir. Deskripsi ini juga menyoroti komitmen perusahaan untuk menyediakan solusi parkir inovatif yang menyederhanakan kehidupan masyarakat.
Bagian Kedua - Tim Perusahaan:

1.)	<section>: Ini adalah elemen HTML yang menandakan sebuah bagian selanjutnya dari halaman web. Bagian ini tampaknya didedikasikan untuk memperkenalkan tim perusahaan.

2.)	<div class="team">: Ini adalah div yang berisi informasi tentang tim perusahaan.

3.)	<div class="garis-kiri"> dan <div class="garis-kanan">: Ini adalah elemen div yang digunakan untuk membuat garis horizontal di sebelah kiri dan kanan judul "Tim Kami."

4.)	<h1>Tim Kami</h1>: Ini adalah judul yang menjelaskan bahwa bagian ini adalah tentang tim perusahaan.

5.)	<div class="foto-team">: Ini adalah div yang berisi informasi dan gambar anggota tim perusahaan.

6.)	<ul>: Ini adalah elemen yang digunakan untuk membuat daftar tak terurut yang akan berisi informasi tentang anggota tim.

7.)	Setiap anggota tim direpresentasikan oleh elemen <li>. Setiap elemen <li> termasuk gambar, nama anggota tim, dan nomor identifikasi. Ini memungkinkan pengunjung untuk mengenal lebih dekat anggota tim perusahaan.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/971ddc55-8da8-4c54-b7e3-df734c5cb63f)

Rating: Di bagian ini, terdapat informasi rating atau penilaian produk atau layanan. Detailnya mencakup:

1.)	"<h1>Penilaian & Ulasan Client</h1>": Ini adalah judul seksi yang memberi tahu pengguna bahwa ini adalah bagian yang berisi penilaian dan ulasan dari klien.

2.)	<h2>4.8 &#9733</h2>: Ini adalah rating produk atau layanan dengan tanda bintang (dalam format desimal) yang menunjukkan rating rata-rata produk atau layanan tersebut.

3.)	<p>2,394 Rating</p>: Ini adalah jumlah total rating atau penilaian yang telah diberikan oleh klien.

4.)	<h3>4+</h3>: Ini menunjukkan jumlah rating dengan skor 4 atau lebih (yang baik).

5.)	<p>Rating 4+</p>: Ini adalah keterangan bahwa jumlah tersebut merujuk pada rating 4 atau lebih.

Ulasan Klien: Di bagian ini, setiap ulasan klien memiliki elemen-elemen berikut:

6.)	Rating: Ini menunjukkan rating dalam bentuk bintang yang merepresentasikan seberapa baik produk atau layanan tersebut dinilai oleh klien.

7.)	Pesan Ulasan: Ini adalah teks ulasan atau komentar yang diberikan oleh klien tentang produk atau layanan.

8.)	Gambar Pengguna: Ini adalah gambar profil pengguna yang memberikan ulasan.

9.)	Nama Pengguna: Ini adalah nama pengguna atau nama lengkap dari pengguna yang memberikan ulasan.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/9a6e29cc-4086-42b7-9c15-68db472e7570)

1.	<section class="login">: Ini adalah elemen yang mengelilingi seluruh area login pada halaman. Ini adalah elemen yang memberikan sebagian besar gaya dan tata letak untuk elemen-elemen yang ada dalam area login.

2.	<div class="login-box">: Ini adalah kotak yang berisi elemen-elemen login, seperti formulir masuk, teks, dan tombol.


3.	<h1>Member Login</h1>: Ini adalah judul yang menunjukkan bahwa ini adalah area untuk login anggota.

4.	<form>: Ini adalah elemen formulir yang digunakan untuk mengumpulkan informasi login dari pengguna.

1.	<label for="email">: Ini adalah label yang terkait dengan elemen input dengan id "email". Ini digunakan untuk memberi tahu pengguna apa yang harus dimasukkan di dalam input tersebut.

2.	<input type="text" id="email" name="email" required>: Ini adalah input teks yang memungkinkan pengguna memasukkan alamat email atau nama pengguna mereka. Properti "required" menunjukkan bahwa pengisian input ini adalah wajib.

3.	<label for="password">: Ini adalah label yang terkait dengan elemen input dengan id "password". Ini digunakan untuk memberi tahu pengguna apa yang harus dimasukkan di dalam input tersebut.

4.	<input type="password" id="password" name="password" required>: Ini adalah input kata sandi yang memungkinkan pengguna memasukkan kata sandi mereka. Properti "required" menunjukkan bahwa pengisian input ini adalah wajib.


5.	<div class="forget-pss">: Ini adalah div yang berisi tautan "Forget Password" yang mengarah ke halaman yang memungkinkan pengguna mengatur ulang kata sandi mereka jika mereka lupa.

6.	<button type="submit">Login</button>: Ini adalah tombol "Login" yang digunakan untuk mengirimkan formulir login.

Footer:

5.	<footer>: Ini adalah elemen footer yang berisi informasi kontak, tautan ke media sosial, dan opsi langganan newsletter.

1.	<div class="contact-info">: Ini adalah div yang berisi informasi kontak, seperti alamat, email, dan nomor telepon.

2.	<div class="social-media">: Ini adalah div yang berisi tautan ke platform media sosial, seperti Facebook, Twitter, dan Instagram.

3.	<div class="subscribe">: Ini adalah div yang berisi formulir untuk pengguna yang ingin berlangganan newsletter. Formulir ini meminta pengguna untuk memasukkan alamat email mereka dan memiliki tombol "Send" untuk mengirimkan data.

Script:

6.	<script src="script.js"></script>: Ini adalah tautan ke file JavaScript yang disebut "script.js". Ini mengindikasikan bahwa ada script yang akan dieksekusi pada halaman web ini untuk memberikan interaktivitas tambahan.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/65e54d06-6070-4b62-a577-7169dbf0611c)

Bagian Sign Up:

1.	<section class="signup">: Ini adalah elemen yang mengelilingi seluruh area pendaftaran pada halaman. Ini adalah elemen yang memberikan sebagian besar gaya dan tata letak untuk elemen-elemen yang ada dalam area pendaftaran.

2.	<div class="signup-box">: Ini adalah kotak yang berisi elemen-elemen pendaftaran, seperti formulir pendaftaran, teks, dan tombol.

3.	<h1>Member SignUp</h1>: Ini adalah judul yang menunjukkan bahwa ini adalah area untuk mendaftar sebagai anggota.

4.	<form>: Ini adalah elemen formulir yang digunakan untuk mengumpulkan informasi pendaftaran dari pengguna.

1.	<label for="fullname">: Ini adalah label yang terkait dengan elemen input dengan id "fullname." Ini digunakan untuk memberi tahu pengguna apa yang harus dimasukkan di dalam input tersebut, dalam hal ini adalah nama pengguna.

2.	<input type="text" id="fullname" name="fullname" required>: Ini adalah input teks yang memungkinkan pengguna memasukkan nama pengguna. Properti "required" menunjukkan bahwa pengisian input ini adalah wajib.

3.	<label for="email">: Ini adalah label yang terkait dengan elemen input dengan id "email." Ini digunakan untuk memberi tahu pengguna apa yang harus dimasukkan di dalam input tersebut, dalam hal ini adalah alamat email.

4.	<input type="email" id="email" name="email" required>: Ini adalah input alamat email yang memungkinkan pengguna memasukkan alamat email mereka. Properti "required" menunjukkan bahwa pengisian input ini adalah wajib.

5.	<label for="password">: Ini adalah label yang terkait dengan elemen input dengan id "password." Ini digunakan untuk memberi tahu pengguna apa yang harus dimasukkan di dalam input tersebut, dalam hal ini adalah kata sandi.

6.	<input type="password" id="password" name="password" required>: Ini adalah input kata sandi yang memungkinkan pengguna memasukkan kata sandi mereka. Properti "required" menunjukkan bahwa pengisian input ini adalah wajib.

7.	<label for="confirm_password">: Ini adalah label yang terkait dengan elemen input dengan id "confirm_password." Ini digunakan untuk meminta pengguna mengonfirmasi kata sandi yang mereka masukkan.

8.	<input type="password" id="confirm_password" name="confirm_password" required>: Ini adalah input kata sandi konfirmasi yang memungkinkan pengguna memasukkan kata sandi mereka sekali lagi. Properti "required" menunjukkan bahwa pengisian input ini juga adalah wajib.

9.	<button type="submit">SignUp</button>: Ini adalah tombol "Sign Up" yang digunakan untuk mengirimkan formulir pendaftaran.
Footer:

5.	<footer>: Ini adalah elemen footer yang berisi informasi kontak, tautan ke media sosial, dan opsi langganan newsletter. Ini memiliki struktur yang mirip dengan footer pada contoh sebelumnya.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/990e0b45-d136-41ea-bfe0-04791096b044)

Bagian Contact (Kontak):

1.)	<div class="contact-box">: Ini adalah div (kotak) yang berisi elemen-elemen kontak dan formulir kontak.

2.)	<section class="contact">: Ini adalah elemen kontak yang berisi informasi kontak dan formulir kontak.

1.	<h1>Ada pertanyaan?</h1>: Ini adalah judul yang menanyakan apakah pengunjung memiliki pertanyaan.

2.	<p>Jangan ragu untuk menelepon atau mengirim email kepada kami atau gunakan formulir kontak kami untuk menghubungi kami Kami menantikan kabar dari Anda!</p>: Ini adalah teks yang mengundang pengunjung untuk menghubungi atau menggunakan formulir kontak.

3.	<h1>Keadaan darurat? Hubungi Kami:</h1>: Ini adalah judul yang menunjukkan nomor telepon darurat.

4.	<p>Telepon: 123-456-7890</p>: Ini adalah nomor telepon kontak darurat.

5.	<h1>Kirimi Kami Surat</h1>: Ini adalah judul yang menunjukkan alamat email kontak.

6.	<p>Email: info@smartparkingsytem.com</p>: Ini adalah alamat email kontak.

3.)	<form class="message">: Ini adalah elemen formulir yang digunakan untuk mengumpulkan pesan dari pengunjung.

1.	<label>Name</label><br>: Ini adalah label yang menunjukkan bahwa input berikutnya dimaksudkan untuk memasukkan nama pengunjung.

2.	<input type="text">: Ini adalah input teks yang memungkinkan pengunjung memasukkan nama mereka.

3.	<label>Email</label><br>: Ini adalah label yang menunjukkan bahwa input berikutnya dimaksudkan untuk memasukkan alamat email pengunjung.

4.	<input type="email">: Ini adalah input alamat email yang memungkinkan pengunjung memasukkan alamat email mereka.

5.	<label>Subject</label><br>: Ini adalah label yang menunjukkan bahwa input berikutnya dimaksudkan untuk memasukkan subjek pesan.


6.	<input type="text">: Ini adalah input teks yang memungkinkan pengunjung memasukkan subjek pesan.

7.	<label>Your Message</label><br>: Ini adalah label yang menunjukkan bahwa input berikutnya dimaksudkan untuk memasukkan pesan.

8.	<textarea></textarea>: Ini adalah input area teks yang memungkinkan pengunjung memasukkan pesan mereka.

9.	<button type="submit">Send</button>: Ini adalah tombol "Send" yang digunakan untuk mengirim pesan melalui formulir.

   B. CSS

   ![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/ff687d62-5d11-4d74-8d8c-b0425ecb59fa)
   
CSS.header

•	body: Ini adalah gaya dasar untuk elemen <body>, yang mengatur font, warna teks, margin, padding, dan latar belakang halaman. Gambar latar belakang "Gambar 1.jpg" digunakan dengan efek overlay dan background-size yang disetel ke 100% dan cover.

•	header: Ini adalah gaya untuk elemen <header>, yang mengatur latar belakang warna, padding, dan teks yang akan ditampilkan dalam header.

•	nav: Ini adalah gaya untuk elemen <nav>, yang mengatur tampilan menu navigasi.

•	nav .logo: Ini adalah gaya khusus untuk elemen dengan kelas "logo" yang ada di dalam elemen <nav>. Ini mengatur ukuran font, ketebalan teks, dan tampilan teks untuk logo.

•	nav ul: Ini adalah gaya untuk daftar yang mungkin berisi item menu.

•	nav ul li: Ini adalah gaya untuk item daftar dalam menu. Ini mengatur item menu agar ditampilkan secara horizontal dan memberikan margin di sekitar setiap item.

•	nav li a:hover: Ini adalah gaya untuk item menu ketika kursor mouse berada di atasnya (hover). Ini mengatur perubahan warna, ketebalan teks, dan efek bawah menu saat di-hover.

•	nav a: Ini adalah gaya untuk tautan menu. Ini mengatur warna, dekorasi teks, ketebalan, dan ukuran font.

•	button.signup: Ini adalah gaya untuk tombol dengan kelas "signup". Ini mengatur berbagai properti tombol termasuk warna latar belakang, teks, dan efek hover.

•	button.signup:hover: Ini adalah gaya tambahan yang mengatur tampilan tombol saat tombol tersebut dihover oleh mouse.

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/682e7018-1906-4413-a6ad-de44e49683b3)


![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/4705aef6-d9a3-4c09-9911-aacb9744b68c)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/caca2be9-f065-46bd-8229-c825676bbfe5)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/e336bbab-dece-44f3-8549-ada5d66589f7)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/de41b99f-c809-4e88-abae-410330cd0177)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/61631bbd-096a-49f9-8c1a-94f99954b36d)

![image](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124489939/01b4517b-be6d-466c-998c-6f1c319f406f)
   
   C. JAVASCRIPT
