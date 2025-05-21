# Image Classification with CIFAR-10

Proyek ini bertujuan untuk melakukan klasifikasi gambar menggunakan dataset CIFAR-10. Model deep learning dibangun menggunakan TensorFlow dan MobileNetV2 sebagai arsitektur dasar.

## Dataset

Dataset yang digunakan adalah [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), yang terdiri dari 60.000 gambar berwarna 32x32 piksel dalam 10 kelas berbeda, termasuk pesawat, mobil, burung, kucing, rusa, anjing, katak, kuda, kapal, dan truk.

## Persyaratan

Pastikan Anda telah menginstal semua dependensi yang diperlukan. Semua dependensi tercantum dalam file `requirements.txt`.

## Instalasi

Jalankan perintah berikut untuk menginstal semua dependensi:

```bash
pip install -r requirements.txt
```

## Cara Menggunakan

1. Buka file notebook `Proyek_Klasifikasi_Gambar.ipynb` menggunakan Jupyter Notebook atau Google Colab.
2. Jalankan sel-sel secara berurutan untuk:

   * Memuat dan memproses data CIFAR-10.
   * Melatih model klasifikasi menggunakan arsitektur MobileNetV2.
   * Mengevaluasi performa model.
   * Menyimpan model dalam format `.h5` dan `.json`, atau mengekspornya ke TensorFlow\.js.

## Struktur Proyek

* `Proyek_Klasifikasi_Gambar.ipynb`: Notebook utama yang berisi keseluruhan pipeline klasifikasi gambar.
* `requirements.txt`: Daftar dependensi yang digunakan dalam proyek.
* `README.md`: Dokumentasi proyek ini.

## Kontributor

* Renaldi Endrawan
