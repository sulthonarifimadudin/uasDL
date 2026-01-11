# Eksperimen MNLI (Multi-Genre Natural Language Inference)

Folder ini berisi eksperimen Deep Learning untuk tugas
**Natural Language Inference (NLI)** menggunakan dataset
**MNLI (Multi-Genre Natural Language Inference)**.

Eksperimen ini merupakan bagian dari tugas **Ujian Akhir Semester (UAS)**
mata kuliah **Deep Learning**.

---

## 🎯 Tujuan Eksperimen

Tujuan dari eksperimen ini adalah:
- Mempelajari konsep Natural Language Inference (NLI)
- Menerapkan preprocessing dan tokenisasi pasangan kalimat
- Mengimplementasikan model Transformer untuk klasifikasi NLI
- Mengamati proses pelatihan model pada dataset multi-genre

---

## 📊 Dataset

Dataset MNLI digunakan melalui benchmark **GLUE** dari
library HuggingFace Datasets.

Setiap data terdiri dari:
- Premise (kalimat utama)
- Hypothesis (kalimat pembanding)
- Label hubungan semantik:
  - Entailment
  - Neutral
  - Contradiction

---

## 🧠 Model yang Digunakan

Eksperimen ini menggunakan model Deep Learning berbasis
**Transformer (BERT / DistilBERT)** yang telah dipra-latih
(pretrained model) dan kemudian dilatih ulang pada dataset MNLI.

---

## ⚙️ Alur Eksperimen

Tahapan eksperimen meliputi:
1. Pemuatan dataset MNLI
2. Preprocessing dan tokenisasi pasangan kalimat
3. Inisialisasi model Transformer
4. Pelatihan model
5. Analisis proses pelatihan

---

## 📝 Catatan

- Seluruh eksperimen dijalankan menggunakan Google Colab
- Fokus eksperimen ini adalah pada proses pelatihan model
- Evaluasi akhir tidak dibahas secara terpisah pada README ini
