<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>For Aya 🌹</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />
  <style>
    /* Global Styles */
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(135deg, #ff758c, #ff7eb3, #f86dad);
      background-size: 300% 300%;
      animation: gradientAnimation 15s ease infinite;
      font-family: 'Poppins', sans-serif;
      overflow: hidden;
      position: relative;
    }
    
    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    /* Card Container */
    .card {
      background: rgba(255, 255, 255, 0.95);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
      text-align: center;
      position: relative;
      z-index: 2;
      max-width: 420px;
      transition: transform 0.3s;
      animation: cardFadeIn 2s ease-out;
    }
    
    .card:hover {
      transform: scale(1.05);
    }
    
    @keyframes cardFadeIn {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }
    
    /* Heading Styles */
    h1 {
      font-size: 32px;
      margin: 0 0 10px;
      color: #d63384;
      animation: textGlow 3s infinite alternate;
    }
    
    @keyframes textGlow {
      from { text-shadow: 0 0 10px #ff66b2; }
      to { text-shadow: 0 0 20px #ff3385; }
    }
    
    /* Paragraph Styles */
    p {
      font-size: 20px;
      color: #444;
      margin-top: 20px;
    }
    
    /* Rose Image */
    .rose {
      width: 180px;
      margin: 20px 0;
      transition: transform 0.5s, filter 0.5s;
    }
    
    .rose:hover {
      transform: scale(1.3) rotate(15deg);
      filter: drop-shadow(0 0 15px #ff3366);
    }
    
    /* Floating Elements Container */
    .floating {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 1;
    }
    
    .floating span {
      position: absolute;
      display: block;
      opacity: 0.8;
      font-size: 24px;
      animation: floatEffect 10s linear infinite;
    }
    
    @keyframes floatEffect {
      0% { transform: translateY(100vh) rotate(0deg); opacity: 0; }
      50% { opacity: 0.8; }
      100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
    }
    
    /* Floating Elements with individual delays */
    .floating span:nth-child(1) { left: 10%; animation-duration: 12s; animation-delay: 0s; }
    .floating span:nth-child(2) { left: 25%; animation-duration: 10s; animation-delay: 2s; }
    .floating span:nth-child(3) { left: 40%; animation-duration: 14s; animation-delay: 4s; }
    .floating span:nth-child(4) { left: 55%; animation-duration: 9s;  animation-delay: 1s; }
    .floating span:nth-child(5) { left: 70%; animation-duration: 11s; animation-delay: 3s; }
    .floating span:nth-child(6) { left: 85%; animation-duration: 13s; animation-delay: 5s; }
    
    /* Additional Floating Hearts */
    .floating-heart {
      position: absolute;
      font-size: 28px;
      color: #ff4d4d;
      animation: heartFloat 6s infinite ease-in-out;
    }
    
    @keyframes heartFloat {
      0% { transform: translateY(0) scale(1); opacity: 1; }
      100% { transform: translateY(-120px) scale(1.5); opacity: 0; }
    }
    
    .floating-heart:nth-child(1) { left: 15%; animation-delay: 0s; }
    .floating-heart:nth-child(2) { left: 60%; animation-delay: 1s; }
    .floating-heart:nth-child(3) { left: 80%; animation-delay: 2s; }
    
  </style>
</head>
<body>
  <!-- Floating Background Elements -->
  <div class="floating">
    <span>🌸</span>
    <span>🌷</span>
    <span>💐</span>
    <span>🌺</span>
    <span>🌹</span>
    <span>✨</span>
  </div>
  
  <!-- Main Card -->
  <div class="card">
    <h1>Happy Women's Day, Hbeba Aya! 🌹</h1>
    <img src="https://www.pngmart.com/files/1/Red-Rose-PNG-File.png" alt="Rose for Aya" class="rose">
    <p>You deserve all the love and happiness in the world.</p>
  </div>
  
  <!-- Floating Hearts (Extra Layer) -->
  <div class="floating-heart" style="bottom: 10%;">❤️</div>
  <div class="floating-heart" style="bottom: 5%;">💖</div>
  <div class="floating-heart" style="bottom: 15%;">💘</div>
</body>
</html>
