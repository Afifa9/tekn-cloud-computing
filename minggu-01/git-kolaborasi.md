# 04 Kolaborasi
# FORK
  Fork adalah membuat clone dari suatu repo di GitHub milik upstream author, diletakkan ke milik kontributor. Fork hanya dilakukan sekali saja. Pada dasarnya, proses untuk fork ini meliputi:
  1. Fork repo di web GitHub.
  2. Clone fork tersebut di komputer lokal.
  3. Kontributor harus mem-fork repo upstream author sehingga di repo kontributor muncul repo tersebut. Proses forking ini dijelaskan dengan langkah-langkah berikut:
    1. Login ke GitHub
    2. Akses repo yang akan di-fork: https://github.com/AnggitaAlbiantara/tekn-cloud-computing
    3. Pada sisi kanan atas, klik Fork:
      ![gmb01](https://user-images.githubusercontent.com/114986359/224532029-5095463c-3965-4cbf-b0bc-4c82aebbe591.png)
      ![gmb02](https://user-images.githubusercontent.com/114986359/224532068-f40696e9-2c78-42a6-a2a9-58454dca1f94.png)
Setelah proses tersebut, clone di komputer lokal:
![gmb1](https://user-images.githubusercontent.com/114986359/224532138-cdf2fb84-e03f-4c6f-b3df-df43316305df.png)
Setelah itu, konfigurasikan repo lokal kontributor. Pada kondisi saat ini, di komputer lokal sudah terdapat repo playground-1 yang berada pada direktori dengan nama yang sama. Untuk keperluan berkontribusi, ada 2 nama repo yang harus diatur:
  ```origin: menunjuk ke repo milik kontributor di GitHub, hasil dari fork.
  upstream: menunjuk ke repo milik upstream author (repo asli) di account oldstager.```
Repo origin sudah dituliskan konfigurasinya pada saat melakukan proses clone dari repo kontributor. Konfigurasi repo upstream harus dibuat.
