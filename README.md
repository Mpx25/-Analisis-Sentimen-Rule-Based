# ﻿Isi Repository
Repositori ini memuat implementasi proyek analisis sentimen terhadap ulasan pengunjung Pantai Labuhan Jukung, Lampung, yang bersumber dari Google Maps. Proyek ini menggunakan pendekatan Rule-Based Classification (Lexicon-Based) untuk mengategorikan ulasan menjadi sentimen Positif, Netral, atau Negatif. Tujuan utamanya adalah mengekstraksi wawasan terkait aspek yang disukai maupun keluhan wisatawan guna mendukung evaluasi kualitas pelayanan destinasi tersebut.

# Workflow
1. Data Scraping: Pengambilan data ulasan secara otomatis menggunakan library Selenium untuk menarik informasi teks dan rating dari Google Maps.
2. Pre-processing Data: Melakukan pembersihan data mentah (cleaning), normalisasi teks, dan penanganan data kosong agar siap diproses.
3. Implementasi Rule-Based: Menerapkan algoritma berbasis kamus kata (Lexicon) untuk menentukan bobot sentimen dari setiap ulasan pengunjung.
4. Klasifikasi & Analisis: Mengelompokkan hasil sentimen dan menghitung persentase distribusi untuk melihat tren kepuasan wisatawan.
5. Visualisasi Informasi: Menyajikan hasil akhir dalam bentuk grafik interaktif (Pie Chart dan Bar Chart) untuk mempermudah interpretasi data oleh pemangku kepentingan.

# Hasil Visualisasi
<img width="570" height="495" alt="image" src="https://github.com/user-attachments/assets/90e9e5d8-690a-44e5-beb8-092a7f9ee0d9" />
<img width="454" height="471" alt="image" src="https://github.com/user-attachments/assets/5caebc07-5d76-4f1d-8df8-cccde4fcdc4b" />
<img width="546" height="467" alt="image" src="https://github.com/user-attachments/assets/3e54c111-c2f1-4601-8b33-bc28fc2d0de3" />
<img width="790" height="425" alt="image" src="https://github.com/user-attachments/assets/3b967072-b2ce-417e-8830-2842bd0bbf88" />
<img width="780" height="423" alt="image" src="https://github.com/user-attachments/assets/0af8cd1f-7b4a-426f-9d26-5b15ff87daec" />

