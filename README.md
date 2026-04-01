# Tugas Individu 5 Dasar Python Bagian 4

**Mata Kuliah:** Praktikum Machine Learning (Computer Vision)  
**Dosen Pengampu:** Herfandi, Ph.D. — Informatika — Universitas Teknologi Sumbawa (UTS)

---

## Profil Mahasiswa
* **Nama:** Sherly Novia
* **NIM:** 231001057
* **Kelas:** Informatika — [C]

---

## Deskripsi Proyek
Repositori ini merupakan dokumentasi teknis hasil praktik mandiri mengenai fundamental Pemrograman Berorientasi Objek (OOP) pada Python. Praktikum ini dirancang sebagai tahap krusial untuk memahami arsitektur kode yang terstruktur dan modular, sebelum diimplementasikan pada algoritma *Machine Learning* dan *Computer Vision* yang lebih kompleks. 

Materi praktik merujuk pada panduan tugas untuk materi dasar Python mengenai **Class, Object, Inheritance, Scope, dan Module**.

---

## Lingkungan Pengembangan (Environment)
Seluruh skrip dalam repositori ini disusun dan diuji menggunakan spesifikasi berikut:
* **Kode Editor:** Jupyter Notebook
* **Interpreter:** Python 3.x
* **Metode Eksekusi:** Cell-by-cell execution pada antarmuka Jupyter

---

## Cakupan Praktikum
Tahapan koding yang dilakukan mencakup:
1.  **Classes & Objects:** Mendefinisikan sebuah *blueprint* (Class) dan menciptakan wujud nyatanya berupa *instance* (Object) untuk menyimpan sekumpulan data statis.
2.  **Konstruktor & Methods:** Menggunakan fungsi bawaan `__init__()` untuk melakukan konfigurasi data awal (seperti *booting* parameter) saat objek dibuat, serta membuat fungsi internal (*methods*) yang memanfaatkan parameter `self`.
3.  **Manipulasi Objek:** Melakukan modifikasi nilai properti secara instan dan menggunakan perintah `del` untuk menghapus komponen atau keseluruhan objek dari memori.
4.  **Inheritance (Pewarisan):** Menerapkan pewarisan sifat dari *Class* Induk ke *Class* Anak (termasuk *Multi-Class Inheritance*) dan menggunakan fungsi `super()` agar pewarisan hierarki berjalan sempurna.
5.  **Scope (Cakupan Variabel):** Membedah perbedaan akses antara *Local Scope* (variabel terisolasi di dalam fungsi) dan *Global Scope* (variabel terbuka di luar fungsi).
6.  **Integrasi Module:** Mengimpor fungsionalitas dari *file* Python eksternal maupun modul sistem bawaan pabrik seperti `os` untuk otomatisasi manajemen *file*.

---

## 🔍 Analisis & Kesimpulan Teknis
Setelah melakukan praktik mandiri, berikut adalah beberapa catatan analisis saya:

1.  **Struktur Modular yang Aman:** Penggunaan konsep OOP (Class dan Object) memungkinkan penyusunan program layaknya merakit komponen *hardware* keras atau merancang topologi jaringan. Setiap objek memiliki *state* dan fungsinya masing-masing. Hal ini membuat pengelolaan data untuk *Computer Vision* nantinya jauh lebih rapi karena modifikasi pada satu bagian tidak akan merusak sistem utama.
2.  **Isolasi Data via Scope:** Konsep *Local Scope* terbukti sangat krusial untuk menjaga keamanan alur kerja. Variabel yang berjalan di dalam sebuah fungsi diisolasi persis seperti IP *Private* dalam jaringan lokal (LAN). Uji coba pemanggilan variabel lokal dari luar jaringan fungsi secara konsisten menghasilkan `NameError`, membuktikan sistem proteksi memori Python beroperasi dengan ketat.
3.  **Efisiensi dengan Inheritance:** Saat membangun model AI, kita seringkali membutuhkan banyak variasi algoritma dengan dasar yang sama. Melalui *Inheritance*, kita tidak perlu menulis ulang ribuan baris kode; *class* baru bisa secara otomatis mewarisi *rule* dan spesifikasi dari *class* induknya, mempercepat proses *deployment*.
4.  **Kesimpulan:** Python menyediakan sintaksis OOP yang sangat efisien. Pemahaman mengenai alokasi memori objek dan jangkauan variabel (Scope) ini adalah pondasi wajib agar terhindar dari *bug* fatal seperti `TypeError` saat menangani *dataset* besar di tahapan *Machine Learning* selanjutnya.

---

## 📽️ Presentasi Video
Demonstrasi lengkap mengenai langkah-langkah praktikum, bedah kodingan baris demi baris, serta simulasi *troubleshooting error* dapat diakses melalui tautan berikut:

👉 [https://youtu.be/huNfj0ruQ3M]

---
