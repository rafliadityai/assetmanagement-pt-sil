# Framework CodeIgniter 4

## Apa Itu CodeIgniter?

CodeIgniter adalah sebuah framework web full-stack berbasis PHP yang ringan, cepat, fleksibel, dan aman.
Informasi lebih lanjut dapat ditemukan di [situs resmi](http://codeigniter.com).

Repository ini berisi versi distribusi dari framework ini,
termasuk panduan pengguna. Ini telah dibangun dari
[repositori pengembangan](https://github.com/codeigniter4/CodeIgniter4).

Informasi lebih lanjut tentang rencana untuk versi 4 dapat ditemukan dalam [pengumuman](http://forum.codeigniter.com/thread-62615.html) di forum.

Panduan pengguna yang sesuai dengan versi framework ini dapat ditemukan
[di sini](https://codeigniter4.github.io/userguide/).

## Perubahan Penting dengan index.php

`index.php` tidak lagi berada di akar proyek! Itu telah dipindahkan ke dalam folder _public_,
untuk keamanan yang lebih baik dan pemisahan komponen.

Ini berarti Anda harus mengkonfigurasi server web Anda untuk "menunjuk" ke folder _public_ proyek Anda, dan
bukan ke akar proyek. Praktik yang lebih baik adalah mengkonfigurasi virtual host untuk menunjuk ke sana. Praktik yang kurang baik adalah mengarahkan server web Anda ke akar proyek dan berharap memasukkan _public/..._, karena logika Anda dan kerangka kerja lainnya akan terekspos.

**Tolong** baca panduan pengguna untuk penjelasan yang lebih baik tentang bagaimana CI4 bekerja!

## Pengelolaan Repository

Kami menggunakan isu GitHub di repositori utama kami, untuk melacak **BUG** dan melacak paket pekerjaan **DEVELOPMENT** yang disetujui.
Kami menggunakan [forum](http://forum.codeigniter.com) kami untuk memberikan DUKUNGAN dan untuk mendiskusikan
PERMINTAAN FITUR.

Repository ini adalah yang "distribusi", dibangun oleh skrip persiapan rilis kami.
Masalah dengan ini dapat diajukan di forum kami, atau sebagai masalah di repositori utama.

## Berkontribusi

Kami menyambut kontribusi dari komunitas.

Silakan baca bagian [_Berkontribusi ke CodeIgniter_](https://github.com/codeigniter4/CodeIgniter4/blob/develop/CONTRIBUTING.md) di repositori pengembangan.

## Persyaratan Server

Versi PHP 7.4 atau lebih tinggi diperlukan, dengan ekstensi berikut terpasang:

- [intl](http://php.net/manual/en/intl.requirements.php)
- [libcurl](http://php.net/manual/en/curl.requirements.php) jika Anda berencana menggunakan perpustakaan HTTP\CURLRequest

Selain itu, pastikan bahwa ekstensi berikut diaktifkan di PHP Anda:

- json (diaktifkan secara default - jangan matikan)
- [mbstring](http://php.net/manual/en/mbstring.installation.php)
- [mysqlnd](http://php.net/manual/en/mysqlnd.install.php)
- xml (diaktifkan secara default - jangan matikan)
