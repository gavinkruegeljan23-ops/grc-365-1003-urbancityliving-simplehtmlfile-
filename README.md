!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Urban City Living</title>

    <style>
        body {
            width: 1024px;
            margin: auto;
            padding: 40px;
            background-color: #f4f4f4;
            font-family: Baskerville, 'Book Antiqua', Palatino, 'Century Schoolbook L', 'Times New Roman', serif;
        }

        /* Title */
        h1 {
            font-size: 48pt;
            color: #000000;
            text-align: center;
            text-shadow: 0 0 6px #E033FF, 0 0 12px #E033FF, 0 0 24px #E033FF;
            margin-bottom: 10px;
            line-height: 0.8;
            font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
        }

        /* Big U for paragraph */
        .big-letter {
            font-size: 70pt;
            color: #000000;
            line-height: 0.6;
            font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
        }

        /* Credit line */
        .credit {
            text-align: center;
            font-size: 16pt;
            color: #333;
            margin-top: 0;
            margin-bottom: 20px;
            font-style: italic;
        }

        /* Banner image */
        #banner {
            width: 100%;
            height: 350px;
            object-fit: cover;
            display: block;
            margin: 30px 0;
            border: 3px solid #333;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        /* Inline photo */
        .city-photo {
            width: 320px;
            float: left;
            margin: 0 25px 20px 0;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            border: 3px solid #333;
        }

        p {
            color: #222;
            font-size: 14pt;
            line-height: 1.6em;
        }
    </style>
</head>

<body>

    <h1>Urban City Living</h1>
    <p class="credit">By Gavin Kruegel</p>

    <img id="banner" src="images/banner.jpg" alt="City Banner">

    <p>
        <span class="big-letter">U</span>rban city living offers a vibrant lifestyle full of energy, culture, and opportunity...
    </p>

    <img class="city-photo" src="images/cityphoto.jpg" alt="City Photo">

    <p>
        Living in the city means access to restaurants, entertainment, public transportation, and endless activities...
    </p>

</body>
</html>
