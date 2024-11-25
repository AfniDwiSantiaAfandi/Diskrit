---
title: Social Network Analysis (SNA)

---

# Social Network Analysis (SNA)
SNA merupakan bidang kajian yang mengekplorasi tentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. 
Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan graph
![image](https://hackmd.io/_uploads/rk3r-MJ71g.png)
![image](https://hackmd.io/_uploads/Byg7zfyQkg.png)
Terdapat node yang mewakili orang atau individu atau aktor. Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut. Cari node yang paling penting dalam suatu jaringan.

## Centrality (Pusat Jaringan)
Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network. 
Centrality dibagi menjadi 4 jenis: 
### 1. Degree Centrality
Degree centrality adalah jumlah koneksi yang dimiliki sebuah node. Degree Centrality akan menghitung bobot suatu node berdasar banyaknya edge yang terbentuk antara node i dengan node yang lainnya. 
Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut :
- Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
- Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 

Rumus Degree Centrality: 
![image](https://hackmd.io/_uploads/B1RNHG1Xkx.png)
keterangan: 
- $\Sigma$ = Penjumlahan atas semua simpul yang terhubung dengan$v_i$
- $C_D$($v_i$) = Degree centrality dari simpul $v_i$
- $d_i$ = Derajat (jumlah koneksi) dari smpul $v_i$
- $A_i{_j}$ = Elemen dari matriks adjensi jaringan. Nilaiya 1 jika simpul $i$ terhubung dengan $j$, dan 0 jika tidak. 

Rumus Normalisasi Degree Centrality:
![image](https://hackmd.io/_uploads/SJ5JgVgQkx.png)
keterangan: 
- $d_i$ = Jumlah koneksi simpul $v_i$ 
- $n-1$ = Jumlah simpul lain dalam jaringan 

Contoh :
![image](https://hackmd.io/_uploads/S1-bW4xXkx.png)
penjelasan : 
Untuk  node 1, degree centrality adalah 3.
Normalisasi degree centrality adalah  
3/(9-1)=3/8.

### 2. Closeness Centrality
Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

Rumus Average Distance: 
![image](https://hackmd.io/_uploads/HJxdfNeQkx.png)
keterangan: 
- $D_a{_v}{_g} (v_i)$ = Rata-rata jarak dari simpul $v_i$ ke semua simpul lainnya dalam jaringan 
- $g(v_i,v_j)$ = path terpendek antara simpul $v_i$ dan $v_j$
- $n$ = Jumlah total simpul dalam jaringan

Rumus Closeness Centrality: 
![image](https://hackmd.io/_uploads/rJTgSEeXke.png)
keterangan: 
- $C_c(v_i)$ = closeness centrality dari simpul $v_i$
- $g(v_i,v_j)$ = path terpendek antara simpul $v_i$ dan $v_j$
- $n-1$ = Jumlah simpul lain dalam jaringan

Contoh: 
![image](https://hackmd.io/_uploads/Bk6cHVemkx.png)
![image](https://hackmd.io/_uploads/S13oB4eX1e.png)
penjelasan: 
![image](https://hackmd.io/_uploads/HyXTHNxQkg.png)
### 3. Betweenness Centrality
Betweeness centrality adalah cara untuk mengukur seberapa penting sebuah titik (node) dalam sebuah jaringan. 

Skor betweeness centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi

Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas
- Menghitung jumlah lintasan terpendek yang melewati suatu node
- Node dengan betweenness tinggi adalah penting dalam komunikasi dan penyebaran informasi.

Rumus Betweenness Centrality: 
![image](https://hackmd.io/_uploads/SJ-fj4lmkg.png)
keterangan: 
- $\sigma _s{_t}$ = Jumlah lintasan terpendek antara simpul $s$ dan $t$ (tanpa memperhatikan smpul lain)
- $\sigma _s{_t} (v_i)$ = Jumlah lintasan terpendek antara simpul $s$ dan $t$ yang melewati simpul $v_i$
- $\Sigma$ 
$v{_s}{_\neq}v{_i}{_\neq}v{_t}\in V, s<t$ = Penjumlahan dilakukan untuk semua pasangan simpul s dan t, dimana $v_i$ menjadi simpul penghubung diantaranya. 
![image](https://hackmd.io/_uploads/rJioTVemJx.png)
![image](https://hackmd.io/_uploads/HkiM0Eg7Jx.png)
![image](https://hackmd.io/_uploads/SkX-ANeXyx.png)
Rumus Normalisasi Betweenness Centrality: 
![image](https://hackmd.io/_uploads/SyoVREgQ1x.png)
keterangan: 
- $C_B(i)$ = Nilai asli betweenness centrality dari node yang dihitung 
- $n$ = jumlah total node dalam jaringan
- $(n-1)(n-2)$ = Nilai maksimum betweenness centrality dalam jaringan. 
 















