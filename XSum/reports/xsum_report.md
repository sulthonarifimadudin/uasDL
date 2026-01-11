# Laporan Eksperimen XSum (Text Summarization)

## 1. Pendahuluan
Eksperimen ini dilakukan untuk memenuhi tugas Ujian Akhir Semester (UAS)
mata kuliah Deep Learning. Fokus dari eksperimen ini adalah penerapan
model Deep Learning untuk tugas **Text Summarization** menggunakan
dataset **XSum**.

Text summarization bertujuan untuk menghasilkan ringkasan singkat
yang tetap mempertahankan informasi penting dari teks asli.

---

## 2. Dataset XSum

Dataset XSum dimuat menggunakan library HuggingFace Datasets.
Dataset ini terdiri dari teks artikel berita dan ringkasan singkat
yang bersifat abstractive.

![Pemuatan dataset XSum](xsum_dataset.png)

Dataset dibagi menjadi data latih dan data validasi
untuk mendukung proses pelatihan model.

---

## 3. Tokenisasi dan Encoding

Sebelum dilakukan pelatihan model, teks artikel pada dataset XSum
melalui proses tokenisasi menggunakan tokenizer dari model Transformer.

![Tokenisasi dataset XSum](xsum_tokenization.png)

Tokenisasi bertujuan untuk mengubah teks menjadi representasi numerik
yang dapat diproses oleh model Deep Learning.

---

## 4. Model Deep Learning

Model yang digunakan dalam eksperimen ini adalah model Transformer
berbasis BART atau T5 yang dirancang khusus untuk tugas text
summarization.

![Inisialisasi model Transformer untuk XSum](xsum_model.png)

Model diinisialisasi dari pretrained model sebelum dilakukan pelatihan.

---

## 5. Proses Pelatihan Model

Gambar berikut menunjukkan proses pelatihan model XSum selama beberapa
epoch. Selama pelatihan, nilai training loss dan validation loss
dipantau sebagai indikator proses pembelajaran model.

![Proses pelatihan model XSum](xsum_training.png)

Penurunan nilai loss menunjukkan bahwa model mampu mempelajari pola
perangkum teks dengan baik.

---

## 6. Inferensi Model

Setelah proses pelatihan selesai, model digunakan untuk menghasilkan
ringkasan teks dari artikel yang diberikan.

![Hasil inferensi model XSum](xsum_inference.png)

Hasil inferensi menunjukkan bahwa model mampu menghasilkan ringkasan
teks yang lebih singkat namun tetap relevan dengan isi artikel.

---

## 7. Kesimpulan

Berdasarkan hasil eksperimen, dapat disimpulkan bahwa model Deep Learning
berbasis Transformer mampu digunakan untuk tugas text summarization
menggunakan dataset XSum.

Eksperimen ini menunjukkan bahwa pendekatan Deep Learning efektif
dalam menghasilkan ringkasan teks secara otomatis.
