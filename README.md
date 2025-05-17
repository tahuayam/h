<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Website Speaking</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            width: 80%;
            margin: auto;
        }
        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 0;
        }
        .logo {
            width: 100px;
            height: 100px;
            background-color: #ccc;
            text-align: center;
            line-height: 100px;
        }
        h1 {
            text-align: center;
        }
        nav {
            background-color: #f0f0f0;
            text-align: center;
            margin-top: 10px;
        }
        nav a {
            display: inline-block;
            padding: 10px 20px;
            text-decoration: none;
            color: #000;
        }
        .content {
            display: flex;
            margin-top: 20px;
        }
        .main {
            flex: 2;
            padding: 10px;
        }
        .main img {
            width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        .sidebar {
            flex: 1;
            padding: 10px;
            background-color: #f9f9f9;
        }
        footer {
            margin-top: 20px;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Logo</div>
        <h1>Judul Website</h1>
    </header>

    <nav>
        <a href="#">HOME</a>
        <a href="#">PENDAFTARAN</a>
        <a href="#">INFORMASI</a>
        <a href="#">KONTAK KAMI</a>
    </nav>

    <div class="content">
        <div class="main">
            <img src="gambar1.jpg" alt="Gambar 1">
            <p>Paragraf artikel 1...</p>
            <img src="gambar2.jpg" alt="Gambar 2">
            <p>Paragraf artikel 2...</p>
        </div>
        <div class="sidebar">
            <h3>ISI SIDEBAR 1</h3>
            <ul>
                <li>Buku Terbaru 1</li>
                <li>Buku Terbaru 2</li>
            </ul>
            <h3>ISI SIDEBAR 2</h3>
            <ul>
                <li>Daftar Buku Populer</li>
                <li>Daftar Buku Paling Sering Dipinjam</li>
            </ul>
        </div>
    </div>

    <footer>
        Nama Anda @copyright 2025
    </footer>

</body>
</html>
