# Lab3Web
Nama : Ilham Sabili

NIM  : 312210120

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
> 1. Persiapkan text editor misalnya VSCode.
> 2. Buat folder baru dengan nama Lab3Web
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
> 4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## Praktikum
**1. Membuat Ordered List & Undordered List**

```
<section id="order-list">
  <h2>Ordered List</h2>
  <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>
```
![Cuplikan layar 2023-10-14 203136](https://github.com/ilhamsabili/Lab3Web/assets/115677697/047efae2-4657-4462-9981-c3270b9af48b)


```
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
  </ul>
</section>
```
![Cuplikan layar 2023-10-14 203307](https://github.com/ilhamsabili/Lab3Web/assets/115677697/6176d5c2-e0ba-4532-b7e3-759931101db6)


**2. Membuat Description List**

```
<section id="unorder-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Industri</dd>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```
![Cuplikan layar 2023-10-14 203504](https://github.com/ilhamsabili/Lab3Web/assets/115677697/d30d6e21-96ab-4305-87de-c9502672b54e)


**3. Membuat Table**

```
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```
![Cuplikan layar 2023-10-14 204120](https://github.com/ilhamsabili/Lab3Web/assets/115677697/3b0a0793-f025-43c4-aa68-227735c50824)


**4. Membuat Margin dan Padding**

```
<table border="1" cellpadding="4" cellspacing="0"></table>
```
![Screenshot (323)](https://github.com/FathiaDjawas/Lab3Web/assets/115916422/fc6d1c1d-07b6-45ee-9cbb-78bac48e4617)

**5. Menggabungkan Sel Data**

```
<tr>
  <td>1.</td>
  <td rowspan="3">Teknik</td>
  <td>Teknik Informatika</td>
</tr>
```
![Screenshot (324)](https://github.com/FathiaDjawas/Lab3Web/assets/115916422/7f66782a-a861-4c36-86bf-323c0cc6fb95)

**6. Membuat Form**

```
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama" />
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l"
        >Laki-laki</label
      >
      <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        qafor="jk_p"
        >Perempuan</label
      >
    </p>
    <p><input type="submit" value="Login" /></p>
  </fieldset>
</form>
```
![Screenshot (325)](https://github.com/FathiaDjawas/Lab3Web/assets/115916422/2f7cb034-5f48-43e3-9538-49560523692a)

**7. Menambahkan Style**

```
<style>
        form p > label {
            display: inline-block;
            width: 100px;
        }
        form input[type="text"], form textarea {
            border: 1px solid #197a43;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
    </style>
```
![Screenshot (326)](https://github.com/FathiaDjawas/Lab3Web/assets/115916422/48c506ed-9185-468b-b3c4-7c2a4470779f)


**8. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org**


![Screenshot (46)](https://github.com/syifaaurellia/Lab3Web/assets/115867244/3c8eadc5-7fb4-43ad-bdc6-4a54cd9ee31b)

![Screenshot (47)](https://github.com/syifaaurellia/Lab3Web/assets/115867244/1fc5bf7c-4f16-44bc-bfbb-569a792f5644)


## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan **dropdown** menu dan **listbox** dengan *multiple selection.*

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Form Dropdown and Listbox</title>
    <link rel="style" href="style.css">
</head>

<body>
    <nav>
        <a href="lab3_list.html">List HTML</a>
        <a href="lab3_tabel.html">Tabel HTML</a>
        <a href="lab3_form.html">Form HTML</a>
        <a href="lab3_tugas.html">Form Dropdown & Listbox</a>
    </nav>
    <header>
        <h1>Form Dropdown & Listbox</h1>
    </header>

    <form class="form_tugas">
        <label for="dropdown">Pilih salah satu buah:</label>
        <select name="dropdown" id="dropdown">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangak">Semangka</option>
        </select>

        <br><br>

        <label for="listbox">Pilih beberapa buah:</label>
        <select name="buah[]" multiple id="listbox">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangka">Semangka</option>
            <option value="kelapa">Kelapa</option>
            <option value="anggur">Anggur</option>
            <option value="melon">Melon</option>
            <option value="pepaya">Pepaya</option>
            <option value="nanas">Nanas</option>
        </select>

        <br>

        <input type="submit" value="Submit" id="input_tugas">
    </form>
</body>

</html>
```

```
body {
    font-family: Tahoma;
  }
  
  h1 {
    margin-top: 50px;
    text-align: center;
    color: #3d9a38;
  }
  
  .tabel {
    margin: 20px auto;
  }
  
  form p > label {
    display: inline-block;
    width: 100px;
  }
  
  form input[type="text"],
  form textarea {
    border: 1px solid #4dacd1;
  }
  
  form input[type="submit"] {
    border: 1px solid #84a9d4;
    background-color: #5375b9;
    color: #da8383;
    font-weight: bold;
    padding: 5px 15px;
    border-radius: 10px;
  }
  
  form input[type="submit"]:hover {
    background-color: #2098cb;
    cursor: pointer;
  }
  
  nav {
    background-color: #3fb8e0c5;
    padding: 10px;
    position: fixed;
    top: 0px;
    right: 0px;
    left: 0px;
    text-align: center;
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
    padding: 2px 4px;
    font-size: 13px;
  }
  
  nav a:hover {
    color: #487689;
  }
  
  nav a:active {
    color: #3dd274;
  }
  
  /* Style untuk form dropdown & listbox */
  .form_tugas {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #a9e664;
    background-color: #eb9ee1;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  /* Style untuk label */
  .form_tugas label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
  }
  
  /* Style untuk select dropdown dan listbox */
  .form_tugas select {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #be77a7;
    border-radius: 3px;
  }
  
  /* Style untuk tombol Submit */
  .form_tugas #input_tugas {
    background-color: #6caaed;
    color: #984f4f;
    padding: 5px 15px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  
  .form_tugas #input_tugas:hover {
    background-color: #d469ca;
  }
```

![Screenshot (332)](https://github.com/FathiaDjawas/Lab3Web/assets/115916422/629a007c-f560-4a38-99dc-e36651d33055)


## Finish, Terima Kasih
