# DazedStew902.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ACP Innovations Landscaping</title>

  <style>
    :root {
      --green-primary: #2FA855;
      --green-light: #E3FFE6;
      --green-dark: #1C612C;
      --gray-dark: #525252;
    }

    body {
      margin: 0;
      font-family: "Inter", sans-serif;
      background: #ffffff;
      color: var(--gray-dark);
      line-height: 1.6;
    }

    /* NAVBAR */
    nav {
      width: 100%;
      background: white;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 20;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 24px;
    }

    nav .logo-area {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    nav img {
      height: 48px; /* Logo size — replace your logo here */
    }

    nav .nav-links {
      display: flex;
      gap: 24px;
    }

    nav a {
      text-decoration: none;
      color: var(--gray-dark);
      font-weight: 600;
      transition: 0.2s;
    }

    nav a:hover {
      color: var(--green-primary);
    }

    /* HERO SECTION */
    header {
      background: var(--green-light);
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      color: var(--green-dark);
    }

    header p {
      font-size: 1.25rem;
      max-width: 600px;
      margin: 0 auto;
      color: var(--gray-dark);
    }

    .cta-button {
      display: inline-block;
      margin-top: 30px;
      background: var(--green-primary);
      padding: 14px 32px;
      color: white;
      font-weight: 600;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.2s;
    }

    .cta-button:hover {
      background: var(--green-dark);
    }

    /* RESPONSIVE */
    @media(max-width: 768px) {
      nav .nav-links {
        display: none; /* For now — can convert to hamburger menu */
      }

      header h1 {
        font-size: 2.3rem;
      }
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav>
    <div class="logo-area">
      <!-- PLACE YOUR LOGO HERE -->
      <img src="YOUR-LOGO-FILE.png" alt="ACP Innovations Logo" />
      <strong>ACP Innovations Landscaping</strong>
    </div>

    <div class="nav-links">
      <a href="#portfolio">Our Portfolio</a>
      <a href="#services">Our Services</a>
      <a href="#about">About Us</a>
      <a href="#quote">Schedule a Quote Today</a>
    </div>
  </nav>

  <!-- HERO / MAIN HEADER -->
  <header>
    <!-- You can also place a larger logo here if you want -->
    <h1>ACP Innovations Landscaping</h1>
    <p>Modern, sustainable, and beautifully crafted outdoor spaces for every home and business.</p>

    <a class="cta-button" href="#quote">Schedule a Quote</a>
  </header>

</body>
</html>
