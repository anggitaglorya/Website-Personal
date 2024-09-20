<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan Anggita Glorya</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
        }
        form {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Selamat Datang di Halaman Perpustakaan Anggita Glorya Sinulingga</h1>
    <p><strong>Perpustakaan Anggita Glorya dengan NIM 222201005</strong></p>
    <p>D-III Perpustakaan Universitas Sumatera Utara</p>
    <p>Perkenalkan, nama saya Anggita Glorya, saya adalah mahasiswa ilmu perpustakaan. Ini homepage pertama saya karena saya baru belajar tentang cara membuat homepage.</p>

    <h2><strong>Perpustakaan Kota Medan</strong></h2>
    <p>Berikut ini adalah gambar Perpustakaan Kota Medan:</p>
    <img src="logo perpus medan.png" alt="Logo Perpustakaan Kota Medan" width="1200">
    <p>Perpustakaan Kota Medan adalah salah satu pusat sumber informasi dan literasi di kota ini. Terletak di lokasi strategis, perpustakaan ini menyediakan berbagai koleksi buku, majalah, dan materi referensi lainnya yang mencakup berbagai topik. Selain itu, fasilitas komputer dan akses internet juga tersedia untuk masyarakat yang ingin mencari informasi secara online.</p>
    
    <h2><strong>Video Perpustakaan Nasional</strong></h2>
    <video width="400" controls>
        <source src="video perpus medan.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <h2><strong>Formulir Anggota Perpustakaan Program Studi Perpustakaan dan Sains Informasi</strong></h2>
    <form>
        <label for="nama">Nama:</label><br>
        <input type="text" id="nama" name="nama"><br><br>
        
        <label for="nim">NIM:</label><br>
        <input type="text" id="nim" name="nim"><br><br>

        <label for="alamat">Alamat:</label><br>
        <input type="text" id="alamat" name="alamat"><br><br>

        <label for="gender">Jenis Kelamin:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Pria</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Wanita</label><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>

        <label for="phone">No HP:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>

        <label for="birthplace">Tempat Lahir:</label><br>
        <input type="text" id="birthplace" name="birthplace"><br><br>

        <label for="birthdate">Tanggal Lahir:</label><br>
        <input type="date" id="birthdate" name="birthdate"><br><br>

        <input type="submit" value="Submit">
    </form>

    <h2><strong>Table Peminjaman dan Pengembalian Buku</strong></h2>
    <table>
        <thead>
            <tr>
                <th>No</th>
                <th>Nama Peminjam</th>
                <th>Judul Buku</th>
                <th>Nama Pengarang</th>
                <th>Tanggal Peminjaman</th>
                <th>Tanggal Pengembalian</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Ridwansyah</td>
                <td>Nusantara : Biologi umum</td>
                <td>Handayani</td>
                <td>10-9-2023</td>
                <td>13-9-2023</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Angelica Mutiara</td>
                <td>Mikrobiologi kedokteran</td>
                <td>Soedarto</td>
                <td>19-9-2023</td>
                <td>29-9-2023</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Jelita Ratih</td>
                <td>Hukum agraria : diktat hukum agraria</td>
                <td>Hanafi</td>
                <td>10-10-2023</td>
                <td>25-10-2023</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Adrian Camalino</td>
                <td>Akuntansi biaya : pencatatan dan kelola biaya</td>
                <td>Pirmatua Sirait</td>
                <td>5-10-2023</td>
                <td>20-10-2023</td>
            </tr>
            <tr>
                <td>5</td>
                <td>Adli Gunawan</td>
                <td>Ikatan Kimia</td>
                <td>Sukardjo</td>
                <td>12-10-2023</td>
                <td>26-10-2023</td>
            </tr>
        </tbody>
    </table>

    <h2><strong>Form Pemesanan Buku</strong></h2>
    <form>
        <label for="book-title">Judul Buku:</label><br>
        <input type="text" id="book-title" name="book-title"><br><br>

        <label for="author">Pengarang:</label><br>
        <input type="text" id="author" name="author"><br><br>

        <label for="quantity">Jumlah Buku:</label><br>
        <input type="number" id="quantity" name="quantity"><br><br>

        <input type="submit" value="Pesan Buku">
    </form>

    <h2><strong>Form Perpanjangan Peminjaman Buku</strong></h2>
    <form>
        <label for="borrower-name">Nama Peminjam:</label><br>
        <input type="text" id="borrower-name" name="borrower-name"><br><br>

        <label for="borrowed-book">Judul Buku:</label><br>
        <input type="text" id="borrowed-book" name="borrowed-book"><br><br>

        <label for="extension-date">Tanggal Perpanjangan:</label><br>
        <input type="date" id="extension-date" name="extension-date"><br><br>

        <input type="submit" value="Perpanjang Peminjaman">
    </form>

    
