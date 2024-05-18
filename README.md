<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background: #333;
            color: #fff;
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
            border-bottom: 1px solid #ccc;
        }

        h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            background: #f4f4f4;
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
        <h1>About Us</h1>
    </header>
    <section class="person" id="person1">
        <h2>Person 1</h2>
        <img src="path-to-person1-picture.jpg" alt="Person 1 Picture">
        <section class="introduction">
            <h3>Introduction</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ac venenatis lorem.</p>
        </section>
        <section class="hobbies">
            <h3>Hobbies</h3>
            <ul>
                <li>Lorem ipsum dolor sit amet</li>
                <li>Consectetur adipiscing elit</li>
                <li>Curabitur ac venenatis lorem</li>
            </ul>
        </section>
    </section>
    <section class="person" id="person2">
        <h2>Person 2</h2>
        <img src="[path-to-person2-picture.jpg](https://images.uncyc.org/commons/thumb/8/8a/North_Korea.png/300px-North_Korea.png)" alt="Person 2 Picture">
        <section class="introduction">
            <h3>Introduction</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ac venenatis lorem.</p>
        </section>
        <section class="hobbies">
            <h3>Hobbies</h3>
            <ul>
                <li>Lorem ipsum dolor sit amet</li>
                <li>Consectetur adipiscing elit</li>
                <li>Curabitur ac venenatis lorem</li>
            </ul>
        </section>
    </section>
</body>
</html>
