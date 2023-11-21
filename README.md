# Landing-page
Codsoft Landing Page using Html and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f1f1f1;
            padding: 20px;
            text-align: center;
        }

        .hero {
            background-image: url('https://images.unsplash.com/photo-1571760766010-06c09c3d923d');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero h1 {
            font-size: 3em;
            color: #333;
        }

        .cta {
            background-color: #d1d1d1;
            padding: 20px;
            text-align: center;
        }

        .cta a {
            background-color: #4CAF50;
            color: white;
            padding: 15px 30px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
        }

        .cta a:hover {
            background-color: #45a049;
        }

        footer {
            background-color: #f1f1f1;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
    </header>

    <section class="hero">
        <h1>Get 10% off your first order!</h1>
    </section>

    <section class="cta">
        <a href="#">Sign Up Now</a>
    </section>

    <footer>
        <p>&copy; 2022 Our Website. All rights reserved.</p>
    </footer>
</body>
</html>
