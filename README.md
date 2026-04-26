[index.html](https://github.com/user-attachments/files/27097178/index.html)
# portfolio-miftahul
web
<!doctype html>
<html lang="id"><img width="1200" height="1600" alt="foto" src="https://github.com/user-attachments/assets/3cff943c-ca59-4493-87b9-70e70a26f34d" />
<img width="1200" height="1600" alt="khair" src="https://github.com/user-attachments/assets/8346fd50-9d48-4508-ad00-d9facfdbc181" />

  <head>
    <meta charset="UTF-8" />
    <title>Portfolio - Muhammad Miftahul Khair</title>

    <!-- ICON (WA, IG, YT) -->
    <script
      src="https://kit.fontawesome.com/yourcode.js"
      crossorigin="anonymous"
    ></script>

    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial;
      }

      body {
        background: #f4f4f4;
      }

      /* NAVBAR */
      nav {
        background: #2c3e50;
        padding: 15px;
        position: sticky;
        top: 0;
      }

      nav ul {
        display: flex;
        justify-content: center;
        list-style: none;
      }

      nav ul li {
        margin: 0 20px;
      }

      nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
      }

      /* HEADER */
      header {
        text-align: center;
        padding: 50px;
        color: white;
        background: linear-gradient(to right, #53bc1a, #a5be93);
      }

      header img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        border: 5px solid white;
      }

      /* CARD */
      .card {
        background: white;
        margin: 20px auto;
        padding: 20px;
        border-radius: 10px;
        width: 80%;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      }

      /* BUTTON SOSIAL */
      .sosial {
        display: flex;
        gap: 15px;
        margin-top: 15px;
      }

      .sosial a {
        text-decoration: none;
        color: white;
        padding: 12px 20px;
        border-radius: 30px;
        display: flex;
        align-items: center;
        gap: 8px;
        transition: 0.3s;
      }

      /* WARNA */
      .wa {
        background: #25d366;
      }
      .ig {
        background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
      }
      .yt {
        background: #ff0000;
      }

      /* HOVER */
      .sosial a:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
      }

      footer {
        text-align: center;
        padding: 15px;
        background: #2c3e50;
        color: white;
      }
    </style>
  </head>

  <body>
    <!-- NAVBAR -->
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <!-- HEADER -->
    <header id="home">
      <img src="khair.jpg" />
      <h1>Muhammad Miftahul Khair</h1>
      <p>Mahasiswa Ilmu Komputer - Semester 6</p>
    </header>

    <!-- ABOUT -->
    <div
      class="card"
      id="about"
    >
      <h2>👤 Tentang Saya</h2>
      <p>
        Saya adalah mahasiswa Fakultas Ilmu Komputer di Yatsi Madani yang saat ini sedang menempuh pendidikan pada semester 6. Selama menjalani perkuliahan, saya memiliki ketertarikan yang besar terhadap dunia teknologi, khususnya di bidang
        pemrograman dan pengembangan sistem. Ketertarikan ini mendorong saya untuk terus belajar dan mengasah kemampuan, baik melalui materi perkuliahan maupun eksplorasi mandiri di luar kelas. Saya dikenal sebagai pribadi yang memiliki
        semangat belajar tinggi, disiplin, dan mampu bekerja secara mandiri maupun dalam tim. Dalam proses belajar, saya selalu berusaha memahami konsep secara mendalam serta mengaplikasikannya dalam bentuk proyek nyata, seperti pembuatan
        aplikasi berbasis web dan sistem informasi. Hal ini saya lakukan sebagai bentuk kesiapan dalam menghadapi dunia kerja di bidang teknologi informasi yang terus berkembang.
      </p>
    </div>

    <div class="card">
      <h2>📍 Informasi</h2>
      <p>
        Saya berasal dari Kota Tangerang, sebuah kota yang dikenal dengan perkembangan pesat di bidang industri dan teknologi. Lingkungan tersebut turut membentuk pola pikir saya untuk terus berkembang dan mengikuti kemajuan zaman,
        khususnya dalam bidang teknologi informasi yang saya tekuni saat ini. Saat ini, saya tinggal di Kampung Margasari. Lingkungan tempat tinggal saya memberikan suasana yang nyaman dan sederhana, serta menjadi tempat yang mendukung saya
        untuk fokus dalam belajar dan mengembangkan diri. Dari lingkungan ini, saya juga belajar tentang nilai kebersamaan, kerja keras, dan pentingnya menjaga hubungan baik dengan orang lain. Saya merupakan anak ke-2 dari 3 bersaudara.
        Posisi ini membuat saya belajar untuk menjadi pribadi yang bertanggung jawab, mandiri, serta mampu menjadi penghubung yang baik dalam keluarga.
      </p>
    </div>

    <!-- CONTACT -->
    <div
      class="card"
      id="contact"
    >
      <h2>📞 Kontak</h2>
      <p>Email: miftahulkhair2677@gmail.com</p>

      <div class="sosial">
        <!-- WHATSAPP -->
        <a
          href="https://wa.me/08568766753"
          target="_blank"
          class="wa"
        >
          <i class="fab fa-whatsapp"></i> WhatsApp
        </a>

        <!-- INSTAGRAM -->
        <a
          href="https://instagram.com/zherof26"
          target="_blank"
          class="ig"
        >
          <i class="fab fa-instagram"></i> Instagram
        </a>

        <!-- YOUTUBE -->
        <a
          href="https://youtube.com/@MiftahulKhair-l1x"
          target="_blank"
          class="yt"
        >
          <i class="fab fa-youtube"></i> YouTube
        </a>
      </div>
    </div>

    <footer>
      <p>© 2026 Muhammad Miftahul Khair</p>
    </footer>
  </body>
</html>
