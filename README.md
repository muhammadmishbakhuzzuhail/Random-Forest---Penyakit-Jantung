# Prediksi Penyakit Jantung dengan Random Forest

## Deskripsi
Proyek ini menggunakan algoritma **Random Forest** untuk memprediksi kemungkinan penyakit jantung berdasarkan dataset tertentu. Proyek ini juga menggunakan **Streamlit** sebagai antarmuka untuk memvisualisasikan dan mengoperasikan model secara interaktif.

---

## Keperluan
Agar proyek ini dapat berjalan, pastikan Anda telah menginstal beberapa library Python berikut:
- **Streamlit**: Untuk membuat antarmuka aplikasi berbasis web.
- **Pandas**: Untuk manipulasi dan analisis data.
- **Scikit-learn**:
  - Untuk preprocessing data menggunakan **MinMaxScaler**.
  - Membagi data menjadi training dan testing menggunakan **train_test_split**.
  - Membuat model klasifikasi menggunakan **RandomForestClassifier**.

---

## Library yang Digunakan dan Kegunaannya
1. **Streamlit (`import streamlit as st`)**:
   - Membuat dashboard interaktif.
   - Menampilkan input data, tabel, grafik, dan hasil prediksi.

2. **Pandas (`import pandas as pd`)**:
   - Membaca dataset (CSV atau file lainnya).
   - Mengelola data tabular untuk preprocessing dan analisis.

3. **MinMaxScaler (`from sklearn.preprocessing import MinMaxScaler`)**:
   - Menskalakan data ke dalam rentang tertentu (biasanya antara 0 dan 1) untuk meningkatkan performa algoritma machine learning.

4. **train_test_split (`from sklearn.model_selection import train_test_split`)**:
   - Membagi dataset menjadi data training dan testing untuk evaluasi model.

5. **RandomForestClassifier (`from sklearn.ensemble import RandomForestClassifier`)**:
   - Membangun model klasifikasi menggunakan algoritma Random Forest.

---

## Langkah Instalasi
1. Clone repository:
   ```bash
   git clone https://github.com/muhammadmishbakhuzzuhail/Random-Forest---Penyakit-Jantung.git
   cd Random-Forest---Penyakit-Jantung

2. Buat Virtual Environment
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate      # Windows

4. Install Dependensi
   ```bash
   pip install -r requirements.txt

5. Jalankan aplikasi Streamlit
   ```bash
   streamlit run app.py
