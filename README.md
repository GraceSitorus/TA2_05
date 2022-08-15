# TA2_05

Topik Proyek: Machine Learning

Nama Sistem atau Aplikasi : “Penerapan Sentiment Analysis pada Review Menggunakan Metode Support Vector Machine dan Bidirectional Encoder Representations from Transformers”

Jenis Sistem atau Aplikasi (Desktop/ Mobile/ Web, dll): Google Colab

Persiapan, mencakup: 
Lingkungan  yang  digunakan  dalam  implementasi  Tugas  Akhir  ini  mencakup lingkungan perangkat keras dan perangkat lunak  yang digunakan dalam implementasi. Spesifikasi perangkat keras yang digunakan untuk implementasi adalah sebagai berikut.
1.	Spesifikasi hardware lingkungan operasional aplikasi antara lain:
    a.	PC type : Lenovo.
    b.	Processor : Intel(R) Core(TM) i5-7200U CPU @2.50 GHz (4 CPUs), ~2.7GHz
    c.	Memory : 8.00 GB 
    d.	OS : Windows 10
2.	Spesifikasi software lingkungan operasional aplikasi antara lain:
    a.	Tools Pengembang : Jupyter Notebook, Google Colaboratory
    b.	Programming Language :  Python
    c.	Database : MySQL

Langkah-langkah menjalankan aplikasi web atau mobile tersebut. Jelaskan dengan detail mulai dari download source code  dari github, hingga proses instalasi berhasil dijalankan. Gunakan kalimat yang benar dan gambar yang sesuai.
Cara Download Repositori:

A. Cara download repository di GitHub secara langsung menjadi .zip:
1. Pastikan Anda di halaman repositori GitHub yang ingin diunduh.
2. Klik tombol ‘Code’ yang berwarna hijau.
3. Klik ‘Download ZIP’.
4. Repositori GitHub sudah tersimpan dalam direktori download di komputer Anda.
5. Setelah itu ekstrak  Repositori tersebut.

B. Cara git clone menggunakan Git Bash
Berikut cara git clone atau cara men-download suatu repository menggunakan Git Bash:
1. Kunjungi halaman repositori yang ingin di-clone ke komputer Anda.
2. Klik tombol ‘Code’ yang berwarna hijau.
3. Salin (copy) teks yang ada di dalam kotak. Teks ini merupakan alamat web dari halaman repositori. Kami sarankan Anda untuk mencatat teks ini.
4. Buka folder tempat Anda ingin menyimpan repositori di komputer.
5. Klik kanan pada folder tersebut, kemudian pilih Git Bash Here.
6. Ketik git clone, kemudian tempel (paste) teks yang tadi disalin. (Tip: untuk mem-paste di command prompt seperti ini, tekan Shift+Insert atau Shift+Ins secara bersamaan)
7. Tekan Enter, maka Git akan mulai men-download repositori tersebut. Anda dapat menunggu sampai seluruh file selesai diunduh.

Setelah selesai Download Repositori, selanjutnya adalah menjalankan sistemnya. Machine learningnya dapat dijalankan pada Google Colaboratory dan Jupyter notebook:
A. Google Colaborator
1. Buka drive.google.com.
2. Di kiri atas, klik Baru lalu  Upload File atau Upload Folder.
3. Pilih file atau folder yang ingin diupload. 
4. Setelah itu klik button Baru di drive
5. Klik lainnya, pilih "hubungkan aplikasi lainnya"
![image](https://user-images.githubusercontent.com/60635181/184630482-85e9c186-9ca6-4cad-a737-c2c79fb8d448.png)
6. Pada kotak pencarian ketik "Google Colab" dan klik install
![image](https://user-images.githubusercontent.com/60635181/184630638-7153cb7e-5887-49ba-bfc7-56f2720cf7f2.png)

Setelah folder terpuload, maka selanjutnya kita dapat menjalankan machine learningnya:
1. Sistem yang akan di run terdapat pada folder BERT dan SVM
2. Pertama kita menjalankan metode SVM di folder SVM
![image](https://user-images.githubusercontent.com/60635181/184631445-df349bb4-8f4f-4bac-addb-be0483450de9.png)
4. Buka salah satu file yang ada  pada folder tersebut
5. Pilih icon files, klik upload files. Upload dataset "ebay reviews.csv"
![image](https://user-images.githubusercontent.com/60635181/184631515-03817564-abc1-4bca-82f5-f01840b1fef8.png)
6. Copy path tempat dataset yang upload ke cell berikut
![image](https://user-images.githubusercontent.com/60635181/184631322-f4bcab4e-5d8c-49bd-bf8e-4a2bd295b994.png)
7. Kemudian  pilih menu runtime  pilih "run all"
![image](https://user-images.githubusercontent.com/60635181/184631381-3d394437-2014-4ede-ac5f-e56de6bb39bc.png)
8. Langkah 1-6 dapat dilakukan pada semua file yang ada di folder BERT dan SVM


