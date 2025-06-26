<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhinav Naman | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="icon" href="favicon.ico" />
  <style>
  /* Reset & Base Styles */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  html {
    scroll-behavior: smooth;
    font-family: Arial, sans-serif;
    background-color: #0d1117;
    color: white;
  }

  body {
    line-height: 1.6;
  }

  a {
    color: #58a6ff;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    padding: 2rem 0;
  }

  h1, h2, h3 {
    font-weight: 700;
    margin-bottom: 1rem;
  }

  h1 {
    font-size: 2.5rem;
    text-align: center;
  }

  h2 {
    font-size: 2rem;
    text-align: center;
  }

  /* Hero Section */
  #hero {
    position: relative;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    overflow: hidden;
    background: #0d1117;
  }

  .hero-content {
    position: relative;
    z-index: 2;
  }

  .subtitle {
    font-size: 1.5rem;
    color: #c9d1d9;
    margin-bottom: 0.5rem;
  }

  .desc {
    color: #8b949e;
    max-width: 600px;
    margin: 1rem auto;
  }

  .socials {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    margin: 1rem 0;
  }

  .button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background: white;
    color: black;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
  }

  .button:hover {
    background: #ddd;
  }

  .scroll-down {
    margin-top: 2rem;
    animation: bounce 2s infinite;
    font-size: 1.5rem;
    color: #c9d1d9;
  }

  /* Animated background */
  .animated-bg {
    position: absolute;
    top: 0;
    left: -50%;
    width: 200%;
    height: 100%;
    background: linear-gradient(-60deg, #111 50%, #333 50%);
    animation: slide 15s ease-in-out infinite alternate;
    z-index: 0;
    opacity: 0.1;
  }

  @keyframes slide {
    0% { transform: translateX(-25%); }
    100% { transform: translateX(25%); }
  }

  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }

  /* Tech Stack */
  #techstack .tech-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
  }

  .tech-bubbles {
    position: relative;
    width: 250px;
    height: 250px;
    background: #161b22;
    border-radius: 1rem;
    border: 1px solid #30363d;
    overflow: hidden;
    display: none;
  }

  .tech-bubbles img {
    position: absolute;
    width: 40px;
    height: 40px;
    animation: float 10s infinite linear;
  }

  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
    text-align: center;
  }

  .tech-grid div {
    background: #1f2937;
    padding: 1rem;
    border-radius: 8px;
  }

  @keyframes float {
    0% { transform: translate(0, 0); }
    50% { transform: translate(100px, 50px); }
    100% { transform: translate(0, 0); }
  }

  /* Experience & Projects */
  .exp-card, .project {
    background: #161b22;
    border: 1px solid #30363d;
    padding: 1.5rem;
    border-radius: 8px;
    margin-bottom: 1.5rem;
  }

  .exp-card h3, .project h3 {
    font-size: 1.2rem;
    margin-bottom: 0.3rem;
  }

  /* Blog Section */
  #blog ul {
    list-style-type: none;
    padding: 0;
  }

  #blog li {
    margin: 0.5rem 0;
  }

  /* Resume Iframe */
  iframe {
    width: 100%;
    border: none;
    border-radius: 6px;
    background: white;
  }

  /* Contact Section */
  form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 600px;
    margin: auto;
  }

  input, textarea {
    padding: 0.75rem;
    border-radius: 4px;
    border: none;
    font-size: 1rem;
    color: black;
  }

  button[type="submit"] {
    padding: 0.75rem;
    background: white;
    color: black;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.2s;
  }

  button:hover {
    background: #ccc;
  }

  /* Footer */
  footer {
    text-align: center;
    padding: 2rem 1rem;
    background: #0a0a0a;
    font-size: 0.9rem;
    color: #666;
  }

  /* Responsive */
  @media screen and (min-width: 768px) {
    .tech-wrapper {
      flex-direction: row;
      align-items: flex-start;
    }
    .tech-bubbles {
      display: block;
    }
  }
</style>

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
