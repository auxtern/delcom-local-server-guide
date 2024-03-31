# Composer

Composer adalah alat manajemen paket untuk bahasa pemrograman PHP yang digunakan untuk mengelola dependensi dan pustaka yang digunakan dalam proyek pengembangan perangkat lunak. Dengan Composer, pengembang dapat dengan mudah menambahkan, menghapus, dan mengelola paket-paket PHP yang diperlukan oleh aplikasi mereka. Composer memungkinkan untuk mendefinisikan dependensi dalam sebuah file konfigurasi (`composer.json`) dan secara otomatis mengunduh dan menginstal paket-paket tersebut serta semua dependensinya. Ini membantu mempercepat proses pengembangan, meningkatkan keamanan, dan memudahkan pengelolaan proyek PHP yang kompleks.

- Situs Resmi: https://getcomposer.org/



## Instalasi Composer

- Silahkan download composer dengan [membuka situs resminya](https://getcomposer.org/).  Selanjutnya pada halaman awal composer pilih tombol `Download`.

  <img style="display: block; margin: 0;" src="D:/repository/delcom-local-server-guide/php-manager/assets/4.jpg" />

- Pada halaman `download`  composer, scroll ke bawah sampai pada bagian `Manual Download`. Selanjutnya download composer sesuai dengan versi PHP Minimum yang dibutuhkan. Perhatikan tabel berikut:

  | Versi Composer   | Versi PHP Minimum  | Status    |
  | ---------------- | ------------------ | --------- |
  | besar dari 2.2.x | 7.2 dan lebih baru | Active    |
  | 2.2.x            | 5.3 sampai 7.1     | LTS       |
  | kecil dari 2.2x  | 5.3                | Deprected |

- Dikarenakan sebelumnya telah mengunduh PHP versi `8.3.4` maka versi composer yang dipilih adalah `2.7.2` merupakan versi terbaru composer saat ini. Pada halaman unduh composer, pilih pada versi tersebut untuk mulai mengunduh.

​	<img style="display: block; margin: 0;" src="D:/repository/delcom-local-server-guide/php-manager/assets/5.jpg" />

- Setelah selesai mengunduh composer berupa file `composer.phar`. Selanjutnya pindahkan file composer tersebut ke lokasi PHP yang telah diunduh sebelumnya. Dalam kasus ini menggunakan PHP versi `8.3.4` yang berada pada lokasi `D:/local-server/bundles/php/php-8.3.4`.

​	<img style="display: block; margin: 0;" src="D:/repository/delcom-local-server-guide/php-manager/assets/6.jpg" />

- Buka windows terminal pada lokasi PHP tersebut. Selanjutnya tuliskan perintah `php composer.phar --version` jika berhasil maka akan tampil versi dari composer yang telah di-instal sebelumnya. Dalam kasus ini menggunakan composer versi `2.7.2`.

​	<img style="display: block; margin: 0;" src="assets/10.jpg" />