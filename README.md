# Review Artikel: A Novel Efficient and Effective Preprocessing Algorithm for Text Classification

Artikel *“A Novel Efficient and Effective Preprocessing Algorithm for Text Classification”* (Zhu & Luo, 2023) membahas strategi preprocessing baru yang memadukan teknik dasar (tokenisasi, konversi huruf kecil, filtering, dan stopword removal) dengan **Orthogonal Matching Pursuit (OMP)**. Hasilnya adalah pendekatan **Preprocessing Bag of Words (PBOW)** yang terbukti mampu mengurangi dimensi fitur, meningkatkan akurasi, serta mempercepat waktu komputasi dibanding metode baseline pada tugas klasifikasi teks.

---

## Critical Review

### Kebaruan
Menggabungkan preprocessing dasar (tokenisasi, lowercasing, filtering, stopword removal) dengan **Orthogonal Matching Pursuit (OMP)** untuk menghasilkan PBOW (Preprocessing Bag of Words) yang lebih efisien.

### Kontribusi Utama
- Mengurangi dimensi fitur teks sebesar **19–38%**.  
- Meningkatkan akurasi klasifikasi sebesar **5–9%**.  
- Mempercepat waktu komputasi klasifikasi hingga **17–33%**.  

### Kekuatan
- Menunjukkan secara empiris bahwa preprocessing bukan sekadar tahap awal, tetapi **berpengaruh langsung pada efisiensi dan akurasi**.  
- Eksperimen dilakukan secara sistematis dengan membandingkan beberapa varian preprocessing (NP0–NP3) dan algoritme supervised (DT, RF, AB, KNN).  

### Kelemahan
- Dataset terbatas pada subset **20 Newsgroups** (empat kategori saja).  
- Belum diuji pada teks modern seperti media sosial yang lebih “noisy”.  
- Tidak dibandingkan dengan model **deep learning mutakhir** (CNN, Transformer).  

### Implikasi
- PBOW + OMP bisa menjadi alternatif efektif untuk **big data text classification** atau sistem yang membutuhkan efisiensi tinggi.  
- Namun, untuk konteks **NLP modern**, metode ini perlu diuji lebih lanjut agar relevan dengan data dan model terkini.  
