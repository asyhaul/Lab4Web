# Langkah-langkah Praktikum
Buat file baru dengan nama header.php, footer.php, home.php, home.php

# Membuat Routing
Routing digunakan untuk mempermudah akses halaman web agar SEO Friendly.

Langkah awal adalah menyiapkan file utama (index.php) yang berisi routing untuk mengakses banyak
halaman.

Buat file baru dengan nama index.php

Aktivasi mod_rewrite (.htaccess)
Mod_rewrite digunakan untuk mengubah URL dari query string menjadi SEO Friendly.
Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada

configurasi httpd.conf.
Aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut,
kemudian restart Apache2.
![2023-04-02 (10)](https://user-images.githubusercontent.com/116356016/229342864-f013a591-088c-4eb7-b93c-22bbfeee4f7e.png)
Langkah berikutnya adalah membuat file .htaccess
![2023-04-02 (9)](https://user-images.githubusercontent.com/116356016/229342727-c2bb686b-4ed4-4048-b9fb-c4e13e6b89cc.png)
Cara aksesnya menjadi:

• Halaman Home ( http://localhost/lab4_php_moduler/home )
![2023-04-02 (7)](https://user-images.githubusercontent.com/116356016/229343310-d1925d66-bfad-4474-ad55-12e02c9401af.png)
• Halaman About ( http://localhost/lab4_php_moduler/about )
![2023-04-02 (8)](https://user-images.githubusercontent.com/116356016/229343293-6db92436-3ca3-4b89-8426-aa399c21130f.png)
