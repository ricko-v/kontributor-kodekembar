---
title: Apa Itu HTML
slug: apa-itu-html
description: Mari berkenalan dengan HTML.
category: Html
tag: ['HTML', 'html-dasar']
penulis: ricko-v
---

Halo teman-teman semua! Selamat datang di tutorial seri HTML. Diseri ini, kita akan belajar HTML dari dasar. Mulai dari pengertian, sejarah versinya, hingga cara membuatnya.

# Pengertian
**HTML** (**H**ypertext **M**arkup **L**anguage) adalah sebuah sistem yang sesuai dengan XML untuk membuat anotasi dokumen dengan 'tag'. Ini digunakan secara khusus untuk membuat konten untuk halaman web dan aplikasi web, yang kemudian dapat dibagikan melalui jaringan. Artinya, jika teman-teman ingin membuat website, maka teman-teman wajib mempelajari HTML.

Selain teks, versi HTML saat ini sudah mendukung berbagai jenis media, termasuk gambar dan video. Artinya, teman-teman dapat mamasukan gambar, audio, dan video kedalam halaman website yang akan dibuat nanti.

# Versi HTML
| Versi | Keterangan | Tahun |
| ----- | ---------- | ----- |
| 1.0   | N/A        | 1994-01-01 |
| 2.0   | <a href='https://tools.ietf.org/html/rfc1866' target='_blank'>RFC 1866</a>       | 	1995-11-24 |
| 3.2   | <a href='https://www.w3.org/TR/REC-html32' target='_blank'>W3C: HTML 3.2</a>       | 	1997-01-14 |
| 4.0   | <a href='https://www.w3.org/TR/1998/REC-html40-19980424/' target='_blank'>W3C: HTML 4.0</a>       | 	1998-04-24 |
| 4.01   | <a href='https://www.w3.org/TR/html401/' target='_blank'>W3C: HTML 4.01</a>       | 	1999-12-24 |
| 5   | <a href='https://html.spec.whatwg.org/multipage/' target='_blank'>WHATWG: HTML 5</a>       | 		2014-10-28 |
| 5.1   | <a href='https://www.w3.org/TR/2016/REC-html51-20161101/' target='_blank'>W3C: HTML 5.1</a>       | 		2016-11-01 |

# Pengantar
**HTML** (**H**ypertext **M**arkup **L**anguage) adalah sebuah bahasa markup yang digunakan untuk membuat dokumen yang dirancang untuk ditampilkan pada browser web. Seperti yang sudah dijelaskan diatas, dengan HTML teman-teman dapat menampilkan teks, gambar, audio, dan video ke halaman website yang akan dibuat nanti.

Ada beberapa orang yang menganggap HTML adalah bahasa pemrograman, tetapi hal itu tidaklah benar. Karena HTML tidak bisa melakukan *programming logic* seperti percabangan, perulangan, dan hal-hal lainnya yang dapat dilakukan oleh bahasa pemrograman pada umumnya.

Lalu, apakah bisa membuat website hanya dengan HTML? Jawabannya bisa, tetapi website yang dibuat nantinya akan monoton dan tampilannya terlihat tidak bagus. Oleh karena itu, dibutuhkan **CSS** (**C**ascading **S**tyle **S**heets) yang akan digunakan untuk mempercantik tampilan website. Dibutuhkan juga **Javascript** untuk membuat website bisa menjadi interaktif dengan pengunjung.

Jika dianalogikan, maka kira-kira seperti ini:

<img src='/post_img/HTML/Apa Itu HTML/analogi-website.png'>

# Tag HTML
Tag HTML memberikan makna semantik dan keterbacaan mesin browser pada konten di halaman website. Sebuah elemen HTML biasanya terdiri dari tag pembuka (```<elemen>```), tag penutup (```</elemen>```), dan isi konten yang terletak didalam tag.

Contoh:
```html
<p>Hallo</p>
```

Dari contoh diatas, dapat disimpulkan bahwa:
1. p adalah salah satu elemen HTML.
2. ```<p>``` adalah tag untuk membuat sebuah paragraf.
3. Hallo adalah isi konten dari tag ```<p>```.

# Membuat Website Sederhana
Mari kita coba buat sebuah website sederhana yang akan menampilkan tulisan "Hello World". Jika teman-teman belum tau apa itu Hello World, mungkin teman-teman bisa membacanya di <a href='https://en.wikipedia.org/wiki/%22Hello,_World!%22_program' target='_blank'>wikipedia</a>.

Langkah pertama yang harus teman-teman lakukan adalah membuat sebuah file dengan ekstensi **.htm** atau **.html**. Teman-teman bisa membuatnya lewat <a href='https://en.wikipedia.org/wiki/Text_editor' target='_blank'>teks editor</a>.

Setelah membuat file HTML, masukan script dibawah ini dan simpan filenya:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Website Sederhana</title>
    </head>
    <body>
        <p>Hello World!</p>
    </body>
</html>
```

Lalu buka file HTML tersebut menggunakan web browser. Jika teman-teman mengikuti langkah-langkahnya dengan benar, maka akan keluar tulisan "Hello World" pada web browser.

# Break Down Script
Mari kita break down script yang digunakan pada contoh diatas:

| Nama Tag | Keterangan |
| ----- | ---------- |
| ```<!DOCTYPE html>```   | Mendefinisikan versi HTML yang dipakai. Pada contoh ini adalah HTML5 |
| ```<html>```   | Memuat sebuah dokumen HTML. Semua elemen lain harus merupakan turunan dari elemen ini. |
| ```<head>```   | Berisi informasi yang dapat dibaca mesin (metadata) tentang dokumen, seperti tag ```<title>```, ```<script>```, ```<meta>```, ```<link>```. |
| ```<meta>```   | Berfungsi sebagai Metadata dari website yang dibuat |
| ```<title>```   | Mendefinisikan judul website yang dibuat. |
| ```<body>```   | Mempresentasikan isi dari dokumen HTML. Hanya ada satu tag ```<body>``` dalam dokumen.  |
| ```<p>```   | Berfungsi untuk membuat paragraf |

# Apa Selanjutnya?
Ketika ingin membuat sebuah file HTML, maka diperlukan **teks editor**. Di tutorial selanjutnya, kita akan belajar bersama mengenai teks editor mana yang harus dipilih dengan pertimbangan spek device masing-masing.