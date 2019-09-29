# Tugas-2-Pemrograman-Jaringan_1301188565

<p align="center"
  <a><strong>  NAMA KELOMPOK :  </strong></a> 
</p>
<p align="center">
  <a>  I Putu Surya Baratha (1301188566)  </a> 
</p> 

<p align="center">
  <a>  Muhammad Risdham Nur A.P (1301188603)  </a> 
</p>

<p align="center">
  <a>  Sella Tresnasari  (1301188565)  </a> 
</p> 



#### SOAL NOMOR 1 ####

1. Kelompok kami akan membuat sebuah perncangan jaringan pada sebuah perusahaan penerbangan.

2. Pada perusahaan penerbangan ini sangat dibutuh kan sebuah Web Server yang fungsinya untuk melakukan penjualan tiket secara online. Web Server ini juga nantinya dapat di akses oleh pelanggan dan data pelanggan, transaksi dan sebagainya akan di simpan ke dalam Database Server. Selain Web Server, Perusahaan ini juga membutuhkan sebuah FTP Server yang berfungsi sebagai sebuah protokol atau media untuk melakukan proses download maupun upload E-Ticket. Dalam proses bisnisnya, perusahaan ini juga membutuhkan sebuah Mail Server. Mail Server berfungsi untuk memberikan notifikasi kepada pelanggan melalui email. Dan yang terakhir perusahaan ini membutuhkan Server Monitoring untuk melakukan proses pengumpulan data dan melakukan analisis terhadap data-data tersebut dengan tujuan untuk memaksimalkan seluruh sumberdaya yang dimilki.

3. Pihak yang bertanggung jawab mengnai proses instalasi dan maintenance adalah Kami dan Network Engineer di persuhaan tersebut.

#### SOAL NOMOR 2 ####

[![Screen-Shot-2019-09-06-at-20-36-07.png](https://i.postimg.cc/CKjMsn32/Screen-Shot-2019-09-06-at-20-36-07.png)](https://postimg.cc/94QjW0FP)

Topologi yang kami pakai adalah topologi tree. Kami memakai topologi tree karena topologi ini cocok diterapkan pada jaringan computer untuk skala besar. Dan juga bentuknya bercabang seperti pohon sehingga memungkinkan jaringan point to point. Jaringan point to point sendiri akan mempermudah identifikasi jika terjadi kerusakan didalam jaringan.

Kekurangan Topologi Tree:
1.	Jika kabel utama rusak, maka seluruh jaringan akan tergangung
2.	Hub memegang peran pentiig dalam jaringan ini, jika hubnya rusak maka seluruh jaringan akan terganggu
3.	Jika computer tang berada diatas rusak atau gangguan, maka computer yang berada dibawah juga mengalaminya
4.	Biaya yang diperlukan lebih mahal, karena menggunakan lebih banyak kabel dan hub
5.	Konfigurasi dan pemasangan kabel lebih rumit dari topologi lain
6.	Perawatan lebih sulit karena banyak perncangan pada node
7.	Kinerja jaringan lebih lambat karena komunikasi antar komputer tidak berjalan langsung, namun harus melalui hub terlebih dahulu
8.	Lalu lintas sangat padat, karena melalui kabel utama sehingga kemungkinan terjadi tabrakan file data sangat besar

Kelebihan Topologi Tree:
1.	Identifikasi kerusakan pada jaringan dapat dilakukan dengan mudah
2.	Mendukung untuk diterapkan pada jaringan skala besar
3.	Jika salah satu client mengalami kerusakan, client lain tidak akan terpengaruh
4.	Pengembangan jaringan yang berada dibawah hub pusat dapat dilakukan dengan mudah
5.	Manajemen data yang baik, karena komunikasi terjadi secara point to point

#### SOAL NOMOR 3 ####
- Web Server
<img width="1440" alt="Screen Shot 2019-09-07 at 01 17 40" src="https://user-images.githubusercontent.com/54678313/64468604-ea4cc780-d150-11e9-89d2-3ae678ef9353.png">

- Database Server
<img width="1440" alt="Screen Shot 2019-09-07 at 02 32 43" src="https://user-images.githubusercontent.com/54678313/64468606-eae55e00-d150-11e9-820f-8c15649c89c1.png">

- FTP
<img width="1440" alt="Screen Shot 2019-09-07 at 02 46 35" src="https://user-images.githubusercontent.com/54678313/64468607-eb7df480-d150-11e9-80fd-c567252cbcaf.png">

- Mail Server

![image](https://user-images.githubusercontent.com/54678313/65835942-db53d200-e316-11e9-909d-4e682a8ee1f8.png)

- Server monitoring

![image](https://user-images.githubusercontent.com/54678313/65835951-ea3a8480-e316-11e9-835e-6a50af39679e.png)
