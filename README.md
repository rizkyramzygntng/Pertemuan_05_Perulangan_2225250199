\# Pertemuan 05 - Perulangan For dan While



Nama: Muhammad Rizky Ramzy Ramadhan

NIM: 2225250199

Kelas: 3E



\## Tujuan



Menggunakan `for` dan `while` untuk menyelesaikan masalah iteratif.



\## Struktur Program



```text

pertemuan-05-perulangan-2225250199/

├── README.md

├── .gitignore

├── latihan/

│   ├── 01\_tabel\_perkalian.py

│   ├── 02\_jumlah\_bilangan.py

│   ├── 03\_validasi\_input.py

│   └── 04\_hitung\_genap.py

└── kuis/

&#x20;   └── kuis2\_deret\_aritmetika.py

```



\## Cara Menjalankan



Contoh perintah:



```bash

python latihan/01\_tabel\_perkalian.py

python latihan/02\_jumlah\_bilangan.py

python latihan/03\_validasi\_input.py

python latihan/04\_hitung\_genap.py

python kuis/kuis2\_deret\_aritmetika.py

```



\## Algoritma Kuis 2



1\. Membaca suku pertama `a` dan beda `d`.

2\. Membaca banyak suku `n`.

3\. Memvalidasi `n` menggunakan `while` sampai `n` bernilai positif.

4\. Mengatur `total = 0`.

5\. Menggunakan `for` untuk menghasilkan `n` suku.

6\. Menghitung nilai setiap suku.

7\. Menambahkan setiap suku ke `total`.

8\. Menampilkan jumlah akhir.



\## Hasil Pengujian



| Test Case | Input                   | Hasil          |

| --------- | ----------------------- | -------------- |

| 1         | a = 2, d = 3, n = 5     | Jumlah = 40.00 |

| 2         | a = 10, d = -2, n = 4   | Jumlah = 28.00 |

| 3         | a = 1.5, d = 0.5, n = 3 | Jumlah = 6.00  |



\## Refleksi



Kesalahan yang perlu diperhatikan dalam perulangan adalah batas `range`, pembaruan variabel, dan posisi akumulator. Pengujian dilakukan dengan beberapa test case untuk memastikan loop berhenti dan menghasilkan nilai yang benar.



