<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Free Palestine</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      color: white;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }
    .watermark {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 5rem;
      color: rgba(255, 255, 255, 0.05);
      font-weight: bold;
      z-index: 0;
      pointer-events: none;
      text-transform: uppercase;
    }
    .content {
      position: relative;
      z-index: 1;
      text-align: center;
    }
    .profile-img {
      max-width: 300px;
      border-radius: 16px;
      box-shadow: 0 0 15px rgba(255,255,255,0.3);
    }
    .chat-button {
      margin-top: 20px;
      padding: 12px 24px;
      background-color: #10a37f;
      border: none;
      border-radius: 8px;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .chat-button:hover {
      background-color: #0e8f70;
    }
  </style>
</head>
<body>
  <div class="watermark">Free Palestine</div>
  <div class="content">
    <img src="https://files.catbox.moe/x6ls3z.jpg" alt="Your Photo" class="profile-img" />
    <div>
      <button class="chat-button" onclick="window.open('https://chat.openai.com', '_blank')">
        Chat with ChatGPT
      </button>
    </div>
  </div>
</body>
</html>
