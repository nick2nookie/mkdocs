# Chapter 2: Development environment setup

Tergantung pada penggunaan masing-masing, ada beberapa cara untuk menginstal Odoo. Tutorial ini kita akan mengikuti penginstalan sumber ( menggunakan Source Code ), yang paling cocok untuk pengembangan dev. Odoo.

Di sepanjang dokumen ini, kita berasumsi bahwa Anda menginstal lingkungan pengembangan Anda di laptop Linux ubuntu yang sudah terinstal dan mutakhir. Jika bukan itu marilah  kita gunakan Windows(seperyi penulis web ini) atau bisa juga menggunakan Mac OS tinggal disesuaikan saja di panduan instalasi odoo, tergantung pada OS yang kita gunakan. 

Langkah-langkahnya pada dasarnya tetap sama.

*1* Siapkan Git

Instal dan konfigurasikan Git

Langkah pertama dari proses instalasi adalah menginstal sistem kontrol versi Git karena kode sumber Odoo dikelola di GitHub .
```bash title="install GIT"
 $ sudo apt install git
```

``` bash title="Tips"
 $ git --version # (1)
```

1.  :man_raising_hand: Periksa apakah Git terinstal dengan mencoba mencetak versi Git dengan perintah ini.

