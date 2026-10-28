<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Your Name - Frontend Developer building fast, responsive web experiences.">
  <title> Subham Bhumij | Frontend Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Sora:wght@600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="bg-glow" aria-hidden="true"></div>
  <!---logo image-->

  <header class="header" id="header">
    <nav class="nav container">
      <a href="#home" class="logo ">Game<span>su.</span></a>

      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span>
        <span></span>
        <span></span>
      </button>

      <ul class="nav-links" id="navLinks">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-grid">
        <div class="hero-text">
          <p class="eyebrow reveal">Hello, I&rsquo;m</p>
          <h1 class="reveal">Subham Bhumij</h1>
          <h2 class="hero-role reveal">I build <span class="typed" id="typed"></span><span class="caret">|</span></h2>
          <p class="hero-desc reveal">
            A frontend developer focused on crafting fast, accessible and
            pixel-perfect interfaces that feel great on every screen.
          </p>

          <div class="hero-actions reveal">
            <a href="#projects" class="btn btn-primary">View My Work</a>
            <a href="#contact" class="btn btn-ghost">Let&rsquo;s Talk</a>
          </div>

          <div class="socials reveal">
            <a href="https://github.com/samon-wq/" target="_blank" rel="noopener" aria-label="GitHub">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M12 .5a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2c-3.3.7-4-1.6-4-1.6-.6-1.4-1.4-1.8-1.4-1.8-1.1-.8.1-.8.1-.8 1.2.1 1.9 1.3 1.9 1.3 1.1 1.8 2.8 1.3 3.5 1 .1-.8.4-1.3.8-1.6-2.7-.3-5.5-1.3-5.5-5.9 0-1.3.5-2.4 1.2-3.2-.1-.3-.5-1.5.1-3.2 0 0 1-.3 3.3 1.2a11.5 11.5 0 0 1 6 0C17.3 3.4 18.3 3.7 18.3 3.7c.6 1.7.2 2.9.1 3.2.8.8 1.2 1.9 1.2 3.2 0 4.6-2.8 5.6-5.5 5.9.4.4.8 1.1.8 2.2v3.3c0 .3.2.7.8.6A12 12 0 0 0 12 .5Z"/></svg>
            </a>
            <a href="https://www.linkedin.com/in/subham-bhumij/" target="_blank" rel="noopener" aria-label="LinkedIn">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5a2.5 2.5 0 1 1 0 5 2.5 2.5 0 0 1 0-5ZM3 9h4v12H3V9Zm6 0h3.8v1.7h.1c.5-1 1.8-2 3.7-2 4 0 4.7 2.5 4.7 5.8V21h-4v-5.7c0-1.4 0-3.2-2-3.2s-2.3 1.5-2.3 3.1V21H9V9Z"/></svg>
            </a>
            <a href="mailto:hello@example.com" aria-label="Email">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.8" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="m3 7 9 6 9-6"/></svg>
            </a>
          </div>
        </div>

        <div class="hero-visual reveal">
          <div class="avatar-ring-stable">
           <img src="c:\Users\Lenovo\Desktop\portfol\kypo.jpg.jpeg" alt="150px" height="150px">
          </div>
          <span class="float-chip chip-1">HTML</span>
          <span class="float-chip chip-2">CSS</span>
          <span class="float-chip chip-3">JavaScript</span>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2 class="section-title reveal">About <span>Me</span></h2>
        <div class="about-grid">
          <div class="about-text reveal">
            <p>
              I&rsquo;m a frontend developer who loves turning ideas into clean,
              interactive experiences. I care about performance, accessibility and
              the small details that make a product feel polished.
            </p>
            <p>
              When I&rsquo;m not coding, you&rsquo;ll find me exploring new design trends,
              contributing to open source, or tweaking side projects.
            </p>
          </div>
          <div class="about-stats reveal">
            <div class="stat">
              <strong>3+</strong>
              <span>Years Experience</span>
            </div>
            <div class="stat">
              <strong>25+</strong>
              <span>Projects Built</span>
            </div>
            <div class="stat">
              <strong>15+</strong>
              <span>Happy Clients</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="skills" class="section">
      <div class="container">
        <h2 class="section-title reveal">My <span>Skills</span></h2>
        <div class="skills-grid">
          <div class="skill-card reveal">
            <span class="skill-icon">&lt;/&gt;</span>
            <h3>HTML5</h3>
            <p>Semantic, accessible markup.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">#</span>
            <h3>CSS3</h3>
            <p>Flexbox, Grid, animations.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">JS</span>
            <h3>JavaScript</h3>
            <p>ES6+, DOM, async patterns.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">R</span>
            <h3>React</h3>
            <p>Components and hooks.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">N</span>
            <h3>Node.js</h3>
            <p>APIs and tooling.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">G</span>
            <h3>Git</h3>
            <p>Version control workflows.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">F</span>
            <h3>Figma</h3>
            <p>Design to code handoff.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">@</span>
            <h3>Responsive</h3>
            <p>Mobile-first layouts.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2 class="section-title reveal">Featured <span>Projects</span></h2>
        <div class="projects-grid">
          <article class="project-card reveal">
            <div class="project-thumb thumb-1">
              <span>Task List App</span>
            </div>
            <div class="project-body">
              <h3>Task List App</h3>
              <p>A clean to-do app with add, complete and delete actions plus local persistence.</p>
              <div class="tags">
                <span>HTML</span><span>CSS</span><span>JS</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>

          <article class="project-card reveal">
            <div class="project-thumb thumb-2">
              <span>Weather Dashboard</span>
            </div>
            <div class="project-body">
              <h3>Weather Dashboard</h3>
              <p>Live weather data with search, geolocation and a responsive card layout.</p>
              <div class="tags">
                <span>JavaScript</span><span>API</span><span>CSS</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>

          <article class="project-card reveal">
            <div class="project-thumb thumb-3">
              <span>Landing Page</span>
            </div>
            <div class="project-body">
              <h3>Product Landing Page</h3>
              <p>A conversion-focused landing page with smooth scroll and micro-interactions.</p>
              <div class="tags">
                <span>HTML</span><span>CSS</span><span>Animation</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2 class="section-title reveal">Get In <span>Touch</span></h2>
        <div class="contact-grid">
          <div class="contact-info reveal">
            <p>Have a project in mind or just want to say hi? My inbox is always open.</p>
            <ul class="contact-list">
              <li>
                <span class="contact-label">Email</span>
                <a href="mailto:hello@example.com">hello@example.com</a>
              </li>
              <li>
                <span class="contact-label">Location</span>
                <span>India</span>
              </li>
              <li>
                <span class="contact-label">Social</span>
                <span>@yourhandle</span>
              </li>
            </ul>
          </div>

          <form class="contact-form reveal" id="contactForm">
            <div class="field">
              <label for="name">Name</label>
              <input type="text" id="name" name="name" placeholder="Your name" required>
            </div>
            <div class="field">
              <label for="email">Email</label>
              <input type="email" id="email" name="email" placeholder="you@example.com" required>
            </div>
            <div class="field">
              <label for="message">Message</label>
              <textarea id="message" name="message" rows="4" placeholder="Tell me about your project..." required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
            <p class="form-status" id="formStatus" role="status"></p>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer-inner">
      <p>&copy; <span id="year"></span> Your Name. All rights reserved.</p>
      <a href="#home" class="back-top">Back to top &uarr;</a>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
