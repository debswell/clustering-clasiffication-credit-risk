# Credit Risk 

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis risiko kredit dengan menggunakan metode **clustering dan klasifikasi** pada dataset **financial_loan**. Tahapan utama dalam analisis ini mencakup:

1. **Clustering** → Mencari label risiko kredit berdasarkan pola dalam data.
2. **Klasifikasi** → Menggunakan model machine learning untuk mengkategorikan data berdasarkan label yang telah ditemukan.

---

## 📊 Tahapan Analisis
### **1️⃣ Clustering untuk Menentukan Label**
- Menggunakan teknik **unsupervised learning** untuk mengelompokkan data finansial berdasarkan karakteristik tertentu.
- Algoritma clustering digunakan untuk **menemukan pola tersembunyi** dan menetapkan label risiko kredit (0 = Beresiko, 1 = Tidak Beresiko).

### **2️⃣ Klasifikasi Risiko Kredit**
- Setelah label diperoleh dari clustering, dilakukan **supervised learning** untuk membangun model prediksi risiko kredit.
- Model yang digunakan dalam klasifikasi adalah **K-Nearest Neighbors (KNN)** dan dibandingkan dengan **DecisionTreeClasifier**.
- Model dievaluasi dengan **Accuracy, Precision, Recall, dan F1-Score**.

---

## 🚀 Hasil Evaluasi Model
Model klasifikasi KNN yang diterapkan menunjukkan hasil yang sangat baik:
- **Accuracy:** 99.97%
- **Precision:** 100%
- **Recall:** 99.92%
- **F1-Score:** 99.96%

---


📌 **Created:** Debi Welani Christin Saragih 
📅 **Date:** March 2025
