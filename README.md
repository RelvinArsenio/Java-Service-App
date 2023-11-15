# Java-Service-App
Aplikasi Service HP (UAS Pemrograman Menengah)

## Deskripsi

Java-Service-App adalah aplikasi service HP yang dibuat dengan Java 17 dan Netbeans 18. Aplikasi ini memungkinkan pengguna untuk melakukan pemesanan service HP dan melihat riwayat service.

## Persyaratan

Untuk menjalankan aplikasi ini, Anda memerlukan:

- Java 17 atau versi lebih baru
- Netbeans IDE
- MySQL Server atau XAMPP
- JDBC Driver

## Instalasi

Langkah-langkah untuk menginstal dan menjalankan aplikasi ini adalah sebagai berikut:

1. Clone repositori ini ke komputer Anda dengan menggunakan perintah `git clone https://github.com/RelvinArsenio/Java-Service-App.git`
2. Buka Netbeans IDE dan pilih menu File -> Open Project. Cari folder Java-Service-App yang telah Anda clone dan klik Open Project.
3. Buka MySQL Server dan buat database dengan nama `service`. Import file `database/service_hp.sql` yang ada di folder repositori ke dalam database tersebut.
4. Buka file `src/service/ConnectionDB.java` di Netbeans IDE dan ubah nilai variabel `url`, `user`, dan `password` sesuai dengan konfigurasi MySQL Server Anda.
5. Jalankan aplikasi dengan menekan tombol Run Project (F6) di Netbeans IDE.

## Lisensi

Proyek ini dilisensikan di bawah Eclipse Public License 2.0. Lihat file [LICENSE](./LICENSE) untuk detail lebih lanjut.
