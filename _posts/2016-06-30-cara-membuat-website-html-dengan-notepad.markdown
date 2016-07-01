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

Untuk merapikan tampilan dari halaman HTML tersebut agar list-product nampak memanjang ke bawah, tambahkan beberapa script `CSS` berikut:
<!--
ambil contoh konten posting jual barang dari facebook ubah jadi landing page
endi gunawan
Sukabumi, Indonesia
MRZ"SPEEDOMETER CUSTOM

Asallammualaikum ,Hallo Guys Untuk pecinta modifikasi motor buat teman2 yang ingin motor nya terlihat tampil beda yu pesan papan speedometer custom nya desain/gambar bebas bisa menggunakan poto,logo club dll keunggulan speedometer custom bisa menyala dimalam hari dengan cahaya lampu yang menembus di bagian papan sehingga membuat gambar tampak hidup, penasaran pengen tau lebih lanjut?? yuu kepoin dulu ajj....
Ready Pola :
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

Untuk Konsultasi Silahkan Hubungi
Call/SmS : 08126193905 / 081391181893
Pin BBM. : 57A71A05

Alamat Jelas : Kp Raweuy Utara Rt 04/06 Desa Sukakarya Kec Warudoyong Kota Sukabumi.

Terimakasih Telah Menyimak dengan baik
Salam Modifikasi INDONESIA, MRZ Speedometer Custom, Have a Nice Day 
-->