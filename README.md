# UAS Deep Learning

Repository ini dibuat untuk memenuhi tugas **Ujian Akhir Semester (UAS)**
mata kuliah **Deep Learning**. Repository ini berisi beberapa eksperimen
Deep Learning berbasis **Transformer** yang diimplementasikan menggunakan
Python dan library HuggingFace.

Setiap eksperimen disusun secara terpisah, rapi, dan terstruktur sesuai
standar akademik, lengkap dengan notebook, laporan eksperimen, dan
dependency yang digunakan.

---

## 🎯 Tujuan Repository

Tujuan dari repository ini adalah:
- Mengimplementasikan berbagai tugas Deep Learning berbasis teks
- Memahami alur eksperimen Machine Learning dan Deep Learning
- Melatih dan memantau proses training model Transformer
- Menyusun laporan eksperimen secara sistematis dan terdokumentasi

---

## 📂 Struktur Repository

Setiap eksperimen berada dalam satu folder terpisah dan memiliki struktur
minimum sebagai berikut:

experiment_name/
├── README.md
├── notebooks/
├── reports/
└── requirements.txt


Struktur ini bertujuan agar setiap eksperimen mudah dipahami, direplikasi,
dan dievaluasi secara mandiri.

---

## 🧪 Daftar Eksperimen

### 1. GoEmotions
Eksperimen klasifikasi emosi **multi-label** pada teks menggunakan dataset
**GoEmotions** dengan pendekatan Deep Learning berbasis Transformer.

📁 Folder: `goemotions/`

---

### 2. AG News
Eksperimen klasifikasi topik berita menggunakan dataset **AG News**
untuk tugas klasifikasi teks berbasis Deep Learning.

📁 Folder: `agnews/`

---

### 3. MNLI (Multi-Genre Natural Language Inference)
Eksperimen **Natural Language Inference (NLI)** menggunakan dataset
**MNLI**, yang bertujuan menentukan hubungan semantik antar pasangan
kalimat.

📁 Folder: `mnli/`

---

### 4. SQuAD (Question Answering)
Eksperimen **Question Answering (QA)** menggunakan dataset **SQuAD**,
dengan tujuan menghasilkan jawaban berdasarkan konteks teks dan
pertanyaan.

📁 Folder: `SQuAD/`

---

### 5. XSum (Text Summarization)
Eksperimen **Text Summarization** menggunakan dataset **XSum** untuk
menghasilkan ringkasan singkat dari artikel berita secara otomatis.

📁 Folder: `Xsum/`

---

## 🛠️ Tools dan Library

Eksperimen dalam repository ini menggunakan beberapa tools dan library,
antara lain:
- Python
- PyTorch
- HuggingFace Transformers
- HuggingFace Datasets
- NumPy
- Scikit-Learn
- Weights & Biases (wandb)

---

## 👥 Anggota Kelompok

- **Abyan Rizki Arianto** — NIM: 1103220002  
- **JIhan Nur Mardatillah** — NIM: 1103223129  
- **Sulthon Arif Imadudin** — NIM: 1103223206  

---

## 📝 Catatan

- Seluruh eksperimen dijalankan menggunakan Google Colab
- Fokus utama repository ini adalah proses dan alur eksperimen
- Laporan eksperimen disusun dalam bahasa Indonesia
