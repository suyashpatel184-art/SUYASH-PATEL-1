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
    
