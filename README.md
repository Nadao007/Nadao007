<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ขอโทษนะ</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f8f9fa;
      color: #333;
      padding: 20px;
    }
    h1 {
      color: #ff6b6b;
    }
    .heart {
      font-size: 100px;
      color: #ff6b6b;
    }
    button {
      background-color: #ff6b6b;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #e63946;
    }
  </style>
</head>
<body>
  <div>
    <h1>ขอโทษนะที่รัก</h1>
    <div class="heart">❤️</div>
    <p>เราขอโทษจริง ๆ ที่ทำให้คุณเสียใจ<br>เราสัญญาว่าจะไม่ทำแบบนี้อีก</p>
    <p>หวังว่าคุณจะยกโทษให้เรา...</p>
    <button onclick="forgiveMe()">ยกโทษให้</button>
  </div>

  <script>
    function forgiveMe() {
      alert("ขอบคุณนะที่ยกโทษให้ เรารักคุณมาก ๆ ❤️");
    }
  </script>
</body>
</html>
