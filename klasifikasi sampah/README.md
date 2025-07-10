# Proyek Klasifikasi Sampah dengan CNN

Proyek ini menggunakan **Convolutional Neural Network (CNN)** untuk mengklasifikasikan gambar sampah ke dalam berbagai kategori seperti plastik, kaca, metal, dan lainnya. Dataset yang digunakan berasal dari [Garbage Dataset](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2).

## Fitur Proyek
- **Preprocessing Data**: Memuat dan menyiapkan dataset.
- **Model CNN**: Membangun dan melatih model deep learning menggunakan TensorFlow/Keras.
- **Evaluasi Model**: Mengukur akurasi training, validasi, dan test.
- **Export Model**: Menyimpan model yang telah dilatih untuk digunakan lebih lanjut.

## Cara Penggunaan
1. **Clone repository ini** atau buat notebook baru di Google Colab.
2. **Unduh dataset** dan pastikan file berada di direktori yang benar.
3. **Jalankan notebook** dengan urutan berikut:
   - Preprocessing dataset
   - Melatih CNN
   - Evaluasi hasil
   - Menyimpan model

## Cara Mengunduh Folder di Colab
Jika kamu ingin mengunduh folder hasil training di Google Colab, gunakan perintah berikut:
```python
!zip -r /content/model.zip /content/nama_folder
from google.colab import files
files.download("/content/model.zip")