# _jawaban tes_
<hr>

### pertanyaan

Dalam sebuah perusahaan Andi bekerja sebagai DevOps, jelaskan menurut pendapatmu definisi tentang DevOps dan seberapa penting DevOps di suatu perusahaan serta gambarkan flow DevOps dari development hingga ke production?

### jawaban

DevOps kepanjangan dari __development__ dan __operations__ dengan pengembangan perangkat lunak yang menggabungkan perangkat lunak (dev) dengan operasi teknologi informasi (Ops)

![diagram devops](https://musaamin.web.id/wp-content/uploads/2019/01/devops.png)

devops sangat penting dalam suatu perusahaan karna dalam suatu aplikasi pasti ada masalah maka devops akan memperbaiki bug tersebut

  ![proses development](https://1.bp.blogspot.com/-sBWzwWzXRNM/Xqz3wN7GL3I/AAAAAAAAROg/5AVms0nmCfwo6_DNb3KeTQ25AzBZvDUMQCNcBGAsYHQ/s320/devops-5-644x644.png) 

dalam mengerjakan development akan:
1. developer akan menulis kode secara lokal di laptop masing-masing
2. operation mempersiapkan server test
3. developer meminta tim operation untuk menguplaod kode ke server test
4. operation mengupload kode ke server test
5. QA/tester melakukan pengetesan
6. developer meminta tim operation untuk mengupload kode ke sever production
7. operation mempersiapkan server production
8. operation mengupload kode ke server production

![metode waterfall](https://1.bp.blogspot.com/-iNB-Qi-jbIg/Xqz4FLttrJI/AAAAAAAAROo/eCKeaCd3g8Q_h6DOrMqUbHnB93-dSQVAACNcBGAsYHQ/s400/052615_1232_WhatisSDLCo1.png)
<hr>

### pertanyaan

Bagaimana cara kamu mencari sebuah file di sistem linux, tetapi kamu hanya mengetahui isi dari file tersebut?

### jawaban

<hr>

### pertanyaan

Dalam praktiknya seorang DevOps akan menggunakan web server dalam setiap proses deployment, baik itu untuk kebutuhan load balancing dan konfigurasi SSL. Menurut kamu, apa itu load balancing, SSL serta berikan contoh-contoh web server yang kamu ketahui?

### jawaban

Load balancing adalah teknik untuk mendistribusikan beban trafik pada dua atau lebih jalur koneksi secara seimbang, agar trafik dapat berjalan optimal, memaksimalkan throughput, memperkecil waktu tanggap dan menghindari overload pada salah satu jalur koneksi.

SSL (Secure Socket Layer) adalah sebuah standar teknologi yang digunakan untuk membangun koneksi terenkripsi antara webserver (website) dengan client (Browser) atau antara mail server dengan mail client.

beberapa contoh web server:

- IIS
- XAMPP
- Apache Tomcat

<hr>
    
### pertanyaan

Jelaskan perbedaan mencolok antara Docker dengan VMware, serta berikan penjelasan kapan kita harus menggunakan Docker dan VMware?

### jawaban

Docker didefinisikan sebagai project open source dengan menyediakan jenis platform terbuka yang digunakan untuk developer juga administrator admin, supaya pengembang bisa membangun, mengemas, serta menjalankan berbagai aplikasi dalam lokasi manapun sebagai sebuah container  yang bersifat ringan.
Docker mempunyai fungsi utama dalam menyederhanakan berbagai konfigurasi yang telah dibangun berdasarkan teknologi container.

<img src="https://idcloudhost.com/wp-content/uploads/2020/02/docker3.png" style="width:80%" />

VMware adalah penyedia perangkat lunak virtualisasi dan komputasi awan
Dengan virtualisasi server VMware, hypervisor diinstal di server fisik untuk memungkinkan beberapa mesin virtual (VM) berjalan di server fisik yang sama

<img src="https://idcloudhost.com/wp-content/uploads/2020/10/vmware.jpg" style="width:80%" />

<hr>

### pertanyaan

jika saat ini Kamu adalah seorang DevOps di sebuah perusahaan, bagaimana caramu mengamankan server-server tersebut?

### jawaban

ganti port RDP default Peretas sering mendapatkan akses ke server kita menggunakan RDP.
Terapkan Otentikasi Tingkat Jaringan.
Terapkan enkripsi koneksi.
Batasi pengguna yang diizinkan masuk melalui Layanan Terminal seminimal mungkin, dan jangan izinkan akun "khusus" seperti Administratorakun domain default , atau idealnya akun hak istimewa tinggi lainnya.

<hr>

### pertanyaan

Jika kamu menjadi seorang DevOps di sebuah perusahaan dan kamu ditugaskan untuk memonitoring server, tools apa saja yang akan kamu gunakan serta berikan keuntungan menggunakan tools tersebut?

### jawaban

tools yang akan digunakan saat memonitoring:

- icinga
icinga dapat digunakan plugin plugin yang diperuntukan untuk nagios, dan proses development icinga cukup aktif bisa di lihat dilaman github icinga
- retrace
dapat memantau alat open source solusi untuk kesalahan APM, dan log, bisa juga dijadikan alat pemantau java dan NET
- PRTG
Software ini memungkinkan untuk secara cepat mempersiapkan dan menjalankan sebuah proses pemantauan untuk sebuah jaringan tertentu

<hr>

### pertanyaan

Menurut kamu, apa itu DNS dan bagaimana cara kerjanya?

### jawaban

DNS singkatan dari domain name server adalah sistem yang menghubungkan URL dengan IP address

cara kerja DNS dimulai meminta informas, kemudian dilanjutkan dengan tahapan lain seperti DNS recursion, root nameserver, TLD nameserver, sampai authoritative nameserver

<hr>


### pertanyaan

Buatlah sebuah server sederhana menggunakan web server di komputer kamu, kemudian setting web server tersebut menjadi domain dumbways-namakamu.xyz!

### jawaban



