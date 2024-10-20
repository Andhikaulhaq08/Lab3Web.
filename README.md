# Lab3Web.
<form action="proses.php" method="post">
    <fieldset>
    <legend>Login</legend>
    <p>
    <label for="uname">Username</label>
    <input type="text" id="uname" name="username">
    </p>
    <p>
    <label for="passwd">Password</label>
    <input type="password" id="passwd" name="password">
    </p>
    <p><input type="submit" value="Login"></p>
     </fieldset>
    </form>
<img width="953" alt="image" src="https://github.com/user-attachments/assets/9eae1c71-9587-4d37-bd6f-e07046dffcb1">

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>

<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
    </section>
<img width="635" alt="image" src="https://github.com/user-attachments/assets/051653f0-2626-4e4f-94ce-95928bd23804">

<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>
<img width="799" alt="image" src="https://github.com/user-attachments/assets/e3b8b42c-7bf9-4bc5-8fc1-29cc8f8f4895">

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
<img width="805" alt="image" src="https://github.com/user-attachments/assets/fb6dbc20-14c5-418d-a81e-19fd1285c466">

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
</header>
</body>
</html>

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

<img width="792" alt="image" src="https://github.com/user-attachments/assets/bddf211a-4d34-4e2f-9668-d30158351e83">

 
    <table border="1" cellpadding="6" cellspacing="0">
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
        <td rowspan="3">Teknik</td>
        <td>Teknik Informatika</td>
        </tr>
        <tr>
        <td>2.</td>
        <td>Teknik Industri</td>
        </tr>
        <tr>
        <td>3.</td>
        <td>Teknik Lingkungan</td>
        </tr>
        </tbody>
        </table>

<img width="278" alt="image" src="https://github.com/user-attachments/assets/f591c978-8734-4d53-adc8-310122362fe4">

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
</body>
</html>

<form action="proses.php" method="post">
    <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
    <label for="nama">Nama</label>
    <input type="text" id="nama" name="nama">
    </p>
    <p>
    <label for="alamat">Alamat</label>
    <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
    <label>Jenis Kelamin</label>
    <input id="jk_l" type="radio" name="kelamin" value="L" /><label
    for="jk_l">Laki-laki</label>
    <input id="jk_p" type="radio" name="kelamin" value="P" /><label

for="jk_p">Perempuan</label>
</p>
<p><input type="submit" value="Login"></p>
</fieldset>
</form>

<img width="953" alt="image" src="https://github.com/user-attachments/assets/e794390b-6e7a-41cc-9afa-33aeb2c43a59">

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

<img width="955" alt="image" src="https://github.com/user-attachments/assets/e520870c-6e16-4c89-b506-b508e104b09c">





