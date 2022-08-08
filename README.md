###### Nama      : Achmad Setiawan Andyatama
###### Kelas     : XII-RPL 1
###### No. Absen : 05

# Modul-4
# View Blade Template

# Tugas 
Buatlah View untuk Project Anda dan Buatlah Layout dengan App Template Blade untuk Projek Anda!!!

1. Buatlah Folder Layout didalam resources/views/Layout setelah itu buatlah juga file app.blade.php sebagai template viewnya

![image](https://user-images.githubusercontent.com/109930523/183356831-c1f12c8a-f867-439e-b7fd-99658426a6ce.png)

2. Setelah membuat filenya isi filenya seperti berikut agar bisa membuat tampilan sederhana yang bagus

![image](https://user-images.githubusercontent.com/109930523/183357475-62c35316-ba05-4142-9b0b-f65dccb4e49b.png)

Saya mengambil css dan javascriptnya di Boostrap untuk mempercantik halamannya

3. Setelah Mengisi file App. kita hanya perlu memanggilnya di file home dan index menggunakan

```
@extends('Layout.app')
```
dan isi file home menggunakan code berikut

![image](https://user-images.githubusercontent.com/109930523/183358654-ab5634f4-75e7-4fdb-aa45-b99c1a01abf6.png)

fungsi dari code diatas adalah untuk memanggil template view yang sudah kita buat di file app.blade.php dan code diatas akan membuat tampilan seperti berikut

![image](https://user-images.githubusercontent.com/109930523/183359944-9e826c43-4b09-40b2-ab88-61651352b7f6.png)

4. Lalu Isi file index sama seperti file home, hanya saja tidak isinya berbeda dengan file home karena file index hanya untuk nama kategorinya saja

![image](https://user-images.githubusercontent.com/109930523/183359712-51bacd39-7c57-42a9-adb9-6f3a7454c74f.png)

Hasilnya akan jadi seperti ini 

![image](https://user-images.githubusercontent.com/109930523/183359868-63343ef7-e457-4323-9d2d-e23333e47b0d.png)



