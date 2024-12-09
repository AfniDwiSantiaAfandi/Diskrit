---
title: UAS

---

# UAS Matematika Diskret

#### Soal dan jawaban 1
|No|P |Q |R |S|$(P\to Q)$|$(R\to S)$|$(P\to Q)\to(R\to S)$|
| -| -| -| -| -| -|-|-|
|1.|T |T |T |T |T |T|T|              
|2.|T |T |T |F |T |F|F|
|3.|T |T |F |T |T |T|T|
|4.|F |F |T |F |T |F|F|
|5.|T |F |T |T |F |T|T|
|6.|F |T |F |F |T |T|T|
|7.|F |F |F |T |T |T|T|
|8.|F |T |T |T |T |T|T|

#### Soal dan jawaban 2
![graph](https://hackmd.io/_uploads/HkIZaGE41e.png)


**a. Hitung Closeness Centrality**
|Node| A | B | C | D | E | F |
| -- | --| --| --| --| --| --|
| A  | 0 | 1 | 2 | 2 | 3 | 4 |
| B  | 1 | 0 | 1 | 1 | 2 | 3 |
| C  | 2 | 1 | 0 | 1 | 2 | 3 |
| D  | 2 | 1 | 1 | 0 | 1 | 2 |
| E  | 3 | 2 | 2 | 1 | 0 | 1 |
| F  | 4 | 3 | 3 | 2 | 1 | 0 |

**Rumus:**
$C_C(v) = \frac{n-1}{\sum_{u \in V} d(v, u)}$

penyelesaian:
##### Node A
$C_C(v) = \frac{6-1}{12} = \frac{5}{12} = 0,416$
##### Node B
$C_C(v) = \frac{6-1}{8} = \frac{5}{8} = 0,625$
##### Node C
$C_C(v) = \frac{6-1}{9} = \frac{5}{9} = 0,6$
##### Node D
$C_C(v) = \frac{6-1}{7} = \frac{5}{7} = 0,714$
##### Node E
$C_C(v) = \frac{6-1}{9} = \frac{5}{9} = 0,6$
##### Node F
$C_C(v) = \frac{6-1}{13} = \frac{5}{13} = 0,384$

**b. Hitung Betweenness Centrality**
**Rumus:**







