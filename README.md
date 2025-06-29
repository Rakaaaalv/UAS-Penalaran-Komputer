# 📂 Sistem Pencarian & Klasifikasi Putusan Mahkamah Agung

Sistem ini dirancang untuk:

- ✅ Pencarian kasus serupa (Case Retrieval)
- ✅ Klasifikasi jenis perkara menggunakan TF-IDF & BERT
- ✅ Prediksi solusi berbasis top-k kasus serupa

---

## ⚙️ Library yang Dibutuhkan

- `pandas`, `numpy`
- `scikit-learn`
- `transformers` (HuggingFace BERT)
- `torch`
- `matplotlib`, `seaborn`
- `nltk`

Instalasi:

```bash
pip install pandas numpy scikit-learn transformers torch matplotlib seaborn nltk
```

---

## 🚀 Langkah Penggunaan

1. **Scrapping Data**

   ```bash
   Jalankan Tahap 1.ipynb
   ```

2. **Preprocessing Data**

   ```bash
   Jalankan Tahap 2.ipynb
   ```

3. **Training Model TF-IDF & BERT**

   ```bash
   Jalankan Tahap 3.ipynb
   ```

4. **Prediksi Solusi Query Baru**

   ```bash
   Jalankan Tahap 4.ipynb
   ```

5. **Evaluasi Sistem & Performa**

   ```bash
   Jalankan Tahap 5.ipynb
   ```

---

## 📊 Output Penting

- `results/predictions.csv` → Prediksi solusi untuk tiap query
- `results/retrieval_metrics.csv` → Evaluasi kinerja retrieval model
- `results/prediction_metrics.csv` → Evaluasi akurasi klasifikasi model

---

## 📒 Catatan

- Dataset menggunakan putusan Mahkamah Agung RI.
- Model BERT idealnya dijalankan dengan GPU untuk efisiensi.
- Struktur kode sudah dipisah modular: TF-IDF dan BERT di file berbeda.
- Retrieval menggunakan top-k ranking, prediksi solusi dengan majority vote.

---

## 👥 Kontribusi & Pengembangan Lanjutan

Rencana pengembangan:

- Penambahan model lain (contoh: Random Forest, Deep Learning)
- Visualisasi komparasi performa model
- Error analysis untuk perbaikan prediksi
- Ekstensi ke dokumen hukum lain

---
