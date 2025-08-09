# index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SkyNest – Your Gateway to the Stars</title>
  <style>
    /* Reset & Base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #fff;
      background: linear-gradient(to bottom, #000428, #004e92);
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    header nav {
      padding: 2rem;
      text-align: center;
    }

    .logo {
      font-size: 2rem;
      font-weight: bold;
      color: #00eaff;
    }

    .hero {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }

    .headline {
      font-size: 3rem;
      animation: pulse 3s ease-in-out infinite;
      margin-bottom: 1rem;
      color: #ffffff;
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
        color: #ffffff;
      }
      50% {
        transform: scale(1.1);
        color: #00eaff;
      }
      100% {
        transform: scale(1);
        color: #ffffff;
      }
    }

    .subtext {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto 2rem auto;
      color: #cfd9df;
    }

    .cta-button {
      background-color: #00eaff;
      padding: 1rem 2rem;
      border: none;
      border-radius: 50px;
      text-decoration: none;
      font-size: 1rem;
      color: #000;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #00c3d9;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: rgba(0, 0, 0, 0.2);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <h1 class="logo">SkyNest</h1>
    </nav>
  </header>

  <main class="hero">
    <section>
      <h2 class="headline">Your Gateway to the Stars</h2>
      <p class="subtext">Book your first orbit and explore the beauty of Earth from space. Affordable. Safe. Unforgettable.</p>
      <a href="#" class="cta-button">Reserve Your Flight</a>
    </section>
  </main>

  <footer>
    <p>© 2025 SkyNest Inc. All rights reserved.</p>
  </footer>
</body>
</html>
