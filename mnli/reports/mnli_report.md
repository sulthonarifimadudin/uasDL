# Laporan Eksperimen MNLI (Multi-Genre Natural Language Inference)

## 1. Pendahuluan
Eksperimen ini dilakukan untuk memenuhi tugas Ujian Akhir Semester (UAS)
mata kuliah Deep Learning. Fokus dari eksperimen ini adalah melakukan
Natural Language Inference (NLI) menggunakan dataset MNLI dengan
pendekatan Deep Learning.

Tugas Natural Language Inference bertujuan untuk menentukan hubungan
semantik antara dua kalimat, yaitu apakah kalimat kedua bersifat
entailment, contradiction, atau neutral terhadap kalimat pertama.

---

## 2. Dataset MNLI

Dataset MNLI dimuat menggunakan library HuggingFace Datasets melalui
benchmark GLUE. Dataset ini terdiri dari pasangan kalimat yang berasal
dari berbagai genre teks.

Dataset dibagi menjadi data latih dan data validasi untuk mendukung
proses pelatihan dan pemantauan performa model.

![Pemuatan dataset MNLI](mnli_dataset.png)

---

## 3. Preprocessing dan Tokenisasi

Sebelum digunakan dalam pelatihan model, pasangan kalimat pada dataset
MNLI melalui tahap preprocessing dan tokenisasi menggunakan tokenizer
dari model Transformer.

Proses tokenisasi menghasilkan representasi input berupa `input_ids`
dan `attention_mask` yang digunakan sebagai masukan model.

![Proses tokenisasi dataset MNLI](mnli_tokenization.png)

Tahap ini bertujuan untuk memastikan data teks dapat diproses dengan
baik oleh model Deep Learning.

---

## 4. Model Deep Learning

Model yang digunakan dalam eksperimen ini adalah model Transformer
berbasis BERT atau DistilBERT yang dirancang untuk tugas klasifikasi
sekuens.

Model diinisialisasi dari pretrained model dan kemudian dilatih
menggunakan dataset MNLI.

![Inisialisasi model Transformer MNLI](mnli_model.png)

---

## 5. Proses Pelatihan Model

Gambar berikut menunjukkan proses pelatihan model selama beberapa epoch.
Pada setiap epoch dicatat nilai training loss serta metrik pemantauan
performa pada data validasi.

![Proses training model MNLI](mnli_training.png)

Hasil pelatihan menunjukkan bahwa nilai training loss mengalami
penurunan seiring bertambahnya epoch, yang menandakan bahwa model
mampu mempelajari hubungan semantik antar pasangan kalimat.

---

## 6. Kesimpulan

Berdasarkan hasil eksperimen, dapat disimpulkan bahwa model Deep Learning
berbasis Transformer mampu digunakan untuk tugas Natural Language
Inference pada dataset MNLI.

Eksperimen ini menunjukkan bahwa pendekatan Deep Learning efektif
dalam memahami hubungan makna antar pasangan kalimat dari berbagai
genre teks.
