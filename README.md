# Ujian kelompok

## Anggota
Terdapat enam orang anggota pada kelompok ini dengan fraksi kontribusinya pada pengerjaan tiap soal dapat dilihat dalam tabel berikut.

| NIM      | Nama                  | Peran pada soal (dan fraksi kontribusinya)   |
|----------|-----------------------|----------------------------------------------|
|          |                       |                                              |
| 10217022 | M. Luthfi Aditya	   | 1 (0.10) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.16) |
| 10217025 | Muhammad Tegar P      | 1 (0.20) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.17) |
| 10217047 | Ahmad Al Ghiffari     | 1 (0.10) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.16) |
| 10217074 | Irsan Ferdian A S	   | 1 (0.20) 2 (0.00) 3 (0.00) 4 (0.10) 5 (0.17) |
| 10217077 | Larolina K		   | 1 (0.20) 2 (0.50) 3 (0.20) 4 (0.00) 5 (0.17) |
| 10217086 | Muhri Ihza		   | 1 (0.20) 2 (0.50) 3 (0.20) 4 (0.00) 5 (0.17) |
|          |                       |                                              |
|          | Total                 | 1 (1.00) 2 (1.00) 3 (1.00) 4 (1.00) 5 (1.00) |



# Jawaban

## Nomor 1 | Sistem Bandul dengan Sistem Koordinat Kartesian
### Poin A

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Dari sistem yang diketahui didapatkan diagram gaya bola pada sistem dan hubungan $\theta$, $x$, dan $y$, (skema terlampir).
	<br /><br />
	
	Hukum Newton II diungkapkan dengan persamaan berikut.
	
	\begin{equation}
	F=ma
	\end{equation}
	
	Pendulum bergerak dengan lintasan lingkaran, sehingga akan muncul gaya sentripetal pada bola karena adanya gaya dalam arah radial. Sehingga ungkapan $T$ adalah sebagai berikut.
	
	\begin{equation}
	\\T-mgcos{\theta}=\frac{mv^2}{l}
	\\T = mgcos{\theta}+\frac{mv^2}{l}
	\end{equation}
	
	Hubungan antara $v$ dengan $\theta$ diungkapkan sebagai berikut, dimana $x'$ dan $y'$ menunjukkan masing-masing kecepatan pada sumbu $x$ dan $y$.
	
	\begin{equation}
	x'=vcos{\theta}
	\end{equation}
	\begin{equation}
	y'=vsin{\theta}
	\end{equation}
	\begin{equation}
	v^2=x'^2+y'^2
	\end{equation}
	
	Sedangkan hubungan antara sudut dan sumbu kartesian adalah sebagai berikut (skema terlampir).
	
	\begin{equation}
	sin{\theta}=\frac{x}{l}
	\end{equation}
	\begin{equation}
	cos{\theta}=\frac{-y}{l}
	\end{equation}
	
	Menggunakan persamaan viskositas, maka nilai $F_{drag}$ diungkapkan sebagai berikut.
	
	\begin{equation}
	F_{drag}=3{\eta}{\pi}Dv
	\end{equation}
	
	Pada sumbu $x$ dan hubungan sebelumnya didapatkan persamaan sebagai berikut.
	
	\begin{equation}
	\\-mx''=-Tsin{\theta}+F_{drag}cos{\theta}
	\\x''-\frac{(mgcos{\theta}+\frac{mv^2}{l})sin{\theta}}{m}+\frac{(3{\eta}{\pi}D)vcos{\theta}}{m}=0
	\\x''-gsin{\theta}cos{\theta}-\frac{(\sqrt{x'^2+y'^2})^2}{l}sin{\theta}+\frac{3{\eta}{\pi}D}{m}vcos{\theta}=0
	\\x''+g\frac{x}{l}\frac{y}{l}-\frac{x'^2+y'^2}{l}\frac{x}{l}+\frac{3{\eta}{\pi}D}{m}x'=0
	\\x''+\frac{g}{l^2}xy-\frac{1}{l^2}(x'^2+y'^2)x+\frac{3{\eta}{\pi}D}{m}x'=0
	\end{equation}
	
	Sedangkan pada sumbu $x$ dan hubungan sebelumnya didapatkan persamaan sebagai berikut.
	
	\begin{equation}
	\\my''=-mg+Tcos{\theta}+F_{drag}sin{\theta}
	\\y''=-g+\frac{(mgcos{\theta}+\frac{mv^2}{l})}{m}cos{\theta}+\frac{(3{\eta}{\pi}D)}{m}vsin{\theta}
	\\y''-gcos^2{\theta}-\frac{(\sqrt{x'^2+y'^2})^2}{l}cos{\theta}+\frac{(3{\eta}{\pi}D)}{m}y'=-g
	\\y''-g\frac{y^2}{l^2}+\frac{1}{l^2}(x'^2+y'^2)y+\frac{(3{\eta}{\pi}D)}{m}y'=-g
	\end{equation}
	
**Lampiran :**
1. Diagram gaya sistem pada koordinat kartesian.

![alt text](https://user-images.githubusercontent.com/64627989/80791365-9e590200-8bbb-11ea-80da-92c7efd41c1a.png)

2. Hubungan sudut dengan koordinat kartesian

![alt text](https://user-images.githubusercontent.com/64627989/80790873-33f39200-8bba-11ea-9e19-bdd723a793b0.png)

### Poin B

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Dari persamaan 9 dan 10 pada Poin A terdapat beberapa suku yang sama.
	<br/><br/>
	
	1. Suku $x''$ dan $y''$
	<br/><br/>
	Suku ini merupakan variabel percepatan dari sistem pada koordinat $x$ dan $y$. Pada persamaan sumbu $y$ terdapat variabel $g$ dan $gy^2/l^2$, sedangkan pada sumbu $x$ terdapat variabel $gxy/l^2$ dimana suku ini muncul karena perhitungan persamaan gerak yang relatif terhadap pusat $O(0,0)$.
	<br/><br/>
	
	2. Suku $(x'^2+y'^2)/l^2$
	<br/><br/>
	Suku ini menjelaskan adanya percepatan sentripetal pada masing-masing sumbu $x$ dan $y$.
	<br/><br/>
	
	3. Suku $3{\eta}{\pi}D/m$
	<br/><br/>
	Suku ini menjelaskan adanya faktor hambatan atau viskositas $\eta$ yang muncul pada sistem.
	
### Poin C

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Pada kasus tanpa gaya hambatan maka nilai $\eta=0$. Sehingga ungkapan dari persamaan (9) dan (10) pada Poin A menjadi seperti berikut.
	<br/><br/>
	
	Untuk sumbu $x$ :
	
	\begin{equation}
	\\x''+\frac{g}{l^2}xy-\frac{1}{l^2}(x'^2+y'^2)x=0
	\end{equation}
	
	Untuk sumbu $y$ :
	
	\begin{equation}
	\\y''-g\frac{y^2}{l^2}+\frac{1}{l^2}(x'^2+y'^2)y=-g
	\end{equation}
	
	Terlihat bahwa kebergantungan sistem hanya karena percepatan sentripetal yang muncul akibat osilasi yang lintasannya melingkar.
	
### Poin D

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Untuk kasus tanpa hambatan maka dapat digunakan persamaan (1) dan (2) pada Poin C untuk persamaan gerak sistem. Sedangkan untuk penggunaan simpangan kecil maka terdapat aproksimasi yang digunakan yaitu $y=l$ dan $x{\ll}l$. Sehingga persamaan (1) dan (2) pada Poin C dapat ditulis sebagai berikut.
	<br/><br/>
	
	Untuk sumbu $x$ :
	
	\begin{equation}
	\\x''+g\frac{x}{l}-\frac{1}{l^2}(x'^2+y'^2)x=0
	\end{equation}
	
	Untuk sumbu $y$ :
	
	\begin{equation}
	\\y''+\frac{x'^2+y'^2}{l}=0
	\end{equation}
## Nomor 2 | Sistem Bandul dengan Sistem Koordinat Polar
### Poin A

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Pada koordinat polar maka diagram gaya digambarkan seperti pada skema, (skema terlampir).

	<br/><br/>

	Pada sumbu $\theta$ :

	\begin{equation}
	\\m{\theta}''=-mgsin{\theta}
	\\{\theta}''+\frac{g}{l}sin{\theta}=0
	\end{equation}

	Pada sumbu $r$ :

	\begin{equation}
	\\m{\theta}'^2l=T-mgcos{\theta}
	\\{\theta}'^2+\frac{g}{l}cos{\theta}=\frac{T}{ml}
	\end{equation}

**Lampiran :**
1. Diagram gaya sistem pada koordinat kartesian.

![alt text](https://user-images.githubusercontent.com/64627989/80791604-5be3f500-8bbc-11ea-8d4d-3e07aef2df41.png)

### Poin B

Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Untuk nilai $\theta$ kecil maka dapat dilakukan aproksimasi nilai sebagai beirikut.

	\begin{equation}
	sin{\theta}=\theta
	\end{equation}

	\begin{equation}
	cos{\theta}=1
	\end{equation}

	Sehingga persamaan (1) dan (2) dari Poin A akan direduksi menjadi berikut.
	<br/><br/>

	Untuk sumbu $\theta$ :

	\begin{equation}
	{\theta}''+\frac{g}{l}{\theta}=0
	\end{equation}

	Solusi umum dari persamaan (3) adalah sebagai berikut.

	\begin{equation}
	{\theta}(t) = Asin({\omega}t) + Bcos({\omega}t)
	\end{equation}

	Dengan kondisi awal simpangan yaitu pada saat $t=0$, $\theta=\theta_0$ maka solusi dapat diambil sebagai kasus initial value problem sebagai berikut.

	\begin{equation}
	{\theta}(0)={\theta}_0=B
	\end{equation}

	Sehingga solusi dari persamaan (3) adalah sebagai berikut.

	\begin{equation}
	{\theta}(t) = {\theta}_{0}cos({\omega}t)
	\end{equation}

	Dengan $\omega$ diungkapkan sebagai berikut.

	\begin{equation}
	{\omega} = \sqrt{\frac{g}{l}}
	\end{equation}

	Untuk sumbu $r$ :

	\begin{equation}
	{\theta}'^2+\frac{g}{l}=\frac{T}{ml}
	\end{equation}

	Turunan pertama dari $\theta_0$ terhadap waktu adalah sebagai berikut.

	\begin{equation}
	\frac{d\theta}{dt}={\theta}'=-{\omega}{\theta}_{0}sin({\omega}t)
	\end{equation}

	Dari persamaan (8) dan (9) didapatkan ungkapan untuk $T$ sebagai berikut.

	\begin{equation}
	\\T=ml(-{\omega}{\theta}_{0}sin({\omega}t)^2+\frac{g}{l})
	\\T=ml({\omega}^2{\theta}^2_{0}sin^2({\omega}t)+\frac{g}{l})
	\end{equation}

	Dengan memasukkan nilai $\omega=g/l$ maka hasil persamaan (10) sebagai berikut.

	\begin{equation}
	\\T=ml(\frac{g}{l}{\theta}^2_{0}sin^2(\frac{g}{l}t)+\frac{g}{l})
	\\T=mg({\theta}^2_{0}sin^2(\frac{g}{l}t)+1)
	\end{equation}

### Poin C

Solusi numerik menggunakan metode Euler dengan membandingkan persamaan 1 Poin A (solusi persamaan umum) dan persamaan 1 Poin B (solusi persamaan khusus - aproksimasi sudut kecil).

1. Sudut 5 derajat dari t = 0 sampai t = 4.95
![alt text](https://user-images.githubusercontent.com/64627989/80800604-12070900-8bd4-11ea-86e9-02e8f6688781.png)

Untuk memperjelas perbandingan, kurva diperbesar dan didapatkan hasil sebagai berikut.
![alt text](https://user-images.githubusercontent.com/64627989/80800618-19c6ad80-8bd4-11ea-9d4f-678fb34718df.png)

2. Sudut 30 derajat dari t = 0 sampai t = 4.95
![alt text](https://user-images.githubusercontent.com/64627989/80800633-23e8ac00-8bd4-11ea-8c97-9f773cb37eae.png)

### Poin D
Program dibuat dan dapat dijalankan pada [http://cpp.sh/](http://cpp.sh/).

```C++
// Example program
#include <iostream>
#include <string>
#include <math.h>

using namespace std;

int main()
{
  float theta;
  
  cout << "Masukkan nilai theta (dalam derajat) : ";
  cin >> theta;
  
  theta = (theta/180)*M_PI;
    
  //variabel sistem
  float g = 9.8;
  float l = 2.0;
  
  //jumlah data dari t = 0 sampai t = 5 dengan interval 1e-2
  int n = 100;
  
  //interval penambahan
  float h = 5.00/n;
  float t[n];
  
  cout << "WAKTU" << endl;
  
  for (int i = 0; i < n; i++){
      t[i] = h*i;
      cout << t[i] << endl;
  }

  //solusi umum (theta'' + (g/l)sin(theta)=0)
  float v1[n];  //array kecepatan
  float th1[n];  //array posisi
  
  for (int i = 0; i < n; i++){
      v1[i] = 0;
      th1[i] = 0;
  }
  
  //Kondisi awal v(0) = 0, theta(0)=theta0
  th1[0] = theta;
  
  cout << endl;
  cout << "NILAI POSISI SOLUSI UMUM" << endl;
  cout << endl;

  
  for (int i = 1; i <= n; i++){
      v1[i] = v1[i-1] + h*(-(g/l)*sin(th1[i-1]));
      th1[i] = th1[i-1] + h*v1[i-1];

      //output
      cout << th1[i] << endl;
  }
  
  //solusi khusus (theta'' + (g/l)theta=0)
  float v2[n];  //array kecepatan
  float th2[n];  //array posisi
  
  for (int i = 0; i < n; i++){
      v2[i] = 0;
      th2[i] = 0;
  }
  
  //Kondisi awal v(0) = 0, theta(0)=theta0
  th2[0] = theta;
  
  cout << endl;
  cout << "NILAI POSISI SOLUSI KHUSUS" << endl;
  cout << endl;
  
  for (int i = 1; i <= n; i++){
      v2[i] = v2[i-1] + h*(-(g/l)*(th2[i-1]));
      th2[i] = th2[i-1] + h*v2[i-1];
      
      //output
      cout << th2[i] << endl;
  }
  
  
}
```

## Nomor 3 | Jaringan Syaraf Tiruan dengan Aplikasi TensorFlow

## Nomor 4 | Algoritma Genetik Sederhana dengan JS

### Poin A
```javascript
/*
	ga.js
	Simple genetic algoritm (GA)
	
	Sparisoma Viridi | https://github.com/dudung/jsxPhys
	
	20200501
	1255 Create this program.
	1318 Cancel the use of online compiler [1].
	
	Refrences
	1. https://jsconsole.com/ [20200501]
*/


// Execute main funtion
main();


// Define main function
function main() {
	var p = "0010110";
	var xy, ys, gs;
	
	getValues(p);
	
}


// Get interpretation of position and group from chromosome
function getValues() {
	p = arguments[0];
	
	xs = p.slice(0, 3);
	ys = p.slice(3, 6);
	gs = p.slice(6);
	
	console.log("p = ", p);
	console.log("x = ", xs);
	console.log("y = ", ys);
	console.log("g = ", gs);
	
}
```

### Poin B

```javascript
/*
	ga.js
	Simple genetic algoritm (GA)
	
	Sparisoma Viridi | https://github.com/dudung/jsxPhys
	
	20200501
	1255 Create this program.
	1318 Cancel the use of online compiler [1].
	
	Refrences
	1. https://jsconsole.com/ [20200501]
*/


// Execute main funtion
main();


// Define main function
function main() {
	var p = "0010110";
	var x0, x, y0, y;
	var dr, val;
	
	getValues(p);
	fitness(p);
	
}


// Get interpretation of position and group from chromosome
function getValues() {
	p = arguments[0];
	
	x0 = p.slice(0, 1);
	x = p.slice(1, 2);
	y0 = p.slice(3, 4);
	y = p.slice(4, 5);
	
	console.log("x0 = ", x0);
	console.log("x = ", x);
	console.log("y0 = ", y0);
	console.log("y = ", y);
	
}

// Create fitness function
function fitness() {
	p = arguments[0];
	
	dr = Math.sqrt(Math.pow(x-x0, 2) + Math.pow(y-y0, 2));
	
	val = 1 / (1 + dr);
	
	console.log("dr = ", dr);
	console.log("val = ", val);
	
}
```

## Nomor 5 | Research Based Learning
### a Tujuan
### b Rumusan Masalah
### c Metode
### d Hasil dan Diskusi
### Referensi
