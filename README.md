# 🧠 Customer Attrition Prediction & Feature Importance Analysis

🎯 Objective
Tujuan dari proyek ini adalah untuk menganalisis dan memprediksi perilaku nasabah dalam rangka mengidentifikasi nasabah yang berisiko untuk berhenti menggunakan layanan kartu kredit. Secara khusus, proyek ini bertujuan untuk:

Mengidentifikasi faktor-faktor penting yang berkontribusi terhadap attrition atau berhentinya nasabah.

Membangun model klasifikasi yang dapat memprediksi status nasabah (Attrited atau Existing) secara akurat berdasarkan data demografis dan perilaku transaksi.

Melakukan analisis feature importance guna mengetahui fitur mana yang paling berpengaruh terhadap keputusan model.

Memberikan insight strategis kepada tim bisnis/marketing agar dapat melakukan intervensi yang tepat untuk mempertahankan pelanggan bernilai tinggi.

## 📌 Project Overview

Tujuan dari proyek ini adalah untuk memahami faktor-faktor penting yang mempengaruhi status nasabah dalam dataset pelanggan kartu kredit, serta membangun model prediktif untuk mengklasifikasikan apakah seorang nasabah masih aktif (**Existing**) atau telah berhenti (**Attrited**).

Proyek ini berfokus pada:

- Exploratory Data Analysis (EDA)
- Feature importance menggunakan metode pemodelan
- Interpretasi model menggunakan teknik explainability

## 📂 Dataset Description

Dataset berisi informasi demografis dan perilaku pelanggan kartu kredit, dengan fitur-fitur seperti:

- `user_id`: Nomor akun nasabah
- `attrition_flag`: Status nasabah (Existing atau Attrited)
- `customer_age`: Usia
- `gender`: Jenis kelamin
- `dependent_count`: Jumlah tanggungan
- `education_level`: Tingkat pendidikan
- `marital_status`: Status pernikahan
- `income_category`: Kategori penghasilan
- `card_category`: Jenis kartu yang digunakan
- `months_on_book`: Lama menjadi pelanggan
- dan fitur-fitur lainnya terkait transaksi dan aktivitas finansial

## 🛠 Methods

Langkah-langkah utama dalam analisis:

- **Preprocessing Data**: Cleaning dan encoding fitur kategorikal
- **Modeling**:
  - Random Forest Classifier untuk klasifikasi
- **Feature Importance**:
  - Menggunakan `feature_importances_` dari Random Forest
- **Interpretability**:
  - Interpretasi model

## 🚀 How to Run

Clone repository ini, jalankan digoogle colab atau jupyter notebook
