 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive Landing Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    /* Header */
    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
    }

    header .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.5rem;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    .nav-links a {
      color: #fff;
      text-decoration: none;
    }

    /* Hero Section */
    .hero {
      background: #f4f4f4;
      padding: 3rem 0;
      text-align: center;
    }

    .hero h2 {
      margin-bottom: 1rem;
      font-size: 2rem;
    }

    .hero p {
      margin-bottom: 1.5rem;
    }

    .btn {
      background: #333;
      color: #fff;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      border-radius: 5px;
    }

    /* Footer */
    footer {
      background: #222;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }

    .social-links a {
      margin: 0 10px;
      color: #fff;
      text-decoration: none;
    }

    /* Responsive Media Queries */
    @media (max-width: 768px) {
      header .container {
        flex-direction: column;
        text-align: center;
      }

      .nav-links {
        flex-direction: column;
        gap: 0.5rem;
        margin-top: 1rem;
      }
    }
  </style>
  
</head>
<body>

  <header>
    <div class="container">
      <img src="E:\Project\Html\logo.png">

      <h1 class="logo">Technology Solutions For Businesses Grow</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="9835969066">Contact</a></li>
           <li><a href="kritiayush2006@gmail.com">Email</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>Welcome to Our Site</h2>
      <p>We create smart and responsive technology solutions to help businesses grow.</p>
      <a href="#" class="btn">Get Started</a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 MyWebsite.</p>
      <p>Follow us:</p>
      <div class="social-links">
        <a href="https://www.instagram.com/iamayushkriti?igsh=MTJsd3QzaHZmczQ4ZQ==">Instagram</a>
        <a href="https://www.facebook.com/share/1H8rveCpDq/">Facebook</a>
        <a href="https://www.linkedin.com/in/ayush-kriti-7234732a4">LinkedIn</a>
      </div>
    </div>
  </footer>

</body>
</html>
