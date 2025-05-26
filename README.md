# 🍎 Klasifikasi Gambar Buah dengan CNN

Repositori ini berisi notebook klasifikasi gambar buah menggunakan model Convolutional Neural Network (CNN) yang dibangun dengan TensorFlow dan Keras. Tujuan proyek ini adalah melatih model untuk mengenali berbagai jenis buah berdasarkan gambar dan mengevaluasi performanya menggunakan data validasi.

--- 

## 📦 Dataset

Dataset diperoleh dari Kaggle:  
🔗 [Fruit-360]([https://www.kaggle.com/datasets/lakshith25pathi/bike-sharing-dataset](https://www.kaggle.com/datasets/moltean/fruits))

> Dataset berasal dari kumpulan gambar buah yang telah dipisahkan berdasarkan label masing-masing kelas. Dataset dibagi menjadi tiga bagian:
- train: Data untuk melatih model
- validation: Data untuk validasi selama pelatihan
- test: Data untuk menguji performa model

---

## 🛠️ Tools yang Digunakan

- Google Colab
- Python 3
- TensorFlow & Keras
- NumPy
- Matplotlib (untuk visualisasi hasil pelatihan)

---

## 🗂️ Struktur Folder

Submission/

├── tfjs_model/

│ ├── group1-shard1of7.bin

│ ├── group1-shard2of7.bin

│ ├── group1-shard3of7.bin

│ ├── group1-shard4of7.bin

│ ├── group1-shard5of7.bin

│ ├── group1-shard6of7.bin

│ ├── group1-shard7of7.bin

│ └── model.json/

├── tflite

│ ├── label.txt

│ ├── model.tflite

├── saved_model

│ ├── variables

│ ├── saved_model.pb

├── Notebook.ipynb

├── requirements.txt

└── README.md

---


- `train/`: Gambar buah untuk pelatihan model
- `validation/`: Gambar buah untuk validasi selama pelatihan
- `test/`: Gambar buah untuk evaluasi akhir model

---

## 🧠 Arsitektur Model CNN

Model CNN dibangun dengan arsitektur berikut:
- Beberapa lapisan Convolutional dan MaxPooling
- Lapisan Flatten untuk meratakan fitur
- Lapisan Dense (fully connected)
- Lapisan output dengan Softmax untuk klasifikasi multi-kelas

---

## 📈 Evaluasi dan Hasil

Notebook ini mencakup:
-Pelatihan model CNN selama beberapa epoch
- Visualisasi akurasi dan loss model
- Evaluasi menggunakan data uji
- Prediksi gambar baru

---

## ▶️ Menjalankan Proyek

### 1. Clone repositori:
      git clone https://github.com/Yuliana1453/Klasifikasi-Gambar.git
      cd Klasifikasi-Gambar

### 2. Install dependensi:
      pip install -r requirements.txt
> Atau jalankan langsung di Google Colab untuk memudahkan.

### 3. Jalankan Notebook:
Buka Notebook.ipynb dan jalankan setiap sel untuk melakukan pelatihan dan evaluasi model.

---

## 🧑‍💻 Kontributor

- [Yuliana1453](https://github.com/Yuliana1453)


---
