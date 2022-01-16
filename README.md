# Project-Machine-Learning-Diabetic-Retinopathy
# Diabetic Retinopathy Project
# Tugas_Besar_023_043
- Autors
1. Muhammad Marlianur (201810370311023)
2. Ernowo Gordon Unus (201810370311043)
# Image Retrieval Diabetic Retinopaty Menggunakan MobileNet

# Overview Jurnal Referensi
1. Jurnal Referensi

- Jurnal referensi pada projek ini berjudul Deep Learning untuk Klasifikasi Diabetic Retinopathy menggunakan Model EfficientNet
- Link Jurnal : http://dx.doi.org/10.26760/elkomika.v8i3.693
- Diabetic Retinopathy merupakan penyakit yang dapat mengakibatkan kebutaan mata yang disebabkan oleh adanya komplikasi penyakit diabetes melitus. Oleh karena itu mendeteksi secara dini sangat diperlukan untuk mencegah bertambah parahnya penyakit tersebut. Penelitian ini merancang sebuah sistem yang dapat mendeteksi Diabetic Retinopathy berbasis Deep Learning dengan menggunakan Convolutional Neural Network (CNN). EfficientNet model digunakan untuk melatih dataset yang telah di pre-prosesing sebelumnya. Hasil dari penelitian tersebut didapatkan akurasi sebesar 79.8% yang dapat mengklasifikasi 5 level penyakit Diabetic Retinopathy. 

2. Dataset yang digunakan pada Jurnal

- Data yang digunakan pada referensi tersebut merupakan data dari kaggle tentang Diabetic Retinopaty
https://www.kaggle.com/c/aptos2019-blindness-detection/data

3. Hasil Pembuatan Paper Project
- Link Drive Paper: https://drive.google.com/file/d/1nz7wOFJRf7pa4G6wDnvs9MH1dlqnbnBV/view?usp=sharing




# Hasil
- Link Program : 

- Hasil deploy program (Program tidak bisa di Deploy ke Heroku karena terbatasnya kapasitas yang ada di Heroku)
- Tampilan depan




![photo_2021-12-28_15-21-49](https://user-images.githubusercontent.com/92302616/147545463-be7121d6-dca6-461a-ae3d-20825d7321c9.jpg)
![photo_2021-12-28_15-21-49 (2)](https://user-images.githubusercontent.com/92302616/147545469-039d9bf3-1809-495a-8f12-c098b21bdfbb.jpg)




- Tampilan setelah penginputan gambar





![photo_2021-12-28_15-21-20](https://user-images.githubusercontent.com/92302616/147545689-8516a725-e21e-42ba-bee5-3a66fd0c2be0.jpg)
![photo_2021-12-28_15-21-20 (2)](https://user-images.githubusercontent.com/92302616/147545699-3a491585-05cc-44fd-be69-9fdc44be9428.jpg)
![photo_2021-12-28_15-21-21](https://user-images.githubusercontent.com/92302616/147545712-e6e941b9-80b9-4e39-8507-00b3664410b4.jpg)
![photo_2021-12-28_15-21-19](https://user-images.githubusercontent.com/92302616/147545720-dfec27a7-6ecf-467c-9b2b-408dfd1e71e5.jpg)
![photo_2021-12-28_15-21-19 (2)](https://user-images.githubusercontent.com/92302616/147545741-10122d7c-c337-4e67-81cb-8a694367e95b.jpg)


- Catatan :
1. Pada uji coba deploy didapatkan hasil bahwa dari tiga skenario model terlihat Model CNN dan Resnet50 memberikan akurasi tertinggi pada kelas NO DR masing-masing 100% dan 71%. Sedangkan pada model MobileNet memiliki akurasi tertinggi sekitar 99% pada kelas Moderate.
2. Deploy ini memiliki kekurangan pada tampilan hasil gambar. Gambar yang ditampilkan saat result masih sering gagal muncul, tetapi pada saat uji coba pertama hal tersebut masih bisa di atasi.
