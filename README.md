# Image Classification with CIFAR-10

Proyek ini bertujuan untuk membangun sistem klasifikasi gambar menggunakan dataset CIFAR-10. Model dikembangkan menggunakan arsitektur deep learning berbasis **TensorFlow dan Keras Sequential API**, dengan **penambahan layer Conv2D dan MaxPooling2D secara eksplisit**, sesuai dengan standar pembelajaran pada program Machine Learning Engineer - Dicoding x DBS Foundation (Cohort University 2025).

## Dataset

Dataset yang digunakan adalah [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), yang terdiri dari 60.000 gambar RGB berukuran 32x32 piksel yang terbagi ke dalam 10 kelas berbeda:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Data dibagi menjadi 3 bagian: **train set, validation set, dan test set**, guna mendukung proses pelatihan dan evaluasi model yang efektif.

## Arsitektur Model

Model dibangun menggunakan arsitektur **Keras Sequential** yang terdiri dari:
- Beberapa layer Conv2D dan MaxPooling2D
- Flatten dan Dense layer
- Output layer dengan softmax activation untuk klasifikasi 10 kelas

Model ini dilatih menggunakan **loss function `categorical_crossentropy`** dan **optimizer `adam`**.

## Cara Menjalankan Proyek

1. Pastikan Anda telah menginstal seluruh dependensi dari file `requirements.txt`.
2. Buka file `Proyek_Klasifikasi_Gambar.ipynb` di Jupyter Notebook atau Google Colab.
3. Jalankan seluruh sel secara berurutan untuk:
   - Memuat dan memproses dataset
   - Melatih model klasifikasi
   - Mengevaluasi akurasi model pada validation dan test set
   - Menampilkan confusion matrix
   - Menyimpan model dalam format `.h5` dan `.json`, atau mengekspornya ke TensorFlow.js (opsional)

## Struktur Proyek

- `Proyek_Klasifikasi_Gambar.ipynb` — Notebook utama berisi seluruh proses klasifikasi gambar
- `requirements.txt` — Daftar dependensi Python untuk menjalankan proyek
- `README.md` — Dokumentasi dan petunjuk penggunaan proyek

## Persyaratan Sistem

Library utama yang digunakan:
- TensorFlow 2.14.0
- scikit-learn 1.2.2
- matplotlib 3.7.1
- seaborn 0.12.2
- numpy 1.24.3

## Kontributor

- Renaldi Endrawan
