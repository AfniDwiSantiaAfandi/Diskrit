---
title: Logika Matematika

---

# Logika Matematika

## Negasi
Negasi adalah penyangkalan atau kebalikan dari suatu pernyataan. Negasi ditandai dengan simbol (~). Jika preposisi awal p bernilai benar, maka pernyataan negasinya (~p) adalah salah. 
| p | $\neg p$ |
| -------- | -------- | 
| B     | S     | 
| S     | B     |

Contoh:
 1. p: Semua anak suka menonton film. (benar)
~p: Tidak semua anak suka menonton film. (salah)
2. p: Amir memiliki banyak buku. (benar) 
~p: Amir tidak memiliki buku. (salah)

## Konjungsi
Konjungsi adalah pernyataan majemuk dengan kata hubung “dan”. Sehingga, notasi “p ∧ q” dibaca “p dan q”.
Contoh: 
| p | q | p^q |
| -------- | -------- | -------- |
| B     | B     |  B   |
| S     | B     |  S   |

Contoh:
p: Echidna adalah mamalia yang bertelur. (benar) 
q: Platipus adalah mamalia yang bertelur.(benar) 
p^q: Echidna dan platipus adalah hewan mamalia yang bertelur. (benar)

Jika salah satu premisnya bernilai salah maka konjungsinya sudah pasti bernilai salah juga. Contohnya: 
p: Katak adalah kelompok hewan reptil. (salah) 
q: Buaya adalah kelompok hewan reptil. (benar) 
p^q: Katak dan buaya adalah kelompok hewan reptil. (salah)

## Disjungsi
Disjungsi adalah pernyataan majemuk dengan kata hubung “atau”. Sehingga notasi “p∨q” dibaca “p atau q”.
| p | q | p∨q |
| -------- | -------- | -------- |
| B     | S     | B     |

Contoh:
p: Paus adalah mamalia (benar)
q: Paus adalah herbivora (salah)
p∨q: Paus adalah mamalia atau herbivora (benar)

# Implikasi
Implikasi adalah pernyataan majemuk dengan kata hubung “jika… maka…” Sehingga notasi dari “p ⇒ q” dibaca “Jika p, maka q”


| p | q | p ⇒ q |
| -------- | -------- | -------- |
| B     | B    | B     |

Contoh:
p: Andi belajar dengan aplikasi quipper. (benar)
q: Andi dapat belajar di mana saja. (benar)
p ⇒ q: Jika Andi belajar dengan aplikasi quipper, maka Andi dapat belajar dari mana saja (benar)

## Biimplikasi
Biimplikasi adalah pernyataan majemuk dengan kata hubung “… jika dan hanya jika”. Sehingga, notasi dari “p ⇔ q” akan dibaca “p jika dan hanya jika q”.
Biimplikasi akan bernilai benar jika sebab dan akibatnya (pernyataan p dan q) bernilai sama. Baik itu sama-sama benar, atau sama-sama salah.
Contoh:
Pintu akan terbuka jika Anda memasukkan kunci, dan pintu hanya akan terbuka jika Anda memasukkan kunci.


## Latihan Soal
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$