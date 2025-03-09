# SISTEM PERSAMAAN LINIER

Nama    : MUHAMMAD UMAR FARUQ

NIM     : 230411100008

Email   : umrfrqqq@gmail.com




## Pengertian Sistem Persamaan Linier
Sistem Persamaan Linier (SPL) adalah kumpulan dari dua atau lebih persamaan linier yang memiliki variabel yang sama dan harus diselesaikan secara bersamaan. Persamaan linier sendiri merupakan persamaan matematika di mana setiap variabel berpangkat satu dan tidak terdapat perkalian antar variabel.

Secara umum, SPL dengan dua variabel dapat dituliskan sebagai:

$$
\begin{cases} 
a_1x + b_1y = c_1 \\ 
a_2x + b_2y = c_2  
\end{cases}
$$
 
​
 
di mana 𝑥x dan 𝑦y adalah variabel yang dicari, sedangkan 𝑎1,𝑎2,𝑏1,𝑏2,𝑐1,a1,a2,b1,b2,c1, dan 𝑐2
adalah konstanta.


## Mengapa Sistem Persamaan Linier Penting?

SPL memiliki banyak aplikasi dalam kehidupan sehari-hari, mulai dari bidang teknik, ekonomi, hingga ilmu komputer. Contohnya:

* Di bidang ekonomi, SPL digunakan untuk menentukan keseimbangan antara permintaan dan penawaran.
* Dalam teknik dan fisika, SPL digunakan untuk menganalisis rangkaian listrik dan sistem mekanik.
* Di ilmu komputer, SPL sering diterapkan dalam kecerdasan buatan dan pemrosesan data.


## Solusi Persamaan Linier

1. Penyelesaian Tunggal (Unique Solution)
Definisi: Sistem persamaan linier memiliki satu solusi jika garis-garis yang merepresentasikan persamaan tersebut berpotongan di satu titik.

Contoh: Misalkan kita memiliki sistem persamaan berikut: 

$
\begin{align*}
2x + 3y &= 6 \quad (1) \\
x - y &= 1 \quad (2)
\end{align*}
$

Jika kita menyelesaikan sistem ini, kita akan menemukan satu titik \((x, y)\) yang memenuhi kedua persamaan.  
Misalnya, solusi dari sistem ini adalah: 

$
x = 3, \quad y = 0
$

2. Banyak Penyelesaian (Infinite Solutions)
Definisi: Sistem persamaan linier memiliki banyak solusi jika garis-garis yang merepresentasikan persamaan tersebut tumpang tindih (berimpit).

Contoh: Misalkan kita memiliki sistem persamaan berikut: 

$
\begin{align*}
2x + 4y &= 8 \quad (1) \\
x + 2y &= 4 \quad (2)
\end{align*}
$

Persamaan (1) dapat disederhanakan menjadi \( x + 2y = 4 \), yang sama dengan persamaan (2).  
Karena kedua persamaan ini merepresentasikan garis yang sama, maka ada **banyak solusi**, yaitu semua pasangan \((x, y)\) yang memenuhi: 

$
x + 2y = 4
$

3. Tidak Ada Penyelesaian (No Solution)
Definisi: Sistem persamaan linier tidak memiliki solusi jika garis-garis yang merepresentasikan persamaan tersebut sejajar dan tidak pernah berpotongan.

Contoh: Misalkan kita memiliki sistem persamaan berikut: 

$
\begin{align*}
2x + 3y &= 6 \quad (1) \\
2x + 3y &= 8 \quad (2)
\end{align*}
$

Kedua persamaan ini memiliki koefisien yang sama untuk \( x \) dan \( y \), tetapi konstanta di sisi kanan berbeda.  
Ini berarti kedua garis **sejajar** dan **tidak akan pernah berpotongan**, sehingga **tidak ada solusi** untuk sistem ini.

<iframe scrolling="no" title="Systems of Linear Equations - Practice" src="https://www.geogebra.org/material/iframe/id/dbthscjy/width/800/height/520/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/true/ctl/false" width="800px" height="520px" style="border:0px;"> </iframe>

### Eliminasi
**Definisi:** Metode eliminasi adalah teknik untuk menyelesaikan sistem persamaan linier dengan mengeliminasi satu variabel pada satu waktu, sehingga sistem dapat diselesaikan dengan lebih mudah.

**Contoh:** Misalkan kita memiliki sistem persamaan berikut:

$
\begin{align*}
2x + 3y &= 6 \quad (1) \\
x - y &= 1 \quad (2)
\end{align*}
$

**Langkah-langkah:**
1. Dari persamaan (2), kita ekspresikan \( x \) dalam bentuk \( y \): 

   $
   x = y + 1
   $

2. Substitusi nilai \( x \) ke dalam persamaan (1):  

   $
   2(y + 1) + 3y = 6
   $
   $
   2y + 2 + 3y = 6
   $
   $
   5y + 2 = 6
   $
   5y = 4 \quad \Rightarrow \quad y = \frac{4}{5}
   $

3. Substitusi \( y = \frac{4}{5} \) kembali ke dalam persamaan (2): 

   $
   x = \frac{4}{5} + 1 = \frac{9}{5}
   $

**Solusi:**

$
\left( x = \frac{9}{5}, \quad y = \frac{4}{5} \right)
$

### Eliminasi Gaus
**Definisi:**  
Eliminasi Gauss adalah metode sistematis untuk menyelesaikan sistem persamaan linier dengan mengubah matriks koefisien menjadi bentuk segitiga atas.

**Contoh:**  
Misalkan kita memiliki sistem persamaan berikut:

$
\begin{align*}
2x + 3y + z &= 1 \quad (1) \\
4x + y - z &= 2 \quad (2) \\
-2x + y + 2z &= 3 \quad (3)
\end{align*}
$

1. Tulis sistem dalam bentuk matriks augmented:

   $
   \begin{bmatrix} 
   2 & 3 & 1 & | & 1 \\  
   4 & 1 & -1 & | & 2 \\  
   -2 & 1 & 2 & | & 3  
   \end{bmatrix}
   $

2. Lakukan operasi baris elementer untuk mengubahnya menjadi bentuk segitiga atas.

   Setelah beberapa langkah, kita mendapatkan:

   $
   \begin{bmatrix} 
   2 & 3 & 1 & | & 1 \\  
   0 & -5 & -3 & | & 0 \\  
   0 & 0 & 1 & | & 1  
   \end{bmatrix}
   $

3. Dari sini, kita bisa menyelesaikan dengan **substitusi mundur** untuk menemukan \( x \), \( y \), dan \( z \).

### Solusi Grafik
**Definisi:**  
Metode grafik menyelesaikan sistem persamaan linier dengan menggambar grafik setiap persamaan dan mencari titik potongnya.

**Contoh:**

$
\begin{align*}
y &= 2x + 1 \quad (1) \\
y &= -x + 4 \quad (2)
\end{align*}
$

Titik potong dari kedua grafik adalah **solusi dari sistem**.

```{code-cell} python
import numpy as np
import matplotlib.pyplot as plt

# Pastikan Matplotlib berjalan di Jupyter Notebook
%matplotlib inline

# Definisikan rentang x
x = np.linspace(-5, 5, 100)

# Definisikan dua persamaan linier
y1 = 2*x + 1   # y = 2x + 1
y2 = -x + 4    # y = -x + 4

# Cari titik potong kedua garis
sol_x = (4 - 1) / (2 + 1)  # x = (4 - 1) / (2 + 1)
sol_y = 2 * sol_x + 1      # y = 2x + 1

# Buat plot
plt.figure(figsize=(8, 6))
plt.plot(x, y1, label=r'$y = 2x + 1$', color='blue', linewidth=2)
plt.plot(x, y2, label=r'$y = -x + 4$', color='red', linewidth=2)

# Tandai titik potong
plt.scatter(sol_x, sol_y, color='black', zorder=3, s=100, label=f'Solusi: $({sol_x:.2f}, {sol_y:.2f})$')

# Anotasi titik potong agar lebih jelas
plt.annotate(f'({sol_x:.2f}, {sol_y:.2f})', 
             xy=(sol_x, sol_y), 
             xytext=(sol_x + 0.5, sol_y - 1),
             fontsize=12,
             arrowprops=dict(facecolor='black', shrink=0.05))

# Tambahkan sumbu x dan y
plt.axhline(0, color='black', linewidth=1)
plt.axvline(0, color='black', linewidth=1)

# Tambahkan grid untuk memperjelas
plt.grid(True, linestyle='--', alpha=0.6)

# Tambahkan label dan judul
plt.xlabel('x', fontsize=14)
plt.ylabel('y', fontsize=14)
plt.title('Solusi Sistem Persamaan Linier dengan Grafik', fontsize=16)
plt.legend(fontsize=12)

# Tampilkan grafik
plt.show()


```{tableofcontents}
```
