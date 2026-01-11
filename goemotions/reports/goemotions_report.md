# Laporan Eksperimen GoEmotions

## Pendahuluan
Eksperimen ini bertujuan untuk melakukan klasifikasi emosi pada teks
menggunakan pendekatan Deep Learning. Dataset yang digunakan adalah
GoEmotions, yaitu dataset komentar Reddit yang dianotasi dengan
berbagai label emosi.

---

## Dataset
GoEmotions merupakan dataset multi-label yang memungkinkan satu teks
memiliki lebih dari satu emosi. Dataset ini sangat cocok untuk
menguji kemampuan model Deep Learning dalam memahami konteks teks.

---

## Model
Model yang digunakan dalam eksperimen ini adalah model berbasis
Transformer untuk klasifikasi sekuens teks.

Model dilatih menggunakan data latih dan dievaluasi menggunakan
data uji untuk mengukur performa klasifikasi.

---

## Evaluasi
Evaluasi performa model dilakukan menggunakan metrik:
- F1-score
- Precision
- Recall

Metrik ini dipilih karena sesuai untuk kasus klasifikasi multi-label.

---

## Kesimpulan
Hasil eksperimen menunjukkan bahwa pendekatan Deep Learning berbasis
Transformer mampu memberikan performa yang baik dalam tugas
klasifikasi emosi pada teks.
