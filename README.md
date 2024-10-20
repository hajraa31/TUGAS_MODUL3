﻿# TUGAS_MODUL3
SOAL 1

Program ini dalam bahasa Go menghitung permutasi dan kombinasi dari dua set bilangan. Program menggunakan fungsi rekursif untuk faktorial, kemudian menghitung permutasi \((P(n, r))\) dan kombinasi \((C(n, r))\) berdasarkan input pengguna. Jika input valid (nilai pertama ≥ nilai kedua untuk kedua pasangan), hasil permutasi dan kombinasi ditampilkan. Jika tidak, program menampilkan "Invalid input".

SOAL 2

Program ini dalam bahasa Go melakukan komposisi fungsi pada tiga operasi matematika dasar: kuadrat, pengurangan, dan penambahan. Program terdiri dari beberapa fungsi: `f(x)` (mengkuadratkan nilai), `g(x)` (mengurangi 2), dan `h(x)` (menambah 1). Ada tiga fungsi komposisi:

- **`fogoh(x)`**: menghitung \( f(g(h(x))) \).
- **`gohof(x)`**: menghitung \( g(h(f(x))) \).
- **`hofog(x)`**: menghitung \( h(f(g(x))) \).

Program menerima tiga input bilangan bulat dan menampilkan hasil dari ketiga komposisi fungsi tersebut untuk masing-masing input.

SOAL 3

Program ini dalam bahasa Go mengecek apakah suatu titik berada di dalam dua lingkaran. Program menggunakan fungsi:

- **`jarak(a, b, c, d)`**: menghitung jarak antara dua titik \((a, b)\) dan \((c, d)\) menggunakan rumus jarak Euclidean.
- **`didalam(cx, cy, r, x, y)`**: mengecek apakah titik \((x, y)\) berada di dalam lingkaran dengan pusat \((cx, cy)\) dan jari-jari \(r\).

Program membaca koordinat dan jari-jari dua lingkaran, serta koordinat titik yang diuji. Kemudian, program menentukan apakah titik tersebut berada di dalam lingkaran pertama, kedua, atau keduanya, dan menampilkan hasilnya.
