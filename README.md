# Chatbot Layanan Informasi Akademik Berbasis NLP

Proyek ini dibuat untuk memenuhi **Tugas Praktikum AI Mahasiswa** pada program studi Sistem dan Teknologi Informasi. Proyek mengimplementasikan teknik *Natural Language Processing* (NLP) menggunakan ekstraksi fitur **TF-IDF** dan algoritma **Multinomial Naive Bayes** untuk melakukan klasifikasi maksud (*intent classification*) pertanyaan mahasiswa.

---

## Deskripsi Singkat
Bagian pelayanan akademik kampus sering mengalami kendala keterlambatan respon akibat tingginya volume pertanyaan berulang dari mahasiswa (seperti KRS, UKT, Cuti, dan Transkrip Nilai). Chatbot ini dirancang untuk menjawab pertanyaan secara otomatis 24/7 berdasarkan *intent* yang terdeteksi.

---

## Teknologi & Library
- **Bahasa Pemrograman:** Python 3.10+
- **Machine Learning & NLP:** `scikit-learn` (`TfidfVectorizer`, `MultinomialNB`)
- **Pengolahan Data:** `pandas`, `numpy`
- **Visualisasi:** `matplotlib`, `seaborn`

---

## Cara Menjalankan Project

1. **Buka di Google Colab / Jupyter Notebook:**
   Jalankan file notebook yang terdapat pada folder `notebooks/chatbot_nlp_akademik.ipynb`.

2. **Install Dependensi jika dijalankan secara lokal:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
