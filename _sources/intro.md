# SISTEM PERSAMAAN LINIER

Nama    : MUHAMMAD UMAR FARUQ

NIM     : 230411100008

Email   : umrfrqqq@gmail.com


# PENDAHULUAN

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


**1. Konsep**

Tulis ringkasan (1 sampai dengan 4 paragraf, jika memungkinkan berikan contohh dalam python)

1. Tipe Data
2. Algoritma (Definisi, Jenis-jenis algoritma, bagaimana menulis algoritma)
1.Tipe Data

Tipe data adalah sebuah tipe dalam sebuah data bisa berbentuk Integer, Float, String, Boolean. Tipe data digunakan untuk mengklasifikasikan data ke dalam kategori tertentu sehingga program dapat memahami cara mengoperasikannya. Berikut adalah beberapa tipe data umum dalam pemrograman:

a.Tipe Data Integer (int) : Tipe data ini digunakan untuk mempresentasikan bilangan bulat.
Contohnya adalah 2, 5, 6, -4, -9

b. Tipe Data Float (float) : Tipe data ini digunakan untuk mempresentasikan bilangan desimal atau pecahan.
Contohnya adalah 3.14, 0.99, 0.9

c. Tipe Data String (str) : Tipe data ini digunakan untuk mempresentasikan teks atau karakter.
Contohnya  yaitu "ayo belajar pyhton", "python itu seru"

d. Tipe Data Boolean (bool) : Tipe data ini hanya memiliki dua nilai, yaitu True (Benar) dan False (Salah)
print("Contoh tipe data")

#tipe data string
print("ayo belajar python :" , type("ayo belajar pyhton"))

#tipe data float
print("0.99 :", type(0.99))

#tipe data integer
print("6 :", type(6))

#tiipe data boolean
print("True :", type(True))
2. Algoritma

Pengertian Algooritma
Algoritma pemrograman adalah serangkaian langkah terperinci yang dirancang untuk memecahkan masalah atau tugas tertentu dengan menggunakan komputer.

Jenis-jenis Algoritma
a. Algoritma Sekuensial adalah algoritma yang dilakukan secara bertahap dan juga berurutan. Contohnya dapat kita temukan pada kegiatan sehari-hari ketika kita ingin memasak mi. Biasanya, pada bungkus tersebut terdapat langkah-langkah penyajian untuk menghidangkan makanan tersebut.
b. Algoritma Percabangan adalah suatu algoritma yang dapat digunakan untuk memilih atau melanjutkan salah satu perintah dari beberapa perintah yang sudah ada sebelumnya. Akan tetapi, pada jenis agoritma percabangan ini untuk melakukan langkah selanjutnya maka harus memenuhi syarat yang sudah ada.
c. Algoritma Perulangan adalah algoritma yang dapat menyelesaikan berbagai macam masalah yang kejadiannya akan terus berulang. Contohnya adalah ketika anda pergi kke tempat kerja setiap hari, maka anda mengikuti algoritma perulangan yang sama dengan mengikuti rute yang sama dengan langkah-laangkah yang serupa setiap harinya.,br>

Cara menuis Algoritma
a. Pseudocode adalah cara penulisan algoritma yang menyerupai bahasa pemrogramaan tingkat tinggi. Pada umumnya notasi pseudocode menggunakan bahasa yang mudah dimengerti secara umum dan juga lebih ringkas dari algoritma.
b. Deskriptif adalah dilakukan dengan cara menuliskan intruksi-intruksi yang harus dilaksanakan dalam bentuk rangkaian kalimat deskriptif dengan menggunakan bahasa yang jelas.
c. Flowchart adalah simbol gambar (chart) dari proses terhadap data, digunakan untuk menggambarkan prosedur sistem.
# New Section
2. Implementasi
2.1 Luas dan Keliling Lingkaran
Tuliskan suatu program menampilkan luas dan keliling dari suatu lingkaran dengan jari-jari merupakan inputan dari user seperti gambar 1a dan 1b dengan menggunakan rumus berikut:

L = πr2

K = 2πr

L = luas lingkaran

K = keliling lingkaran

r = jari-jari lingkaran (inputan user)
phi = 22/7
jarijari = int(input("Masukkan jari-jari lingkaran :"))
Luas = phi*jarijari**2
Keliling = 2*phi*jarijari
print("Luas Lingkaran dengan jari-jari", jarijari, "cm adalah", Luas, "cm")
print("Keliling Lingkaran dengan jari-jari", jarijari, "cm adalah", Keliling, "cm")
phi = 22/7
jarijari = int(input("Masukkan jari-jari lingkaran :"))
Luas = phi*jarijari**2
Keliling = 2*phi*jarijari
print("Luas Lingkaran dengan jari-jari", jarijari, "cm adalah", Luas, "cm")
print("Keliling Lingkaran dengan jari-jari", jarijari, "cm adalah", Keliling, "cm")
2.2 Kecepatan Rata-rata
Tuliskan suatu program yang menampilkan rata-rata kecepatan dalam satuan km/jam, untuk jarak (km) dan waktu (jam, menit, detik) merupakan inputan dari user. Ingat waktu masih dalam satuan (jam, menit, detik) jadi rubah dulu ke dalam satuan jam untuk rumus kecepatan rata-rata bisa dilihat di bawah ini.

V = s/t

s = jarak(km)

t = waktu (jam)

V = kecepatan (km/jam)
s = float(input("Masukkan jarak (km) : "))
Jam = float(input("Masukkan waktu satuan (jam) : "))
Menit = float(input("Masukkan waktu satuan (menit) : "))
Detik = float(input("Masukkan waktu satuan (detik) : "))
t = (Jam/1)+(Menit/60)+(Detik/3600)
V = s/t
print("Kecepatan =", V , "km/jam" )
s = float(input("Masukkan jarak (km) : "))
Jam = float(input("Masukkan waktu satuan (jam) : "))
Menit = float(input("Masukkan waktu satuan (menit) : "))
Detik = float(input("Masukkan waktu satuan (detik) : "))
t = (Jam/1)+(Menit/60)+(Detik/3600)
V = s/t
print("Kecepatan =", V , "km/jam" )
2.3 Landasan Pacu
Diberikan akselerasi a dan kecepatan take-off v dari suatu pesawat terbang, anda dapat menghitung panjang landasan pacu minimal yang diperlukan agar suatu pesawat udara dapat take off secara aman dengan menggunakan formula berikut :
panjang = v2 / 2a

Tuliskan suatu program yang meminta pengguna uuntuk memasukkan v daalam satuan meters/second (m/s) dan akselerasi a dalam meters/seecond kuadrat (m/s2), dan kemudian menampilkan panjang minimum dari landasan tersebut.

berikut ini adlah contoh tampilan saat program berjalan :
v = float(input("Masukkan kecepatan (v): "))
a = float(input("Masukkan akselerasi (a): "))
Panjang = (v**2)/(2*a)
print(Panjang,"meter")
v = float(input("Masukkan kecepatan (v): "))
a = float(input("Masukkan akselerasi (a): "))
Panjang = (v**2)/(2*a)
print(Panjang,"meter")
2.4 Energi yaang diperlukan
Tulislah suatu program yang menghitung energi yang dibutuhkan untuk memanaskan air dari suatu suhu awal (intial temperature) sampai mencapai suhu akhir. Program yang dibuat harus meminta pengguna untuk memasukkan jumlah air dalam satuan kilogram, juga temperatur awal dan akhir dari air tersebut. Rumus untuk menghitung energi adalah

Q = M * (temperaturAkhir - temperaturAwal) * 4184

dimana M adalah berat air dalam Kilogram, temperatur dalam derajat Celsius, dan Q diukur dalam satuan joule.

Berikut ini adalah contoh eksekusi programnya :
M = float(input("Masukkan jumlah air dalam satuan kilograms : "))
Tawal = float(input("Masukkan temperatur awal : "))
Takhir = float(input("Masukkan temperatur akhir : "))
Q = M * (Takhir-Tawal) * 4184
print("Energi yang diperlukan adalah ",Q,"Joule")
M = float(input("Masukkan jumlah air dalam satuan kilograms : "))
Tawal = float(input("Masukkan temperatur awal : "))
Takhir = float(input("Masukkan temperatur akhir : "))
Q = M * (Takhir-Tawal) * 4184
print("Energi yang diperlukan adalah ",Q,"Joule")


```{tableofcontents}
```
