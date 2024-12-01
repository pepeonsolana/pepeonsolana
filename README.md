<!DOCTYPE html>
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
            top: 0;
            bottom: 0;
            left: 0;
            right: 0;
            display: flex;
            justify-content: space-between;
            gap: 20px;
            z-index: 1;
        }

        .left-side, .right-side {
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            gap: 20px;
        }

        .left-side img, .right-side img {
            border-radius: 10px;
            width: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .left-side img:hover, .right-side img:hover {
            transform: scale(1.05);
        }

        .left-side img:nth-child(1) {
            height: 200px;
        }

        .left-side img:nth-child(2) {
            height: 250px;
        }

        .left-side img:nth-child(3) {
            height: 300px;
        }

        .right-side img:nth-child(1) {
            height: 200px;
        }

        .right-side img:nth-child(2) {
            height: 250px;
        }

        .right-side img:nth-child(3) {
            height: 300px;
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
    <div class="left-side">
        <!-- Placeholder images for the left side -->
        <img src="https://via.placeholder.com/200x200/00FFA3/ffffff?text=SOLPEPE" alt="SOLPEPE Image 1">
        <img src="https://via.placeholder.com/250x250/9945FF/ffffff?text=SOLPEPE" alt="SOLPEPE Image 2">
        <img src="https://via.placeholder.com/300x300/DC1FFF/ffffff?text=SOLPEPE" alt="SOLPEPE Image 3">
    </div>
    <div class="right-side">
        <!-- Placeholder images for the right side -->
        <img src="https://via.placeholder.com/200x200/00FFA3/ffffff?text=SOLPEPE" alt="SOLPEPE Image 4">
        <img src="https://via.placeholder.com/250x250/9945FF/ffffff?text=SOLPEPE" alt="SOLPEPE Image 5">
        <img src="https://via.placeholder.com/300x300/DC1FFF/ffffff?text=SOLPEPE" alt="SOLPEPE Image 6">
    </div>
</div>

</body>
</html>
