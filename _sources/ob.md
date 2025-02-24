## Penyelesaian Sistem Persamaan Linier
### Operasi Baris Elementer 

### Eliminasi Gauss

Soal 1

Selesaikan dengan Menggunakan Eliminasi Gauss

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2
\end{array}
$$

Penyelasaian :

1. Mengubah bentuk Matriks Augmentasi

$$
\begin{bmatrix}
1&2&3&|6\\
2&4&6&|12\\
0&1&1&|2
\end{bmatrix}
$$

2. Eliminasi Gauss

Langkah pertama, nolkan elemen di bawah pivot pertama : 

$$
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
$$

Tukar baris kedua dan ketiga untuk mendapatkan pivot lebih baik : 

$$
\begin{bmatrix}
1&2&3&|6\\
0&1&1&|2\\
0&0&0&|0
\end{bmatrix}
$$
 
 Solusi Akhir
$$
\begin{aligned}
x_1&=2-t\\
x_2&=2-t\\
x_3&=t
\end{aligned}
$$

Sistem memiliki tak hingga banyak solusi


Soal 2

$$
\begin{align}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=3
\end{align}
$$

Bentuk Matriks Augmentasi

$$
\begin{bmatrix}
1&1&1&|3\\
2&0&1&|5\\
1&2&0&|3
\end{bmatrix}
$$

Eliminasi Gauss-Jordan
Pertama, nolkan elemen dibawah pivot ;

$$
\begin{bmatrix}
1&1&1&|3\\
0&-2&-1&|-1\\
0&1&-1&|0
\end{bmatrix}
$$

Kemudian, ubah pivot menjadi 1 ;

$$
\begin{bmatrix}
1&1&1&|3\\
0&1&\frac{1}{2}&|\frac{1}{2}\\
\end{bmatrix}
$$



