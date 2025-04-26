# website1
this is the code  for my site using java,html,css 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Krishnesh Verma | Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
  <link href="https://fonts.googleapis.com/css2?family=Forum&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar">
    <div class="container">
      <h1>Krishnesh Verma</h1>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero fade-in">
    <div class="container">
      <h2>Hello, I'm Krishnesh</h2>
      <p>Computer Science and Communication Engineering student passionate about building impactful solutions.</p>
      <div class="buttons">
        <a href="/mnt/data/b33bbd40-e1e7-4074-8653-a3fe6e431915.pdf" class="btn" target="_blank">Download Resume</a>
        <a href="https://www.linkedin.com/in/krishnesh-verma-989390279/" class="btn" target="_blank">LinkedIn</a>
        <a href="https://github.com/God1641" class="btn" target="_blank">GitHub</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="fade-in">
    <div class="container">
      <h2>About Me</h2>
      <p>I'm a Computer Science and Communication Engineering student at KIIT, passionate about crafting innovative digital solutions. I love tackling challenging problems and constantly learning new technologies. My ultimate goal is to build software that has a real, positive impact on people’s lives.</p>
      <ul>
        <li>Started coding at age 18</li>
        <li>Fluent in English, elementary knowledge of French</li>
        <li>Enjoy 3D modeling and design in my free time</li>
      </ul>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="fade-in">
    <div class="container">
      <h2>Projects</h2>
      <div class="projects-grid">

        <div class="project-card">
          <img src="images/web-portfolio.jpg" alt="Web Portfolio" class="project-image">
          <h3>Web Portfolio</h3>
          <p>A responsive portfolio website showcasing my skills and projects. Built using V0.dev and React.</p>
          <p><strong>Technologies:</strong> HTML, CSS, JavaScript, React</p>
        </div>

        <div class="project-card">
          <img src="images/hostel-navigator.jpg" alt="Hostel Navigator" class="project-image">
          <h3>Hostel Navigator</h3>
          <p>A mobile app concept helping students find hostels based on budget and facilities. Built with Flutter and Firebase (in progress).</p>
          <p><strong>Technologies:</strong> Flutter, Firebase</p>
        </div>

      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="fade-in">
    <div class="container">
      <h2>Experience</h2>
      <div class="timeline">
        <div class="timeline-item">
          <h3>Comviva Intern</h3>
          <span>June 2024 - July 2024</span>
          <p>Interned at Comviva, contributing to customer analytics and notification platforms.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="fade-in">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Feel free to connect with me through LinkedIn or GitHub.</p>
    </div>
  </section>

  <footer class="fade-in">
    <div class="container">
      <p>&copy; 2024 Krishnesh Verma. All rights reserved.</p>
    </div>
  </footer>

  <script src="js/script.js"></script>
</body>
</html>

