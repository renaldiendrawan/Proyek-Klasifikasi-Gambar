# Image Classification with CIFAR-10

Proyek ini membangun sistem klasifikasi gambar menggunakan dataset **CIFAR-10**, dengan model deep learning berbasis **TensorFlow** dan **Keras Sequential API**. Arsitektur model mencakup beberapa layer **Conv2D** dan **MaxPooling2D**, sesuai standar program Machine Learning Engineer - Dicoding x DBS Foundation (Cohort University 2025).

## Dataset

Dataset yang digunakan adalah [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), yang terdiri dari 60.000 gambar RGB berukuran 32x32 piksel dalam 10 kelas:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

Data dibagi menjadi tiga bagian:

* **Training set**: 45.000 gambar
* **Validation set**: 5.000 gambar
* **Test set**: 10.000 gambar

## Arsitektur Model

Model dikembangkan menggunakan **Keras Sequential API** dengan komponen berikut:

* 3 blok Conv2D (ReLU) + MaxPooling2D
* Flatten layer
* Dense layer (512 unit, ReLU)
* Output layer (Dense 10 unit, softmax)

Model dikompilasi menggunakan:

* **Loss function**: `categorical_crossentropy`
* **Optimizer**: `adam`
* **Metrics**: `accuracy`

## Pelatihan dan Evaluasi

Notebook mencakup:

* Visualisasi data (jumlah data per kelas)
* Preprocessing: normalisasi, one-hot encoding
* Pelatihan model dengan `ModelCheckpoint` dan `EarlyStopping`
* Evaluasi akurasi pada validation dan test set
* Plot confusion matrix untuk hasil klasifikasi
* Penyimpanan model dalam `.h5` dan `.json`

## Cara Menjalankan

1. Instal dependensi dengan:

   ```bash
   pip install -r requirements.txt
   ```
2. Jalankan `Proyek_Klasifikasi_Gambar.ipynb` di Jupyter Notebook atau Google Colab.
3. Eksekusi sel notebook secara berurutan.

## Struktur Proyek

* `Proyek_Klasifikasi_Gambar.ipynb`: Notebook utama proyek
* `requirements.txt`: Daftar library yang diperlukan
* `README.md`: Dokumentasi proyek

## Persyaratan Sistem

Library utama:

* TensorFlow 2.14.0
* scikit-learn 1.2.2
* matplotlib 3.7.1
* seaborn 0.12.2
* numpy 1.24.3

## Kontributor

* Renaldi Endrawan
