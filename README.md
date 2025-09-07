<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>TROLL THÔNG TIN</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: radial-gradient(circle at center, #000 40%, #111 100%);
      color: white;
      font-family: "Arial Black", sans-serif;
      overflow: hidden;
    }

    h1 {
      font-size: 55px;
      text-align: center;
      text-transform: uppercase;
      background: linear-gradient(270deg, red, yellow, cyan, magenta, lime);
      background-size: 1000% 1000%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: gradientMove 6s ease infinite, flicker 1.2s infinite;
      text-shadow: 0 0 20px red, 0 0 40px yellow, 0 0 60px cyan;
      line-height: 1.3;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    @keyframes flicker {
      0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% { opacity: 1; }
      20%, 24%, 55% { opacity: 0.2; }
    }

    /* chữ chạy ngang màn hình */
    .marquee {
      position: absolute;
      bottom: 20px;
      white-space: nowrap;
      font-size: 22px;
      color: #00ffcc;
      animation: scroll 12s linear infinite;
      text-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffaa;
    }

    @keyframes scroll {
      0%   { left: 100%; }
      100% { left: -100%; }
    }
  </style>
</head>
<body>
  <div>
    <h1>CHÚC MỪNG<br>BẠN ĐÃ BỊ LEAK<br>THÔNG TIN NGÂN HÀNG ⚠️</h1>
  </div>

  <div class="marquee">🚨 Hệ thống đã ghi nhận rò rỉ dữ liệu... Đang xử lý... 🚨</div>
</body>
</html>
