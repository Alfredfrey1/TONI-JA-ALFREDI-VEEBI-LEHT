<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
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

        .introduction, .hobbies, .contact {
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

        form {
            display: flex;
            flex-direction: column;
        }

        form label {
            margin-top: 1rem;
        }

        form input, form textarea, form button {
            padding: .5rem;
            margin-top: .5rem;
        }

        form button {
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
            margin-top: 1rem;
        }

        form button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>About Me</h1>
    </header>
    <section class="introduction">
        <h2>Introduction</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ac venenatis lorem.</p>
    </section>
    <section class="hobbies">
        <h2>Hobbies</h2>
        <ul>
            <li>Lorem ipsum dolor sit amet</li>
            <li>Consectetur adipiscing elit</li>
            <li>Curabitur ac venenatis lorem</li>
        </ul>
    </section>
    <section class="contact">
        <h2>Contact</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Form submitted!');
        });
    </script>
</body>
</html>
