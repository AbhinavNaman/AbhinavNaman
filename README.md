<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
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
        h1,
        h2,
        h3 {
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
        #hero {
            position: relative;
            height: 80vh;
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
            max-width: 800px;
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
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            text-align: center;
        }
        .tech-grid div {
            background: #1f2937;
            padding: 1rem;
            border-radius: 8px;
        }
        .exp-card,
        .project {
            background: #161b22;
            border: 1px solid #30363d;
            padding: 1.5rem;
            border-radius: 8px;
            margin-bottom: 1.5rem;
        }
        .exp-card h3,
        .project h3 {
            font-size: 1.2rem;
            margin-bottom: 0.3rem;
        }
        #blog ul {
            list-style-type: none;
            padding: 0;
        }
        #blog li {
            margin: 0.5rem 0;
        }
        iframe {
            width: 100%;
            border: none;
            border-radius: 6px;
            background: white;
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
        h4{margin-bottom: 10px; margin-top: 20px;}
    </style>
</head>

<body class="dark">
    <!-- Hero Section -->
    <section id="hero">
        <div class="container hero-content">
            <h1>Abhinav Naman</h1>
            <p class="subtitle">Full Stack Developer & DevOps Enthusiast</p>
            <p class="desc">
                I am a Full Stack Developer and DevOps Enthusiast with experience in building scalable applications and
                automating infrastructure. I’ve interned at Pluralsight and Profile.fyi, worked on CI/CD, OG images,
                cloud infra, and more. I love combining clean code with automation and intelligent systems.
            </p>
            <div class="socials">
                <a href="https://linkedin.com/in/abhinav-naman" target="_blank">LinkedIn</a>
                <a href="mailto:abhinavnaman3@gmail.com">Email</a>
            </div>
            <a class="button" target="_blank" href="https://drive.google.com/file/d/1dvgbiI9dBi1u9N3VQaQZt5QLk4TRmK9O/view" download>Download Resume</a>
        </div>
    </section>
    <section id="techstack">
        <div class="container">
            <h2>Tech Stack</h2>
            <h4>Frontend</h4>
            <div class="tech-wrapper">
                <div class="tech-grid">
                    <div>React.js</div>
                    <div>Next.js</div>
                    <div>SvelteKit</div>
                </div>
            </div>
            <h4>Backend & Database</h4>
            <div class="tech-wrapper">
                <div class="tech-grid">
                    <div>Node.js</div>
                    <div>Express</div>
                    <div>MongoDB</div>
                    <div>PostgreSQL</div>
                    <div>Firebase</div>
                </div>
            </div>
            <h4>Cloud & DevOps</h4>
            <div class="tech-wrapper">
                <div class="tech-grid">
                    <div>AWS</div>
                    <div>Docker</div>
                    <div>Terraform</div>
                    <div>Kubernetes</div>
                    <div>GitHub Actions</div>
                    <div>GitLab CI</div>
                </div>
            </div>
        </div>
    </section>
    <section id="experience">
        <div class="container">
            <h2>Experience</h2>
            <div class="exp-card">
                <h3>Pluralsight – DevOps Intern</h3>
                <p>Jan 2025 – Present</p>
                <p>
                    Automated infrastructure monitoring with Terraform and Grafana. Built GitLab CI pipelines to
                    validate Kubernetes deployments. Reduced manual DevOps overhead by 70%.
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
    <section id="blog">
        <div class="container" styles="display:flex; ">
            <h2>Latest Blogs</h2>
            <ul>
                <li class="exp-card"><a href="https://medium.com/@abhinavnaman3/what-is-docker-bake-46dc909366c9">🐳 What is Docker
                        Bake?</a></li>
                <li class="exp-card"><a href="#">🚀 Infrastructure as Code: Terraform & GitHub Actions</a></li>
                <li class="exp-card"><a href="#">🧠 How RAG is Changing AI Retrieval</a></li>
            </ul>
        </div>
    </section>
    <section id="resume">
        <div class="container">
            <h2>View My Resume</h2>
            <iframe src="https://drive.google.com/file/d/1dvgbiI9dBi1u9N3VQaQZt5QLk4TRmK9O/preview" width="100%" height="600px"></iframe>
        </div>
    </section>

</body>

</html>
