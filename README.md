# AI IN SOCIAL NETWORKS
# 🤖 Prediksi Kepopuleran Video (Logistic Regression)

> Proyek sederhana Machine Learning untuk mengklasifikasikan apakah sebuah video akan **Populer** atau **Tidak Populer** berdasarkan jumlah **Views** dan **Likes** menggunakan model **Regresi Logistik**.
>
> Proyek ini dibuat sebagai pemenuhan tugas Team Based Project-UAS Mata Kuliah Pengantar Kecerdasan Buatan

---

## 🚀 Kelompok 2

| :--- | :--- |
| **Alya Rena Azzahra** | M0125006 |
| **Jessica Allia Faaiza Hesgita** | M0125017 |
| **Maria Cahyaningtyas** | M0125020 |

---

## 💡 Konsep Dasar

Proyek ini mengimplementasikan algoritma **Regresi Logistik** (Logistic Regression) dari pustaka `scikit-learn`.

* **Regresi Logistik** adalah algoritma klasifikasi yang digunakan untuk memprediksi probabilitas variabel dependen biner (dua kategori, seperti 0 atau 1).
* Dalam konteks ini:
    * **Fitur Input (X):** `views` dan `likes`.
    * **Variabel Target (y):** `label` (0 = Tidak Populer, 1 = Populer).
* Model menggunakan fungsi sigmoid untuk memetakan prediksi ke dalam probabilitas, yang kemudian diklasifikasikan.

---

## 🛠️ Persyaratan Instalasi

Pastikan Anda telah menginstal pustaka Python berikut. Anda dapat menginstalnya menggunakan `pip`:

  ```bash
  pip install pandas scikit-learn
