<!DOCTYPE html>
<html>
<head>
  <title>Happy Birthday Sister Samra 🎉</title>
  <!-- Google Font similar to your reference -->
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      overflow: hidden;
      background: url('https://i.pinimg.com/736x/b6/8c/d2/b68cd2c21df95e1f2d445c0d2f997e8b.jpg') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Great Vibes', cursive;
      text-align: center;
      color: #fff;
    }

    h1 {
      margin-top: 15%;
      font-size: 70px;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
      animation: fadeIn 3s ease-in-out;
    }

    p {
      font-size: 28px;
      animation: fadeIn 4s ease-in-out;
      margin-top: 20px;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    .flower {
      position: absolute;
      animation: fall linear infinite;
      opacity: 0.9;
    }

    @keyframes fall {
      0% {top: -10%; transform: rotate(0deg);}
      100% {top: 110%; transform: rotate(360deg);}
    }
  </style>
</head>
<body>

<!-- Background music -->
<audio autoplay loop>
  <source src="https://www.bensound.com/bensound-music/bensound-buddy.mp3" type="audio/mpeg">
</audio>

<h1>Sister Samra</h1>
<p>Wishing you a day full of love, joy, and endless happiness! 🎉<br>
May Allah bless you with health, success, and all the smiles in the world! 💖</p>

<script>
  // Array of pink & white flowers (original-looking)
  const flowerImages = [
    "https://i.ibb.co/6B1tFQp/pink-flower.png", 
    "https://i.ibb.co/5n2rXqW/white-flower.png"
  ];

  for(let i=0; i<50; i++){
    let flower = document.createElement("img");
    flower.src = flowerImages[Math.floor(Math.random()*flowerImages.length)];
    flower.className = "flower";
    flower.style.left = Math.random()*100 + "vw";
    flower.style.width = (30 + Math.random()*30) + "px";
    flower.style.animationDuration = (Math.random()*5 + 5) + "s";
    document.body.appendChild(flower);
  }
</script>

</body>
</html>
