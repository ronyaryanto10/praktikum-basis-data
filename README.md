
# Praktikum 3
```
1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 
2. Hapus satu record dat pada tabel dosen yang telah dirjuk pada tabel mahasiswa. 
3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT. 
4. Lakukan perubahan data pada tabel dosen (kd_ds). 
5. Lakukan penghapusan data pada tabel dosen, 
6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL 
7. Lakukan penghapusan data pada tabel dosen.
```

1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 
![pc pem](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/f6aac358-f264-4766-9819-ff2f39bb4efe)

![pc 1](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/4c6866f4-86ab-4d15-a4e0-f9bc2cfebcca)

2. Hapus satu record dat pada tabel dosen yang telah dirjuk pada tabel mahasiswa.
![pc 2](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/071b243c-46a3-4c9f-81ac-b28997e458e4)

3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT.

![pc 3](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/bb65c0b6-85a3-413e-accd-0ee5d29d6035)

4. Lakukan perubahan data pada tabel dosen (kd_ds). 

![pc 4](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/3956ca26-1b72-4f73-aec5-a95c21c74f35)

5. Lakukan penghapusan data pada tabel dosen.

![pc 5](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/54e8642a-6890-4c39-b725-60daa1ebf6b3)


6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL

![pc 6](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/bcf88342-b196-4309-b759-a5f735cfc99b)

7. Lakukan penghapusan data pada tabel dosen.

![pc 5](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/bddc4797-18da-4b1c-a098-34fcdaf40692)



Evaluasi dan pertanyaan.

1. Apa bedanya pengguna RESTRICT dan CASCADE.?

Penggunaan RESTRICT dan CASCADE adalah dua jenis aturan referential integrity (keutuhan
referensial) yang dapat diterapkan pada kunci asing (foreign key) di basis data relasional.
RESTRICT berarti bahwa ketika ada sebuah baris data di tabel induk (parent table) yang ingin dihapus 
atau diubah, maka sistem basis data akan memeriksa apakah ada baris data di tabel anak (child table) 
yang masih merujuk ke baris data tersebut. Jika ada, maka sistem basis data akan mencegah 
penghapusan atau perubahan data pada baris data di tabel induk yang berdampak pada baris data di 
tabel anak yang masih merujuk ke baris data tersebut.
Sementara itu, CASCADE adalah sebuah baris data di tabel induk dihapus atau diubah, maka sistem 
basis data akan secara otomatis menghapus atau mengubah baris data di tabel anak yang merujuk ke 
baris data yang dihapus atau diubah tersebut.

2. Berikan kesimpulan 

RESTRICT dan CASCADE adalah aturan refential intrgrity Yang dapat diterapkan pada kunci asing yang 
basis data relasional. RESTRICT mencegah penghapusan atau perubahan data pada tabel induk yang 
berdampak pada tabel anak yang masih merujuk ke data yang di hapus atau di ubah. Sementara 
CASCADE dengan secara otomatis menghapus atau mengubah data pada tabel anak yang merujuk ke 
data yang di apus atau di ubah pada tabel induk. Kedua aturan tersebut memiliki kelebihan dan 
kekurangan msing-masing dan harus dipilih secara bijak sesuai dengan kebutuhan dan konteks 
penggunaannya agar dapat memastikan keutuhan data didalam system basis data
