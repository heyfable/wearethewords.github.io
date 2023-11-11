# wearethewords
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>wearethewords</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 1em;
            margin: 0 10px;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #555;
        }

        section {
            padding: 20px;
        }

        .main-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .main-content article {
            flex: 1;
            margin: 10px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>

    <header>
        <h1>Your Stylish Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <section class="main-content">
        <article>
            <h2>Welcome to Our Website</h2>
            <p>This is a modern and stylish website. Feel free to explore our content and learn more about what we have to offer.</p>
        </article>

        <article>
            <h2>About Us</h2>
            <p>Learn about our history, mission, and values. We are committed to providing the best services to our clients.</p>
        </article>
    </section>

    <footer>
        <p>&copy; 2023 Your Stylish Website. All rights reserved.</p>
    </footer>

</body>

</html>
