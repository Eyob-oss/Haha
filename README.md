<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Eyob Tesfaye | Portfolio</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico" />

  <link rel="stylesheet" href="styles.css" />
</head>
<body class="dark-mode">

  <!-- Dark Mode Toggle -->
  <button id="theme-toggle" class="theme-toggle"><i class="fas fa-moon"></i></button>

  <!-- Navigation -->
  <nav class="navbar">
    <div class="logo">Eyob T.</div>
    <ul class="nav-links" id="nav-links">
      <li><a href="#hero">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <button class="menu-toggle" id="menu-toggle"><i class="fas fa-bars"></i></button>
  </nav>

  <!-- Hero Section -->
  <section id="hero" class="hero-section">
    <div class="hero-content">
      <h1>Eyob Tesfaye</h1>
      <p class="typewriter-text"></p>
    </div>
    <a href="#about" class="scroll-down"><i class="fas fa-chevron-down"></i></a>
  </section>

  <!-- About Section -->
  <section id="about" class="section about-section">
    <div class="container">
      <h2>About Me</h2>
      <div class="about-grid">
        <div class="about-image">
          <img src="https://via.placeholder.com/300x300" alt="Eyob Tesfaye" />
        </div>
        <div class="about-text">
          <p>I am a creative professional with experience in video editing, digital content creation, web development, and graphic design. I bring ideas to life through visual storytelling and clean code.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="section services-section">
    <div class="container">
      <h2>My Skills</h2>
      <div class="service-grid">
        <div class="service-card">
          <i class="fas fa-film service-icon"></i>
          <h3>Video Editing</h3>
        </div>
        <div class="service-card">
          <i class="fas fa-video service-icon"></i>
          <h3>Digital Content</h3>
        </div>
        <div class="service-card">
          <i class="fas fa-code service-icon"></i>
          <h3>Web Development</h3>
        </div>
        <div class="service-card">
          <i class="fas fa-paint-brush service-icon"></i>
          <h3>Graphic Design</h3>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="section portfolio-section">
    <div class="container">
      <h2>Portfolio</h2>
      <div class="portfolio-grid">
        <div class="portfolio-item" onclick="openModal('https://via.placeholder.com/800x600?text=Project+1')">
          <img src="https://via.placeholder.com/400x300?text=Project+1" alt="Project 1" />
        </div>
        <div class="portfolio-item" onclick="openModal('https://via.placeholder.com/800x600?text=Project+2')">
          <img src="https://via.placeholder.com/400x300?text=Project+2" alt="Project 2" />
        </div>
        <div class="portfolio-item" onclick="openModal('https://via.placeholder.com/800x600?text=Project+3')">
          <img src="https://via.placeholder.com/400x300?text=Project+3" alt="Project 3" />
        </div>
        <div class="portfolio-item" onclick="openModal('https://via.placeholder.com/800x600?text=Project+4')">
          <img src="https://via.placeholder.com/400x300?text=Project+4" alt="Project 4" />
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact-section">
    <div class="container">
      <h2>Contact Me</h2>
      <form class="contact-form">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <div class="contact-info">
        <p>Email: <a href="mailto:eyob@example.com">eyob@example.com</a></p>
        <div class="social-links">
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-github"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2025 Eyob Tesfaye. All rights reserved.</p>
  </footer>

  <!-- Modal -->
  <div id="modal" class="modal">
    <span class="close-modal" onclick="closeModal()">&times;</span>
    <img class="modal-content" id="modal-img" />
  </div>

  <script src="script.js"></script>
</body>
</html>
