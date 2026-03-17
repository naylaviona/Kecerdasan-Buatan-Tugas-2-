KNN vs Decision Tree Classification - Iris Dataset

# Deskripsi
Project ini merupakan implementasi algoritma K-Nearest Neighbors (KNN) dan Decision Tree untuk melakukan klasifikasi pada dataset Iris.
Model digunakan untuk membandingkan performa kedua algoritma dalam hal akurasi dan penggunaan memori.

# Dataset
Dataset yang digunakan adalah Iris Dataset dengan beberapa fitur utama:
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target:
0 → Setosa
1 → Versicolor
2 → Virginica

# Tools & Library
Project ini menggunakan:
Python
Google Colab

Library:
numpy
scikit-learn
pickle

# Konsep yang Digunakan
1. K-Nearest Neighbors (KNN)
KNN merupakan algoritma Non-Parametric yang bekerja dengan mencari K tetangga terdekat dari suatu data.
Jika nilai K terlalu kecil (misalnya K=1):
* Sensitif terhadap noise
* Mudah terpengaruh data yang tidak normal
* Berpotensi overfitting

2. Decision Tree
Decision Tree merupakan algoritma yang menggunakan struktur pohon untuk membuat keputusan berdasarkan aturan (if-else).
Kelebihan:
* Lebih efisien dalam memori
* Proses testing lebih cepat

# Analisis Memori
KNN:
* Menyimpan seluruh data training
* Membutuhkan memori lebih besar

Decision Tree:
* Hanya menyimpan struktur pohon
* Lebih hemat memori

# Hasil
Model menghasilkan perbandingan:
* Akurasi KNN
* Akurasi Decision Tree
* Ukuran memori masing-masing model

# Cara Menjalankan
1. Buka file .ipynb di Google Colab
2. Jalankan semua cell
3. Hasil akan menampilkan:
4. Akurasi model
5. Perbandingan ukuran memori

# Repository
Link repository GitHub:
https://github.com/naylaviona/Kecerdasan-BuatanTugas-2

Nayla Viona Azahra
