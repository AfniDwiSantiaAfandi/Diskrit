---
title: Algoritma

---

# ALGORITMA
## Definisi Algoritma
Algoritma adalah urutan dari sejumlah langkah logis dan sistematis untuk memecahkan suatu masalah tertentu.
### Algoritma Sequential Search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan.
Algoritma sequential search sederhana dan mudah dimengerti, tetapi cenderung tidak efisien untuk kumpulan data yang sangat besar.
Algoritma Sequential Search bekerja dengan melakukan perbandingan satu persatu secara beruntun dalam kumpulan data dengan data yang dicari sampai data tersebut ditemukan atau tidak ditemukan.

Proses pencarian ini hanya melakukan pengulangan data dari 1 sampai dengan jumlah data (N). Setiap pengulangan, dilakukan perbandingan data ke-i dengan data yang sedang dicari. Jika data sama dengan yang dicari, berarti data telah berhasil ditemukan. Sebaliknya, jika sampai akhir pengulangan tidak ada data yang sama dengan yang dicari, berarti data tidak ditemukan.
### Langkah-langkah Urutan Sequential Search
1. Mulai dari elemen pertama dalam daftar atau array.
2. Bandingkan elemen tersebut dengan nilai yang dicari (kunci pencarian).
3. Jika elemen cocok dengan kunci pencarian, pencarian berhenti, dan indeks elemen tersebut dikembalikan.
4. Jika elemen tidak cocok, lanjutkan ke elemen berikutnya.
5. Jika sampai elemen terakhir tidak ada yang cocok, berarti data tidak ditemukan.
Contoh: 
Misalkan kita memiliki daftar angka [10, 25, 30, 45, 50] dan kita ingin mencari angka 30.
Hasil: 
Output akan menunjukkan indeks di mana angka 30 ditemukan, yaitu indeks ke-2
### Algoritma Binary Search
Binary Search merupakan algoritma pencarian yang membagi data menjadi dua bagian dan mencari elemen yang dicari di salah satu bagian tersebut. 
Jika elemen yang dicari lebih besar dari elemen tengah data, maka pencarian dilanjutkan ke bagian kanan data. Sebaliknya, jika elemen yang dicari lebih kecil dari elemen tengah, pencarian dilanjutkan ke bagian kiri data. Proses ini diulangi sampai elemen yang dicari ditemukan atau seluruh data telah diperiksa.
### Cara Kerja Binary Search 
1. Tentukan batas awal dan akhir dari daftar.
2. Cari elemen tengah daftar.
3. Bandingkan nilai elemen tengah dengan nilai yang dicari:
    a.) Jika nilai elemen tengah sama dengan nilai yang dicari, algoritma berhenti, dan posisi elemen tersebut dikembalikan.
    b.) Jika nilai elemen tengah lebih kecil dari nilai yang dicari, abaikan bagian kiri daftar, dan fokus pada bagian kanan.
    c.) Jika nilai elemen tengah lebih besar dari nilai yang dicari, abaikan bagian kanan daftar, dan fokus pada bagian kiri.
4. Ulangi proses ini sampai elemen ditemukan atau sampai batas pencarian tidak valid lagi.
Contoh: 
Misalkan kita memiliki daftar [10, 20, 30, 40, 50] dan ingin mencari angka 30
Hasil: 
Output akan menunjukkan indeks di mana angka 30 ditemukan, yaitu indeks ke-2.
## Pseudocode
Pseudocode merupakan cara menuliskan langkah-langkah dalam sebuah algoritma memakai bahasa yang sederhana. Elemen yang digunakan pada pseudocode biasanya tidak memperhatikan deklrarasi variabel, atau yang menjurus pada suatu bahasa pemrograman tertentu. 
## Big O Algoritma
Notasi Big O adalah bahasa yang kita gunakan untuk berbicara tentang berapa lama suatu algoritma berjalan (kompleksitas waktu) atau berapa banyak memori yang digunakan oleh suatu algoritma (kompleksitas ruang).
Notasi Big O menggunakan huruf O (dari kata order) untuk menunjukkan orde pertumbuhan sebuah fungsi, dan menggunakan variabel n untuk menyatakan ukuran masalah. Misalnya, O(1) berarti bahwa kinerja algoritma tidak bergantung pada ukuran masalah, O(n) berarti bahwa kinerja algoritma berbanding lurus dengan ukuran masalah, O(n^2) berarti bahwa kinerja algoritma berbanding kuadrat dengan ukuran masalah, dan seterusnya.
## Hitung Big O dari Algoritma Sequential Search
* Waktu Kompleksitas (time complexity)
Time Complexity adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma.
* Ruang Kompleksitas (space complexity)
Space Complexity adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. 

## Referensi
https://www.gramedia.com/literasi/pengertian-algoritma/#Pengertian_Algoritma
https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/
https://engineerpalsu.medium.com/memahami-linear-search-algorithm-algoritma-pencarian-sederhana-untuk-data-1b97f456a558
https://kantinit.com/programming/binary-search-adalah-pengertian-cara-kerja-dan-implementasi/#Apa_itu_Binary_Search
https://dibimbing.id/blog/detail/pseudocode-definisi-fungsi-ciri-ciri-cara-nulis-contoh
https://itkampus.com/pengertian-pseudocode/
https://medium.com/@memories.risset/notasi-big-o-dan-analisis-algoritma-dengan-contoh-python-6a9dc79d43fe
https://ichi.pro/id/notasi-big-o-penjelasan-sederhana-dengan-contoh-181845825280714
https://medium.com/bee-solution-partners/penjelasan-sederhana-tentang-time-complexity-dan-big-o-notation-4337ba275cfe


