# Computer Vision Project Progress Report (25%)

**Project Name**: Prediksi Kondisi Cuaca Berdasarkan Citra Langit Menggunakan YOLOv8
**Student Name**: Wiwin Sigalingging 

**Course/Institution**: Computer Vision/Politeknik Caltex Riau  

## Latar Belakang
Dalam perkembangan teknologi komputer modern, computer vision telah menjadi salah satu bidang yang banyak dimanfaatkan untuk mendukung otomatisasi dalam berbagai sektor kehidupan. Salah satu implementasinya adalah dalam prediksi kondisi cuaca berbasis citra langit. Proyek Prediksi Cuaca ini bertujuan untuk mengidentifikasi kondisi cuaca seperti cerah, mendung, atau hujan secara otomatis menggunakan algoritma YOLOv8, sehingga dapat memberikan alternatif yang efisien, cepat, dan terjangkau dibandingkan metode tradisional yang menggunakan sensor atmosfer atau citra satelit.

## Perumusan Masalah
 Merancang dan membangun sistem berbasis computer vision yang mampu mengklasifikasikan kondisi cuaca berdasarkan citra langit secara akurat dan efisien

## Batasan Masalah
- Kondisi cuaca yang dikenali:
    a) Cerah
    b) Hujan
    c) Mendung
   

- Input berupa gambar citra langit
- Dataset berjumlah ±768 gambar per kategori
- Menggunakan Python
  
## Tujuan
- Membangun model YOLOv8 untuk mendeteksi dan mengklasifikasikan kondisi cuaca berdasarkan citra langit.
- Mengevaluasi performa model YOLOv8 dalam memprediksi cuaca dengan data citra.

## Manfaat
- Membantu memprediksi apakah cuaca akan cerah, berawan, atau hujan hanya dari foto langit.

## Target Sistem
- Mengklasifikasikan kondisi cuaca ke 4 kelas: shine, rainy dan cloudy.
- Mencapai akurasi klasifikasi ≥ 80%
- Menggunakan dataset Kaggle
- Antarmuka sederhana untuk input dan output hasil

## Tools & Teknologi
- Bahasa Pemrograman: Python
- Object Detection: YOLOv8
- Dataset: Kaggle https://www.kaggle.com/datasets/abhay06102003/weather-recognizer-with-cnn
