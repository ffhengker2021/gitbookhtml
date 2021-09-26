---
description: Penjelasan pandangan dan sejarah singkat tentang HTML
---

# Apa Itu HTML

HTML singkatan dari Hypertext Markup Language, yang merupakan bahasa markah dasar dalam membuat sebuah kerangka halaman web, saat ini HTML telah berada pada versi HTML5.

![Ini adalah lambang dari HTML5](../.gitbook/assets/gambar%20%281%29.png)

## Sejarah

HTML diciptakan oleh Tim Berners-Lee pada tahun 1980, dimana waktu itu dia bekerja di CERN \(Centre Europeen pour la Recherchee Nucleaire\). Ia menggunakan HTML sebagai peramban untuk menafsirkan dan menulis teks, gambar dan bahan lainnya ke dalam halaman web secara visual dan suara. Kemudian HTML ditingkatkan dengan menggunakan tambahan halaman web desain dengan menggunakan CSS agar halaman web lebih menarik.

## Versi HTML

HTML sendiri telah memiliki banyak versi, dimulai dari awal peluncurannya hingga saat ini semakin tinggi versi HTML nya,maka semakin bertambah juga fitur dan kelebihannya.

### HTML 2.0

HTML versi ini diluncurkan sebagai IETF RFC pada tanggal 24 November 1995, fitur yang ditambahkan pada HTML versi ini adalah dapat mengunggah file, membuat tabel, dan internasionalisasi.

### HTML 3.2

HTML versi ini diluncurkan dan dikerjakan oleh W3C \(World Wide Web Consortium\) pada tanggal 14 Januari 1997. HTML pada versi inilah yang digunakan sebagai versi awal standar yang langsung dikembangkan W3C yang mana Tim Berners Lee adalah pemimpin dari organisasi ini dan IETF telah menutup kerja HTMLnya pada tanggal 12 September 1996. Fitur atau perubahan yang ada pada HTML versi ini adalah menghilangkan rumus matematika karena adanya ketumpang tindaihan terhadap kepemilikan dan adopsi seabgian besar bahasa markah dari Netscape.

### HTML 4.0

HTML versi ini diluncurkan oleh W3C pada tanggal 18 Desember 1997. Versi ini memiliki beberapa variasi yakni : 

* Ketat, di mana elemen terdeprekasi dilarang.
* Transisional, di mana elemen terdeprekasi diperbolehkan.
* Frameset, di mana sebagian besar hanya elemen yang berkaitan dengan frame diperbolehkan.

### HTML 5.0

HTML versi ini diluncurkan pada bulan Juni 2011 bahkan sampai saat ini masih dalam tahap pengembangan. Banyak fitur HTML baru setelah HTML5 diluncurkan, diantaranya adanya tag semantic element seperti `<section>` , `<header>` ,`<footer>` ,`<main>`, `<nav>`, `<aside>`, dan lainnya. Fitur lainnya adalah kemampuan untuk membaca format file svg dan penghapusan beberapa tag element seperti `<font>`, `<framset>`, `<dir>`, `<tt>`, dan lainnya.

## Contoh HTML

{% tabs %}
{% tab title="contoh.html" %}
```markup
<!DOCTYPE html>
<html>
    <head>
        <title>Ini Adalah Judul</title>
    </head>
    <body>
        <p>Ini Adalah Program Saya</p>
        <p>Saya belajar bersama Inlearn</p>
    </body>
</html>
```
{% endtab %}

{% tab title="Hasil" %}
```
Hasilnya harap untuk dibuat sendiri ya, cara membuatnya menggunakan code editor
Cek pada halaman selanjutnya.
```
{% endtab %}
{% endtabs %}

### Penjelasan

Kode diatas merupakan salah satu contoh dari kodingan HTML kita yang mana menampilkan dua buah paragprah yang berisikan "Ini Adalah Program Saya" dan "Saya belajar bersama Inlearn".

#### &lt;!DOCTYPE html&gt;

Syntax ini memberitahukan kepada web browser, bahwa kita ingin menggunakan bahasa markah HTML5. Jika kamu ingin menggunakan HTML4 maka, kamu harus mendeklarasikannya terlebih dahulu dengan menuliskan syntax : `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`

#### &lt;head&gt;

Syntax ini berfungsi sebagai menyimpan informasi halaman web pada browser yang kita gunakan untuk membaca kode HTML kita.

#### &lt;title&gt;

Syntax ini berfungsi untuk menampilkan judul yang ada pada tab browser kita, ini bertujuan agar kita dapat membedakan dimana halaman web satu dengan yang lain dengan menggunakan judul pada tab browser kita. Penggunaan syntax ini harus berada dalam cakupan atau didalm element `<head>`.

#### &lt;body&gt;

Syntax ini merupakan element dimana akan menampilkan isi dalam yang ada pada element tersebut kedalam halaman web browser kita sehingga element yang ada didalam `<body>` akan ditampilkan pada layar perangkat kita.

#### &lt;p&gt;

Syntax ini adalah salah satu dari sekian banyak syntax atau element yang dapat ditampilkan didalam element atau tag `<body>`. Syntax ini berfungsi sebagai menampilkan sebuah paragraph.

## Penggunaan Markah

Dalam penggunaan tag HTML, kita harus menggunakan tag pembuka dan tag penutup. Seperti `<tagpembuka>konten</tagpenutup>`. Namun, tidak semua tag harus menggunakan tag penutup diantaranya seperti tag `<img>` yang berfungsi sebagai menampilkan gambar. tag `<img>` tidak perlu menggunakan tag penutup, contohnya `<img src="gambar.png">`.

## Terima kasih telah melakukan kontribusi

Kami mengucapkan terima kasih yang sebesarnya bagi siapapun kontributor pada halaman ini.

* Ikram Wadudu

