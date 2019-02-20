
### SOFTWARE REQUIRMENT SPESIFICATION


**1.** **Pendahuluan** <br>
	**1.1**	**Tujuan** <br>
		Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun ”Aplikasi Random Grup”. Dokumen ini dibangun untuk memudahkan dalam melakukan proses pembagian kelompok secara acak dan merata yang dilakukan oleh pengguna. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak ”APPK” (aplikasi pemesanan produk konveksi). <br>
	**1.2**	**Lingkup Masalah** <br>
		APPK singkatan dari aplikasi pemesanan produk konveksi adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk memesan berbagai produk konveksi. Selama ini untuk pemesanan produk konveksi masih secara tradisional akibatnya muncul berbagai kendala diantaranya, pemesanan harus datang ke tempat konveksi, data produk yang dipesan sulit dicari, data rentan hilang, serta laporan pemesanan sulit dicari dan terpantau. <br>
	**1.3**	**Definisi, akronim, singkatan** <br>
		Akronim dan Singkatan : <br>
		- APPK : Aplikasi Pemesanan Produk Konveksi <br>
		- SRS : Software Requirement Specification <br>
		Definisi : <br>
		Software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasih pembuat dengan pengguna. use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. <br>
	**1.4**	**Referensi** <br>
		Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah: <br>
			- Praktikum Analisis dan Desain Sistem Informasi, 2009 <br>
			- http://yaniwid.wordpress.com/2008/10/16/kebutuhan-fungsional-vs-non-fungsional/ <br>
	**1.5**	**Overview** <br>
		Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu : <br>
		Bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak. Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.

**2.** **Gambaran Umum**<br>
<ol>Pada umumnya toko konveksi metode pemesanan produknya masih manual sepert	i harus datang ke toko tersebut jika belum memiliki kontaknya kemudian dalam pembuatan desain terkadang tidak sesuai dengan keinginan client dan metode transaksi pembayarannya client harus datang ke tempat tersebut dengan metode tersebut akan memakan waktu dan tidak efisien, karena untuk pembayaran transaksi harus cepat dan tepat.<br></ol>

<ol>Oleh karena itu kelompok kami mempunyai ide yang mungkin dapat mempermudah dalam proses pemesanan produk konveksi yaitu dengan membuat aplikasi pemesanan produk konveksi yang berbasis website dan android.</ol>

<ol>Pada sistem Admin memiliki fungsi utama yaitu :<br></ol>

- Memberitahu pemesanan dari client
- Menginput data informasi produk konveksi

<ol>Pada sistem Client memiliki fungsi utama yaitu :<br></ol>

- Melihat informasi produk konveksi
- Memesan salah satu produk konveksi
- Menginput data pemesanan

**2.1** **Perspektif produk**<br>
<ol>Aplikasi pemesanan produk konveksi adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk memesan berbagai produk konveksi. Selama ini untuk pemesanan produk konveksi masih secara tradisional akibatnya muncul berbagai kendala diantaranya, pemesanan harus datang ke tempat konveksi, data produk yang dipesan sulit dicari, data rentan hilang, serta laporan pemesanan sulit dicari dan terpantau.<br></ol>

<ol>Oleh karena itu dibutuhkan suatu sistem pemesanan sebagai solusi alternatif pemesanan produk seta mempermudah dalam pembuatan laporan. Selain itu dapat mengatasi masalah yang ada pada sistem yang lama sehingga mampu memenuhi semua kebutuhan sistem, dimana aplikasi pengolahan tersebut dibuat dengan Framework Laravel dan Android Studio yang dapat diterapkan langsung sebagai solusi dalam meningkatkan kinerja dengan sistem terintegrasi sehingga dapat menghasilkan sistem pelaporan data dengan cepat dan akurat.<br></ol>

**2.1.1** **Antarmuka Sistem**<br>
	<ol>Aplikasi pemesanan produk konveksi ini mempunyai 2 user yaitu Admin, Client. Dalam aplikasinya terdapat 2 fungsi utama yaitu melakukan pemesanan dan pengolahan data. Admin memiliki fungsi yang ada pada apikasi seperti data informasi produk, data client, data produk, dan data laporan pemesanan. Client mempunyai fungsi memesan produk dengan cara melakukan pengisian identitas terlebih dahulu kemudian baru pesan produk yang telah diinginkan.<br></ol>
**2.1.2** **Antarmuka pengguna**<br>
	<ol>Perangkat lunak untuk aplikasi ini dibuat dengan menggunakan aplikasi android studio dan framework laravel. Dimana tampilan didesain dengan menggunakan template yang ada. Perangkat lunak untuk layanan dalam aplikasi ini dilengkapi dengan menu untuk pengaksesan berbagai fungsi yang disediakan.</ol>

**2.1.3** **Antarmuka perangkat keras**<br>
	<ol>1. PC/Laptop<br>
		Untuk admin membutuhkan PC/Laptop untuk dapat mengolah data Aplikasiproduk konveksi ini.
	2. Smartphone Android<br>
		Dibutuhkan sebuah smartphone dengan os android.</ol>

**2.1.4** **Antarmuka perangkat lunak**<br>
<ol>Perangkat lunak yang dibutuhkan untuk aplikasi ini yaitu :<br></ol>

- Android Studio
- Sublime Teks
- XAMPP
- Balsamiq Mockup3
- Laragon

**2.1.5** **Antarmuka komunikasi**<br> 
<ol>Yang dibutuhkan hanya sebuah android dan pc yang dapat terhubung ke internet.</ol>