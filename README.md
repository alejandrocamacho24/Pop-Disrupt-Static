<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pop Disrupt | Seasoning Revolution</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --netflix-red: #E50914;
            --black: #141414;
            --gray: #808080;
        }

        body {
            background-color: var(--black);
            color: white;
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* --- NAVIGATION --- */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 4%;
            background: linear-gradient(to bottom, rgba(0,0,0,0.7) 10%, transparent);
            z-index: 1000;
            box-sizing: border-box;
        }

        .main-logo {
            height: 45px;
        }

        .mini-logo {
            height: 40px;
            border-radius: 4px;
        }

        /* --- HERO SECTION --- */
        .hero {
            height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding-left: 4%;
            background: linear-gradient(to right, rgba(0,0,0,0.8), transparent), 
                        url('Campfire S\'mores.jpg'); /* Featured Flavor Background */
            background-size: cover;
            background-position: center;
        }

        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .hero-description {
            max-width: 500px;
            font-size: 1.2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            margin-bottom: 20px;
        }

        /* --- FLAVOR ROWS --- */
        .row {
            padding: 20px 0 20px 4%;
        }

        .row-title {
            font-size: 1.4rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .flavors-container {
            display: flex;
            overflow-x: auto;
            gap: 10px;
            padding-bottom: 20px;
            scrollbar-width: none; /* Hide scrollbar Firefox */
        }

        .flavors-container::-webkit-scrollbar {
            display: none; /* Hide scrollbar Chrome/Safari */
        }

        .flavor-card {
            min-width: 280px;
            transition: transform 0.3s ease;
            cursor: pointer;
        }

        .flavor-card img {
            width: 100%;
            border-radius: 4px;
            object-fit: cover;
        }

        .flavor-card:hover {
            transform: scale(1.05);
            z-index: 2;
        }

        /* --- FOOTER / CTA --- */
        footer {
            padding: 50px 4%;
            text-align: center;
            background-color: var(--black);
        }

        .amazon-btn {
            background-color: #FF9900; /* Amazon Orange */
            color: black;
            padding: 15px 40px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 4px;
            font-size: 1.2rem;
            transition: opacity 0.2s;
            display: inline-block;
        }

        .amazon-btn:hover {
            opacity: 0.8;
        }

        .copyright {
            margin-top: 30px;
            color: var(--gray);
            font-size: 0.8rem;
        }
    </style>
</head>
<body>

    <nav>
        <img src="Pop Disrupt title.png" alt="Pop Disrupt" class="main-logo">
        <img src="pd logo.png" alt="PD" class="mini-logo">
    </nav>

    <section class="hero">
        <div class="hero-content">
            <p style="color: #46d369; font-weight: bold;">98% Match for Snack Lovers</p>
            <p class="hero-description">Disrupting your taste buds with chef-inspired seasonings. From sweet dreams to spicy kicks, your popcorn will never be the same.</p>
            <a href="#" class="amazon-btn" style="background-color: white; color: black; margin-right: 10px;">► Play Taste</a>
        </div>
    </section>

    <div class="row">
        <div class="row-title">Trending Now</div>
        <div class="flavors-container">
            <div class="flavor-card"><img src="Campfire S'mores.jpg" alt="Campfire S'mores"></div>
            <div class="flavor-card"><img src="Chocolate Peanut Butter Cup.jpg" alt="Chocolate Peanut Butter Cup"></div>
            <div class="flavor-card"><img src="Dubai Chocolate.jpg" alt="Dubai Chocolate"></div>
            <div class="flavor-card"><img src="Grilled Cheese.jpg" alt="Grilled Cheese"></div>
            <div class="flavor-card"><img src="Korean Hot Honey.jpg" alt="Korean Hot Honey"></div>
            <div class="flavor-card"><img src="Mexican Street Corn.jpg" alt="Mexican Street Corn"></div>
            <div class="flavor-card"><img src="Taco Truck Twist.jpg" alt="Taco Truck Twist"></div>
            <div class="flavor-card"><img src="Tres Leches Dream.jpg" alt="Tres Leches Dream"></div>
        </div>
    </div>

    <footer>
        <a href="YOUR_AMAZON_LINK_HERE" class="amazon-btn">Buy on Amazon</a>
        <p class="copyright">© 2026 Pop Disrupt Seasonings. All Rights Reserved.</p>
    </footer>

</body>
</html>
