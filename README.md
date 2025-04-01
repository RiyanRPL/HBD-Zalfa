<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday Zalfa</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #f8e1f4, #fde2e4);
      color: #333;
      text-align: center;
    }
    .container {
      padding: 50px 20px;
    }
    h1 {
      font-size: 3em;
      color: #d45d79;
      margin-bottom: 10px;
    }
    h2 {
      font-weight: normal;
      color: #555;
      margin-bottom: 30px;
    }
    .message {
      max-width: 600px;
      margin: 0 auto;
      background-color: #fff7fb;
      border: 2px solid #f3d1e3;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .video-container {
      margin-top: 30px;
    }
    video {
      width: 90%;
      max-width: 600px;
      border-radius: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    button {
      margin-top: 30px;
      padding: 10px 20px;
      background-color: #f49ac2;
      color: white;
      border: none;
      border-radius: 30px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #d45d79;
    }
    #secret {
      margin-top: 20px;
      display: none;
      background-color: #fff0f6;
      border: 1px solid #f5c6d6;
      border-radius: 15px;
      padding: 15px;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Happy 18th Birthday, Zalfa!</h1>
    <h2>15 Oktober 2025</h2>
    <div class="message">
      <p>Hari ini adalah hari yang sangat spesial. Ulang tahun ke-18mu, momen penting yang menandai awal dari petualangan baru dalam hidupmu.</p>
      <p>Semoga semua impian dan harapanmu tercapai. Kamu pantas mendapatkan kebahagiaan yang luar biasa.</p>
      <p>Teruslah menjadi Zalfa yang kuat, baik hati, dan bersinar.</p>
    </div><div class="video-container">
  <video controls>
    <source src="video.mp4" type="video/mp4">
    Browser kamu tidak mendukung pemutaran video.
  </video>
</div>

<button onclick="revealSecret()">Klik untuk buka surat rahasia</button>
<div id="secret">
  <p>Selamat ulang tahun, Zalfa. Mungkin aku bukan siapa-siapa, tapi aku selalu mendoakan yang terbaik buatmu. Terima kasih sudah jadi bagian dari cerita hidupku, walau sebentar atau hanya lewat tatapan. Semoga kamu selalu bahagia.</p>
</div>

  </div>
  <script>
    function revealSecret() {
      document.getElementById('secret').style.display = 'block';
    }
  </script>
</body>
</html>
