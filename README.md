<p align="center">
  <b>© 2026 Yoga Adi Prakoso</b><br>
  <sub>Machine Learning • Data Science • Analytics</sub>
</p>

---


# 🏠 Clustering House Category – Jabodetabek

## 📌 Project Overview

Project ini bertujuan untuk melakukan segmentasi dan klasifikasi kategori rumah di wilayah Jabodetabek menggunakan pendekatan Data Science. Metode yang digunakan meliputi Exploratory Data Analysis (EDA), Principal Component Analysis (PCA), K-Means Clustering, dan Logistic Regression.

Dataset bersumber dari Kaggle:  
https://www.kaggle.com/datasets/nafisbarizki/daftar-harga-rumah-jabodetabek

---

## 🎯 Objectives

- Mengelompokkan rumah menjadi tiga kategori: **Menengah**, **Premium**, dan **Premium Atas**
- Memvisualisasikan pola data menggunakan PCA
- Membangun model klasifikasi menggunakan Logistic Regression
- Mengevaluasi performa model dengan Confusion Matrix

---

## 📊 Dataset Information

Dataset berisi informasi harga rumah di wilayah Jabodetabek dengan fitur seperti:

- Harga
- Luas tanah
- Luas bangunan
- Jumlah kamar
- Lokasi

**Source:**  
Nafis Barizki – Kaggle  
Daftar Harga Rumah Jabodetabek

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Data cleaning
- Handling missing values
- Feature selection
- Feature scaling

### 2. Dimensionality Reduction
- Principal Component Analysis (PCA)

### 3. Clustering
- K-Means (K=3)

### 4. Classification
- Logistic Regression
- Evaluation using Confusion Matrix

---

## 📈 Results

- Data berhasil dipisahkan menjadi tiga segmen yang cukup jelas
- PCA membantu memperlihatkan pemisahan antar kategori
- Logistic Regression menunjukkan performa sangat baik dengan tingkat kesalahan yang sangat rendah

---

## 💡 Business Insight

- Segmentasi membantu developer atau agen properti dalam menentukan positioning produk
- Kategori Premium Atas memiliki variasi karakteristik paling tinggi
- Model dapat digunakan untuk memprediksi kategori rumah baru berdasarkan spesifikasinya

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run

Clone repository:

```bash
git clone https://github.com/username/clustering-house-category.git
```

Masuk ke folder project:

```bash
cd clustering-house-category
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Jalankan notebook:

```bash
jupyter notebook
```

---

## 📂 Dataset Setup

Download dataset dari Kaggle:

https://www.kaggle.com/datasets/nafisbarizki/daftar-harga-rumah-jabodetabek

Simpan file CSV ke dalam folder:

```
data/
```

---

## 📚 Attribution

---

Dataset Source:  
Nafis Barizki  
Daftar Harga Rumah Jabodetabek – Kaggle

---

<p align="center">
  <b>© 2026 Yoga Adi Prakoso</b><br>
  <sub>Clustering House Category Project</sub>
</p>
