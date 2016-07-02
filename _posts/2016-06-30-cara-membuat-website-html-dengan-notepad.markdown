---
layout: post
title: Cara Membuat Website HTML Keren dengan NOTEPAD. Emang bisa???
date:   2016-06-30 02:24:36 +0900
categories: html
permalink: cara-membuat-website-html-notepad
excerpt_separator: <!--more-->
author: railondi
---
<strong>Cara membuat website HTML keren hanya dengan NOTEPAD</strong> - Banyak yang pesimis dengan judul ini, masa sih cuma dengan Notepad, bisa membuat website? Kan harus pake Adobe Dreamweaver atau<!--more--> yang lagi keren dan banyak dipakai saat (karena unik warnanya) adalah Sublime-Text.

<blockquote>
	Tutorial berikut ditujukan bagi kalangan pemula (tingkat basic) untuk pengenalan kode HTML dan CSS serta penerapannya dalam membangun situs sederhana hanya dengan menggunakan Notepad (Text-Editor).
</blockquote>

Yang sudah tau pasti bilang: `Tentu bisalah !!!, kan sama aja. Yang penting hafal formatnya toh??`. Pernyataan demikian hampir betul, cuma kurang tepat. Paling penting dalam programming adalah `pemahaman`, apapun jenis bahasa program-nya. Agar lebih paham lagi, kita langsung ke pembahasan materi :D

![Cara buat website dengan Notepad]({{ base.url }}/pictures/buat-web-dengan-notepad.jpg){: .center-image }

<h2>Yang Penting Hafal Formatnya Toh??</h2>
Hingga saat ini main-format HTML belum beruah, beberapa tag reguler yang dimaksuda yakni seperti `HTML`, `head`, `body`. Kapanpun kita membuat halaman web, entah ditulis secara manual ataupun melalui proses perintah program, sebuah halaman HTML akan selalu mengandung beberapa `tag` dasar tersebut.

Sekarang coba buka aplikasi Notepad kamu, yang biasanya terdapat pada group menu Accessories di `Windows`. Bisa juga dengan menekan kombinasi tombol `Windows+R` lalu ketik `notepad.exe` pada `run box` dan tekan `Enter` untuk running perintah pemanggilan `Notepad`.

Siapkan folder tempat menyimpan "mahakarya" website keren kalian nantinya. Misalnya, buat dalam `My Documents` lalu beri nama `website`.

<blockquote>
	Pada tutorial ini saya menggunakan gedit, bisa dikatakan sebagai notepad-nya Linux. Pada dasarnya sama saja, hanya berbeda pada jumlah fitur dan antar muka grafis (GUI) serta kemampuan mengenali jenis script.
</blockquote>

Ketik script HTML berikut:

{% highlight ruby %}
<html>
<head>
	<title>Website Keren</title>
</head>
<body>
<h1>Helo dunia!!!!</h1>
</body>
</html>
{% endhighlight %}
<i>Jika kamu benar-benar pemula dalam menulis kode HTML, biasakan untuk menghindari `copy+paste` script. Usahakan mengetik secara manual agar kamu terbiasa menghafal tag HTML yang sering dipakai ini.</i>

Simpan dengan nama index.html pada folder yang sudah kamu buat tadi. Dengan demikian sebuah halaman website sudah berhasil kamu buat. Coba `double click` untuk membuka halaman web tadi dengan Internet Browser bawaan di komputer kamu. Tampilan-nya akan nampak sebagai berikut:

![Cara buat web html keren dengan Notepad]({{ base.url }}/pictures/buat-web-dengan-notepad-helo-dunia.jpg){: .center-image }

<h2>Yes Berhasil! Tapi Kok Tidak Keren Ya?</h2>
Masih terlalu subuh untuk berdandan tante...!! Sebaiknya dirumuskan dalu mau buat website tipe apa sekarang? Kalau situs dinamis dengan penggunaan basis data sepertinya terlalu berat untuk permulaan.

Sebaiknya coba buat situs tipe `landing page` yang mempromosikan barang/jasa/pribadi/kelompok dan lain sebagainya, biar mudah. Setelah itu baru di-<i>dandan</i> dengan riasan CSS biar lebih cantik, menggoda dan membangkitkan gairah. OK? Lanjut !!!

<h2>Isi Website dengan Konten</h2>
Kata para pakar internet marketing, konten adalah raja. Dari pada pusing pikir 'raja' apa yang cocok untuk mengisi situs ini, mending cari di postingan media sosial. Banyak penjual semi-online yang memasarkan produk dengan cara spam. Kita ambil salah satu contoh postingan-nya.

Salah satu contoh adalah postingan tentang "penjualan speedometer segala jenis motor" berikut. Nampaknya memiliki gambar yang cukup lengkap serta keterangan jenis produk yang banyak.

![Cara buat web html keren dengan Notepad]({{ base.url }}/pictures/buat-web-dengan-notepad-fb-post.jpg){: .center-image }

Setelah isi postingan facebook tadi di-copy, selanjutnya di isi kedalam halaman HTML tadi dengan sedikit perubahan pada judul serta penambahan gambar. Kode HTML-nya adalah sebagai berikut:
{% highlight ruby %}
<html>
<head>
	<title>Website Keren</title>
<style type="text/css">
img{border-radius:5%;}
</style>
</head>
<body>
<div class="isi">

<h1>MRZ"SPEEDOMETER CUSTOM</h1>

<p>
Asallammualaikum ,Hallo Guys Untuk pecinta modifikasi motor buat teman2 yang ingin motor nya terlihat tampil beda yu pesan papan speedometer custom nya desain/gambar bebas bisa menggunakan poto,logo club dll keunggulan speedometer custom bisa menyala dimalam hari dengan cahaya lampu yang menembus di bagian papan sehingga membuat gambar tampak hidup, penasaran pengen tau lebih lanjut?? yuu kepoin dulu ajj....
</p>
<img src="speedometer.jpg" />
<h3>Ready Pola :</h3>

<div class="list">
Yamaha nouvo Z
Yamaha nouve lele
Yamaha mio garnish 2010
Yamaha mio sporty cw 2007
Yamaha xeon GT 125
Yamaha X-ride
Yamaha mio GT/J
Yamaha mio M3
Yamaha mio soul
Yamaha mio soul GT
Yamaha Vega Zr
Yamaha Vega New
Yamaha Fino Fi
Yamaha Jupiter MX Old
Yamaha Jupiter MX king 150 FI
Yamaha. Jupiter MX NEw
Yamaha Jupiter Z"Burung Hantu"
Yamaha vixion old
Yamaha New Vixion Lightning/Advance
Honda Vario Tecno 125
Honda Vario Cw 110
Honda Vario Techno 110 Cbs
Honda vario 150 fi
Honda Cb 150 R
Honda Revo Fit
Honda blade
Honda Beat karbu
Honda Beat Fi
Honda Beat POP
Honda suprax125
Honda scoopy Fi
Honda scoopy karbu
Honda Astrea
Suzuki Satria F 150
Kawasaki Ninja Z250
Kawasaki Ninja Vr
</div>

</div>
</body>
</html>
{% endhighlight %}


Selanjutnya buka tampilan-nya di browser bawaan, yang nampak adalah sebuah halaman web dengan tampilan standar rata-kiri serta list produk yang memanjang dan bersambung seperti pada gambar berikut ini:

![Cara buat web html keren dengan Notepad]({{ base.url }}/pictures/buat-web-dengan-notepad-hasil-1.jpg){: .center-image }

<h2>Penerapan CSS-Style Untuk Memperindah Tampilan</h2>

Untuk merapikan tampilan dari halaman HTML tersebut agar list-product bisa nampak memanjang ke bawah, serta mengatur tata-letak dan warna dapat dimodifikasi sesuai selera, berikut ini adalah contoh sederhana permainan warna dengan kode `CSS`:

{% highlight ruby %}

<html>
<head>
	<title>Website Keren</title>
<style type="text/css">
body{
background-color:#ccf;
font-family: "lucida grande", tahoma, verdana, arial, sans-serif;
}

header{
background: linear-gradient(#00f,#007);
height:70px;
vertical-align:middle;
color:#fff;
}

footer{
background: linear-gradient(#00f,#007);
height:30px;
text-align:center;
vertical-align: middle;
color:#fff;
}

blockquote{
color:#fff;
background-color:#700;
text-align:center;
padding:5px;
}

h1{
text-align:center;
}

img{border-radius:5%;}

hr{border:none;border-bottom:1px dashed #ccc;}

.konten{padding:10px;}

.isi{
background-color:#fff;
margin:0 auto;
max-width:800px;
text-align:justify;
}

.pola{
margin-top:10px;
background-color:#ddf;
padding:5px;
}

.kontak{
float:right;
align-left:5px;
}
</style>
</head>
<body>
<div class="isi">

<header>
<h1>MRZ"SPEEDOMETER CUSTOM</h1>
</header>

<div class="konten">

<p>
Asallammualaikum ,Hallo Guys Untuk pecinta modifikasi motor buat teman2 yang ingin motor nya terlihat tampil beda yu pesan papan speedometer custom nya desain/gambar bebas bisa menggunakan poto,logo club dll.</p>
<p>Keunggulan speedometer custom bisa menyala dimalam hari dengan cahaya lampu yang menembus di bagian papan sehingga membuat gambar tampak hidup, penasaran pengen tau lebih lanjut?? yuu kepoin dulu ajj....
</p>
<center>
<img src="speedometer.jpg" />
</center>
<div class="pola">
<h3>Ready Pola :</h3>
<div class="list">
<ul>
<li>Yamaha nouvo Z</li>
<li>Yamaha nouve lele</li>
<li>Yamaha mio garnish 2010</li>
<li>Yamaha mio sporty cw 2007</li>
<li>Yamaha xeon GT 125</li>
<li>Yamaha X-ride</li>
<li>Yamaha mio GT/J</li>
<li>Yamaha mio M3</li>
<li>Yamaha mio soul</li>
<li>Yamaha mio soul GT</li>
<li>Yamaha Vega Zr</li>
<li>Yamaha Vega New</li>
<li>Yamaha Fino Fi</li>
<li>Yamaha Jupiter MX Old</li>
<li>Yamaha Jupiter MX king 150 FI</li>
<li>Yamaha. Jupiter MX NEw</li>
<li>Yamaha Jupiter Z"Burung Hantu"</li>
<li>Yamaha vixion old</li>
<li>Yamaha New Vixion Lightning/Advance</li>
<li>Honda Vario Tecno 125</li>
<li>Honda Vario Cw 110</li>
<li>Honda Vario Techno 110 Cbs</li>
<li>Honda vario 150 fi</li>
<li>Honda Cb 150 R</li>
<li>Honda Revo Fit</li>
<li>Honda blade</li>
<li>Honda Beat karbu</li>
<li>Honda Beat Fi</li>
<li>Honda Beat POP</li>
<li>Honda suprax125</li>
<li>Honda scoopy Fi</li>
<li>Honda scoopy karbu</li>
<li>Honda Astrea</li>
<li>Suzuki Satria F 150</li>
<li>Kawasaki Ninja Z250</li>
<li>Kawasaki Ninja Vr</li>
</div>

</div>

<blockquote>
Untuk Konsultasi Silahkan Hubungi<br/>
Call/SmS : 08124561545 / 081378945645<br/>
Pin BBM. : 57ABCDEFG<br/>
<br/><br/>
Alamat Jelas : Kp Raweuy Utara Rt 04/06 Desa Sukakarya Kec Warudoyong Kota Sukabumi.<br/><br/>

Terimakasih Telah Menyimak dengan baik<br/>
Salam Modifikasi INDONESIA, MRZ Speedometer Custom, Have a Nice Day
</blockquote>


</div>
<hr/>
<footer>
<i>&reg;SitusKeren.com. Hak Cipta Dilindungi Undang-Undang &copy;2016</i>
</footer>
</div>
</body>
</html>

{% endhighlight %}

Sehingga tampilan web HTML akan menjadi lebih tertata dengan beberapa kontra warna untuk tiap bagian yang terbagi seperti gambar, judul, isi, list dan lain sebagianya. Tampilan akhirnya adalah sebagai berikut:

![Cara buat web html keren dengan Notepad]({{ base.url }}/pictures/buat-web-dengan-notepad-hasil-akhir.jpg){: .center-image }

<h2>Kesimpulan dan Penutup</h2>
Dari praktek yang dipaparkan di atas, dapat disimpulkan bahwa membuat website atau menulis kode HTML tidak harus menggunakan tools hebat, dengan Text-Editor sekelas Notepad pun bisa dihasilkan halaman website sesuai keinginan.

Yang terpenting di sini adalah, penguasaan dan pemahaman fungsi perintah serta kreatifitas untuk mengatur tampilan agar lebih menarik dengan berbagai permainan tata-letak dan warna.

Contoh situs web yang dibuat tadi hanyalah sebagian kecil dari penerapan kode HTML dan CSS, masih banyak fungsi perintah yang dapat kalian explorasi serta kembangkan pada penulisan dan pengembangan website.