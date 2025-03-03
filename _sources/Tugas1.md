## Penyelesaian Sistem Persamaan Linier 

### Operasi Baris Elementer 
Operasi Baris Elementer adalah operasi yang dilakukan pada baris-baris suatu matriks untuk mempermudah proses penyelesaian system persamaan linier atau manipulasi matriks. Operasi ini digunakan dalam metode eliminasi Gauss dan Gauss-Jordan untuk mengubah matriks menjadi bentuk yang lebih sederhana, seperti matriks eselon baris atau matriks identifikasi. Tujuan utama dari OBE adalah untuk menyederhanakan matriks, terutama dalam menyelesaikan sistem persamaan linier, mencari invers matriks, atau menentukan rank matriks. OBE tidak mengubah solusi dari sistem persamaan linier yang direpresentasikan oleh matriks tersebut. 

Jenis-Jenis Operasi Baris Elementer (OBE)
1. Pertukaran baris 
Operasi ini menukarkan posisi dua baris dalam matriks. 
2. Perkalian baris dnegan konstanta bukan Nol 
Operasi ini mengalikan semua elemen dalam suatu baris dengan konstanta bukan nol 

Ciri-Ciri Baris Elementer 
1. Tidak mengubah solusi sistem persamaan linier
Operasi ini hanya mengubah bentuk sistem tanpa mengubah solusi dari sistem tersebut. 
2. Dapat digunakan untuk menyederhanakan matriks
Berguna dalam mencari invers matriks, menyelesaikan sistem persamaan linier, dan menentukan determinan. 
3. Operasi bersifat reversibel (dapat dibalik)
a. Pertukaran daua baris dapat dikembalikan dengan pertukaran yang sama. 
b. Penjumlahan dengan kelipatan baris lain dapat dikembalikan dengan operasi sebaliknya.

Contoh Penggunaan Operasi Baris Elementer 
1. Contoh Penggunaan dalam Eliminasi Gauss 
a. Digunakan untuk mencari elemen utama (pivot) di setiap kolom. 
b. Menggunakan OBE untuk membuat semua elemen di bawah pivot menjadi nol.
c. Melanjutkan proses ini untuk kolom-kolom berikutnya. 
2. Contoh penggunaan dalam eliminasi Gauss Jordan 
Eliminasi Gauss Jordan adalah variasi dari eliminasi Gauss yang lebih lanjut mengubah matriks menjadi bentuk eleson baris tereduksi. Dalam bentuk ini, semua elemen di aats dan di bawah pivot adalh nol, dan smeu pivot adalah 1. 

### Eliminasi Gauss 
Metode Eliminasi Gauss dikembangkan oleh Carl Friedrich Gauss (1777-1855). Carl adalah matematikawan berkebangsaan Jerman yang berkontribusi dalam geometri, teori bilangan, fungsi, dan teori probabilitas. 

Eliminasi Gauss adalah sebuah algoritma dalam aljabar untuk menyelesaikan sistem persamaan linier. Metode ini bekerja dengan mengubah sistem persamaan linier manjeadi bentuk matriks eselon baris (row echelon form) atau matriks eselon baris tereduksi (reduced row echelon form) melalui serangkaian operasi baris elementer. Bentuk eslon ini memudahkan kita untuk menemukan solusi dari sistem persamaan tersebut. 

#### Bentuk Eselon Baris 
Suatu matriks memiliki eselon baris jika memenuhi 3 kriteria berikut : 
1. Jika didalam baris terdapat elemen-elemen yang tidak semuanya 0, maka bilangan tak nol pertama di dalam baris tersebut adalah 1. 
2. Kalau terdapat baris-baris yang semua elemennya bernilai 0 semua, maka baris-baris tersebut harus dikelompokkan dan diletakkan dibagian bawah matriks. 
3. Jika terdapat dua barais berurutan yang memenuhi kriteria pertama, maka angka 1 dari baris yang lebih rendah ke kanan dari angka 1 baris yang diatasnya.

Terdapat 3 operasi yang dapat dilakukan 
1. Tukarkan posisi kedua persamaan. 
2. Kalikan persamaan dengan bilangan apa pun yang bukan nol. 
3. Gantikan suatu persamaan dengan jumlah persamaan itu sendiri dan kelipatan persamaan lainnya. 

Langkah - Langkah Eliminasi Gauss 
1. Representasi Matriks : Ubah sistem persamaan linier menjadi bentuk matriks augmented. Matriks augmented terdiri dari matrik koefisien dari variabel dan matriks kolom konstanta. 
2. Operasi Baris Elementer : Lakukan operasi baris elementer untuk mengubah matriks menjadi eselon baris. 
3. Membuat Nol dibawah dialog utama : Gunakan operasi baris elementer untuk membuat semua elemen di bawah dialog utama matriks menjadi nol. Ini akan menghasilkan matriks eselon baris.
4. Back Subtitution (Subtitusi Balik) : Setelah mendapatkan matriks eselon baris, gunakan substitusi balik untuk menemukan nilai variabel. 

### Contoh Soal 1
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2
\end{array}
$$

Penyelesaian
Langkah 1: Tulis dalam Bentuk Matriks Augmented
Bentuk matriks augmented dari sistem ini adalah:

$$
\begin{bmatrix}
1&2&3&|6\\
2&4&6&|12\\
0&1&1&|2
\end{bmatrix}
$$

Langkah 2: Eliminasi Baris
Kita akan menghilangkan elemen di bawah elemen utama di kolom pertama. Gunakan operasi:

$$
\begin{array}{cc}
R_2 \rightarrow R_2 - 2R_1
\end{array}
$$

Sehingga:

$$
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
$$

Langkah 3: Interpretasi
Baris kedua dirubah menjadi *0 = 0*

$$
\begin{aligned}
x_1+2x_2+3x_3&= 6\\
x_2+x_3&= 2
\end{aligned}
$$

Langkah 4: Substitusi
Dari persamaan kedua:

$$
\begin{array}{cc}
x_2=2-x_3
\end{array}
$$

Substitusikan ke persamaan pertama:

$$
\begin{array}{cc}
x_1+2(2-x_3)+3x_3&=6\\
x_1+4-2x_3+3x_3&=6\\
x_1+4+x_3&= 6\\
x_1=&2-x_3
\end{array}
$$

Kesimpulan
Solusi umum dari sistem ini adalah:

$$
\begin{aligned}
x_1&=2-x_3\\
x_2&=2-x_3\\
x_3 &= x_3
\end{aligned}
$$

### Contoh Soal 2 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=3
\end{array}
$$

Penyelesaian 
Langkah 1: Tulis dalam Bentuk Matriks Augmented

$$
\begin{bmatrix}
1&1&1&|3\\
2&0&1&|5\\
1&2&0&|3
\end{bmatrix}
$$

Langkah 2: Eliminasi Baris
Kita akan menghilangkan elemen di bawah elemen utama di kolom pertama.

$$
\begin{array}{cc}
R_2 \rightarrow R_2 - 2R_1
\end{array}
$$

$$
\begin{array}{cc}
R_3 \rightarrow R_3 - R_1
\end{array}
$$

Sehingga matriks berubah menjadi:

$$
\begin{bmatrix}
1&1&1&|3\\
0&-2&-1&|-1\\
0&1&-1&|0
\end{bmatrix}
$$

Selanjutnya, buat elemen utama di baris kedua menjadi 1 dengan membagi baris kedua dengan -2:

$$
\begin{array}{cc}
R_2 \rightarrow \frac{R_2}{-2}
\end{array}
$$

Hasilnya:

$$
\begin{bmatrix}
1&1&1&|3\\
0&1&\frac{1}{2}&|\frac{1}{2}\\
0&1&-1&|0
\end{bmatrix}
$$

Kemudian eliminasi elemen di bawah elemen utama dengan:

$$
\begin{array}{cc}
R_3 \rightarrow R_3 - R_2
\end{array}
$$

Sehingga diperoleh:

$$
\begin{bmatrix}
1&1&1&|3\\
0&1&\frac{1}{2}&|\frac{1}{2} \\
0&0&-\frac{3}{2}&|-\frac{1}{2}
\end{bmatrix}
$$

Langkah 3: Substitusi Balik
Dari baris ketiga:

$$
\begin{array}{cc}
-\frac{3}{2} x_3 = -\frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_3 = \frac{1}{3}
\end{array}
$$

Dari baris kedua:

$$
\begin{array}{cc}
x_2 + \frac{1}{2} x_3 = \frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2 + \frac{1}{2} \times \frac{1}{3} = \frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2 + \frac{1}{6} = \frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2 = \frac{1}{2} - \frac{1}{6} = \frac{3}{6} - \frac{1}{6} = \frac{2}{6} = \frac{1}{3}
\end{array}
$$

Dari baris pertama:

$$\begin{array}{cc}
x_1 + x_2 + x_3 = 3
\end{array}
$$

$$
\begin{array}{cc}
x_1 + \frac{1}{3} + \frac{1}{3} = 3
\end{array}
$$

$$
\begin{array}{cc}
x_1 = 3 - \frac{2}{3} = \frac{9}{3} - \frac{2}{3} = \frac{7}{3}
\end{array}
$$

Kesimpulan
Jadi, solusi dari sistem persamaan adalah:

$$\begin{aligned}
x_1&=\frac{7}{3}\\
x_2&=\frac{1}{3}\\
x_3&=\frac{1}{3}
\end{aligned}
$$

### Contoh Soal 3 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
2x_1+2x_2&=4\\
x_1+x_2&=2
\end{array}
$$

Penyelesaian 
Langkah 1 : Menyelesaikan ke bentuk matriks augmented 

$$
\begin{bmatrix} 
2&2&|4\\ 
1&1&|2 
\end{bmatrix}
$$

Langkah 2 : membuat elemen di bawah pivot menjadi nol. 

$$
\begin{array}{cc}
R_1 \leftarrow R_1 - 2R_2
\end{array}
$$

Setelah melakukan perhitungan kita mendapatkan :

$$
\begin{array}{cc}
R_1: 2 - 2 \cdot 1 = 0\\
2 - 2 \cdot 1 = 0\\
4 - 2 \cdot 2 = 0
\end{array}
$$

Sehingga matriks augmented menjadi : 

$$
\begin{bmatrix} 
1&1&|2\\
0&0&|0 
\end{bmatrix}
$$

Dari baris kedua, kita dapat mengekspresikan (x_1) dalam bentuk (x_2): 

$$
\begin{array}{cc}
x_1 + x_2 = 2 \Rightarrow x_1 = 2 - x_2
\end{array}
$$

Karena kita memiliki satu persamaan dengan dua variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan (x_2 = t), maka:

$$
\begin{array}{cc}
x_1 = 2 - t
\end{array}
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases} 
x_1=2-t\\
x_2=t
\end{cases}
$$

di mana (t) adalah parameter bebas.

### Contoh Soal 4 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
$$

Penyelesaian : 

1. Tulis sistem persamaan dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1&1&0&|&5\\
1&0&2&|&4
\end{bmatrix}
$$

2. Lakukan operasi baris untuk mendapatkan bentuk eselon baris:

$$
\begin{array}{cc}
R_2 \rightarrow R_2 
\end{array}
$$

Hasilnya : 

$$
\begin{bmatrix}
1&1&0&|&5\\
0&-1&2&|&-1
\end{bmatrix}
$$
$$
\begin{array}{cc}
R_2 \rightarrow \frac{R_2}{-1}
\end{array}
$$

Hasilnya : 

$$
\begin{bmatrix}
1&1&0&|&5\\
0&1&-2&|&1
\end{bmatrix}
$$

3. Lakukan substitusi mundur untuk menemukan solusi:

- Dari baris 2:

$$
\begin{array}{cc}
x_1 + x_2 = 2 \Rightarrow x_1 = 2 - x_2
\end{array}
$$

- Dari baris 1:

$$
\begin{array}{cc}
x_1 + x_2 = 5 \implies x_1 + (1 + 2x_3) = 5 \implies x_1 = 4 - 2x_3
\end{array}
$$

4. Solusi Akhir:

$$
\begin{aligned}
x_1&=4-2x_3\\
x_2&=1+2x_3\\
x_3&=x_3
\end{aligned}
$$

Jadi, solusi dari sistem persamaan adalah:

$$
\begin{array}{cc}
\left(x_1, x_2, x_3\right) = \left(4 - 2t, 1 + 2t, t\right), \quad t \in \mathbb{R}
\end{array}
$$

Sistem ini memiliki banyak solusi karena terdapat parameter bebas $( t )$.