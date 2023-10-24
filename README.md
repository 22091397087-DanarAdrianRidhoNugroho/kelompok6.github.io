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
   
   - Start: Ini adalah titik awal dari navigasi di website profil perusahaan. Ketika pengguna pertama kali
mengakses website, mereka akan memulai dari sini.

  - Halaman Utama: Setelah pengguna memulai dari "Start," mereka akan diarahkan ke halaman utama atau
homepage perusahaan. Halaman utama biasanya berisi informasi ringkas tentang perusahaan dan tautan menu
ke bagian-bagian lain dari website.

   - Tentang Perusahaan: Pengguna memiliki opsi untuk mengklik tautan "Tentang Kami" di halaman utama, yang
akan membawa mereka ke halaman yang memberikan rincian tentang perusahaan, sejarah, dan nilai-nilai.

   - Produk/Layanan: Pengguna juga dapat memilih untuk mengeksplorasi produk atau layanan yang ditawarkan
oleh perusahaan. Ini mungkin mencakup deskripsi produk, spesifikasi, dan lainnya.

   - Sign In: Selain itu, jika pengguna ingin masuk ke akun mereka atau mengakses area yang memerlukan
otentikasi, mereka dapat memilih "Sign In."

   - Kontak: Pengguna dapat mencari informasi kontak perusahaan, seperti alamat, nomor telepon, atau formulir
kontak di halaman "Kontak."

   - Media Sosial: Jika perusahaan aktif di media sosial, pengguna dapat mengeklik tautan ke halaman media
sosial perusahaan di mana mereka dapat mengikuti atau berinteraksi dengan perusahaan di platform tersebut.

   - End: Flowchart diakhiri dengan "End," yang menunjukkan akhir dari navigasi pengguna. Pengguna dapat
kembali ke halaman utama atau keluar dari website.   

   B. UseCase Diagram

   ![Use Case](https://github.com/22091397087-DanarAdrianRidhoNugroho/kelompok6.github.io/assets/124551854/5ad985df-b6b7-439c-843a-756b407349e8)

  1. View Homepage (Melihat Halaman Depan):

      • Aktor Utama: Pengguna customer.
     
      • Deskripsi: Pengguna mengunjungi situs web dan melihat halaman depan
(homepage) untuk mendapatkan informasi umum tentang bisnis atau layanan
yang ditawarkan.

      • Langkah-langkah:
     
         1) Pengguna membuka peramban web.
     
         2) Pengguna memasukkan URL situs web.
     
         3) Halaman depan situs web dimuat.
     
         4) Pengguna melihat konten halaman depan, seperti gambar, teks, dan
mungkin tautan ke halaman lain.

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

   • Deskripsi: Pengguna ingin menghubungi perusahaan atau individu yang terkait
dengan situs web tersebut.

   • Langkah-langkah:
      
      1) Dari halaman depan atau halaman "About Us," pengguna menemukan
tautan "Contact Us" atau sejenisnya.
      
      2) Pengguna mengklik tautan "Contact Us."
      
      3) Halaman "Contact Us" dimuat.
      
      4) Pengguna melihat informasi kontak, seperti alamat email, nomor
telepon, atau formulir kontak.

4. Register (Mendaftar):\
   
   • Aktor Utama: Pengguna customer.

   • Deskripsi: Pengguna ingin mendaftar atau membuat akun di situs web tersebut
untuk mengakses fitur atau layanan tambahan.

   • Langkah-langkah:
    
      1) Dari halaman depan atau dari tautan khusus "Register" di menu,
pengguna memilih opsi "Register" atau "Sign Up."
      
      2) Pengguna diarahkan ke halaman pendaftaran.
      
      3) Pengguna mengisi formulir pendaftaran dengan informasi yang
diperlukan, seperti nama, alamat email, kata sandi, dan data pribadi
lainnya.
      
      4) Pengguna mengklik tombol "Submit" atau sejenisnya untuk
menyelesaikan pendaftaran.

5. Login (Masuk):

   • Aktor Utama: Pengguna admin.

   • Deskripsi: Pengguna admin perlu masuk ke akun admin mereka untuk mengakses
kontrol dan fitur administratif di situs web.

   • Langkah-langkah:
      
      1) Pengguna admin membuka halaman login di situs web.
      
      2) Pengguna admin memasukkan nama pengguna (username) dan kata
sandi (password) mereka.
      
      3) Sistem memverifikasi informasi login.
      
      4) Jika informasi login valid, pengguna admin diizinkan untuk mengakses
akun admin mereka.
      
6. View Customer on the Web (Melihat Data Customer di Situs Web):

   • Aktor Utama: Pengguna admin.

   • Deskripsi: Pengguna admin ingin melihat data dan informasi terkait dengan
pengguna customer yang terdaftar di situs web.

   • Langkah-langkah:
    
      1) Setelah masuk, pengguna admin mengakses panel administratif.
      
      2) Pengguna admin memilih opsi "View Customers" atau "Lihat Data
Customer."
      
      3) Sistem menampilkan daftar pengguna customer yang terdaftar beserta
detailnya, seperti nama, alamat email, informasi kontak, dan riwayat
transaksi.

7. Edit Web (Mengedit Situs Web):

   • Aktor Utama: Pengguna admin.

   • Deskripsi: Pengguna admin bertanggung jawab untuk mengedit konten dan
pengaturan situs web, seperti mengubah teks, gambar, atau konfigurasi situs.

   • Langkah-langkah:
      
      1) Setelah masuk, pengguna admin mengakses panel administratif.
      
      2) Pengguna admin memilih opsi "Edit Website" atau "Edit Konten" atau
sejenisnya.
      
      3) Pengguna admin dapat mengganti teks, gambar, atau mengkonfigurasi
berbagai aspek situs web, seperti tampilan, tema, dan pengaturan
lainnya.
      
      4) Pengguna admin menyimpan perubahan yang telah dibuat.

8. Logout (Keluar):

   • Aktor Utama: Pengguna admin.

   • Deskripsi: Pengguna admin ingin keluar dari akun admin mereka untuk menjaga
keamanan dan privasi informasi di situs web.

   • Langkah-langkah:
      
      1) Pengguna admin yang telah selesai melakukan tugas administratif
memilih opsi "Logout" atau "Keluar" di panel administratif atau
pada halaman akun mereka.
      
      2) Sistem mengakhiri sesi login pengguna admin dan mengarahkannya
kembali ke halaman login atau halaman depan situs web
   
4. Penjelasan Code
   A. HTML
   
   B. CSS
   
   C. JAVASCRIPT
