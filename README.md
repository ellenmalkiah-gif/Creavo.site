<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pixora Designs</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background: black;
            color: white;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            color: red;
        }
        section {
            padding: 30px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            background: black;
            color: white;
            padding: 15px;
            font-size: 14px;
        }
        button {
            padding: 10px 20px;
            border: none;
            background: red;
            color: white;
            border-radius: 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pixora Designs</h1>
        <p>Posters • Logos • Business Cards</p>
    </header>
    <section>
        <h2>About Us</h2>
        <p>We create modern posters, logos and business cards to help brands stand out.</p>
        <button>Contact Us</button>
    </section>
    <section class="services">
        <div class="card">Poster Design</div>
        <div class="card">Logo Design</div>
        <div class="card">Business Cards</div>
    </section>
    <footer>
        © 2025 Pixora Designs | Built by Malkiah Ellen
    </footer>
</body>
</html>
