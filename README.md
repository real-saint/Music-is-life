
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfect Ikechukwu (reaSAINT) Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('background-image.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            text-align: center;
            overflow-x: hidden;
        }
        .header {
            position: relative;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
        }
        .nav {
            position: absolute;
            left: 20px;
            top: 20px;
        }
        .nav button {
            background: #f1c40f;
            border: none;
            padding: 10px;
            font-size: 1.5em;
            cursor: pointer;
        }
        .header h1 {
            font-size: 4em;
            margin: 0;
            color: #f1c40f;
            text-shadow: 2px 2px 4px #000;
            line-height: 1;
        }
        .header h2 {
            font-size: 1.5em;
            margin: 10px 0 0;
            color: #fff;
            text-shadow: 1px 1px 3px #000;
        }
        .header .button {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background: #f1c40f;
            border: none;
            border-radius: 25px;
            text-decoration: none;
            color: #000;
            font-weight: bold;
            cursor: pointer;
        }
        .section {
            position: relative;
            margin: 40px auto;
            max-width: 80%;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            text-align: left;
        }
        .section h2 {
            font-size: 2em;
            color: #f1c40f;
            margin-bottom: 10px;
        }
        .section p {
            font-size: 1.2em;
            line-height: 1.5;
        }
        .section img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-top: 10px;
        }
        /* Overlay for header image effect */
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.3);
            z-index: 1;
        }
        .header * {
            position: relative;
            z-index: 2;
        }
    </style>
</head>
<body>
    <div class="header" style="background-image: url('header-background.jpg');">
        <div class="nav">
            <button>☰</button>
        </div>
        <h1>PERFECT IKECHUKWU<br>(reaSAINT)</h1>
        <h2>Artist, Aspiring Musician, Builder, Youth Supporter</h2>
        <a href="#portfolio" class="button">Explore My Work</a>
    </div>

    <div class="section" id="portfolio">
        <h2>About Me</h2>
        <p>I'm Perfect Ikechukwu, also known as reaSAINT, an artist with a passion for drawing. My superpower is creating art because I love doing it. I aspire to become a musician, inspired by Juice WRLD, XXXTentacion, and many rappers. I also love building things, having crafted cars, bikes, and houses out of carton during secondary school. My mission is to help youth, reminding them they’re not alone in their struggles.</p>
    </div>

    <div class="section">
        <h2>Drawing</h2>
        <p>I draw because it’s my passion and a way to express myself.</p>
        <img src="drawing-image.jpg" alt="Someone staring at their drawing">
    </div>

    <div class="section">
        <h2>Music</h2>
        <p>I’m inspired to become a musician, following in the footsteps of greats like Juice WRLD and XXXTentacion.</p>
        <img src="music-image.jpg" alt="Someone performing on stage">
    </div>

    <div class="section">
        <h2>Building</h2>
        <p>In secondary school, I built cars, bikes, and houses out of carton, fueling my love for creation.</p>
        <img src="building-image.jpg" alt="Cars, houses, and bikes made of carton">
    </div>

    <div class="section">
        <h2>Saving the Youth</h2>
        <p>I want to support and inspire youth, showing them they’re not alone.</p>
        <img src="youth-image.jpg" alt="Someone advising youths">
    </div>

    <script>
        document.querySelector('.nav button').addEventListener('click', function() {
            alert('Navigation menu would expand here. Add your links!');
        });
    </script>
</body>
</html>
