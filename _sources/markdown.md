## Penyelesaian Sistem Persamaan Linier

### Operasi Baris Elementer

### Eliminasi Gaus

### Contoh Soal 1
selesaikan dengan eliminasi gaus:

$$
\begin{split}
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2
\end{array}
\end{split}
$$

Langkah 1: Tulis dalam Bentuk Matriks Augmented

$$
\begin{split}
\begin{bmatrix}
1&2&3&|6\\
2&4&6&|12\\
0&1&1&|2
\end{bmatrix}
\end{split}
$$

Langkah 2: Eliminasi Baris dengan: 

$$\begin{array}{cc}
R_2 \rightarrow R_2 - 2R_1
\end{array}
$$

$$
\begin{split}
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
\end{split}
$$

Langkah 3: Baris kedua dirubah menjadi 0 = 0

$$
\begin{split}
\begin{aligned}
x_1+2x_2+3x_3&= 6\\
x_2+x_3&=2
\end{aligned}
\end{split}
$$

Langkah 4: Substitusi dari persamaan kedua:

$$
\begin{array}{cc}
x_2=2-x_3
\end{array}
$$

Substitusikan ke persamaan pertama:

$$
\begin{split}
\begin{array}{cc}
x_1+2(2-x_3)+3x_3&=6\\
x_1+4-2x_3+3x_3&=6\\
x_1+4+x_3&=6\\
x_1=&2-x_3
\end{array}
\end{split}
$$

Kesimpulan:

$$
\begin{split}
\begin{aligned}
x_1&=2-x_3\\
x_2&=2-x_3\\
x_3&=x_3
\end{aligned}
\end{split}
$$

### Contoh Soal 2
selesaikan dengan eliminasi gaus:

$$\begin{split}
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=3
\end{array}
\end{split}
$$

Tulis dalam Bentuk Matriks Augmented

$$
\begin{split}
\begin{bmatrix}
  1 & 1 & 1 & | 3 \\
  2 & 0 & 1 & | 5 \\
  1 & 2 & 0 & | 3
\end{bmatrix}
\end{split}
$$


1. **Nol-kan elemen di bawah pivot pertama**
   - Gunakan operasi baris:
     - $\( R_2 \leftarrow R_2 - 2R_1 \)$
     - $\( R_3 \leftarrow R_3 - R_1 \)$

   Matriks menjadi:

$$
   \begin{split}
   \begin{bmatrix}
     1 & 1 & 1 & | 3 \\
     0 & -2 & -1 & | -1 \\
     0 & 1 & -1 & | 0
   \end{bmatrix}
   \end{split}
$$

2. **Nol-kan elemen di bawah pivot kedua**
   - Gunakan operasi:
     - $\( R_3 \leftarrow R_3 + \frac{1}{2} R_2 \)$

   Matriks menjadi:

$$
   \begin{split}
   \begin{bmatrix}
     1 & 1 & 1 & | 3 \\
     0 & -2 & -1 & | -1 \\
     0 & 0 & -1.5 & | -0.5
   \end{bmatrix}
   \begin{split}
$$

Substitusi Balik

- Dari baris ketiga: $\( -1.5x_3 = -0.5 \Rightarrow x_3 = \frac{1}{3} \)$
- Dari baris kedua: $\( -2x_2 - x_3 = -1 \Rightarrow x_2 = \frac{1}{3} \)$
- Dari baris pertama: $\( x_1 + x_2 + x_3 = 3 \Rightarrow x_1 = \frac{7}{3} \)$

Solusi Akhir

$$
\begin{split}
\begin{cases}
  x_1 = \frac{7}{3} \\
  x_2 = \frac{1}{3} \\
  x_3 = \frac{1}{3}
\end{cases}
\end{split}
$$

### Contoh Soal 3
selesaikan dengan eliminasi gaus:

$$\begin{split}
\begin{array}{cc}
2x_1+2x_2&=6\\
x_1+x_2&=2
\end{array}
\end{split}
$$

### Contoh Soal 4
selesaikan dengan eliminasi gaus:

$$\begin{split}
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
\end{split}
$$

```{tableofcontents}
```