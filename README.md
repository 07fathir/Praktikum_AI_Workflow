# Praktikum AI Workflow

## 2306135_Fathir Miftah Nursalim

### Deskripsi Proyek
Proyek ini bertujuan untuk mengimplementasikan konsep kecerdasan buatan (AI) dalam analisis dan prediksi penjualan produk. Dalam proyek ini, beberapa tahap utama yang dilakukan adalah sebagai berikut:

1. **Pembuatan Dataset**
   - Membuat dataset penjualan dalam format CSV dengan informasi produk, jumlah terjual, stok, dan harga satuan.

2. **Pembersihan dan Pengolahan Data**
   - Memproses dataset untuk memastikan data bersih, lengkap, dan siap digunakan dalam model AI.

3. **Pelatihan Model AI**
   - Menggunakan **Decision Tree Classifier** untuk memprediksi apakah suatu produk perlu restock berdasarkan data penjualan.

4. **Prediksi dan Visualisasi**
   - Menggunakan model yang telah dilatih untuk melakukan prediksi.
   - Membuat visualisasi hubungan antara jumlah terjual, stok, dan keuntungan.

---

## Instruksi Cara Menjalankan Kode di Google Colab

### 1. Buka Google Colab
- Kunjungi [Google Colab](https://colab.research.google.com/).
- Pilih **"Unggah"** dan unggah file `praktikum_ai.ipynb`.

### 2. Menjalankan Notebook
- Pastikan semua sel dijalankan satu per satu.
- Jika ada dependensi tambahan, jalankan perintah berikut di dalam sel kode:
  ```python
  !pip install scikit-learn
  ```

### 3. Mengakses File di Google Drive (Opsional)
- Jika data atau model disimpan di Google Drive, hubungkan dengan:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
  ```

### 4. Catatan Tambahan
- Pastikan semua dependensi telah terinstal agar kode dapat berjalan dengan lancar.
- Jika ada kendala, periksa kembali dependensi atau pastikan file telah diunggah dengan benar ke Google Colab.

---

## Lisensi
Proyek ini dibuat untuk keperluan akademik dan dapat digunakan serta dimodifikasi sesuai kebutuhan.

---

**Penulis:** 2306135_Fathir Miftah Nursalim

