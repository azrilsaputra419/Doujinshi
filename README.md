Doujinshi
Website doujinshi adalah situs web yang menyediakan koleksi komik independen atau karya seni yang biasanya dibuat oleh penggemar dan seniman amatir
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman Komik Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        .comic-title {
            font-size: 2em;
            margin-bottom: 20px;
            text-align: center;
        }

        .comic-description {
            font-size: 1.2em;
            margin-bottom: 20px;
            text-align: center;
        }

        .comic-pages {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .comic-page {
            width: 100%;
            max-width: 600px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background-color: #fff;
        }

        .comic-page img {
            width: 100%;
            height: auto;
        }

        .nav-buttons {
            text-align: center;
            margin-top: 20px;
        }

        .nav-buttons a {
            text-decoration: none;
            color: #fff;
            padding: 10px 20px;
            background-color: #ff6600;
            margin: 0 10px;
            border-radius: 5px;
            font-size: 1.1em;
        }

        .nav-buttons a:hover {
            background-color: #ff4500;
        }

        @media (max-width: 768px) {
            .comic-page {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Komik Saya - Halaman 1</h1>
</header>

<div class="container">
    <div class="comic-title">Judul Komik Saya</div>
    <div class="comic-description">
        Selamat datang di komik saya! Cerita ini penuh dengan petualangan yang seru dan karakter yang menarik.
    </div>

    <div class="comic-pages">
        <!-- Halaman Komik 1 -->
        <div class="comic-page">
            <img src="komik_halaman1.jpg" alt="Halaman 1">
        </div>

        <!-- Halaman Komik 2 -->
        <div class="comic-page">
            <img src="komik_halaman2.jpg" alt="Halaman 2">
        </div>

        <!-- Halaman Komik 3 -->
        <div class="comic-page">
            <img src="komik_halaman3.jpg" alt="Halaman 3">
        </div>

        <!-- Tambahkan lebih banyak gambar sesuai halaman komik Anda -->
    </div>

    <div class="nav-buttons">
        <a href="prev_page.html">Halaman Sebelumnya</a>
        <a href="next_page.html">Halaman Berikutnya</a>
    </div>
</div>

</body>
</html>
