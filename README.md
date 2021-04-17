# Pemograman Web
~~~
Nama  : Arif Samsudin
NIM   : 311910255
Kelas : TI 19 C1
~~~
# 1.Membuat dokumen HTML
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  List</h1>
</header>
</body>
</html>
~~~
![1](https://user-images.githubusercontent.com/81839328/115113713-db2d2d00-9fb5-11eb-9207-1d80bd1bddaf.JPG)
# 2.Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
~~~
<section  id="order-list">
<h2>Ordered  List</h2>
<ol>
<li>Pemrograman  Web</li>
<li>Sistem  Informasi</li>
<li>Basis  Data  2</li>
</ol>
</section>
~~~
![2](https://user-images.githubusercontent.com/81839328/115113723-eda76680-9fb5-11eb-81b7-af95ae2c656b.JPG)
# 3.Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
~~~
<section  id="unorder-list">
<h2>Unordered  List</h2>
<ul type="square">
<li>Jaringan  Komputer</li>
<li>Struktur  Data</li>
<li>Algoritma  &amp;  Pemrograman</li>
</ul>
</section>
~~~
![3](https://user-images.githubusercontent.com/81839328/115114141-e4b79480-9fb7-11eb-8991-a378b449b8d3.JPG)
# 4.Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list
~~~
<section  id="unorder-list">
<h2>Description  List</h2>
<dl>
<dt>Fakultas  Teknik</dt>
<dd>Teknik  Industri</dd>
<dd>Teknik  Informatika</dd>
<dd>Teknik  Lingkungan</dd>
<dt>Fakultas  Ekonomi  dan  Bisnis</dt>
<dd>Akuntansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis  Digital</dd>
</dl>
</section>
~~~
![4](https://user-images.githubusercontent.com/81839328/115113785-36f7b600-9fb6-11eb-969a-9ad0d8e95169.JPG)
# 5.Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  Table</h1>
</header>
</body>
</html>
~~~
![5](https://user-images.githubusercontent.com/81839328/115113806-4bd44980-9fb6-11eb-9228-d8831a6db1a8.JPG)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<table  border="1"  cellpadding="4"  cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program  Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td>Teknik</td>
<td>Teknik  Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik</td>
<td>Teknik  Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik</td>
<td>Teknik  Lingkungan</td>
</tr>
</tbody>
</table>
~~~
![6](https://user-images.githubusercontent.com/81839328/115113834-6b6b7200-9fb6-11eb-87e4-a5877337cb74.JPG)
# 6.Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan
cellspacing pada tag table
~~~
<table  border="1"  cellpadding="4"  cellspacing="0">
~~~
# 7.Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
~~~
<table  border="1"  cellpadding="6"  cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program  Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td  rowspan="3">Teknik</td>
<td>Teknik  Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik  Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik  Lingkungan</td>
</tr>
</tbody>
</table>
~~~
![7](https://user-images.githubusercontent.com/81839328/115113855-86d67d00-9fb6-11eb-8333-bd3a4ac8b278.JPG)
# 8.Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut
~~~
<!DOCTYPE  html>
<html  lang="en">
<head>
<meta  charset="UTF-8">
<meta  name="viewport"  content="width=device-width,  initial-scale=1.0">
<title>HTML  Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat  Form</h1>
</header>
</body>
</html>
~~~
![8](https://user-images.githubusercontent.com/81839328/115114022-53e0b900-9fb7-11eb-89ad-b354c6032d7e.JPG)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<form  action="proses.php"  method="post">
<fieldset>
<legend>Data  Pelanggan</legend>
<p>
<label  for="nama">Nama</label>
<input  type="text"  id="nama"  name="nama">
</p>
<p>
<label  for="alamat">Alamat</label>
<textarea  id="alamat"  name="alamat"  cols="20"  rows="3"></textarea>
</p>
<p>
<label>Jenis  Kelamin</label>
<input  id="jk_l"  type="radio"  name="kelamin"  value="L"  /><label for="jk_l">Laki-laki</label>
<input  id="jk_p"  type="radio"  name="kelamin"  value="P"  /><label
for="jk_p">Perempuan</label>
</p>
<p><input  type="submit"  value="Login"></p>
</fieldset>
</form>
~~~
![9](https://user-images.githubusercontent.com/81839328/115114050-71ae1e00-9fb7-11eb-9d21-f594b0559849.JPG)
# 9.Menabahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
~~~
form  p  >  label  {
display:  inline-block; width:  100px;
}
form  input[type="text"],  form  textarea  { border:  3px  solid  #197a43;
}
form  input[type="submit"]  { border:  2px  solid  #197a43; background-color:  #197a43; color:  #ffffff;
font-weight:  bold; padding:  5px  15px;
}
~~~
![10](https://user-images.githubusercontent.com/81839328/115114058-7ffc3a00-9fb7-11eb-90ce-47ddc50b2682.JPG)

# Pertanyaan dan Tugas
1.	Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
menampilkan dropdown menu
~~~
<!doctype html>
 
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Judul Halaman Saya</title>
    <link rel="stylesheet" type="text/css" href="soalcss.css" media="all" />
  </head>
<body>
  <div class="menu-wrap">
	<ul>
		<li><a href="beranda.html">Beranda</a></li>
		<li><a href="tentang.html">Tentang Kami</a></li>
		<li><a href="kontak.html">Kontak Kami</a>
			<ul>
				<li><a href="alamat.html">Alamat Kami</a></li>
				<li><a href="kebijakan.html">Kebijakan</a></li>
			</ul>
		</li>
	</ul><br>
<h1>Listbox Multiple Selection</h1>
<p>Kamu bisa memilih lebih dari satu opsi:</p>
<form action="/action_page.php">
  <label for="cars">Pilih Kendaraan:</label><br>
  <select name="cars" id="cars" multiple>
    <option value="volvo">Mobil</option>
    <option value="saab">Motor</option>
    <option value="opel">Sepeda</option>
    <option value="audi">Bus</option>
  </select>
  <br>
  <input type="submit" value="Submit">
</form>
<p>Hold down the Ctrl (windows) or Command (Mac) button to select multiple options.</p>
</div>
</body>
</html>
~~~
![soal1](https://user-images.githubusercontent.com/81839328/115114084-ad48e800-9fb7-11eb-819c-1d7cbb9ba83f.JPG)
![soal2](https://user-images.githubusercontent.com/81839328/115114085-afab4200-9fb7-11eb-9201-1fffe0581108.png)







