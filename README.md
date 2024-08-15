<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website - [Nama Kamu]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            text-align: center;
            padding: 10px;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #333;
        }

        .portfolio-item {
            margin-bottom: 20px;
        }

        .portfolio-item img {
            max-width: 100%;
            height: auto;
        }

        .portfolio-item h3 {
            margin-top: 10px;
        }

        .contact-form {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-form label {
            display: block;
            margin: 10px 0 5px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
        }

        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>

    <header>
        <h1>[Nama Kamu]</h1>
        <p>Ahli Teknik Gambar Bangunan, Desain Grafis, Website Development, Pelatihan, dan Kursus Online</p>
    </header>

    <nav>
        <a href="#about">Tentang Saya</a>
        <a href="#portfolio">Portofolio</a>
        <a href="#services">Layanan</a>
        <a href="#contact">Kontak</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>[Deskripsi singkat tentang dirimu, pengalaman, dan keahlianmu]</p>
        </section>

        <section id="portfolio">
            <h2>Portofolio</h2>
            <div class="portfolio-item">
                <img src="[link/gambar1.jpg]" alt="Proyek 1">
                <h3>Proyek 1</h3>
                <p>[Deskripsi singkat tentang proyek ini]</p>
            </div>
            <div class="portfolio-item">
                <img src="[link/gambar2.jpg]" alt="Proyek 2">
                <h3>Proyek 2</h3>
                <p>[Deskripsi singkat tentang proyek ini]</p>
            </div>
            <!-- Tambahkan lebih banyak proyek sesuai kebutuhan -->
        </section>

        <section id="services">
            <h2>Layanan</h2>
            <p>Saya menawarkan berbagai layanan seperti teknik gambar bangunan, desain grafis, pembuatan website, pelatihan, dan kursus online. Daftar sekarang untuk mengikuti kursus atau konsultasi.</p>
        </section>

        <section id="contact">
            <h2>Kontak & Pendaftaran Kursus</h2>
            <div class="contact-form">
                <form action="submit_form.php" method="post">
                    <label for="name">Nama:</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Pesan atau Pertanyaan:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>

                    <button type="submit">Kirim</button>
                </form>
            </div>
        </section>
    </div>

</body>

</html>
