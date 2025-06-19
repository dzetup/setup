<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Landing Page Sederhana</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
      text-align: center;
    }

    header {
      background: #4CAF50;
      color: white;
      padding: 60px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 48px;
    }

    header p {
      font-size: 20px;
      margin-top: 10px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      font-size: 16px;
      background-color: white;
      color: #4CAF50;
      border: 2px solid white;
      border-radius: 4px;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #45a049;
      color: white;
      border-color: #45a049;
    }

    section {
      padding: 40px 20px;
    }

    footer {
      background: #333;
      color: white;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Selamat Datang!</h1>
    <p>Ini adalah landing page sederhana menggunakan HTML dan CSS</p>
    <a href="#kontak" class="btn">Hubungi Saya</a>
  </header>

  <section>
    <h2>About Me</h2>
    <p>Halo! Saya sedang belajar membuat website statis dan menghosting-nya di GitHub Pages.</p>
  </section>

  <section id="kontak">
    <h2>Kontak</h2>
    <p>Email: kamu@email.com</p>
    <p>Instagram: @kamu</p>
  </section>

  <footer>
    &copy; 2025 - Dibuat dengan ♥ oleh Saya
  </footer>

</body>
</html>
