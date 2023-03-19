
## Latihan

### 1 ###
1. What is the difference between IaaS, SaaS, and PaaS?
* **Di IaaS**, Anda memilih lapisan OS yang sudah dikalengkan, menyebarkan tumpukan aplikasi, menerapkan kode Anda & kemudian menambahkan data Anda. Infrastruktur sebagai Layanan (IaaS): Ini hanya menyediakan infrastruktur dasar (Mesin virtual, Jaringan Definisi Perangkat Lunak, Penyimpanan terpasang). Pengguna akhir harus mengonfigurasi dan mengelola platform dan lingkungan, menerapkan aplikasi di dalamnya.
![image](https://user-images.githubusercontent.com/114986359/225198773-5635e844-202e-46df-9ae6-bd4bc29f2837.png)
* **Di PaaS**, Anda menerapkan kode Anda (OS/Application Stack adalah bagian dari penawaran) & kemudian menambahkan data Anda. Platform as a Service (PaaS): Ini menyediakan platform yang memungkinkan pengguna akhir untuk mengembangkan, menjalankan, dan mengelola aplikasi tanpa kerumitan membangun dan memelihara infrastruktur.
* **Di SaaS**, Anda menambahkan data Anda (semua bagian lain dari penawaran). Perangkat Lunak sebagai Layanan (SaaS ): Kadang-kadang disebut sebagai "perangkat lunak berdasarkan permintaan". Biasanya diakses oleh pengguna menggunakan thin client melalui web browser. Di SaaS semuanya dapat dikelola oleh vendor: aplikasi, runtime, data, middleware, OS, virtualisasi, server, penyimpanan, dan jaringan, Pengguna akhir harus menggunakannya.
* untuk menjelaskan perbedaan, populer juga gambar segitiga:
![image](https://user-images.githubusercontent.com/114986359/225199810-7210e404-80e2-4b2e-9d31-b794524a39e5.png)

2. SaaS Platform Architecture ###
![image](https://user-images.githubusercontent.com/114986359/225203151-1e3b220b-9d9c-4fcc-b7fe-163de3335557.png)

Adalah model pengiriman dan lisensi perangkat lunak di mana perangkat lunak dilisensikan berdasarkan langganan dan dihosting secara terpusat. Pengguna dapat mengaksesnya dengan bantuan web browser. SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan perpesanan, perangkat lunak manajemen, virtualisasi, dll. Aplikasi SaaS adalah arsitektur multi-penyewa instans tunggal yang memberikan pengalaman kaya fitur yang bersaing dengan aplikasi lokal. Agregator menggabungkan penawaran SaaS dari berbagai vendor dan menawarkannya sebagai bagian dari platform aplikasi terpadu.
* **Arsitektur SAAS :**

Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua dari aplikasi disiapkan untuk menawarkan sekelompok pelanggan terpilih dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode yang unik. Meskipun pengecualian , beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola sejumlah besar pelanggan secara hemat biaya. Apakah multitenancy merupakan komponen yang diperlukan untuk software-as-a-service adalah topik kontroversi.
Ada dua varietas utama SaaS:
  * SaaS Vertikal
     Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
  * SaaS Horisontal
     Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.
![image](https://user-images.githubusercontent.com/114986359/225203122-4d8ac532-41ff-462d-a59d-58e247edd024.png)

* **Manfaat SAAS:**

 Manfaat Model pengiriman sesuai permintaan mengubah beberapa hal ini. Aplikasi SaaS tidak memerlukan penyebaran infrastruktur besar di lokasi klien. Integrasi dapat direncanakan dan dilaksanakan dengan upaya minimal, menciptakan salah satu interval waktu tersingkat yang memungkinkan untuk investasi TI yang besar. Ini juga memungkinkan sejumlah vendor SaaS untuk menawarkan "test drive" perangkat lunak mereka yang bebas risiko (dan seringkali gratis ) untuk jangka waktu terbatas, seperti 30 hari. Pelanggan diberi sebuah kesempatan untuk mencoba sebuah perangkat lunak sebelum membeli.
* **Bagaimana SaaS Mempengaruhi TI?**

 Beberapa area yang perlu diperhatikan dalam daftar periksa uji tuntas meliputi, Standar keamanan data : Memindahkan data bisnis penting “ke luar tembok” menimbulkan risiko kehilangan data atau pemaparan informasi sensitif secara tidak sengaja. Nilai kebutuhan keamanan data Anda, dan pastikan penyedia memiliki tindakan untuk memenuhi standar yang Anda tetapkan. Layanan pelaporan : Karena SaaS melibatkan penyerahan kontrol langsung atas beberapa data Anda, pelaporan yang akurat dan bermanfaat sangatlah penting. Tentukan layanan pelaporan apa yang ditawarkan penyedia, dan apakah layanan tersebut kompatibel dengan persyaratan intelijen bisnis Anda.
* **Dampak pada Peran dan Tanggung Jawab TI**

Dampak yang diakibatkan adalah menyebabkan perubahan mendasar pada peran departemen TI sebagai penyedia layanan informasi. Di masa lalu, sifat penyebaran perangkat lunak telah menempatkan kepala petugas informasi sebagai penjaga gerbang. Mereka dapat menggunakan hak veto dengan menyatakan bahwa mereka tidak akan menyimpannya di pusat data. Dengan SaaS , kendali pusat data tidak harus sama dengan kendali atas seluruh lingkungan komputasi perusahaan. Hal ini dapat menyebabkan penjaga gerbang takut kehilangan kendali.

* **Kesimpulan**

Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dari penambahan SaaS ke portofolio layanan TI mereka. Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI Anda yang berpusat pada layanan.

3. SaaS (Software as a Service) Platform  itecture ###
![image](https://user-images.githubusercontent.com/114986359/225204576-4b360f99-5f34-432f-be44-eda0181f344f.png)
SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak secara terpusat menghosting satu atau lebih aplikasi dan membuatnya tersedia untuk pelanggan melalui internet.Ledakan komputasi Cloud, didorong oleh penyedia layanan cloud seperti Microsoft dengan Azure, Amazon Web Services (AWS), Oracle, dan IBM, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet. Ini termasuk model SaaS berikut:

   * Infrastruktur sebagai Layanan
   * Platform sebagai Layanan
   * Pembelajaran Mesin sebagai Layanan

Pembaruan aplikasi arsitektur SaaS semuanya ditangani oleh penyedia. Pelanggan menginstal ulang versi baru suatu produk karena perangkat lunak dikirimkan melalui internet. beroperasi sebagai arsitektur SaaS multi-penyewa di mana semua database dan templat yang relevan dengan pengguna berlisensi dapat diakses di mana pun lokasinya. 

* **KONSUMEN**

Dari sudut pandang konsumen, aplikasi SaaS adalah salah satu cara termudah dan paling andal untuk menggunakan layanan atau produk digital. layanan aplikasi SaaS yang ditargetkan untuk konsumen seperti:Netflix, Microsoft Office 365,Amazon Perdana, Twitter, Facebook, Google Dokumen, Tenaga penjualan.

* **BISNIS**

Dari perspektif bisnis, produk perangkat lunak yang disampaikan "sebagai layanan" memungkinkan bisnis untuk menawarkan produk mereka dalam skala besar, secara global, sementara juga memungkinkan mereka mempertahankan kontrol keseluruhan atas produk mereka. manfaat lain dari penerapan arsitektur SaaS dalam bisnis termasuk, namun tidak terbatas pada:
    * Mengurangi waktu ke pasar;
    * Biaya pemeliharaan lebih rendah;
    * Peningkatan otomatisasi;
    * Peningkatan yang lebih mudah;
    * Lebih hemat biaya;
    
* **Fitur Utama dan Manfaat Platform Arsitektur SaaS**

    * Kesederhanaan Aplikasi Arsitektur SaaS
    * Nilai Ekonomis
    * Keamanan
    * Kesesuaian
* **Kemampuan Solusi SaaS**

Platform SaaS memiliki beragam kemampuan. Apalagi jika digabungkan dengan penawaran cloud lainnya seperti IaaS (Infrastruktur sebagai Layanan) dan PaaS (Platform sebagai Layanan). Teknologi cloud seperti Microsoft Azure memungkinkan Anda menyediakan server yang dapat menghosting situs web, database, dan banyak lagi.

* **Kerugian Platform SaaS**

    * Kurangnya kontrol dalam platform Arsitektur SaaS
    * Ekosistem terbatas
    * Pertunjukan
    * Kekhawatiran Data

* **Komponen Utama Platform SaaS**
    * Keamanan
    * Pribadi
    * Kustomisasi dan Konfigurasi
 
 * **Pertimbangan Desain untuk Platform Arsitektur SaaS**
   * Skalabilitas
   * Zero downtime dan Perjanjian Tingkat Layanan
   * Multi-tenancy dalam arsitektur SaaS

4. How to build a cloud-based SaaS Application
* **Programming Language**
Bahasa pemprograman yang digunakan adalah Python, karena python banyak melakukan banyak hal selain itu banyak digunakan pegembang karena Pengetikan dinamis, pemrograman meta, pembuatan prototipe cepat. Segalanya mungkin dengan Python. Python aman digunakan
* **Database**
Yang baik dan direkomendasikan adalah database berorientasi dokumen, database berorientasi dokumen berbeda dengan database relasional  karena memungkinkan lebih fleksibilitas, terutama ketika berhadapan dengan perubahan. Dan itu sering kali mengurangi ukuran basis data. Singkatnya, konsep DOB menawarkan pengalaman yang lebih kaya dengan teknik pemrograman modern.
* **Contoh dari Database Dokumen**
   *  MongoDb
* **Queuing system for your SaaS application**
A message queuing system is an asynchronous communication protocol, enabling sender and receiver of a message not interacting at the same time. Also known as Message Queuing (MSMQ) technology it enables web apps to run at different times and to communicate with various 3rd party integrations / APIs / and other services asynchronously.
  * RabbitMQ
  * AWS & EC2
  * Web Storage S3
* **Content Delivery Network for your SaaS application**
A content delivery network (CDN) is basically a system of distributed servers which enables you to serve content to your app users with high performance and high availability.Let’s assume you have 3 EC2s installed. One in the US, one in Europe and one in Singapore. If someone from New York visits your app, the CDN enables you to serve content to the user through the EC2 located in the US. So you might wonder how to connect the dots. Below you can find an overview how we at Usersnap have set up our web app and the role of EC2, S3, and CDN.
* **Recap: SaaS application set up**
With Python, MongoDB – as a great document-orientated database, RabbitMQ software-wise the basic setup is done. However, there is way more to think of. In our follow-up posts, we will address the need of a proper monitoring and analytics software as well as how payment procedures can run smoothly in the cloud.
Further on, we will also show you some in-depth guides on how to set up your tool stack for running your web app on a global scale.
* **Start with software testing now**
This article was brought to you by Usersnap – your feedback and bug tracking tool. Used by software companies like Facebook, Google, and AddThis. Read this blog post about how Usersnap helps during your SaaS application development.
### 2 ###

**1. Visual Paradigma**
**2. Lucidchart**
