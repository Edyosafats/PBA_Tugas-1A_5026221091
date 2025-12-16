# Analisis Sentimen Maxim – Natural Language Processing

## 📋 Gambaran Proyek
Proyek ini merupakan implementasi **pipeline Natural Language Processing (NLP) end-to-end** untuk menganalisis sentimen ulasan pengguna aplikasi transportasi online **Maxim (com.taxsee.taxsee)** yang diambil dari **Google Play Store**.  
Pipeline mencakup seluruh tahapan analisis teks, mulai dari **pengambilan data (scraping)**, **pembersihan data (text preprocessing)**, hingga **klasifikasi sentimen** menggunakan algoritma *Machine Learning*.

---

## 🎯 Tujuan Proyek
- Mengimplementasikan pipeline **End-to-End NLP** untuk teks **Bahasa Indonesia**.
- Menganalisis sentimen ulasan pengguna Maxim (**Positif / Negatif**).
- Mengidentifikasi pola kata yang sering muncul pada keluhan dan pujian pelanggan.
- Membangun model prediksi sentimen otomatis menggunakan **Naive Bayes**.

---

## 🛠️ Teknologi yang Digunakan
- **Python 3.x**
- **Google Play Scraper** – Pengambilan data ulasan dari Play Store
- **Pandas & NumPy** – Manipulasi dan analisis data
- **NLTK** – Tokenisasi dan stopwords Bahasa Indonesia
- **Sastrawi** – Stemming Bahasa Indonesia (opsional/pendukung)
- **Scikit-learn** – Feature extraction (TF-IDF) & modelling (Naive Bayes)
- **Matplotlib & Seaborn** – Visualisasi data (Bar Chart, Confusion Matrix)

---

## 📚 Struktur Proyek
### Week 2 – Data Scraping & Preprocessing
Tahap pengumpulan dan pembersihan data ulasan Maxim.  
**Teknik:** Scraping, Cleaning (Regex), Tokenization, Stopwords Removal

### Week 3 – Feature Extraction (TF-IDF)
Mengubah data teks menjadi representasi numerik agar dapat diproses oleh algoritma Machine Learning.  
**Teknik:** TF-IDF (Term Frequency–Inverse Document Frequency)

### Week 4 – Modelling & Evaluation
Pembangunan model klasifikasi dan evaluasi performa model.  
**Teknik:** Multinomial Naive Bayes, Confusion Matrix, Classification Report

---

## 📊 Dataset
Dataset penelitian ini disimpan pada **media penyimpanan eksternal (Google Drive)** karena keterbatasan ukuran file pada repositori GitHub.  
Dataset mencakup data mentah (*raw*) hingga data yang telah dibersihkan (*clean*).

📂 **Link Dataset:**  
https://drive.google.com/drive/folders/1Zpp6R7zrfo3FNoStqoXnb76kJlHDSzr4?usp=sharing

### File dalam Dataset:
- `maxim_raw.csv`
- `maxim_clean_basic.csv`
- `maxim_clean_final.csv`

---

## 🚀 Cara Penggunaan

### 1. Instalasi Dependencies
```bash
pip install google-play-scraper Sastrawi textblob seaborn matplotlib scikit-learn pandas nltk
```
#### Unduh resource NLTK:
```bash
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
```

### 2. Persiapan Data
Karena dataset berada di Google Drive:
- Unduh seluruh file .csv dari tautan dataset.
- Letakkan file-file tersebut dalam folder yang sama dengan file notebook (.ipynb).

### 3. Menjalankan Notebook
Jalankan notebook utama:
```bash
jupyter notebook "Tugas_1A_Maxim_5026221091.ipynb"
```

## 📝 Struktur Direktori Repository

```
Tugas1A_Maxim_Edward/
│
├── Tugas_1A_Maxim_5026221091.ipynb   # Notebook utama (pipeline NLP)
└── README.md                        # Dokumentasi proyek
```

## 📌 Catatan

- Dataset tidak diunggah langsung ke repository GitHub karena keterbatasan ukuran file.
- Pastikan seluruh dependency telah terpasang sebelum menjalankan notebook.

## 👤 Pembuat

**Edward Yosafat Sirait**  
NRP: 5026221091  
Tugas 1A - Pemrosesan Bahasa Alami (PBA)
