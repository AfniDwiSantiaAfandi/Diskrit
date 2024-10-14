---
title: Aljabar Boolean

---

## Aljabar Boolean dan Gerbang Logika 
### A. Aljabar Boolean 
Aljabar boolean adalah aljabar yang berhubungan dengan variabel biner dan operasi logik, dimana aljabar boolean adalah sistem matematika yang terbentuk dari 3 operator logika berupa "negasi", Logika "AND" dan "OR".

Variabel yang digunakan dalam Aljabar Boolean hanya memiliki dua kemungkinan yaitu logika "0" dan logika "1" tetapi ekspresi jumlah variabel yang dihasilkan tak terbatas yang semuanya dilabeli secara individual untuk mewakili input ke ekspresi. Sebagai contoh, sebuah variabel A , B, C dll, dihasilkan sebuah ekspresi logis yaitu A + B = C, tetapi setiap variabel hanya dapat berupa 0 atau  1.

Dalam menyelesaikan permasalahan yang berkaitan dengan aljabar Boolean dua dan tiga variabel maka digunakan sifat identitas, disamping itu prinsip dualitas juga digunakan pada sifat-sifat identitas. Jika A, B, dan C adalah Variabel Boolean, maka berlaku hukum/sifat berikut: 
1. Hukum Komutatif (Pertukaran)
Hukum komutatif adalah salah satu hukum dasar dalam aljabar Boolean yang menyatakan bahwa urutan operand dalam operasi AND (konjungsi) atau OR (disjungsi) tidak mempengaruhi hasil operasi tersebut. Dengan kata lain, hasil dari operasi akan tetap sama meskipun posisi operand ditukar.
Contoh: 

| Contoh 1     | Contoh 2     | 
| --------     | --------     |
|A + B = B + A | A . B = B . A|
2. Hukum Asosiatif (Pengelompokkan)
Hukum asosiatif adalah hukum yang menyatakan bahwa pengelompokan operand dalam operasi AND (konjungsi) atau OR (disjungsi) tidak mempengaruhi hasil dari operasi tersebut. Dalam aljabar Boolean, meskipun urutan operand tetap sama, kita dapat mengubah posisi tanda kurung tanpa memengaruhi hasil.
Contoh: 

| Contoh 1         |    Contoh 2      | 
| --------         | --------         |
|A+(B+C)=(A+B) + C | A.(B.C)=(A.B) . C|
3. Hukum Distributif
Hukum distributif adalah hukum yang mengatur bagaimana operasi AND (konjungsi) dan OR (disjungsi) dapat didistribusikan satu sama lain dalam suatu ekspresi Boolean. Hukum ini memungkinkan kita untuk menyederhanakan atau memperluas ekspresi Boolean dengan mengelompokkan operand dengan cara tertentu.
Contoh: 

| Contoh 1         |    Contoh 2       | 
| --------         | --------          |
|A.(B+C) = A+B+A.C |A+B.C = (A+B).(A+C)|

#### Prioritas Operasi Aljabar Boolean
Pada teorema Aljabar Boolean dikenal 3 operasi logika yaitu operasi logika OR,AND, dan NOT sehingga dapat dihasilkan berbagai bentuk fungsi logika. Demi memudahkan dalam pengoperasianya maka dipergunakan tanda kurung untuk memberikan prioritas. 
Berikut aturan prioritas operasi Aljabar Booolean: 
1. Bila terdapat tanda kurung maka diselesaikan terlebih dahulu.
2. Bila tidak terdapat tanda kurung, maka suatu penyataan logika diselesaikan dengan urutan : NOT, AND setelah itu OR.

### B. Gerbang Logika
Gerbang Logika adalah sebuah entitas untuk melakukan pengolahan input-input yang berupa bilangan biner. Hanya terdapat 2 kode bilangan biner yaitu, angka 0 dan 1. 

Tabel yang berisikan kombinasi variabel Input yang menghasilkan Output logis disebut dengan “Truth Table” atau “Tabel Kebenaran”.
Input dan Output pada Gerbang Logika hanya terdapat 2 level. Kedua Level tersebut pada umumnya dapat dilambangkan sebagai:
1.) 1 dan 0
2.) ON (Hidup) dan OFF (Mati)
3.) HIGH (tinggi) dan LOW (rendah)
4.) TRUE (benar) dan FALSE (salah)

#### Jenis Gerbang Logika
1. Gerbang AND 
Gerbang AND memerlukan 2 atau lebih input atau masukan untuk menghasilkan hanya 1 output atau keluaran. Gerbang logika AND akan menghasilkan Output logika 1 jika semua Inputnya bernilai logika 1. 
Dan akan menghasilkan Output logika 0 jika salah satu dari Inputnya bernilai logika 0. Simbol untuk menandai operasi gerbang logika AND adalah tanda titik “.” atau tidak memakai tanda sama sekali. Contohnya yaitu Z = X.Y atau Z = XY.
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 0        |
| 0        | 1        | 0        |
| 1        | 0        | 0        |
| 1        | 1        | 1        |
2. Gerbang OR
Gerbang logika OR memerlukan 2 atau lebih Input atau masukan untuk menghasilkan 1 Output atau keluaran. Gerbang OR akan menghasilkan Output 1 jika salah satu atau kedua Input bernilai logika 1.
Jika ingin menghasilkan Output logika 0, maka semua Inputnya harus bernilai logika 0. Operasi Logika OR biasanya ditandai dengan simbol Plus “+”. Contohnya yaitu : Z = X + Y.
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 0        |
| 0        | 1        | 1        |
| 1        | 0        | 1        |
| 1        | 1        | 1        |
3. Gerbang NOT 
Gerbang NOT hanya memerlukan sebuah Input atau masukan untuk menghasilkan hanya 1 Output. Gerbang NOT disebut juga dengan Inverter atau Pembalik. Karena menghasilkan Output yang berlawanan atau berkebalikan dengan Inputnya.
Artinya jika kita ingin mendapatkan Output dengan nilai Logika 0 maka Inputnya harus bernilai Logika 1. Gerbang NOT biasanya dilambangkan dengan simbol minus “-“ yang berada di atas variabel Inputnya.
Tabel kebenaran:

| x        | z        | 
| -------- | -------- | 
| 0        | 1        | 
| 1        | 0        | 
4. Gerbang NAND(NotAnd)
Gerbang NAND merupakan kombinasi dari Gerbang NOT dan Gerbang AND yang menghasilkan kebalikan dari Output Gerbang AND.
Gerbang NAND akan menghasilkan Keluaran Logika 0 apabila semua Inputnya pada Logika bernilai 1. Jika terdapat sebuah Input Logika yang bernilai 0 maka akan menghasilkan Output Logika 1.
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 1        |
| 0        | 1        | 1        |
| 1        | 0        | 1        |
| 1        | 1        | 0        |
5. Gerbang NOR (Not Or)
Gerbang NOR adalah kombinasi dari Gerbang NOT dan Gerbang OR yang menghasilkan kebalikan dari Output Gerbang OR.
Gerbang NOR akan menghasilkan Output Logika 0 jika salah satu dari Inputnya bernilai Logika 1. Jika ingin mendapatkan Output Logika 1, maka semua Inputnya harus bernilai Logika 0.
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 1        |
| 0        | 1        | 0        |
| 1        | 0        | 0        |
| 1        | 1        | 0        |
6. Gerbang X-OR
X-OR merupakan singkatan dari Exclusive OR yang terdiri dari 2 Input dan 1 Output Logika. Gerbang X-OR akan menghasilkan Output logika bernilai 1 jika semua Inputnya mempunyai nilai logika yang berbeda.
Jika nilai logika Inputnya sama, maka akan memberikan hasil Output logika bernilai 0.
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 0        |
| 0        | 1        | 1        |
| 1        | 0        | 1        |
| 1        | 1        | 0        |
7. Gerbang X-NOR
Mirip seperti X-OR, Gerbang logika X-NOR juga terdiri dari 2 Input dan 1 Output. X-NOR adalah singkatan dari Exclusive NOR dan merupakan kombinasi dari Gerbang NOT dan Gerbang X-OR.
Gerbang X-NOR akan menghasilkan Output logika 1 jika seluruh Inputnya bernilai logika yang sama. Akan menghasilkan Output logika 0 apabila semua Inputnya bernilai logika yang berbeda. Atau bisa dibilang merupakan kebalikan dari Gerbang X-OR (Exclusive OR).
Tabel kebenaran: 

| x        | y        | z        |
| -------- | -------- | -------- |
| 0        | 0        | 1        |
| 0        | 1        | 0        |
| 1        | 0        | 0        |
| 1        | 1        | 1        |

## Referensi
https://www.webstudi.site/2019/02/aljabar-boolean.html
https://teknikece.com/gerbang-logika/




