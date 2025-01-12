<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <nav>
      <h1>WALLY</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h2>Hi, I'm Your Name</h2>
    <p>A passionate developer building amazing projects.</p>
    <a href="#projects" class="btn">See My Work</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a web developer specializing in creating clean, responsive, and modern websites. I love solving problems and learning new technologies.
    </p>
    <img src="assets/profile.jpg" alt="Profile Picture">
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="project">
      <img src="assets/project1.png" alt="Project 1">
      <div class="project-info">
        <h3>Project Title</h3>
        <p>Short description of your project.</p>
        <a href="https://github.com/yourusername/project1" target="_blank" class="btn">View on GitHub</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>I'd love to hear from you!</p>
    <a href="mailto:your-email@example.com" class="btn">Email Me</a>
  </section>

  <footer>
    <p>© 2025 Your Name. Built with ❤️ and code.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
