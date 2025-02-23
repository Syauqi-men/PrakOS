**1** Langkah-langkah instalasi Ubuntu:

-  Pastikan Pc/Laptop terhubung internet.

-  Download ISO file Ubuntu pada situs resmi ubuntu (https://ubuntu.com/download/desktop).

-  Install Oracle virtualbox dari website resminya (https://www.virtualbox.org/).

-  Buka VirtualBox, Klik new untuk membuat Virtual machine, berikan nama, pilih ISO file Ubuntu  yang sudah diinstal dan pilih type OS yang benar.

- Buat username, passwowrd dan hostname yang akan digunakan untuk login ke Ubuntu nanti

- Atur dengan kebutuhan sistem:
  ~ CPU : 2 core
  ~ RAM : 4096 mb
  ~ HDD : 25 GB dengan partisi:
     /: 20 GB
     /storage: 5 GB
     swap: 1,5 GB

- Tekan finish dan tungggu beberapa menit.

- Jika sudah selesai, masukkan username dan password untuk masuk ke Ubuntu.

  #kesimpulan:
  Ubuntu memiliki GUI yang user friendly sehingga cocok untuk pemula.


**2** Perbedaan Debian 11 dan Debian 12:

| ASPEK                | DEBIAN 11 (BULLSEYE) | DEBIAN 12 (BOOKWORM)  |
|----------------------|----------------------|-----------------------|
| Versi kernel         | Kernel 5.10          | Kernel 6.1            |
| Performa             | Stabil dan handal    | Optimalisasi lebih lanjut |
| systemd              | Versi sebelumnya     | Diperbarui dengan fitur-fitur terbaru |
| Perbedaan paket      | LibreOffice 7.0, GNOME 3.38, Python 3.9 | LibreOffice 7.4, GNOME 43, python 3.11 |
| keamanan             | Opsional             | Diaktifkan secara default |

#kesimpulan:
Debian 12 (Bookworm) lebih unggul karena dukungan perangkat keras yang lebih luas, peningkatan keamanan serta versi software yang lebih baru.


**3** Cek Environment menggunakan CPU-Z:

```bash
lscpus
```

**4**. Cara lain untuk cari info list apk:
- Cek apk yang terinstall melalui manajer paket:
```bash
dpkg --list
```

- Cek storage: 
```bash
df -h
```
- Cek RAM:
```bash
free -h
```
- mengecek informasi hardware:
```bash
hardinfo
```
- Cek aplikasi yang tersedia:
    - Snap list: 
    ```bash
    snap list
    ```
#kesimpulan:
masing-masing mempunyai fungsi yang berbeda, sehingga harus menggunakan sesuai dengan kebutuhan. 

  
