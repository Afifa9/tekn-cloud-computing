
Latihan
### 1. What is the difference between IaaS, SaaS, and PaaS? ###
* Di IaaS, Anda memilih lapisan OS yang sudah dikalengkan, menyebarkan tumpukan aplikasi, menerapkan kode Anda & kemudian menambahkan data Anda. Infrastruktur sebagai Layanan (IaaS): Ini hanya menyediakan infrastruktur dasar (Mesin virtual, Jaringan Definisi Perangkat Lunak, Penyimpanan terpasang). Pengguna akhir harus mengonfigurasi dan mengelola platform dan lingkungan, menerapkan aplikasi di dalamnya.
![image](https://user-images.githubusercontent.com/114986359/225198773-5635e844-202e-46df-9ae6-bd4bc29f2837.png)
* Di PaaS, Anda menerapkan kode Anda (OS/Application Stack adalah bagian dari penawaran) & kemudian menambahkan data Anda. Platform as a Service (PaaS): Ini menyediakan platform yang memungkinkan pengguna akhir untuk mengembangkan, menjalankan, dan mengelola aplikasi tanpa kerumitan membangun dan memelihara infrastruktur.
* Di SaaS, Anda menambahkan data Anda (semua bagian lain dari penawaran). Perangkat Lunak sebagai Layanan (SaaS ): Kadang-kadang disebut sebagai "perangkat lunak berdasarkan permintaan". Biasanya diakses oleh pengguna menggunakan thin client melalui web browser. Di SaaS semuanya dapat dikelola oleh vendor: aplikasi, runtime, data, middleware, OS, virtualisasi, server, penyimpanan, dan jaringan, Pengguna akhir harus menggunakannya.
     * gambar ini menjelaskan lebih detail perbedaan:
     ![image](https://user-images.githubusercontent.com/114986359/225199403-31442a4f-a350-4158-9368-0727050c2c66.png) 
     * untuk menjelaskan perbedaan, populer juga gambar segitiga:
     ![image](https://user-images.githubusercontent.com/114986359/225199810-7210e404-80e2-4b2e-9d31-b794524a39e5.png)

### 2. SaaS Platform Architecture ###
![image](https://user-images.githubusercontent.com/114986359/225203151-1e3b220b-9d9c-4fcc-b7fe-163de3335557.png)

Adalah model pengiriman dan lisensi perangkat lunak di mana perangkat lunak dilisensikan berdasarkan langganan dan dihosting secara terpusat. Pengguna dapat mengaksesnya dengan bantuan web browser. SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan perpesanan, perangkat lunak manajemen, virtualisasi, dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS). Ini terkait dengan penyedia layanan   aplikasi (ASP) yang menyediakan aplikasi "shrink-wrap" untuk pengguna bisnis melalui Internet. Aplikasi SaaS adalah arsitektur multi-penyewa instans tunggal yang memberikan pengalaman kaya fitur yang bersaing dengan aplikasi lokal. Agregator menggabungkan penawaran SaaS dari berbagai vendor dan menawarkannya sebagai bagian dari platform aplikasi terpadu.
* **Arsitektur SAAS :**

Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua dari aplikasi disiapkan untuk menawarkan sekelompok pelanggan terpilih dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode yang unik. Meskipun pengecualian , beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola sejumlah besar pelanggan secara hemat biaya. Apakah multitenancy merupakan komponen yang diperlukan untuk software-as-a-service adalah topik kontroversi.
Ada dua varietas utama SaaS:
  * SaaS Vertikal
     Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk kesehatan, pertanian, real          estat, industri keuangan)
  * SaaS Horisontal
     Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik              industri.
![image](https://user-images.githubusercontent.com/114986359/225203122-4d8ac532-41ff-462d-a59d-58e247edd024.png)
* **Manfaat SAAS:**

Secara tradisional, menerapkan sistem perangkat lunak skala besar telah menjadi pekerjaan besar. Menyebarkan sistem ini di perusahaan besar membutuhkan biaya lebih banyak. Persyaratan waktu, staf, dan anggaran untuk penyebaran sebesar ini merupakan risiko yang signifikan bagi organisasi dengan ukuran apa pun, dan seringkali menempatkan perangkat lunak semacam itu di luar jangkauan organisasi yang lebih kecil yang jika tidak dapat memperoleh banyak manfaat darinya. kegunaan. Model pengiriman sesuai permintaan mengubah beberapa hal ini. Aplikasi SaaS tidak memerlukan penyebaran infrastruktur besar di lokasi klien. Integrasi dapat direncanakan dan dilaksanakan dengan upaya minimal, menciptakan salah satu interval waktu tersingkat yang memungkinkan untuk investasi TI yang besar. Ini juga memungkinkan sejumlah vendor SaaS untuk menawarkan "test drive" perangkat lunak mereka yang bebas risiko (dan seringkali gratis ) untuk jangka waktu terbatas, seperti 30 hari. Pelanggan diberi sebuah kesempatan untuk mencoba sebuah perangkat lunak sebelum membeli.
* **Bagaimana SaaS Mempengaruhi TI?**

Beberapa area yang perlu diperhatikan dalam daftar periksa uji tuntas meliputi, Standar keamanan data : Memindahkan data bisnis penting “ke luar tembok” menimbulkan risiko kehilangan data atau pemaparan informasi sensitif secara tidak sengaja. Nilai kebutuhan keamanan data Anda, dan pastikan penyedia memiliki tindakan untuk memenuhi standar yang Anda tetapkan. Layanan pelaporan : Karena SaaS melibatkan penyerahan kontrol langsung atas beberapa data Anda, pelaporan yang akurat dan bermanfaat sangatlah penting. Tentukan layanan pelaporan apa yang ditawarkan penyedia, dan apakah layanan tersebut kompatibel dengan persyaratan intelijen bisnis Anda.
* **Dampak pada Peran dan Tanggung Jawab TI**

Dampak yang diakibatkan adalah menyebabkan perubahan mendasar pada peran departemen TI sebagai penyedia layanan informasi. Di masa lalu, sifat penyebaran perangkat lunak telah menempatkan kepala petugas informasi sebagai penjaga gerbang. Mereka dapat menggunakan hak veto dengan menyatakan bahwa mereka tidak akan menyimpannya di pusat data. Dengan SaaS , kendali pusat data tidak harus sama dengan kendali atas seluruh lingkungan komputasi perusahaan. Hal ini dapat menyebabkan penjaga gerbang takut kehilangan kendali.

* **Kesimpulan**

Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dari penambahan SaaS ke portofolio layanan TI mereka. Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI Anda yang berpusat pada layanan.

## 3. SaaS (Software as a Service) Platform  itecture ###
![image](https://user-images.githubusercontent.com/114986359/225204576-4b360f99-5f34-432f-be44-eda0181f344f.png)
SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak secara terpusat menghosting satu atau lebih aplikasi dan membuatnya tersedia untuk pelanggan melalui internet.Ledakan komputasi Cloud, didorong oleh penyedia layanan cloud seperti Microsoft dengan Azure, Amazon Web Services (AWS), Oracle, dan IBM, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet. Ini termasuk model SaaS berikut:

    * Infrastruktur sebagai Layanan
    * Platform sebagai Layanan
    * Pembelajaran Mesin sebagai Layanan

6. How to build a cloud-based SaaS Application
