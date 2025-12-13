# 🤖 AI IN SOCIAL NETWORKS 🤖
# ✨ Prediksi Kepopuleran Video (Logistic Regression)

> Proyek sederhana Machine Learning untuk mengklasifikasikan apakah sebuah video akan **Populer** atau **Tidak Populer** berdasarkan jumlah **Views** dan **Likes** menggunakan model **Regresi Logistik**.
>
> Proyek ini dibuat sebagai pemenuhan tugas Team Based Project-UAS Mata Kuliah Pengantar Kecerdasan Buatan
---

## 🚀 Kelompok 2

| Nama | NIM  |
| :--- | :--- |
| Alya Rena Azzahra | M0125006 |
| Jessica Allia Faaiza Hesgita | M0125017 |
| Maria Cahyaningtyas | M0125020 |

---

## 💡 Konsep Dasar

Proyek ini mengimplementasikan algoritma **Regresi Logistik** (Logistic Regression) dari pustaka `scikit-learn`.

* **Regresi Logistik** adalah algoritma klasifikasi yang digunakan untuk memprediksi probabilitas variabel dependen biner (dua kategori, seperti 0 atau 1).
* Dalam konteks ini:
    * **Fitur Input (X):** `views` dan `likes`.
    * **Variabel Target (y):** `label` (0 = Tidak Populer, 1 = Populer).
* Model menggunakan fungsi sigmoid untuk memetakan prediksi ke dalam probabilitas, yang kemudian diklasifikasikan.

---

## 📤 Struktur Proyek
1. File utama program yang berisi kode ML
   ``` bash
   AIIII
2. Dokumentasi proyek
   ```bash
   README.md

---

## ⚙️ Cara Menjalankan

1. Akses Folder: Pindah ke direktori proyek di terminal Anda:
    ``` bash
    cd [nama-folder-proyek]
2. Jalankan skrip Python dari terminal:
    ``` bash
    python video_popularity_predictor.py
3. Program akan meminta Anda untuk memasukkan jumlah views dan likes.
   ``` bash
   Model Machine Learning berhasil dilatih!
   Masukkan jumlah views: [masukkan angka, cth: 1800000]
   Masukkan jumlah likes: [masukkan angka, cth: 350000]
4. Hasil prediksi akan ditampilkan, seperti contoh berikut:
   ``` bash
    ============================
    HASIL PREDIKSI VIDEO
    ============================
    Views  : 1800000
    Likes  : 350000
    Kategori Video : Populer
    ============================
   
---

## 📝 Dataset Latihan

Model dilatih menggunakan dataset kecil berikut yang didefinisikan dalam kode:
| Views | Likes  | Label (0=Tidak Populer, 1=Populer) |
| :--- | :--- | :--- |
| 500.000 | 100.000 | 0 |
| 1.500.000 | 300.000 | 1 |
| 800.000 | 150.000 | 0 |
| 3.000.000 | 500.000 | 1 |
| 2.000.000 | 250.000 | 1 |
| 900.000 | 100.000 | 0 |
| 1.200.000 | 220.000 | 1 |
| 2.500.000 | 400.000 | 1 |

## ✍️ Kontribusi

   Kami sangat menghargai kontribusi dari siapa pun! Jika Anda memiliki saran perbaikan, penambahan fitur (misalnya, menambahkan fitur 'comment count'), atau menemukan bug, silakan ikuti alur kontribusi standar GitHub: 
1. Fork repositori ini.
2. Buat branch baru 
    ```bash
    (git checkout -b feature/nama-fitur-baru).
3. Lakukan commit perubahan Anda 
    ```bash
    (git commit -m 'feat: Deskripsi singkat fitur').
4. Push ke branch 
    ```bash
    (git push origin feature/nama-fitur-baru).
5. Buka Pull Request ke main branch.
Terima kasih atas kontribusi Anda!

---

Pastikan Anda telah menginstal pustaka Python berikut. Anda dapat menginstalnya menggunakan `pip`:

```bash
pip install pandas scikit-learn
