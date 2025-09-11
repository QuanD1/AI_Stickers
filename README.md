<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>我的專題介紹</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 2rem 1rem;
    }
    section {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
      text-align: left;
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    img {
      max-width: 100%;
      border-radius: 12px;
      margin: 1rem 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>AI 貼圖生成專題</h1>
    <p>勤益科技大學 資工系 Ben</p>
  </header>

  <section>
    <h2>專題簡介</h2>
    <p>
      本專題開發一套能將使用者輸入的文字即時轉換成貼圖的系統，結合自然語言處理、
      圖像生成與影像處理，並以 Android 輸入法呈現，讓貼圖能直接使用於通訊軟體中。
    </p>

    <h2>系統流程</h2>
    <img src="your-image.png" alt="專題架構圖">
    <p>
      使用者輸入文字 + 選擇角色 → 傳送至後端 → 語言模型生成 Prompt → 圖像生成模型繪製 → 
      去背與加字 → 貼圖回傳前端顯示。
    </p>
  </section>
</body>
</html>
