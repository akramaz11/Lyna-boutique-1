<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lyna Boutique</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary: #0f172a;
      --accent: #4f46e5;
      --light: #f1f5f9;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: var(--light);
      color: var(--primary);
    }

    header {
      background: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header img {
      height: 80px;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: var(--primary);
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      text-align: center;
      padding: 4rem 1rem;
      background: linear-gradient(120deg, #4f46e5, #3b82f6);
      color: white;
    }

    .hero h2 {
      margin-bottom: 1rem;
      font-size: 2.5rem;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1200px;
      margin: auto;
    }

    .contact {
      background: white;
      border-radius: 12px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    }

    .socials {
      text-align: center;
      padding: 2rem;
    }

    .socials a {
      color: var(--primary);
      font-size: 2rem;
      margin: 0 0.5rem;
      transition: color 0.3s;
    }

    .socials a:hover {
      color: var(--accent);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: var(--primary);
      color: white;
    }

    @media (max-width: 600px) {
      nav a {
        margin: 0 0.5rem;
      }

      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <a href="#home">
      <img src="logo.png" alt="Store Logo">
    </a>
    <nav>
      <a href="#home">Home</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Welcome</h2>
    <p>Discover quality products crafted with care.</p>
  </section>

  <section class="section contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@lyna.boutique4@gmail.com</p>
    <p>Phone: +1 (123) 456-7890</p>
    <p>Address: Bouzareah, Alger, Air de France</p>
  </section>

  <section class="socials">
    <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
    <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
    <a href="https://tiktok.com" target="_blank"><i class="fab fa-tiktok"></i></a>
  </section>

  <footer>
    <p>&copy; Lyna Boutique. All rights reserved.</p>
  </footer>

</body>
</html>
