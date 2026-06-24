# Babys-funny-link
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>💖 A Question for You</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: linear-gradient(135deg, #ffe6f0, #fff0f5);
      margin: 0;
      padding-top: 120px;
    }

    h1 {
      color: #d63384;
      font-size: 32px;
    }

    button {
      font-size: 18px;
      padding: 12px 25px;
      margin: 10px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.2s;
    }

    button:hover {
      transform: scale(1.05);
    }

    .yes {
      background-color: #28a745;
      color: white;
    }

    .no {
      background-color: #dc3545;
      color: white;
    }

    #message {
      margin-top: 30px;
      font-size: 20px;
      color: #333;
      padding: 0 20px;
    }

    img {
      margin-top: 15px;
      width: 250px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
  </style>
</head>

<body>

  <h1>Will you be mine forever? 💖</h1>

  <button class="yes" onclick="yes()">Yes 💕</button>
  <button class="no" onclick="no()">No 😅</button>

  <div id="message"></div>

  <script>
    function yes() {
      document.getElementById("message").innerHTML =
        "Aww 🥰 You just made me the happiest person in the world. I promise to always cherish you ❤️<br>" +
        "<img src='https://i.imgur.com/4M7IWwP.jpg' alt='love image'>";
    }

    function no() {
      document.getElementById("message").innerHTML =
        "😢 Oh... that's okay. I still care about you and wish you happiness always 💔";
    }
  </script>

</body>
</html>