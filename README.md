<PepSol>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PEPSOL - Pepe on Solana</title>
    <style>
        /* Basic styles */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #00FFA3, #DC1FFF, #9945FF);
            color: white;
            text-align: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
        }

        header {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .intro-text {
            margin: 20px auto;
            padding: 20px;
            max-width: 900px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            font-size: 1.2rem;
            z-index: 2; /* Ensure the text stays on top */
        }

        .crypto-address-box {
            margin-top: 40px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            max-width: 600px;
            width: 100%;
            margin-left: auto;
            margin-right: auto;
        }

        .crypto-address-box input[type="text"] {
            width: 100%;
            padding: 10px;
            font-size: 1.2rem;
            border: 2px solid #fff;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            border-radius: 5px;
        }

        .image-gallery {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 30px;
            z-index: 1; /* Place images below text */
        }

        .image-gallery img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        /* Image positioning */
        .left {
            position: absolute;
            left: 20px;
            top: 50%;
            transform: translateY(-50%);
        }

        .right {
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
        }

        .bottom {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
        }

        .image-gallery img:hover {
            transform: scale(1.05);
        }

    </style>
</head>
<body>

<header>
    PEPSOL - Pepe on Solana
</header>

<div class="intro-text">
    <p>Dive into the meme revolution on Solana, where speed meets hilarity. PEPSOL isn’t just a memecoin; it’s a movement. Fast, low-cost, and packed with PEPE-powered vibes, this is your chance to join the next big thing in crypto. 🚀</p>
    <p><strong>Why PEPSOL?</strong><br>
    ✅ Blazing-fast transactions on Solana<br>
    ✅ The ultimate meme-fueled fun<br>
    ✅ Built for the community, by the community</p>
    <p>Don’t miss out on the hype – buy PEPSOL now and ride the meme wave to the moon! 🌕</p>
    <p><strong>$PEPSOL – Laugh. Trade. Moon.</strong></p>
</div>

<div class="crypto-address-box">
    <label for="crypto-address">Enter your crypto address:</label>
    <input type="text" id="crypto-address" placeholder="Enter your Solana address here">
</div>

<div class="image-gallery">
    <!-- 7 images positioned around the text -->
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 1" class="left">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 2" class="right">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 3" class="bottom">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 4" class="left">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 5" class="right">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 6" class="bottom">
    <img src="purplepepesol1.jpg" alt="SOLPEPE Image 7" class="bottom">
</div>

</body>
</html>
