# Implementasi-Algoritma-Supervised-Learning-untuk-Pengambilan-Keputusan
Repositori ini berisi implementasi algoritma supervised learning (Regresi Logistik, Support Vector Machine, dan Decision Tree) untuk mendukung pengambilan keputusan berbasis data. Studi kasus yang digunakan adalah klasifikasi kelayakan kredit berdasarkan beberapa fitur seperti pendapatan, umur, lama bekerja, dan riwayat pinjaman.
Deskripsi

Repositori ini berisi implementasi algoritma supervised learning (Regresi Logistik, Support Vector Machine, dan Decision Tree) untuk mendukung pengambilan keputusan berbasis data. Studi kasus yang digunakan adalah klasifikasi kelayakan kredit berdasarkan beberapa fitur seperti pendapatan, umur, lama bekerja, dan riwayat pinjaman.

Fitur
Implementasi tiga algoritma supervised learning:
Regresi Logistik → menghasilkan prediksi probabilitas kelayakan.
Support Vector Machine (SVM) → memberikan klasifikasi dengan margin optimal.
Decision Tree → menyusun aturan keputusan yang mudah diinterpretasikan.
Evaluasi model menggunakan metrik akurasi dan classification report.
Visualisasi hasil dengan tabel perbandingan performa.
Laporan dalam format IEEE (LaTeX) siap digunakan untuk kebutuhan akademik.

📂 Struktur Direktori
.
├── data/               # Dataset (simulasi/real)
├── notebooks/          # Implementasi Python (Jupyter Notebook)
├── report/             # Laporan dalam format LaTeX IEEE
├── src/                # Script Python modular
└── README.md           # Dokumentasi proyek

Teknologi
Python 3.x
Scikit-learn
Pandas, NumPy
Matplotlib / Seaborn
LaTeX (untuk laporan IEEE)

Cara Menjalankan
Clone repository:
git clone https://github.com/username/supervised-decision.git
cd supervised-decision

Install dependencies:
pip install -r requirements.txt

Jalankan notebook:
jupyter notebook notebooks/

Hasil Utama
Regresi Logistik: Akurasi ~83%
SVM (Linear): Akurasi ~83%
Decision Tree: Akurasi 100% (namun berpotensi overfitting)

Lisensi
Proyek ini dilisensikan di bawah lisensi MIT – silakan gunakan, modifikasi, dan distribusikan.
