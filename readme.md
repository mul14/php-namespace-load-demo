Silahkan jalankan file "index.php", maka output dari Profile akan keluar.

Padahal nama namespace adalah 

```
Apapun\Beda\Gak\Ngaruh\Dengan\Nama\Folder
```

Sedangkan folder-nya

```
Bukan/Models/Kok/Ini
```

Tapi tetap bisa dipanggil dan output tetap keluar tanpa error.
Ini membuktikan __struktur folder tidak ada hubungannya dengan namespace di PHP__. 

[PSR-0](https://www.php-fig.org/psr/psr-0/) dan [PSR-4](https://www.php-fig.org/psr/psr-4/) 
hanya menstandarisasi agar para programmer tidak terlalu liar 
dan tidak membingungkan programmer lain. Yang penting file tersebut di-load.

Bahasa pemrograman lain seperti C# juga begitu. Gak ngaruh dengan struktur folder fisik.
