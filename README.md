# Tugas Kecil 2 Strategi Algoritma
## Author
   Bariza Haqi (13520018)

## Deskripsi Singkat
   Convex adalah Himpunan titik pada bidang planar yang jika untuk sembarang dua titik
   pada bidang tersebut (misal p dan q), seluruh segmen garis yang berakhir di p dan
   q berada pada himpunan tersebut. Convex hull dari himpunan titik S adalah himpunan convex terkecil
   (convex polygon) yang mengandung S.Terdapat salah satu cara untuk menemukan convex hull yaitu 
   dengan menggunakan Algoritma divide and conquer.
   Program ini dibuat dengan algoritma divide and conquer untuk menemukan convex hull pada sebuah dataset. 
   Fitur yang tersedia dalam Program ini adalah menemukan convex hull dari sebuah dataset menggunakan algoritma 
   divide and conquer dengan memperlihatkan convex hull dari dua atribut sebuah dataset.

## Instalasi
	1. Pastikan python, pip, math, pandas,numpy, dan scikit-learn sudah terinstall (direkomendasikan menggunakan versi terbaru)
	2. Jupyter Notebook (Untuk menjalankan program)
	3. Direkomendasikan menggunakan Windows OS

## Penggunaan

### Melalui Jupyter Notebook
	1. Buka file MyConvexHull pada folder src melalui Jupyter Notebook
	2. Untuk memilih dataset lain, ganti dataset pada variabel data
	3. Untuk memilih atribut lain, ganti angka 0 dan 1 pada bucket.iloc di variabel bucket dengan nomor urutan atribut yang dipilih dikurangi satu. 
	4. Program ini hanya dapat berjalan maksimal pada dataset 3 class, untuk dataset yang lebih dari 3 class tambahkan warna terlebih dahulu pada list colors hingga sebanyak class pada dataset
	5. Tekan tombol eksekusi dari setiap sel dimulai dari sel teratas sampai ke bawah untuk menjalankan program