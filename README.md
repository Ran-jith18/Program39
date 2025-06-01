<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi! I'm a web developer passionate about creating responsive and accessible websites.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>This site demonstrates HTML and CSS best practices with mobile responsiveness.</p>
      <a href="https://example.com" target="_blank">Visit Site</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Your Name</p>
  </footer>
</body>
</html>
