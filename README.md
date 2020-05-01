# Ujian kelompok

## Anggota
Terdapat enam orang anggota pada kelompok ini dengan fraksi kontribusinya pada pengerjaan tiap soal dapat dilihat dalam tabel berikut.

| NIM      | Nama                  | Peran pada soal (dan fraksi kontribusinya)   |
|----------|-----------------------|----------------------------------------------|
|          |                       |                                              |
| 10217022 | M. Luthfi Aditya	   | 1 (0.10) 2 (0.10) 3 (0.30) 4 (0.10) 5 (0.15) |
| 10217025 | Muhammad Tegar P      | 1 (0.30) 2 (0.30) 3 (0.00) 4 (0.10) 5 (0.25) |
| 10217047 | Ahmad Al Ghiffari     | 1 (0.30) 2 (0.30) 3 (0.05) 4 (0.10) 5 (0.15) |
| 10217074 | Irsan Ferdian A S	   | 1 (0.10) 2 (0.10) 3 (0.30) 4 (0.10) 5 (0.15) |
| 10217077 | Larolina K		   | 1 (0.10) 2 (0.10) 3 (0.30) 4 (0.10) 5 (0.15) |
| 10217086 | Muhri Ihza		   | 1 (0.10) 2 (0.10) 3 (0.05) 4 (0.50) 5 (0.15) |
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

### Poin A
Data yang disajikan pada soal pertama-tama dibentuk plot menggunakan excel. Didapatkan data yang terpisah pada sumbu y sehingga dibutuhkan hanya satu inputan yang memisahkan data secara vertikal. Karena data terpisah sudah linear, tidak membutuhkan hidden layer sehingga notasi yang digunakan adalah '(1-1)'.

**Lampiran :**
1. Output ANN Notasi Struktur 3A

![alt text](https://user-images.githubusercontent.com/64627989/80807851-674d1580-8be8-11ea-87dd-88b0458467fb.png)

### Poin B
Data yang disajikan pada soal pertama-tama dibentuk plot menggunakan excel. Didapatkan data yang terpisah melalui garis diagonal sehingga dibutuhkan dua input. Untuk memperbaik pemisahan data, digunakan hidden layer sedemikian sehingga notasinya adalah '(2-5-3-2-1 )'.

**Lampiran :**
1. Output ANN Notasi Struktur 3B

![alt text](https://user-images.githubusercontent.com/64627989/80807858-6ddb8d00-8be8-11ea-93b4-e61d11dba1a2.png)

### Poin C
Data yang disajikan pada soal pertama-tama dibentuk plot menggunakan excel. Didapatkan data yang terpisah secara sentris dengan kelas bernilai 1 berada di tengah. Digunakan dua input dan hidden layer tambahan sedemikian sehingga notasinya adalah '(2-2-4-2-1)'.

**Lampiran :**
1. Output ANN Notasi Struktur 3C

![alt text](https://user-images.githubusercontent.com/64627989/80807871-75029b00-8be8-11ea-8da3-e02ca3681427.png)

### Poin D
Visualisasi data pertama bahwa data terpisah hanya oleh sumbu y sehingga hanya perlu 1 input dan karena pemisah linear maka tidak perlu hidden layer. Untuk data 2, dipisahkan oleh garis miring sehingga kedua sumbu x dan y berpengaruh sehingga diperlukan dua neuron input, diagonal pemisah data perlu ditambah kan hidden layer agar tampilan dapat diperbaik. Sedangkan, untuk data C, diperlukan 2 input dan pemisah harus diwakili oleh tiga boundary sehingga diperlukan hidden layer tambahan. Arsitektur JST yang sesederhana mungkin dibutuhkan karena dalam visualisasi dibutuhkan bentuk yang sederhana, kemudian iterasi yang dilakukan tidak lama dan panjang juga resource yang dibutuhkan. Tapi pada beberapa kasus dengan contoh pada data C, sebenernya bisa didapatkan dengan notasi (2-2-4-1) dengan menggunakan 2 hidden layer. Penambahan hidden layer ketiga untuk mempercepat mendapatkan hasil output, atau mempersedikit iterasi, hal tersebut bisa dibilang lebih sederhana meskipun menambahkan hidden layer. Tapi akibat dari penambahan tersebut tidak berlaku untuk semua kasus.

## Nomor 4 | Algoritma Genetik Sederhana dengan JS

### Poin A
```javascript
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

Output dari program ini adalah sebagai berikut.

```
p = 0010110
x = 001
y = 011
g = 0
```


### Poin B

```javascript
//nilai X0 dan Y0 dibuat = 111

// Execute main funtion
main();

// Define main function
function main() {
    var p = "0010110";
    [xs, ys, cs] = getValues(p);
    var val = 1/(1+fitness(xs,ys));			
    
    console.log("p =", p);
    console.log("x =", xs);
    console.log("y =", ys);
    console.log("kelas =", gs);
    console.log("val = ", val);
}

function getValues() {
    var p = arguments[0];
    var xs = p.slice(0, 3);
    var ys = p.slice(3, 6);
    var gs = p.slice(6);
    return [xs, ys, gs];
}

function fitness(a, b) {		
  return(Math.sqrt(Math.pow((a - 111), 2) + Math.pow((b - 111),2)));
}
```

Output dari program ini adalah sebagai berikut.

```
p = 0010110
x = 001
y = 011
kelas = 0
val = 0.006681781414235262
```

### Poin C

```javascript
// Execute main funtion
main();
// Define main function 
function main() 
{ 
	var p = "1111101";		
	var q = "1111011";
	var r = "1011011";
	var s = "1010110";
	var t = "1010101";
	var threshold= 0.5;
  
	[x1, y1, c1] = getValues(p); 
	[x2, y2, c2] = getValues(q); 
	[x3, y3, c3] = getValues(r); 
	[x4, y4, c4] = getValues(s); 
	[x5, y5, c5] = getValues(t); 

	//Seleksi untuk Kromosom pertama (p)
	var hasil1 = 1/(1+fitness(x1,y1));
	var seleksi1 = selection(threshold, hasil1, p)
		console.log("p =",p); 
		console.log("x =",x1); 
		console.log("y =",y1); 
		console.log("kelas =",c1);
		console.log("val = ",hasil1);
		console.log("seleksi = ",p," ",  seleksi1);
	
	//Seleksi untuk kromosom kedua (q)
	var hasil2 = 1/(1+fitness(x2,y2));
	var seleksi2 = selection(threshold, hasil2, q)
		console.log("q =",q); 
		console.log("x =",x2); 
		console.log("y =",y2); 
		console.log("kelas =",c2); 
		console.log("val = ",hasil2);
		console.log("seleksi = ",q," ",  seleksi2);

	//Seleksi untuk kromosom ketiga (r)
	var hasil3 = 1/(1+fitness(x3,y3));
	var seleksi3 = selection(threshold, hasil3, r)
		console.log("r =",r); 	
		console.log("x =",x3); 
		console.log("y =",y3); 
		console.log("kelas =",c3); 
		console.log("val = ",hasil3);
		console.log("seleksi = ",r," ",  seleksi3);

	//seleksi kromosom keempat(s)
	var hasil4 = 1/(1+fitness(x4,y4));
	var seleksi4 = selection(threshold, hasil4, s)
		console.log("s =",s); 
		console.log("x =",x4); 
		console.log("y =",y4); 
		console.log("kelas =",c4); 
		console.log("val = ",hasil4);
		console.log("seleksi = ",s," ", seleksi4);

	//seleksi untuk kromosom kelima
	var hasil5 = 1/(1+fitness(x5,y5));
	var seleksi5 = selection(threshold, hasil5, t)
		console.log("t =",t); 
		console.log("x =",x5); 
		console.log("y =",y5); 
		console.log("kelas =",c5); 
		console.log("val = ",hasil5);
		console.log("seleksi = ",t," ", seleksi5);
}

function getValues() 
{ 
	var p = arguments[0];
	var xs = p.slice(0, 3); 
	var ys = p.slice(3, 6); 
	var cs = p.slice(6);

	return [xs, ys, cs]; 
}

function fitness(a, b) 
{ 
	return(Math.sqrt(Math.pow((a - 111), 2) + Math.pow((b - 111),2))); 
}

function selection(threshold, a, p)           //fungsi untuk mengecek apakah nilai fitnessnya >= threshold
{ 
	if (a>=threshold) { result="lolos seleksi";
	} else
		{ result="tidak lolos seleksi"; }
		
return (result);
}
```

Output dari program ini adalah sebagai berikut.

```
p = 1111101
x = 111
y = 110
kelas = 1
val = 0.5
seleksi = 1111101	lolos seleksi

q = 1111011
x = 111
y = 101
kelas = 1
val = 0.09090909090909091
seleksi = 1111011	tidak lolos seleksi

r = 1011011
x = 101
y = 101
kelas = 1
val = 0.06604088253131131
seleksi = 1011011	tidak lolos seleksi

s = 1010110
x = 101
y = 011
kelas = 0
val = 0.009852337480068215
seleksi = 1010110	tidak lolos seleksi

t = 1010101
x = 101
y = 010
kelas = 1
val = 0.009756683706576702
seleksi = 1010101	tidak lolos seleksi
```

### Poin D

```javascript
//disini memakai referensi kromosom 1011101

// Execute main funtion
main();

// Define main function
function main() {
    var p = "1011110";    
    [xs, ys, cs] = getValues(p);
    
    var hasil = 1/(1+fitness(xs,ys));
    console.log("p =",p);
    console.log("x =",xs);
    console.log("y =",ys);
    console.log("c =",cs);
    console.log("hasil = ",hasil);

}

function getValues() {
    var p = arguments[0];

    var xs = p.slice(0, 3);
    var ys = p.slice(3, 6);
    var cs = p.slice(6);

    return [xs, ys, cs];
}

function fitness(a, b) 
{
  return(Math.sqrt(Math.pow((a - 101), 2) + Math.pow((b - 110),2)));	
}
```

Output program dari beberapa kali iterasi adalah sebagai berikut.

```
p = 1011111
x = 101
y = 111
c = 1
hasil = 0.5
```

```
p = 1111011
x = 111
y = 101
c = 1
hasil = 0.06918680026152062
```

```
p = 1011000
x = 101
y = 100
c = 0
hasil = 0.09090909090909091
```

```
p = 1011100
x = 101
y = 110
c = 0
hasil = 1
```

Dari hasil fitness beberapa iterasi kromosom didapat 2 kromosom yang paling mendekati dengan kromosom 1011101 adalah kromosom 1011100 dengan nilai fitness adalah 1, dan kromosom 1011111 dengan nilai fitness 0.5.

## Nomor 5 | Research Based Learning
### a Tujuan

Optimalisasi pemodelan pandemik berdasarkan model SIR dengan Deep Neural Network.

### b Rumusan Masalah

Dunia sedang menghadapi masalah serius terkait adanya pandemik virus SARS-CoV-2 atau dikenal luas dengan istilah Covid 19 atau virus Corona. Di Indonesia, per 1 Maret 2020, tercatat sudah 10.551 orang terjangkit virus Corona, dengan total kematian 800 orang, dan total pasien yang sembuh sebanyak 1.591 orang [1]. Selain penanganan medis dilakukan, sejumlah akademisi melakukan pemodelan terkait dengan penyebaran pandemik ini. Pemodelan yang paling sering digunakan adalah model SIR dimana pada model ini terdapat tiga kelompok yaitu *Susceptible*, *Infected*, dan *Recovered*. Model ini dikembangkan dan diungkapkan dalam bentuk persamaan diferensial sebagai berikut [2].

	\begin{equation}
	\frac{dS(t)}{dt} = -{\beta}S(t)I(t)
	\end{equation}

	\begin{equation}
	\frac{dI(t)}{dt} = {\beta}S(t)I(t) - {\gamma}R(t)
	\end{equation}

	\begin{equation}
	\frac{dR(t)}{dt} = {\gamma}R(t)
	\end{equation}
	
	Dimana ${\beta}$ menunjukkan laju penyebaran dan ${\gamma}$ menunjukkan laju penyembuhan.

Dalam memudahkan penyelesaian persamaan diferensial, telah dikembangkan beberapa metode yang dikembangkan. *Runge-Kutta Fourth Order* dan *Euler Method* merupakan beberapa metode penyelesaian persamaan diferensial dengan IVP atau *Initial Value Problem* dimana dibutuhkan nilai awal untuk menggunakan metode ini. Jika dibandingkan dari segi efektivitas untuk pemodelan SIR yang merupakan persamaa diferensial orde 1, *Euler Method* memiliki tingkat efektivitas yang lebih baik daripada *Runge-Kutta Fourth Order*. Ungkapan yang digunakan dalam metode *Euler Method* adalah sebagai berikut [3].

	\begin{equation}
	\frac{dy}{dt} = f{t,y}, y(t_0)=y_0
	\end{equation}
	
	\begin{equation}
	y_{t+1} = y_{t} + hf(x,y)
	\end{equation}

Pemodelan menggunakan persamaan diferensial ini memiliki kelemahan yaitu karena sensitifitas parameternya dan juga penentuan nilai awal menyebabkan kesalahan dalam penentuan nilai dapat menyebabkan kesalahan dalam melakukan prediksi [4]. Kesulitan dalam penentuan nilai parameter disebabkan karena proses yang terjadi merupakan proses stikasti serta parameter laju transmisi dipengaruhi oleh faktor-faktor lain diluar asumsi yang digunakan [5]. Apalagi pada kondisi seperti dibutuhkan pemodelan yang tepat agar keputusan-keputusan strategis dapat dibuat.

Pemanfaatan *Deep Neural Network* menjadi salah satu solusi yang dapat dimanfaatkan dalam optimalisasi model SIR dengan melakukan *learning* terhadap parameter-parameter yang akan digunakan dalam persamaan diferensial dari data yang sudah direkam sehingga prediksi pemodelan menjadi lebih baik [6].

### c Metode

*Neural Network* disusun dari komponen *input*, *perceptron layer*, dan *output* dimana kaitan antar komponennya merupakan proses menggunakan operator parametrik linear. Untuk *input* dibutuhkan data yang cukup dan relevan dengan fenomena yang terjadi sehingga *output* yang diharapkan berupa nilai dari parameter-paramater pemodelan yang dibutuhkan dan dapat dilakukan pemodelan serta prediksi yang lebih efektif dan optimal dari persebaran pandemik.

### d Hasil dan Diskusi

Hasil yang diharapkan dari penggunaan *neural network* dalam optimasi nilai parameter dalam pemodelan SIR adalah prediksi yang lebih baik sehingga keputusan serta rencana strategis dapat dibentuk dan dilaksanakan sesegera mungkin. (Raissi et al, 2019) melakukan pemodelan SIR menggunakan nilai parameter yang dioptimalisasi menggunakan *neural network* dan mendapatkan hasil yang mengindikasikan bahwa metode estimasi parameter ini merupakan metode yang dapat diandalkan.

Meskipun penggunaan *neural network* merupakan suatu kemajuan dalam prediksi penyebaran pandemik, namun limitasi dari penggunaan *neural network* adalah data. Dibutuhkan jumlah data yang cukup agar hasil dari proses *learning* sesuai dengan fenomena yang terjadi. Hal ini menyebabkan penggunaan *neural network* dalam prediksi penyebaran pandemik tidak dapat diandalkan pada periode awal penyebaran. Selain itu kurangnya data karena adanya kasus pasien yang tidak melapor, jenis penyakit yang bersifat asimptomatik, dan strategi pengecekan yang kurang efisien dibandingkan laju penyebaran dapat menyebabkan prediksi tidak sesuai dengan keadaan nyata. Sehingga perlu adanya kerjasama yang baik antara pihak penyedia data dan pihak yang memodelkan agar didapatkan hasil dengan reliabilitas yang baik.

### e Referensi
1. Ihsanuddin, Ramadhan, A., Haryanti, P.S. (2020). *Update 1 Mei: Pasien Positif Covid-19 Mencapai 10.551*. <https://nasional.kompas.com/read/2020/05/01/15473211/update-1-mei-pasien-positif-covid-19-mencapai-10551>, diakses pada tanggal 1 Maret 2020.
2. Kermack, W. O., McKendrick, A. G. (1927). *A Contribution to the Mathematical Theory of Epidemics*. Proceedings of the The Royal Society of London. DOI:700-721.
3. Lanlege, D. I. et al. (2018). *Comparison of Euler and Runge-Kutta methods in solving ordinary differential equation of order two and four*. Leonardo Journal of Sciences. ISSN:1583-0233.
4. Lloyd, A. L. (2009). *Sensitivity of Model-Based Epidemiological Parameter Estimation to Model Assumptions*. Springer. DOI:10.1007/978-90-481-2313-1-6.
5. Anderson, R. M. May, R. M. (1992). *Infectious diseases of humans: Dynamics and control*. Oxford University Press.
6. Raissi, M. et al. (2019). *On parameter estimation approaches for predicting disease transmission through optimization, deep learning and statistical inference methods*. Letters in Biomathematics. DOI:10.1080/23737867.2019.1676172 
