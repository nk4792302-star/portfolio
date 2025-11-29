<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: #111;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to right, #1a1a1a, #333);
      color: white;
      text-align: center;
      padding: 20px;
    }
    .section {
      padding: 60px 40px;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      background: #111;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h2>My Portfolio</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Hi, I'm Nabeel</h1>
    <p>Frontend Developer | Designer | Student</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I am a passionate and creative student who loves web development and design. I enjoy creating clean, modern, and user-friendly websites.</p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card"><h3>Project 1</h3><p>Description...</p></div>
      <div class="project-card"><h3>Project 2</h3><p>Description...</p></div>
      <div class="project-card"><h3>Project 3</h3><p>Description...</p></div>
    </div>
  </section>

  <section id="skills" class="section">
    <h2>Skills</h2>
    <ul>
      <li>HTML / CSS / JavaScript</li>
      <li>React (basic)</li>
      <li>UI/UX Design</li>
    </ul>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: your-email@example.com</p>
  </section>

  <footer>
    <p>© 2025 My Portfolio</p>
  </footer>
</body>
</html>
