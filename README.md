# FishImageDetection-SVM

Mini Projek Tugas Akhir Mata Kuliah Machine Laerning, berfungsi untuk mendeteksi objek ikan dalam sebuah gambar

## Introduction

Mini project Machine Learning ini adalah tentang pembuatan pendeteksian suatu objek yang sebelumnya telah didefinisikan dalam sebuah citra. Objek yang akan dideteksi dalam penelitian ini adalah ikan. Pendeteksian objek mengekstraksi ciri dari objek dan bukan objek/background, serta proses pelatihan (learning) menggunakan Support Vector Machine (SVM) untuk melatih data yang telah diekstrak yang selanjutnya dilakukan proses klasifikasi antara objek dan bukan objek. 

## Tools Used
1. SVM
2. OCR
3. Pyhton
4. Spyder Anaconda

## Support Vector Machine (SVM)

Support vector machine (SVM) adalah suatu teknik untuk melakukan prediksi, baik dalam kasus klasifikasi maupun regresi. SVM berada dalam satu kelas dengan Artificial Neural Network (ANN) dalam hal fungsi dan kondisi permasalahan yang bisa diselesaikan. Keduanya masuk dalam kelas supervised learning. 

## Optical Character Recoginition (OCR)

Optical Character Recognition (OCR) adalah aplikasi yang berfungsi untuk men scan gambar pada image dan dijadikan text, dan aplikasi ini juga bisa menjadi support /aplikasi tambahan untuk scanner. Dengan adanya OCR, Image yang bertulisan tangan, tulisan mesin ketik atau computer text, dapat dimanipulasi. Text yang discan dengan OCR dapat dicari kata per kata atau per kalimat. Dan setiap text dapat dimanipulasi, diganti, atau diberikan barcode.

## Process Step

Tahapan Proses
1. Melatih data
>> Pertama – tama data yang telah kita kumpulkan, yaitu dataset berupa gambar ikan kita sesuaikan ke resolusi yang sama ke ukuran 80x200. Data yang ada berupa 273 yaitu ikan dan 115 bukan ikan. File data ada di folder “datalatih/ikan/TrainImage”

2. Mekstrak ciri ikan
>> Kedua kita mengekstrasi ciri yaitu dengan mengubah gambar menjadi grayscale (hitam putih). Ciri ekstrasi kita gunakan dengan OCR. Lalu akan dideteksi dengan bantuan SVM untuk pengenalan pola klasifikasian ikannya 

3. Pendeteksian Pola
>> Ketiga, SVM ini berfungsi sebagai algoritma yang digunakan untuk pengklasifikasikan antara objek citra masukan dan citra dalam template. 


## Details

Untuk menjalankan cukup jalankan <b>start.py<b>
