
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Renungan Paskah</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #f7f0e8, #fffaf5);
      color: #3b2f2f;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #6b3e26, #b9805d);
      color: white;
      text-align: center;
      padding: 60px 20px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.15);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      opacity: 0.95;
    }

    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.08);
      margin-bottom: 30px;
    }

    .card h2 {
      color: #7a4b2f;
      margin-bottom: 15px;
      font-size: 1.8rem;
    }

    .verse {
      background: #fdf4ed;
      border-left: 6px solid #c47b4f;
      padding: 20px;
      border-radius: 12px;
      margin-top: 20px;
      font-style: italic;
    }

    .embed-section {
      margin-top: 25px;
    }

    .embed-section h3 {
      margin-bottom: 15px;
      color: #6b3e26;
    }

    .embed-box {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 16px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.12);
    }

    .embed-box iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .quote {
      text-align: center;
      font-size: 1.2rem;
      color: #7a4b2f;
      margin-top: 20px;
      font-weight: 500;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      color: #7a6a5d;
      font-size: 0.95rem;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      background: #8b5e3c;
      color: white;
      padding: 12px 22px;
      border-radius: 999px;
      text-decoration: none;
      transition: 0.3s ease;
      font-weight: 600;
    }

    .btn:hover {
      background: #6f4529;
      transform: translateY(-2px);
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      .card {
        padding: 22px;
      }

      .card h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Renungan Paskah</h1>
    <p>Kebangkitan Kristus membawa harapan, pemulihan, dan hidup yang baru.</p>
  </header>

  <div class="container">

    <div class="card">
      <h2>Yesus Telah Bangkit</h2>
      <p>
        Paskah bukan sekadar perayaan tahunan, tetapi pengingat bahwa kasih Tuhan
        tidak berhenti di kayu salib. Kebangkitan Yesus adalah bukti kemenangan
        atas dosa, ketakutan, dan kematian.
      </p>

      <div class="verse">
        <strong>Matius 28:6</strong><br>
        “Ia tidak ada di sini, sebab Ia telah bangkit, sama seperti yang telah dikatakan-Nya.”
      </div>

      <p style="margin-top: 20px;">
        Saat hidup terasa gelap, Paskah mengingatkan kita bahwa selalu ada pagi
        setelah malam. Tuhan sanggup membangkitkan harapan yang sempat mati
        dalam hati kita.
      </p>

      <p class="quote">
        “Dari kubur yang kosong, lahirlah pengharapan yang penuh.”
      </p>

      <a href="#embed" class="btn">Lihat Renungan / Video</a>
    </div>

    <div class="card embed-section" id="embed">
      <h3>Renungan / Video Paskah</h3>
      <p style="margin-bottom: 20px;">
        Anda bisa mengganti link embed di bawah ini dengan video, khotbah, atau renungan favorit Anda.
      </p>

      <div class="embed-box">
        <iframe 
          src="https://heyzine.com/flip-book/868b5b107f.html" 
          title="Renungan Paskah"
          allowfullscreen>
        </iframe>
      </div>
    </div>

  </div>

  <footer>
    © 2026 Renungan Paskah • Dibuat dengan damai dan pengharapan
  </footer>

</body>
</html>
