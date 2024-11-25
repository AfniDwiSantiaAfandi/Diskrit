---
title: Deretan dan Rekursi

---

# Deretan dan Rekursi 
## A. Deretan (sequence) 
Deretan (sequence) adalah suatu urutan atau susunan elemen atau yang disusun secara teratur berdasarkan suatu aturan tertentu. 

Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu.
Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.
N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …}
Notasi deretan: {an}

Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	$a_n$ = 2n
	$a_n$ = 1/n
	$a_n$ = 7 – 3n
Deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
Misalnya:
- Deretan bilangan ganjil: 1,3,5,7,…
- Deretan bilangan genap: 2,4,6,8,…
- Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

### Contoh-contoh Deretan dan Formulanya:
#### 1. Deret Aritmatika
Yaitu deret dengan pola kenaikan atau penurunan tetap. 
Contoh: 2,5,8,11,14,…
Rumus suku ke-n: 
![image](https://hackmd.io/_uploads/SJRasheXJx.png)
keterangan: 
- 𝑎 = suku pertama 
- 𝑏 = beda (selisih antar suku
- 𝑛 = nomor suku yang dicari

#### 2. Deret Geometri
Yaitu deret dengan pola kelipatan tetap.
Contoh: 3,6,12,24,48,…
Rumus suku ke-n:
![image](https://hackmd.io/_uploads/BJ2X6hlmyg.png)
keterangan: 
- 𝑎 = suku pertama 
- 𝑟 = rasio (perbandingan antar suku,
- 𝑛 = nomor suku yang dicari


#### 3. Deret Bilangan Kuadrat
Yaitu deret dengan pola nilai berupa kuadrat bilangan bulat.
Contoh: 1,4,9,16,25,…
Rumus suku ke-n:
![image](https://hackmd.io/_uploads/H1adh3x7yl.png)
keterangan: 
𝑛 = nomor suku yang dicari

#### 4. Deret Bilangan Kubik
Yaitu deret dengan pola nilai berupa kubik bilangan bulat.
Contoh: 1,8,27,64,125,…
Rumus suku ke-n:
![image](https://hackmd.io/_uploads/ryHpa2gmyg.png)
keterangan:
𝑛 = nomor suku yang dicari

#### 5. Deret Fibonacci
Yaitu deret dengan pola dimana setiap suku merupakan jumlah dua suku sebelumnya.
Contoh: 0,1,1,2,3,5,8,…
Rumus suku ke-n (rekursif):
![image](https://hackmd.io/_uploads/HJUN0hlQkg.png)
keterangan: 
- $F_n$ = menunjukkan nilai suku ke-$n$ dalam deret fibonacci
- $F_n{_-}{_1}$ = nilai suku sebelum suku ke-$n$
- $F_n{_-}{_2}$ = nilai dua suku sebelum suku ke-$n$
- $F_0 = 0$ = suku pertama
- $F_1 = 1$ = suku kedua

String adalah deretan berhingga karakter berbentuk : $a_1a_2a_3a_4...a_n$

Panjang string S adalah jumlah karakter di dalam string tersebut.
contoh:  
- informatika adalah string dengan panjang 11 karakter
- 10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan $\lambda$, panjangnya = 0
### Penjumlahan deretan 
Jumlah deretan adalah: 
$a_m,{a_m}{_+}{_1},{a_m}{_+}{_2}...a_n$
$a_m{_+}{a_m}{_+}{_1},{a_m}{_+}{_2}...a_n$
atau dalam notasi sumasi:
![image](https://hackmd.io/_uploads/HkF-N6xXye.png)
keterangan: 
- k = indeks summasi
- m = batas bawah indeks
- n = batas atas indeks

Contoh: 
1. Berapa nilai 
![image](https://hackmd.io/_uploads/Bk8Vr6gX1x.png)
jawaban: 
![image](https://hackmd.io/_uploads/HyqiH6e7ye.png)
2. Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
![image](https://hackmd.io/_uploads/Bykk8pg7kl.png)
3. Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya: 
![image](https://hackmd.io/_uploads/SyvbIaxmkg.png)
4. Hitung nilai 
![image](https://hackmd.io/_uploads/B13tIplQkl.png)
jawaban: 
![image](https://hackmd.io/_uploads/SyYoITgm1l.png)
gunakan rumus: 
![image](https://hackmd.io/_uploads/rJtpU6lmJg.png)
maka: ![image](https://hackmd.io/_uploads/r1DJvalXkl.png)

### Sumasi ganda: 
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.
Contoh: 
![image](https://hackmd.io/_uploads/BykuD6xmke.png)
Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar: 
![image](https://hackmd.io/_uploads/SJWcvTxmkl.png)

Contoh penggunaan: 
Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
![image](https://hackmd.io/_uploads/SyzJdTe71l.png)
jawaban: 
Operasi + terdapat di dalam pernyataan x = x + 2
Operasi ini dilakukan satu kali pada setiap pengulangan
Jumlah seluruh operasi + adalah:
![image](https://hackmd.io/_uploads/HkNjdpeXkx.png)

## B. Rekursi
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 
Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

### Fungsi Rekursif
Fungsi rekursif didefinisikan oleh dua bagian:
1. Basis 
     - Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
     - Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
2. Rekurens
     - Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
     - Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh soal 1: 
Misalkan f didefinsikan secara rekusif sbb
![image](https://hackmd.io/_uploads/Bktx8rWQke.png)
Tentukan nilai f(4)!
penyelesaian: 
f(4) = 2f(3) + 4 
     =  2(2f(2) + 4) + 4
	 =  2(2(2f(1) + 4) + 4) + 4
	 =  2(2(2(2f(0) + 4) + 4) + 4) + 4
	 =  2(2(2(2.3 + 4) + 4) + 4) + 4	
	 =  2(2(2(10) + 4) + 4) + 4
	 =  2(2(24) + 4) + 4
	 =  2(52) + 4
	 = 108	
Cara lain:
f(0) = 3
f(1) = 2f(0) + 4 = 2.3  + 4 = 10
f(2) = 2f(1) + 4 = 2.10 + 4 = 24
f(3) = 2f(2) + 4 = 2.24 + 4 = 52
f(4) = 2f(3) + 4 = 2.52 + 4 = 108
Jadi, f(4) = 108.
Contoh soal 2:
Nyatakan n! dalam definisi rekursif
penyelesaian:
![image](https://hackmd.io/_uploads/rJmddrZ7kg.png)
Jadi, f(4) = 108.
Contoh soal 3:
Nyatakan n! dalam definisi rekursif
penyelesaian:
![image](https://hackmd.io/_uploads/HJBMtBWQke.png)
Misalkan f(n) = n!, maka:
![image](https://hackmd.io/_uploads/ByZLKSWXyg.png)
Menghitung 5! secara rekursif adalah:
5! = 5.4! = 5.4.3! = 5.4.3.2! 
		  = 5.4.3.2.1! 
          = 5.4.3.2.1.0!	
          = 5.4.3.2.1.1 
          = 120
contoh soal 3:
Barisan Fibonacci  0, 1, 1, 2, 3, 5, 8, 11, 19, …. Dapat dinyatakan secara rekursif sebagai berikut:
![image](https://hackmd.io/_uploads/H1y22rZ7yx.png)
contoh soal 4:
Fungsi (polinom) Chebyshev dinyatakan sebagai:
![image](https://hackmd.io/_uploads/ryKC3Sbm1l.png)
contoh soal 5:
![image](https://hackmd.io/_uploads/SJis6SZ7Je.png)
![image](https://hackmd.io/_uploads/Hy-ppr-Q1x.png)
sehingga: ![image](https://hackmd.io/_uploads/S1leABZ7Jl.png)
contoh soal 6:
![image](https://hackmd.io/_uploads/B1Jc-IW7yg.png)
penyelesaian:
![image](https://hackmd.io/_uploads/SkbgGLZQkx.png)
contoh soal 7:
![image](https://hackmd.io/_uploads/HyJGfL-QJe.png)
penyelesaian:
![image](https://hackmd.io/_uploads/rkgEGUZ71x.png)
### Struktur Rekursif
Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![image](https://hackmd.io/_uploads/rJDtGU-Qkl.png)
- Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.
- Jumlah anak pada setiap simpul bisa 1, 2, atau 0.
- Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)
- Simpul yang tidak mempunyai anak disebut simpul daun (leave).
Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).
![image](https://hackmd.io/_uploads/SJzAzL-7Jx.png)
Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:

	(i) Basis: kosong adalah pohon biner
	(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka adalah pohon biner
Proses pembentukan pohon biner secara rekursif:
![image](https://hackmd.io/_uploads/HkoGXU-71l.png)




























