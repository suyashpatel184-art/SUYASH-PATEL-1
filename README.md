<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SUYASH PATEL - व्यक्तिगत वेबसाइट</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@400;600&display=swap" rel="stylesheet">
  <!-- Icons (Font Awesome) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      margin: 0;
      font-family: 'Noto Sans Devanagari', Arial, sans-serif;
      background: #f0f2f5;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background: linear-gradient(135deg, #4CAF50, #2e7d32);
      color: white;
      text-align: center;
      padding: 40px 20px;
      position: relative;
      overflow: hidden;
    }
    header img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 5px solid white;
      margin-bottom: 15px;
      object-fit: cover;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      animation: zoomIn 1s ease;
    }
    header h1 {
      margin: 10px 0 5px;
      font-size: 2.4em;
      animation: fadeInDown 1s ease;
    }
    header p {
      font-size: 1.2em;
      animation: fadeInUp 1.2s ease;
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes zoomIn {
      from { transform: scale(0.8); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }

    nav {
      background: #333;
      padding: 12px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #4CAF50;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 50px 20px;
    }
    .card {
      background: white;
      padding: 25px;
      margin-bottom: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    }
    h2 {
      margin-top: 0;
      color: #2e7d32;
    }
    .social-links a {
      display: inline-block;
      margin: 8px 12px;
      font-size: 1.2em;
      color: #333;
      transition: color 0.3s, transform 0.3s;
    }
    .social-links a:hover {
      color: #4CAF50;
      transform: scale(1.1);
    }
    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <!-- यहाँ आपका नया लोगो लगाएँ -->
    <img src="suyash-logo-2025.png" alt="SUYASH PATEL लोगो" />
    <h1>नमस्ते, मैं SUYASH PATEL</h1>
    <p>मेरे व्यक्तिगत वेबसाइट पर आपका स्वागत है</p>
  </header>

  <nav>
    <a href="#about">मेरे बारे में</a>
    <a href="#work">मेरा काम</a>
    <a href="#contact">संपर्क करें</a>
  </nav>

  <section id="about">
    <div class="card">
      <h2><i class="fa-solid fa-user"></i> मेरे बारे में</h2>
      <p>मेरा नाम <strong>SUYASH PATEL</strong> है।  
      मुझे तकनीक, पढ़ाई और ऐसे प्रोजेक्ट बनाने का शौक है जो लोगों की समस्याओं का हल निकाल सकें।</p>
    </div>
  </section>

  <section id="work">
    <div class="card">
      <h2><i class="fa-solid fa-briefcase"></i> मेरा काम</h2>
      <ul>
        <li>📱 प्रोजेक्ट 1 – छोटा विवरण</li>
        <li>💻 प्रोजेक्ट 2 – छोटा विवरण</li>
        <li>🌐 प्रोजेक्ट 3 – छोटा विवरण</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="card">
      <h2><i class="fa-solid fa-envelope"></i> संपर्क करें</h2>
      <p>📧 ईमेल: <a href="mailto:suyash@email.com">suyash@email.com</a></p>
      <p>📞 फ़ोन: +91-9174589326</p>

      <div class="social-links">
        <h3>सोशल मीडिया</h3>
        <a href="https://wa.me/919174589326" target="_blank"><i class="fa-brands fa-whatsapp"></i> WhatsApp</a>
        <a href="https://instagram.com/mr_suyash_patel_305" target="_blank"><i class="fa-brands fa-instagram"></i> Instagram</a>
        <a href="https://linkedin.com/in/yourid" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
        <a href="https://github.com/yourid" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SUYASH PATEL. सर्वाधिकार सुरक्षित।</p>
  </footer>
</body>
</html>
