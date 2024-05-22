<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <!-- Include the Cabin font from Google Fonts -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cabin:wght@700&display=swap">
    <style>
        body {
            font-family: 'Cabin', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #ADD8E6; 
        }

        header {
            background: #fff;
            color: #407BB2;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        section {
            padding: 2rem;
        }

        .introduction, .hobbies {
            border-bottom: 1px solid #fff
        }

        h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            background: #fff;
            margin: .5rem 0;
            padding: .5rem;
        }

        .person {
            margin-bottom: 2rem;
        }

        .person h2 {
            margin-top: 0;
        }

        .person img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>MEIE KOHTA</h1>
    </header>
    <section class="person" id="person1">
        <h2>Toni Hasa</h2>
        <img src="https://i.imghippo.com/files/kGnFp1716403941.jpg" alt="Person 1 Picture">
        <section class="introduction">
            <h3>Tutvustus</h3>
            <p>Ma sündisin 7. märtsil aastal 2007 Eestis. Ma elasin Viimsis umbes oma 4. eluaastani. Siis kolisin ma Soome, Helisingisse. Ma käisin 5 aastat Soomes koolis ja kolisin siis tagasi Eestisse. Eestis käisin Rocca al Mare koolis 9. klassini ja siis läksin PERG’i.</p>
        </section>
        <section class="hobbies">
            <h3>Hobid</h3>
            <ul>
                <li>Arvutimängude mängimine</li>
                <li>Tennis</li>
                <li>Biljard</li>
            </ul>
        </section>
    </section>
    <section class="person" id="person2">
        <h2>Alfred Frey</h2>
        <img src="https://i.imghippo.com/files/jol5H1716403370.jpg" alt="Person 2 Picture">
        <section class="introduction">
            <h3>Tutvustus</h3>
            <p>Olen ilus mees, kes sündis Võrus, aga elan Tallinnas. Olen oma elu pannud selle peale, et Eesti saaks tugevamaks riigiks. Olen vabal ajal monteerjia ja huvitub kuidas majanuds toimib. Olen uhke PERGi õpilane.</p>
        </section>
        <section class="hobbies">
            <h3>Hobid</h3>
            <ul>
                <li>Arvutide mängude mängimine</li>
                <li>Naljade kirjutamine</li>
                <li>Helitehnika</li>
            </ul>
        </section>
    </section>
</body>
</html>
