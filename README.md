# 💳 Credit Risk Classification

Proyek ini bertujuan untuk membangun model machine learning yang mampu mengklasifikasikan risiko kredit nasabah berdasarkan data pinjaman dan profil keuangan mereka.

---

## 📌 Tujuan Proyek
Memprediksi apakah pinjaman yang diajukan oleh nasabah termasuk dalam kategori **berisiko tinggi (default)** atau **berisiko rendah (tidak default)**, guna membantu institusi keuangan dalam pengambilan keputusan pemberian kredit.

---

## 📂 Struktur Dataset
Dataset terdiri dari beberapa kelompok fitur:

- 🆔 **Fitur Identitas:** Seperti ID pinjaman dan ID nasabah (di-drop sebelum modeling)
- 👤 **Data Nasabah:** Pendapatan, status pekerjaan, kepemilikan rumah, dll
- 💰 **Data Pinjaman:** Jumlah pinjaman, tingkat bunga, jangka waktu, status pembayaran
- 🧾 **Riwayat Kredit:** Catatan keterlambatan, saldo, dan jumlah akun terbuka

---

## ⚙️ Proses Analisis

1. **Eksplorasi Data (EDA)**
2. **Feature Engineering & Selection**
3. **Data Splitting** (Train-Test 80:20)
4. **Modeling** menggunakan:
   - Logistic Regression
   - XGBoost
5. **Hyperparameter Tuning**
6. **Evaluasi Model** dengan:
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC

---

## 📈 Hasil Evaluasi

📍 **Sebelum Tuning:**
- Logistic Regression: ROC-AUC ≈ 0.62
- XGBoost: ROC-AUC ≈ 0.67

📍 **Setelah Tuning:**
- Logistic Regression: Meningkat minor
- XGBoost: ROC-AUC meningkat jadi **≈ 0.78** dan Recall naik signifikan

---

## 💡 Insight & Business Recommendation

- Model **XGBoost setelah tuning** memberikan performa terbaik untuk mendeteksi nasabah berisiko tinggi (Recall tinggi).
- **Recall yang tinggi** penting dalam konteks risiko kredit untuk meminimalkan kerugian akibat gagal bayar.
- Institusi keuangan dapat menggunakan model ini untuk **screening awal** pinjaman dan memfokuskan mitigasi risiko pada kelompok berisiko tinggi.

---

## 🧠 Teknologi yang Digunakan

- Python (Pandas, Scikit-Learn, XGBoost)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 👤 Author

Refdinal F.

---

## 🙏 Terima Kasih!

Proyek ini merupakan bagian dari eksplorasi machine learning untuk membantu pengambilan keputusan di bidang keuangan.
