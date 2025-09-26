<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kuki Designed Group</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #333333;
    }
    header {
      background: linear-gradient(90deg, #0d47a1, #1976d2);
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #e53935;
    }
    .hero {
      background: url('https://picsum.photos/1600/600?blur=3') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 120px 20px;
      position: relative;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(13,71,161,0.6);
    }
    .hero h2, .hero p {
      position: relative;
      z-index: 2;
    }
    .hero h2 {
      font-size: 48px;
      margin: 0;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      border-top: 4px solid #e53935;
    }
    footer {
      background: #0d47a1;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #e53935;
      text-decoration: none;
    }
    /* --- እዚህ ሞባይል አማራጭ ያክሉ --- */
    @media (max-width: 600px) {
      header {
        flex-direction: column;
        text-align: center;
        padding: 15px;
      }
      header img {
        height: 40px;
        margin-bottom: 10px;
      }
      nav {
        margin-top: 10px;
      }
      .hero {
        padding: 60px 10px;
        font-size: 18px;
      }
      .hero h2 {
        font-size: 28px;
      }
      section {
        padding: 30px 10px;
      }
      .projects {
        grid-template-columns: 1fr;
        gap: 10px;
      }
      .card {
        padding: 12px;
        font-size: 16px;
      }
      footer {
        padding: 12px;
        font-size: 13px;
      }
    }
  </style>
</head>
<body>
  <!-- ...ቀድሞው የHTML ኮድ... -->
</body>
</html># Kuki-Designed-group-
Kuki Designed group specializes building design 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kuki Designed Group</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #333333;
    }
    header {
      background: linear-gradient(90deg, #0d47a1, #1976d2);
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #e53935;
    }
    .hero {
      background: url('https://picsum.photos/1600/600?blur=3') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 120px 20px;
      position: relative;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(13,71,161,0.6);
    }
    .hero h2, .hero p {
      position: relative;
      z-index: 2;
    }
    .hero h2 {
      font-size: 48px;
      margin: 0;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      border-top: 4px solid #e53935;
    }
    footer {
      background: #0d47a1;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #e53935;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Kuki Designed Group Logo">
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Innovative Skyscraper & Modern Design</h2>
    <p>We bring your vision to reality</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Kuki Designed Group specializes in skyscraper architecture and modern building design. Our mission is to create iconic, sustainable, and functional spaces for the future.</p>
  </section>

  <section id="projects">
    <h2>Our Projects</h2>
    <div class="projects">
      <div class="card">🏙 Skyscraper Project</div>
      <div class="card">🏗 Modern Architecture</div>
      <div class="card">🌍 Sustainable Design</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@kukidesigned.com</p>
    <p>Phone: +251 900 000 000</p>
  </section>

  <footer>
    <p>&copy; 2025 Kuki Designed Group. All rights reserved. | <a href="#">Privacy Policy</a></p>
  </footer>
</body>
</html>![IMG_20250818_155453_480](https://github.com/user-attachments/assets/7ba9c341-453c-4abf-8c03-3ea6af85da69)
