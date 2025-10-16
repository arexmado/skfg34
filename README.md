<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AREXMADO Studio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d1117;
      color: white;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    /* 헤더 */
    header {
      background: #0b0e12;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #1f2937;
    }

    .logo {
      color: #00eaff;
      font-size: 18px;
      font-weight: bold;
      text-shadow: 0 0 10px #00eaff;
    }

    nav a {
      color: #ccc;
      margin-left: 20px;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #00eaff;
    }

    /* 본문 */
    main {
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
    }

    .neon-text {
      font-size: 64px;
      font-weight: bold;
      color: #00eaff;
      text-shadow: 0 0 10px #00eaff, 0 0 20px #00eaff, 0 0 40px #00eaff;
      margin-bottom: 10px;
    }

    .subtitle {
      color: #aaa;
      font-size: 14px;
    }

    /* 푸터 */
    footer {
      background: #0b0e12;
      padding: 15px 20px;
      border-top: 1px solid #1f2937;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    footer .left {
      color: #777;
      font-size: 13px;
    }

    footer .left a {
      color: #00eaff;
      text-decoration: none;
    }

    footer .right button {
      background: #1e293b;
      color: #fff;
      border: 1px solid #2d3748;
      border-radius: 8px;
      padding: 6px 12px;
      margin-left: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    footer .right button:hover {
      background: #00eaff;
      color: #000;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">AREXMADO Studio</div>
    <nav>
      <a href="#">홈</a>
      <a href="#">프로젝트</a>
      <a href="#">소개</a>
    </nav>
  </header>

  <main>
    <h1 class="neon-text">AREXMADO</h1>
    <p class="subtitle">빛나는 네온 스타일 본문 타이틀</p>
  </main>

  <footer>
    <div class="left">
      © 2025 AREXMADO. All rights reserved. | <a href="#">YouTube</a>
    </div>
    <div class="right">
      <button>개인정보처리방침</button>
      <button>이용약관</button>
      <button>구독하기</button>
    </div>
  </footer>

</body>
</html>
