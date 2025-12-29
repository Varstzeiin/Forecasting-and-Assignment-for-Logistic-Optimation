
# Optimization of Fleet Allocation using Decision Support System (DSS)

## 📌 Project Overview
Proyek ini bertujuan untuk mengoptimalkan alokasi armada transportasi berdasarkan biaya zona (*zone cost*) dan status ketersediaan armada. Sistem ini dikembangkan untuk membantu pengambilan keputusan dalam distribusi logistik secara real-time.

> **Note:** Project ini masih dalam tahap pengembangan (On-Progress). Saat ini fokus pada modul pengujian data dan logika alokasi sistem.

## 🚀 Key Features (Current Progress)
* **Data Preprocessing:** Pembersihan dan transformasi data operasional selama 2 bulan.
* **Cost Analysis:** Perhitungan referensi biaya antar zona (`zone_cost_ref`).
* **Allocation Algorithm:** Implementasi fungsi `run_dss_demo_direct` untuk mencocokkan armada (Ready/On-Trip) dengan kebutuhan distribusi.
* **Top-K Recommendation:** Sistem memberikan rekomendasi armada terbaik berdasarkan bobot biaya terendah.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, XGBoost (for future forecasting), Matplotlib/Seaborn.
* **Environment:** Jupyter Notebook / Google Colab.

## 📊 Logic Flow
Sistem bekerja dengan alur sebagai berikut:
1. Memasukkan data referensi biaya zona.
2. Mengecek status ketersediaan armada (Ready vs On-Trip).
3. Melakukan perhitungan kriteria menggunakan logika DSS.
4. Menghasilkan output berupa urutan armada yang paling optimal untuk ditugaskan.
