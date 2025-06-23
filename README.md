<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Aulia Tasya</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', bold, sans-serif;
        }

        body {
            background-color: #BAA8D6;
            color: #d4a8d6;
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #6e8efb;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0f0f0;
        }

        .info-item {
            margin-bottom: 15px;
        }

        .info-item h3 {
            font-size: 1.1rem;
            color: #555;
        }

        .info-item p {
            color: #777;
        }

        .info-item .date {
            font-size: 0.9rem;
            color: #999;
            font-style: italic;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;


        .social-link {
            display: inline-block;
            width: 40px;
            height: 40px;
            background-color: #6e8efb;
            color: white;
            border-radius: 50%;
            text-align: center;
            line-height: 40px;
            transition: all 0.3s ease;
            text-decoration: none;
        }

        .social-link:hover {
            background-color: #a777e3;
            transform: translateY(-3px);
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .container {
                padding: 10px;
            }
            
            header {
                padding: 30px 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="txt.jpg" alt="Foto Profil" class="profile-img">
            <h1>Aulia Tasya</h1>
            <p class="tagline">Backbuner Related</p>
        </header>

        <main>
            <section class="card">
                <h2>Tentang Saya</h2>
                <div class="info-item">
                    <p>Lulusan SMK yang kini tengah melanjutkan studi di Universitas Pamulang dan mengambil jurusan Teknik Informatika. Cepat tanggap dalam mengikuti arahan, sebelumnya studi di bidang Manajemen Perkantoran saat masih SMK.</p>
                </div>
                <div class="info-item">
                    <h3>Tanggal Lahir</h3>
                    <p>26/05/2006</p>
                </div>
                <div class="info-item">
                    <h3>Alamat</h3>
                    <p>Buaran, Banten, Tangerang Selatan</p>
                </div>
                <div class="info-item">
                    <h3>Email</h3>
                    <p>auliatasyaa2006@gmail.com</p>
                </div>
                <div class="info-item">
                    <h3>Telepon</h3>
                    <p>+62 851 1726 0532</p>
                </div>
            </section>

            <section class="card">
                <h2>Riwayat Pendidikan</h2>
                <div class="info-item">
                    <h3>SMK KUSUMA BANGSA BOGOR</h3>
                    <p>Otomatisasi Tata Kelola dan Perkantoran</p>
                    <p class="date">2021-2024</p>
                </div>
                <div class="info-item">
                    <h3>UNIVERSITAS PAMULANG</h3>
                    <p>Teknik Informatika</p>
                    <p class="date">2025</p>
                </div>
            </section>

            <section class="card">
                <h2>Riwayat Pekerjaan</h2>
                <div class="info-item">
                    <h3>Crew SnackBar</h3>
                    <p>Dairyland Riverside</p>
                    <p class="date">2024</p>
                    <p>Melayani Pelanggan dan Menjual Produk.</p>
                </div>
                <div class="info-item">
                    <h3>Waitress Part Time</h3>
                    <p>Vilo Hang Lekir</p>
                    <p class="date">2025</p>
                    <p>Melayani dan Mengantar Makanan.</p>
                </div>
            </section>

            <section class="card">
                <h2>Kontak & Media Sosial</h2>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/aulia-tasyaa-scy2006" class="social-link" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://www.instagram.com/scyylliaa" class="social-link" title="Instagram"><i class="fab fa-instagram"></i></a>
                </div>
            </section>
        </main>

        <footer>
            <p>&copy; 2025 Aulia Tasya. All rights reserved.</p>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.card');
            cards.forEach((card, index) => {
                setTimeout(() => {
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }, 200 * index);
            });
            cards.forEach(card => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            });
        });
    </script>
</body>
</html>
