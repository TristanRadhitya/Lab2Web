|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|Tristan Radhitya Rama|312310426|TI.23.A4|Pemograman Web|

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
   
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![Screenshot 2024-10-09 054803](https://github.com/user-attachments/assets/215a173e-c417-4547-89c1-2d7980cd6e9d)
disini saya mengubah warna dan hover dalam bagian nav nya menjadi biru muda, lalu mengubah warna link informasi selengkapnya menjadi berwarna kuning

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

perbedaannya kalau hanya menuliskan h1 saja tanpa '#' itu tandanya elemen h1 tsb tidak diberikan id, contoh :
![Screenshot 2024-10-09 061733](https://github.com/user-attachments/assets/50f2579d-37cb-468a-88aa-d6e9f19a3bd7)
semua tulisan h1 akan berwarna biru muda, tapi kalau tulisan #intro yang akan berwarna ungu karna gaya yang lebih spesifik dari #intro h1

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

yang akan muncul dalam hasilnya adalah inline CSS karena inline CSS mempunyai prioritas tinggi diantara internal atau eksternal, contoh:
![Screenshot 2024-10-09 064656](https://github.com/user-attachments/assets/f6e71e0e-f119-4ca3-9cc4-ce9eff786307)

CSS nya
![Screenshot 2024-10-09 064033](https://github.com/user-attachments/assets/fd1662c6-1965-4f65-8f67-089d0b85f47c)

maka hasil yang keluar adalah
![Screenshot 2024-10-09 063908](https://github.com/user-attachments/assets/b315a4b1-58ad-4a85-bf74-44b4fab3e142)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Ketika HTML mempunyai sebuah 2 deklarasi seperti Id dan Class, yang akan dimunculkan pada hasilnya adalah Id karena spesfisitas Id lebih tinggi dibanding Class, contoh
![Screenshot 2024-10-09 065220](https://github.com/user-attachments/assets/407c3ad5-8d38-420b-b5a4-d3ebf553b31d)

ini css nya
![Screenshot 2024-10-09 065250](https://github.com/user-attachments/assets/e9a92e3a-018d-48db-8109-92557a1d02ff)

hasil akhirnya
![Screenshot 2024-10-09 065312](https://github.com/user-attachments/assets/58ae5ff3-43d2-42d4-8ebb-0dd2549b0e2d)
