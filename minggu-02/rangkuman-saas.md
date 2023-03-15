
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

### 2. SaaS Platform Architecture
Adalah model pengiriman dan lisensi perangkat lunak di mana perangkat lunak dilisensikan berdasarkan langganan dan dihosting secara terpusat. Pengguna dapat mengaksesnya dengan bantuan web browser. SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan perpesanan, perangkat lunak manajemen, virtualisasi, dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS). Ini terkait dengan penyedia layanan   aplikasi (ASP) yang menyediakan aplikasi "shrink-wrap" untuk pengguna bisnis melalui Internet. Aplikasi SaaS adalah arsitektur multi-penyewa instans tunggal yang memberikan pengalaman kaya fitur yang bersaing dengan aplikasi lokal. Agregator menggabungkan penawaran SaaS dari berbagai vendor dan menawarkannya sebagai bagian dari platform aplikasi terpadu.
* **Arsitektur SAAS**
Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua dari aplikasi disiapkan untuk menawarkan sekelompok pelanggan terpilih dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode yang unik. Meskipun pengecualian , beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola sejumlah besar pelanggan secara hemat biaya. Apakah multitenancy merupakan komponen yang diperlukan untuk software-as-a-service adalah topik kontroversi.
Ada dua varietas utama SaaS:
  * SaaS Vertikal
     Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk kesehatan, pertanian, real          estat, industri keuangan)
  * SaaS Horisontal
     Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik              industri.

5. SaaS (Software as a Service) Platform  itecture
6. How to build a cloud-based SaaS Application
