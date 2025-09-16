<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CV Gemilang Dhoho</title>
  <style>
    body { 
      font-family: Arial, sans-serif; 
      margin: 0; 
      padding: 0; 
      line-height: 1.6; 
      background: #fff;
    }
    header { 
      background: #003366; 
      color: #fff; 
      padding: 20px; 
      text-align: center; 
    }
    header img { 
      max-height: 80px; 
      display: block; 
      margin: 0 auto 10px; 
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section { 
      padding: 20px; 
      max-width: 1000px; 
      margin: auto; 
    }
    h2 { 
      color: #003366; 
      margin-bottom: 10px; 
    }
    .services { 
      display: flex; 
      flex-wrap: wrap; 
      gap: 20px; 
    }
    .service { 
      flex: 1 1 250px; 
      background: #f4f4f4; 
      padding: 15px; 
      border-radius: 8px; 
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .service:hover { 
      transform: translateY(-5px); 
      box-shadow: 0 4px 10px rgba(0,0,0,0.2); 
    }
    /* Publikasi */
    .catalog {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .book {
      background: #f4f4f4;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .book:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .book img {
      max-width: 100%;
      height: auto;
      border-radius: 6px;
      margin-bottom: 10px;
    }
    footer { 
      background: #003366; 
      color: #fff; 
      text-align: center; 
      padding: 15px; 
      margin-top: 20px;
    }
    a { 
      color: #003366; 
      text-decoration: none; 
    }
    a:hover { 
      text-decoration: underline; 
    }
    @media (max-width: 600px) {
      .services { flex-direction: column; }
    }
  </style>
</head>
<body>

<header>
  <img src="assets/logo.png" alt="Logo CV Gemilang Dhoho">
  <h1>CV GEMILANG DHOHO</h1>
  <p>Penerbit & Percetakan</p>
  <nav>
    <a href="#tentang">Tentang Kami</a>
    <a href="#layanan">Layanan</a>
    <a href="#publikasi">Publikasi</a>
    <a href="#kontak">Kontak</a>
  </nav>
</header>

<section id="tentang">
  <h2>Tentang Kami</h2>
  <p>CV Gemilang Dhoho adalah perusahaan yang bergerak di bidang penerbitan dan percetakan buku. Berdiri sejak 4 Mei 2020, kami berkomitmen untuk mendukung kebutuhan pendidikan dan literasi melalui layanan penerbitan profesional.</p>
</section>

<section id="layanan">
  <h2>Layanan Kami</h2>
  <div class="services">
    <div class="service">
      <h3>Percetakan Buku</h3>
      <p>Layanan cetak buku dengan kualitas terbaik untuk mendukung kebutuhan akademik maupun umum.</p>
    </div>
    <div class="service">
      <h3>Penerbitan Buku</h3>
      <p>Membantu penulis mewujudkan karya dalam bentuk buku yang profesional dan siap edar.</p>
    </div>
    <div class="service">
      <h3>Kebutuhan Pendidikan</h3>
      <p>Penyediaan buku dan bahan bacaan untuk menunjang kegiatan belajar-mengajar.</p>
    </div>
  </div>
</section>

<section id="publikasi">
  <h2>Publikasi</h2>
  <p>Berikut adalah beberapa katalog buku yang telah kami terbitkan:</p>
  <div class="catalog">
    <div class="book">
      <img src="assets/1754023298786.jpg" alt="Aku Sayang Bumi">
      <h3>Aku Sayang Bumi</h3>
      <p>Usia 3A (4–5 Tahun)</p>
    </div>
    <div class="book">
      <img src="assets/1754023191443.jpg" alt="Bermain & Bekerjasama">
      <h3>Bermain & Bekerjasama</h3>
      <p>Usia 4A (4–5 Tahun)</p>
    </div>
    <div class="book">
      <img src="assets/1754023287240.jpg" alt="Aku Cinta Indonesia">
      <h3>Aku Cinta Indonesia</h3>
      <p>Usia 2A (4–5 Tahun)</p>
    </div>
    <div class="book">
      <img src="assets/1754023386603.jpg" alt="Agama & Budi Pekerti">
      <h3>Agama & Budi Pekerti</h3>
      <p>Usia 1A (4–5 Tahun)</p>
    </div>
  </div>
</section>

<section id="kontak">
  <h2>Kontak</h2>
  <p>📍 Jl. Raya Kediri-Wates 218 Jayaraya, Wates, Kab. Kediri, Jawa Timur 64174</p>
  <p>📞 +62 821-3155-9010</p>
  <p>📧 <a href="mailto:gemilangdhoho@gmail.com">gemilangdhoho@gmail.com</a></p>
  <p>📑 Nomor Induk Berusaha: 0220003500848</p>
  <p>📷 Instagram: <a href="https://www.instagram.com/gemilangdhoho" target="_blank">@gemilangdhoho</a></p>
</section>

<footer>
  <p>&copy; 2025 CV Gemilang Dhoho. All rights reserved.</p>
</footer>

</body>
</html>
