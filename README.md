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
	cos{\theta}=\frac{y}{l}
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
	\\x''-g\frac{x}{l}\frac{y}{l}-\frac{x'^2+y'^2}{l}\frac{x}{l}+\frac{3{\eta}{\pi}D}{m}x'=0
	\\x''-\frac{g}{l^2}xy-\frac{1}{l^2}(x'^2+y'^2)x+\frac{3{\eta}{\pi}D}{m}x'=0
	\end{equation}
	Sedangkan pada sumbu $x$ dan hubungan sebelumnya didapatkan persamaan sebagai berikut.
	\begin{equation}
	\\my''=-mg+Tcos{\theta}+F_{drag}sin{\theta}
	\\y''=-g+\frac{(mgcos{\theta}+\frac{mv^2}{l})}{m}cos{\theta}+\frac{(3{\eta}{\pi}D)}{m}vsin{\theta}
	\\y''-gcos^2{\theta}-\frac{(\sqrt{x'^2+y'^2})^2}{l}cos{\theta}+\frac{(3{\eta}{\pi}D)}{m}y'=-g
	\\y''-g\frac{y^2}{l^2}-\frac{x'^2+y'^2}{l^2}y+\frac{(3{\eta}{\pi}D)}{m}y'=-g
	\end{equation}
Lampiran :
1. Diagram gaya sistem pada koordinat kartesian.

![alt text](https://user-images.githubusercontent.com/64627989/80784611-d6564a00-8ba7-11ea-81f1-9cb90b70ff9b.png)

2. Hubungan sudut dengan koordinat kartesian

![alt text](https://user-images.githubusercontent.com/64627989/80785039-35688e80-8ba9-11ea-8bea-c9043693cabd.png)
## Poin B
