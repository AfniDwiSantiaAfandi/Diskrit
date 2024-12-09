---
title: Deretan dan Rekursi

---

# Deretan dan Rekursi
## A. Deretan (Sequence)
**Deretan** adalah suatu daftar bilangan yang disusun berdasarkan aturan tertentu. Setiap bilangan dalam deretan disebut sebagai **suku**.
### Jenis Deretan: 
#### 1. Deret Aritmatika
**Yaitu** bilangan yang memiliki pola tertentu dimana selisih antara dua suku berurutan selalu tetap (disebut beda, $b$) 
Misal: $2,5,8,11...$ selisih antar suku adalah $5-2=3, 8-5=3, dan 11-8=3$. Jadi selisih $(b)=3$

**Rumus suku ke-$n$**: 
$U_n=a+(n-1)$
keterangan: 
$a$ = suku pertama
$b$ = beda

**Rumus jumlah $n$ suku pertama** $(S_n)$: $(S_n)=\frac{n}{2}(2_a+(n-1)b$

##### Contoh Soal:
Diberikan deret aritmatika: $3,7,11,15...$
a. Tentukan suku ke-10
b. Hitung jumlah 10 suku pertama
Penyelesaian: 
a. Suku ke-10 $(U_1{_0})$:
$U_1{_0}=a+(10-1)$
maka, 
$b=3+9(4)=3+36=39$

b. Jumlah 10 suku pertama $(S_1{_0})$:
$(S_1{_0})= \frac{10}{2}(2(3)+(10-1)(4))$
$(S_1{_0}) =5(6+36)=5(42)=210$


#### 2. Deret Geometri
**Yaitu** bilangan yang memiliki pola tertentu dimana perbandingan antara dua suku berurutan selalu tetap. Perbandingan ini disebut rasio, $r$
**Rumus suku ke-$n$**:
$a \cdot r^{n-1}$ 
**Rumus jumlah $n$ suku pertama**: 
$(S_n)= a \frac{1-r^n}{1-r}(r\neq)$
##### Contoh Soal:
Diberikan deret geometri: $2,6,18,54...$
a. Tentukan suku ke-5:
b. Hitung jumlah 5 suku pertama.
Penyelesaian: 
* Suku pertama $(a) = 2$
* Rasio $(r)=6/2=3$

**a**. Suku ke-5 $(U_5)$:
$(U_5)=a.r{^5}^{-1}=2.3^4=2.81=162$

**b.** Jumlah 5 suku pertama $(S_5)$:
$(S_5) = 2\frac{1-3^5}{1-3} =2\frac{1-243}{-2}=2.121=242$
#### 3. Deret Fibonacci
**Yaitu** deret secara berulang, di mana suku berikutnya didefinisikan berdasarkan suku sebelumnya. 
**Rumus suku ke-$n$**:
$F_n = F_n{_-}{_1}+F_n{_-}{_2},F_1=1,F_2=1$
keterangan: 
- $F_n$ = menunjukkan nilai suku ke-$n$ dalam deret fibonacci
- $F_n{_-}{_1}$ = nilai suku sebelum suku ke-$n$
- $F_n{_-}{_2}$ = nilai dua suku sebelum suku ke-$n$
- $F_1 = 1$ = suku pertama
- $F_2 = 1$ = suku kedua

##### Contoh Soal:
Diberikan deret Fibonacci: $1,1,2,3,5,8$
Tentukan suku ke-7 dari deret ini: 
Penyelesaian: 
* Suku ke-3: $F_3=F_2+F_1=1+1=2$
* Suku ke-4: $F_4=F_3+F_2=2+1=3$
* Suku ke-5: $F_5=F_4+F_3=3+2=5$
* Suku ke-6: $F_6=F_5+F_4=5+3=8$
* Suku ke-7: $F_7=F_6+F_5=8+5=13$

Jadi suku ke-7 adalah **13**
## B. Rekursi 
**Rekursi** adalah cara untuk menyelesaikan masalah atau mendefinisikan konsep dengan membaginya menjadi bagian-bagian yang lebih kecil hingga mencapai kondisi sederhana **(base case)**. Ini berguna untuk pola berulang seperti:
* Faktorial
* Deret Fibonacci
### Ciri-Ciri Rekursi
* Basis (Base Case): Nilai awal yang diketahui atau kondisi yang menghentikan rekursi.
* Relasi Rekursif (Recursive Relation): Rumus yang mendefinisikan objek berdasarkan nilai-nilai sebelumnya.
#### Contoh Soal 
1. Faktorial dari $n$ adalah hasil perkalian semua bilangan dari 1 sampai $n$.
$n! =\begin{cases} 1, & \text{jika } n = 0 \text{ atau } n = 1 \quad (\text{Base Case}) \\ 
n \cdot (n-1)!, & \text{jika } n > 1 \quad (\text{Recursive Case})\end{cases}$
Maka, **perhitungan Faktorial Rekursif**:
Misalnya 5! :
* 5! = 5 . 4!
* 4! = 4 . 3!
* 3! = 3 . 2!
* 2! = 2 . 1!
* 1! = 1 . 1! **(Base Case)**
Hasilnya adalah: 
5! = 5.4.3.2.1= **120**
2. Deret Fibonacci didefinisikan sebagai:
$F_n =\begin{cases} 1, & \text{jika } n = 1 \text{ atau } n = 2 \quad (\text{Base Case}) \\ 
F_{n-1} + F_{n-2}, & \text{jika } n > 2 \quad (\text{Recursive Case})\end{cases}$
Deret ini menghasilkan angka: $1,1,2,3,5,8,13..$
Hitung Fibonacci Rekursif untuk $F_6$ !
**Penyelesaian**: 
Untuk menghitung $F_6$ gunakan definisi rekursif:
$F_n = F_{n-1} + F_{n-2}$
mulai dari 6 dan pecahkan hingga mencapai **Base Case:**
* $F_6 = F_5 + F_4$
* $F_5 = F_4 + F_3$
* $F_4 = F_3 + F_2$
* $F_3 = F_2 + F_1$
* $F_2 = 1$
* $F_1 = 1$
maka :
* $F_3 = F_2 + F_1 = 1 + 1 = 2$ 
* $F_4 = F_3 + F_2 = 2 + 1 = 3$
* $F_5 = F_4 + F_3 = 3 + 2 = 5$
* $F_6 = F_5 + F_4 = 5 + 3 = 8$
Jadi $F_6 = 8$
3. Hitung jumlah $6$ suku pertama dari deret Fibonacci $(S_6)$:
**Penyelesaian:**
Jumlah $6$ suku pertama: $S_6 = F_1 + F_2 + F_3 + F_4 + F_5 + F_6$
Gunakan nilai yang telah dihitung pada soal nomor 2 tadi
Maka, $S_6 = 1 + 1 + 2 + 3 + 5 + 8= 20$

