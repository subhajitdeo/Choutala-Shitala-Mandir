index.html
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Choutala Shitala Mandir</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    /* ===== BASE THEME ===== */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #FFF8EE; /* cream */
      color: #3E2723;
    }

    /* ===== HEADER / HERO ===== */
    header {
      background: linear-gradient(
        rgba(122, 30, 30, 0.6),
        rgba(122, 30, 30, 0.6)
      ),
      url("https://images.unsplash.com/photo-1600352703874-63b5a3d1ad59");
      background-size: cover;
      background-position: center;
      color: #fff;
      text-align: center;
      padding: 80px 20px;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 42px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      opacity: 0.95;
    }

    /* ===== SECTION ===== */
    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }

    section h2 {
      font-family: 'Playfair Display', serif;
      color: #7A1E1E;
      margin-bottom: 15px;
      position: relative;
    }

    section h2::after {
      content: "🪔";
      margin-left: 8px;
    }

    section p {
      line-height: 1.8;
      font-size: 16px;
    }

    /* ===== CARD ===== */
    .card {
      background: #ffffff;
      border-radius: 14px;
      padding: 25px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
      margin-top: 20px;
    }

    /* ===== FOOTER ===== */
    footer {
      background: #7A1E1E;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <header>
    <h1>श्री छौटाला शीतला माता मंदिर</h1>
    <p>🙏 Jai Shitala Mata 🙏</p>
  </header>

  <!-- ABOUT -->
  <section>
    <h2>मंदिर के बारे में</h2>
    <div class="card">
      <p>
        यह मंदिर माता शीतला को समर्पित है।
        यहाँ श्रद्धालु दूर-दूर से दर्शन हेतु आते हैं।
        माता की कृपा से भक्तों की सभी मनोकामनाएँ पूर्ण होती हैं।
      </p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    🛕 Choutala Shitala Mandir • Built with Bhakti
  </footer>

</body>
</html>

