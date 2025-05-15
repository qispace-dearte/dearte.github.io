# dearte.github.io
Portofolio Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>taqyya | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #ffffff;
    }
    header {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 6rem 2rem 4rem 2rem;
      background: url('Me.jpg') no-repeat center/cover;
      color: #fffffff;
      text-align: center;
      position: relative;
    }
    header::before {
      content: "Kaana Taqyya";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.4); 
      z-index: 0;
    }
    header h1 {
      font-size: 3.5rem;
      font-weight: 600;
      margin: 0;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.15);
    }
    header img {
      margin-top: 1rem;
      border-radius: 50%;
      width: 140px;
      height: 140px;
      object-fit: cover;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      z-index: 1;
    }
    header p {
      margin-top: 1.5rem;
      font-size: 1.2rem;
      font-style: italic;
      color: #ffffff;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 1rem;
      background: #1a1a1a;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    }
    nav a {
      text-decoration: none;
      color: #f8f8f8;
      font-weight: 600;
      transition: all 0.3s;
    }
    nav a:hover {
      color: #f0c040;
    }
    .section {
      padding: 3rem 2rem;
    }
    .section h2 {
      color: #1a1a1a;
      font-size: 1.8rem;
      border-bottom: 2px solid #f0c040;
      padding-bottom: 0.5rem;
      margin-bottom: 1.5rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 0.5rem;
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .gallery img:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    }
    footer {
      text-align: center;
      padding: 2.5rem;
      background: #fafafa;
      color: #555555;
    }
    .social-links a {
      margin: 0 0.7rem;
      color: #555555;
      text-decoration: none;
      font-weight: 600;
    }
    .social-links a:hover {
      color: #f0c040;
    }
  </style>
</head>
<body>
  <header>
    <h1>Portofolio</h1>
    <img src="Latar 1.jpg" alt="taqyya photo">
    <p>"Design & Law: Two Worlds, One Intuition. Law sharpens my logic. Design fills my soul."</p>
  </header>

  <nav>
    <a href="#coreldraw">CorelDraw</a>
    <a href="#canva">Canva</a>
    <a href="#premiere">Premiere Pro</a>
    <a href="#photography">Photography</a>
  </nav>

  <div class="section" id="coreldraw">
    <h2>CorelDRAW Works</h2>
    <div class="gallery">
      <img src="coreldraw/corel 1.jpg" alt="Buku Cover belakang DRS">
      <img src="coreldraw/corel 2.png" alt="Ganci DRS">
      <img src="coreldraw/corel 3.jpg" alt="Buku Cover depan DRS">
      <img src="coreldraw/corel 4.png" alt="Logo DRS">
      <img src="coreldraw/corel 5.jpg" alt="Buku tengah DRS">
      <img src="coreldraw/corel 6.png" alt="Logo Angkatan PTIQ Emas">
      <img src="coreldraw/corel 7.jpg" alt="Kop Surat DRS">
      <img src="coreldraw/corel 8.jpg" alt="Map DRS">
      <img src="coreldraw/corel 9.jpg" alt="Poster Logo PTIQ">
      <img src="coreldraw/corel 10.jpg" alt="Stiker Inventaris DRS">
      <img src="coreldraw/corel 11.jpg" alt="Poster Lomba DRS">
      <img src="coreldraw/corel 12.jpg" alt="Cap Stempel DRS">
      <img src="coreldraw/corel 13.jpg" alt="Poster Divisi DRS">
      <img src="coreldraw/corel 14.jpg" alt="Feeds PKKMB FH UNESA 2024">
      </div>

  <div class="section" id="canva">
    <h2>Canva Works</h2>
    <div class="gallery">
      <img src="canva/canva 1.png" alt="Poster SiGor 1">
      <img src="canva/canva 2.png" alt="Poster SiGor 2">
      <img src="canva/canva 3.png" alt="Backdrop Disnaker">
      <img src="canva/canva 4.png" alt="backdrop Pelantikan IKA FH UNESA">
      <img src="canva/canva 5.png" alt="Backdrop Disnaker 2">
      <img src="canva/canva 6.png" alt="Banner Dialog Kebangsaan IKA FH UNESA">
      <img src="canva/canva 7.png" alt="Backdrop Pak Eri">
      <img src="canva/canva 8.png" alt="Poster Alumni Talk">
      <img src="canva/canva 9.png" alt="Poster AT Sendiri 1">
      <img src="canva/canva 10.png" alt="Poster SiGor 3">
      <img src="canva/canva 11.png" alt="Poster AT Sendiri 2">
      <img src="canva/canva 12.png" alt="Poster AT Sendiri 3">
      <img src="canva/canva 13.png" alt="Poster Aksi Hari Buruh">
      <img src="canva/canva 14.jpg" alt="Foto Backdrop YLS Goes to Campuss">
      </div>

  <div class="section" id="premiere">
    <h2>Premiere Pro Works</h2>
    <div class="gallery">
      <video controls width="100%">
        <source src="premiere/Aftermovie LFD 7.0.mp4" type="video/mp4">
        Browser kamu gak mendukung video ini.
      </video>
    </div>

  <div class="section" id="photography">
    <h2>Camera Works</h2>
    <div class="gallery">
      <img src="photography/IMG 1.jpg" alt="PKKMB FH UNESA 2024">
      <img src="photography/IMG 2.jpg" alt="PKKMB FH UNESA 2024 2">
      <img src="photography/IMG 3.jpg" alt="PKKMB FH UNESA 2024 3">
      <img src="photography/IMG 4.jpg" alt="PKKMB FH UNESA 2024 4">
      <img src="photography/IMG 5.jpg" alt="PKKMB FH UNESA 2024 5">
      <img src="photography/IMG 6.jpg" alt="PKKMB FH UNESA 2024 6">
      <img src="photography/IMG 7.jpg" alt="PKKMB FH UNESA 2024 7">
    </div>
  </div>

  <footer>
    <p><strong><em>“Plus many others that aren't showcased here!”</em></strong></p>
    <p>Contact me:</p>
    <div class="social-links">
      <a href="https://instagram.com/taqyya_" target="_blank">Instagram</a>
      <a href="https://wa.me/6281276532228" target="_blank">WhatsApp</a>
    </div>
    <p>&copy; 2025 taqyya</p>
  </footer>
</body>
</html>
