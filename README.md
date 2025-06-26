<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhinav Naman | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="icon" href="favicon.ico" />
</head>
<body class="dark">

  <!-- Hero Section -->
  <section id="hero">
    <div class="animated-bg"></div>
    <div class="container hero-content">
      <h1>Abhinav Naman</h1>
      <p class="subtitle">Full Stack Developer & DevOps Enthusiast</p>
      <p class="desc">
        Passionate about building scalable apps and automating infrastructure. Currently diving deep into AI and RAG.
      </p>
      <div class="socials">
        <a href="https://github.com/AbhinavNaman" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/abhinav-naman" target="_blank">LinkedIn</a>
        <a href="mailto:abhinavnaman3@gmail.com">Email</a>
      </div>
      <a class="button" href="Abhinav_Naman_Resume.pdf" download>Download Resume</a>
      <div class="scroll-down">▼ Scroll Down</div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I am a Full Stack Developer and DevOps Enthusiast with experience in building scalable applications and automating infrastructure. I’ve interned at Pluralsight and Profile.fyi, worked on CI/CD, OG images, cloud infra, and more. I love combining clean code with automation and intelligent systems.
      </p>
    </div>
  </section>

  <!-- Tech Stack Section -->
  <section id="techstack">
    <div class="container">
      <h2>Tech Stack</h2>
      <div class="tech-wrapper">
        <div class="tech-bubbles">
          <!-- 12 floating logo images -->
          <img src="react.svg" alt="React" />
          <img src="nodejs.svg" alt="Node.js" />
          <img src="docker.svg" alt="Docker" />
          <img src="tailwind.svg" alt="Tailwind" />
          <img src="aws.svg" alt="AWS" />
          <img src="git.svg" alt="Git" />
          <img src="nextjs.svg" alt="Next.js" />
          <img src="mongo.svg" alt="MongoDB" />
        </div>
        <div class="tech-grid">
          <div>React</div>
          <div>Next.js</div>
          <div>SvelteKit</div>
          <div>Node.js</div>
          <div>Express</div>
          <div>MongoDB</div>
          <div>PostgreSQL</div>
          <div>AWS</div>
          <div>Docker</div>
          <div>Terraform</div>
          <div>Kubernetes</div>
          <div>GitHub Actions</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience">
    <div class="container">
      <h2>Experience</h2>
      <div class="exp-card">
        <h3>Pluralsight – DevOps Intern</h3>
        <p>Jan 2025 – Present</p>
        <p>
          Automated infrastructure monitoring with Terraform and Grafana. Built GitLab CI pipelines to validate Kubernetes deployments. Reduced manual DevOps overhead by 70%.
        </p>
      </div>
      <div class="exp-card">
        <h3>Profile.fyi – SDE Intern</h3>
        <p>Aug – Nov 2024</p>
        <p>
          Developed SvelteKit-based UI and OG image/email APIs. Served 35K+ users with < 200ms page loads.
        </p>
      </div>
      <div class="exp-card">
        <h3>Edcults – Full Stack Intern</h3>
        <p>Jun – Aug 2024</p>
        <p>
          Built SEO-optimized Next.js pages. Improved performance metrics by 30%.
        </p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="project">
        <h3>Ecom Price Tracker</h3>
        <p>Next.js + MongoDB scraper with email alerts for price drops.</p>
      </div>
      <div class="project">
        <h3>Terraform Metrics Dashboard</h3>
        <p>Analyzed CI metrics from GitHub runner logs and visualized via Grafana.</p>
      </div>
      <div class="project">
        <h3>Memories MERN App</h3>
        <p>Social media app with tags, likes, uploads, and Google Auth.</p>
      </div>
    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog">
    <div class="container">
      <h2>Latest Blogs</h2>
      <ul>
        <li><a href="https://medium.com/@abhinavnaman3/what-is-docker-bake-46dc909366c9">🐳 What is Docker Bake?</a></li>
        <li><a href="#">🚀 Infrastructure as Code: Terraform & GitHub Actions</a></li>
        <li><a href="#">🧠 How RAG is Changing AI Retrieval</a></li>
      </ul>
    </div>
  </section>

  <!-- Resume Viewer -->
  <section id="resume">
    <div class="container">
      <h2>View My Resume</h2>
      <iframe src="Abhinav_Naman_Resume.pdf" width="100%" height="600px"></iframe>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form>
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <input type="text" placeholder="Subject" />
        <textarea placeholder="Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Abhinav Naman. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
