# private-cloud-storage-multi-tenant_K6
Perancangan Private Cloud Storage dengan Arsitektur Multi Tenant untuk Penyediaan Layanan Penyimpanan Data
LAPORAN DOKUMENTASI PROGRESS PROYEK

IMPLEMENTASI NEXTCLOUD MULTI TENANT

Bias Seftian Saputra
2407421026
Syafiq Arkhan Fauzi
2407421017

1. Pendahuluan

Dokumentasi ini dibuat untuk menjelaskan perkembangan pekerjaan Kelompok 6 pada tahap implementasi Nextcloud. Fokus progress yang didokumentasikan adalah penggunaan Nextcloud sebagai layanan penyimpanan file dengan pemisahan akses berdasarkan tenant atau kelompok pengguna. Pengujian dilakukan pada akun Tata Usaha, Guru, dan OSIS.

Dokumen ini menjelaskan pekerjaan yang tampak pada bukti dokumentasi dan hasil pengujian yang telah dilakukan. Bagian yang belum memiliki bukti tidak dinyatakan sebagai pekerjaan yang sudah selesai.

2. Tujuan Pengerjaan

Menyiapkan lingkungan Nextcloud yang dapat digunakan untuk menyimpan dan mengelola file.

Menerapkan pemisahan akun atau tenant untuk Tata Usaha, Guru, dan OSIS.

Menguji proses login pada masing-masing tenant menggunakan sesi browser terpisah.

Memeriksa apakah file pada satu tenant dapat terlihat atau diakses oleh tenant lainnya.

3. Langkah-Langkah Implementasi dan Pengujian

3.1 Membuka halaman Nextcloud

Tahap awal dilakukan dengan membuka layanan Nextcloud melalui browser. Setelah berhasil masuk, pengguna diarahkan ke halaman utama Nextcloud. Pada halaman ini tersedia menu Files untuk melihat dan mengelola file yang tersimpan.

3.2 Membuka menu Files

Menu Files digunakan untuk melihat daftar folder dan file pada akun yang sedang aktif. Bagian ini menjadi tempat pengguna melakukan pengelolaan dokumen sesuai hak akses akun masing-masing.

3.3 Menyiapkan akun untuk setiap tenant

Selanjutnya dilakukan penyiapan akun pengguna yang mewakili masing-masing tenant, yaitu Tata Usaha, Guru, dan OSIS. Pada dokumentasi terlihat proses pengelolaan akun melalui halaman administrasi Nextcloud. Setiap akun digunakan untuk menguji akses tenant yang berbeda.

3.4 Mengatur pemisahan akses dan ruang file

Pengujian diarahkan pada pemisahan ruang penyimpanan antar-tenant. Tujuannya agar file milik Tata Usaha, Guru, dan OSIS tidak tercampur serta tidak otomatis terlihat oleh tenant lain. Pengaturan rinci seperti kuota dan izin berbagi tidak disimpulkan dari bukti yang tersedia.

3.5 Melakukan pengujian login dengan Incognito

Untuk menguji beberapa akun secara terpisah, browser dibuka menggunakan mode Incognito. Setiap sesi digunakan untuk login ke akun tenant yang berbeda. Cara ini membantu menghindari penggunaan sesi atau cookie login yang sama ketika berpindah akun.

3.6 Memeriksa halaman masing-masing tenant

Setelah login berhasil, halaman utama Nextcloud diperiksa untuk memastikan akun yang aktif sesuai dengan tenant yang diuji. Dokumentasi memperlihatkan halaman akun Tata Usaha, Guru, dan OSIS.

3.7 Menguji pemisahan file antartenant

Tahap berikutnya adalah memeriksa daftar file pada masing-masing tenant. Pemeriksaan dilakukan untuk memastikan file yang berada pada satu tenant tidak muncul pada daftar file tenant lainnya. Pada dokumentasi, pengujian secara khusus mencatat bahwa tidak ada file portofolio yang diunggah pada tenant OSIS di tenant tersebut, dan kondisi serupa juga dicatat pada tenant Guru.

5. Hasil Sementara

Nextcloud sudah dapat diakses dan halaman Files dapat digunakan untuk melihat daftar file.

Akun untuk tiga tenant yang diuji, yaitu Tata Usaha, Guru, dan OSIS, telah digunakan dalam pengujian login.

Pengujian login dilakukan menggunakan mode Incognito agar sesi antar-akun terpisah.

Pemeriksaan daftar file dilakukan pada tenant yang berbeda untuk melihat apakah terdapat file yang tercampur.

Dokumentasi mencatat bahwa file portofolio tidak muncul pada tenant OSIS dan kondisi serupa juga dicatat pada tenant Guru.

6. Kesimpulan Progress

Berdasarkan dokumentasi yang tersedia, Kelompok 6 telah mencapai tahap implementasi awal Nextcloud multi-tenant dan melakukan pengujian login serta pemeriksaan pemisahan file pada tenant Tata Usaha, Guru, dan OSIS. Hasil ini menjadi bukti progress pada sisi layanan penyimpanan dan pengelolaan file. Pengujian lanjutan masih diperlukan untuk memastikan seluruh aturan hak akses, izin berbagi, dan pemisahan data berjalan sesuai kebutuhan proyek.

7. Rencana Pekerjaan Selanjutnya

Melakukan pengujian upload file pada setiap tenant dengan file uji yang berbeda.

Memastikan file yang diunggah pada satu tenant tidak dapat dilihat oleh tenant lain tanpa izin.

Menguji hak akses pengguna, termasuk kemampuan melihat, mengunggah, mengubah, dan menghapus file.

Mendokumentasikan konfigurasi akun, folder, permission, serta hasil pengujian secara lebih rinci.

Melanjutkan tahapan proyek lain sesuai pembagian pekerjaan kelompok dan kebutuhan sistem.
