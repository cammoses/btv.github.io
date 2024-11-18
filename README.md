# btv.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breeze TV (BTV)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #0078d4;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            text-decoration: none;
            color: #0078d4;
            margin: 0 1rem;
            font-weight: bold;
        }
        main {
            padding: 2rem;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        .form-container {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        input, textarea, button {
            display: block;
            width: 100%;
            margin-bottom: 1rem;
            padding: 0.5rem;
            font-size: 1rem;
        }
        input[type="submit"], button {
            background-color: #0078d4;
            color: white;
            border: none;
            cursor: pointer;
        }
        .shows-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }
        .show {
            background: white;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Breeze TV (BTV)</h1>
        <p>A platform for upcoming shows to gain exposure.</p>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="submit.html">Submit a Show</a>
        <a href="watch.html">Watch Shows</a>
    </nav>

    <main id="homepage">
        <h2>Welcome to Breeze TV</h2>
        <p>Discover new and exciting shows from upcoming creators. If you're a creator, submit your show to gain exposure!</p>
    </main>

    <footer>
        <p>&copy; 2024 Breeze TV. All rights reserved.</p>
    </footer>
</body>
</html>
