# Berkas Ujian FI3201 Fisika Komputasi
## Anggota Kelompok
1. M Luthfi Aditya / 10217022
2. Muhammad Tegar Pambudi / 10217025
3. Ahmad Al Ghiffari / 10217047
4. Irsan Ferdian A S / 10217074
5. Larolina K / 10217077
6. Muhri Ihza / 10217086

## Nomor 1
### Poin A
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
## Poin B
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
## Poin C
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
## Poin D
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
# Nomor 2
## Poin A
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

**Lampiran : **
1. Diagram gaya sistem pada koordinat kartesian.

![alt text](https://user-images.githubusercontent.com/64627989/80791604-5be3f500-8bbc-11ea-8d4d-3e07aef2df41.png)

## Poin B
