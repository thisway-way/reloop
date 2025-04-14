<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ReLoop - 舊裝置新生命</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      min-height: 100vh; /* 確保頁面最小高度為 100vh */
      text-align: center;
      padding: 0 20px;
      background-color: #4CAF50;
      color: white;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin-bottom: 2rem;
    }
    .cta-buttons {
      display: flex;
      gap: 1rem;
      justify-content: center;
    }
    .cta-buttons a {
      text-decoration: none;
      padding: 12px 24px;
      border-radius: 6px;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn-primary {
      background-color: #2ECC71;
      color: white;
    }
    .btn-primary:hover {
      background-color: #27ae60;
    }
    .btn-outline {
      border: 2px solid white;
      color: white;
    }
    .btn-outline:hover {
      background-color: white;
      color: #2ECC71;
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }
      .hero p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>ReLoop - 舊裝置新生命</h1>
    <p>為您提供環保且創新的舊裝置再利用方案</p>
    <div class="cta-buttons">
      <a href="#" class="btn-primary">了解更多</a>
      <a href="#" class="btn-outline">立即聯繫</a>
    </div>
  </div>
</body>
</html>
