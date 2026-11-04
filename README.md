#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Om Darak | Portfolio</title>

    <link rel="stylesheet" href="my.css">
</head>

<body>



<header>
           <div class="logo">
       <img src="logo.jpeg" alt="Om Darak Logo">
       OM <span>DARAK</span>
    </div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    <button id="menu">☰</button>
</header>
<section id="home" class="hero">
    <div class="hero-content">
        <p class="small-title">HELLO, I'M</p>
        <h1>
            OM <span>DARAK</span>
        </h1>
        <h2>B.C.S. Computer Science Student</h2>
        <p class="intro">
            I am a passionate Computer Science student interested in
            programming, web development, databases and learning
            new technologies.
        </p>
        <div class="buttons">
            <a href="#projects" class="btn">View Projects</a>
            <a href="#contact" class="btn outline">
                Contact Me
            </a>
        </div>
        <div class="social">
            <a href="https://github.com/omdarak97-byte" target="_blank">
                GitHub
            </a>
            <a href="https://www.linkedin.com/in/om-darak-635874437/"
               target="_blank">
                LinkedIn
            </a>
            <a href="mailto:omdarak97@gmail.com">
                Email
            </a>
        </div>
    </div>
    <div class="profile">
        <div class="profile-circle">
            <img src="OmDarak.jpeg" alt="OM DARAK Profile Photo">
        </div>
        <div class="code-text">
            Code<br>
            Learn<br>
            Build<br>
            Grow
        </div>
    </div>
</section>
<section id="about" class="section">
    <div class="heading">
        <p>INTRODUCTION</p>
        <h2>About Me</h2>
    </div>
    <div class="about-container">
        <div class="about-text">
            <p>
                I'm Om Darak, a BCS Computer Science student interested
                in software development and technology.
            </p>
            <p>
                I enjoy creating simple and useful applications while
                improving my programming and problem-solving skills.
            </p>
            <p>
                My current areas of learning include C, C++, HTML,
                CSS, JavaScript, PHP, SQL, MySQL, Git, GitHub and Linux.
            </p>
            <a href="#contact" class="btn">
                Let's Connect →
            </a>
        </div>
        <div class="info-box">
            <div>
                <b>Name</b>
                <span>Om Darak</span>
            </div>
            <div>
                <b>Education</b>
                <span>BCS Computer Science</span>
            </div>
            <div>
                <b>Location</b>
                <span>Maharashtra, India</span>
            </div>
            <div>
                <b>Email</b>
                <span>omdarak97@gmail.com</span>
            </div>
        </div>
        <div class="coding-card">
            <h3>
                Better<br>
                Code<br>
                Better<br>
                Tomorrow
            </h3>
            <span>&lt;/&gt;</span>
        </div>
    </div>
</section>
<section id="skills" class="section dark">
    <div class="heading">
        <p>MY SKILLS</p>
        <h2>Technical Skills</h2>
    </div>
    <div class="skills-container">
        <div class="skill">
            <div class="skill-icon">C</div>
            <h3>C Programming</h3>
            <div class="bar">
                <span style="width:80%"></span>
            </div>
            <small>80%</small>
        </div>
        <div class="skill">
            <div class="skill-icon">HTML</div>
            <h3>HTML</h3>
            <div class="bar">
                <span style="width:90%"></span>
            </div>
            <small>90%</small>
        </div>
        <div class="skill">
            <div class="skill-icon">CSS</div>
            <h3>CSS</h3>
            <div class="bar">
                <span style="width:85%"></span>
            </div>
            <small>85%</small>
        </div>
        <div class="skill">
            <div class="skill-icon">JS</div>
            <h3>JavaScript</h3>
            <div class="bar">
                <span style="width:70%"></span>
            </div>
            <small>70%</small>
        </div>
        <div class="skill">
            <div class="skill-icon">PHP</div>
            <h3>PHP</h3>
            <div class="bar">
                <span style="width:75%"></span>
            </div>
            <small>75%</small>
        </div>
        <div class="skill">
            <div class="skill-icon">SQL</div>
            <h3>MySQL / SQL</h3>
            <div class="bar">
                <span style="width:75%"></span>
            </div>
            <small>75%</small>
        </div>
    </div>
</section>
<section id="education" class="section">
    <div class="heading">
        <p>EDUCATION</p>
        <h2>My Education</h2>
    </div>
    <div class="education-container">
        <div class="education-card">
            <div class="edu-icon">🎓</div>
            <div>
                <h3>BCS Computer Science</h3>
                <p>
                    Hi-Tech College of Management and
                    Computer Science
                </p>
                <p>
                    Chhatrapati Sambhajinagar, Maharashtra
                </p>
                <span class="badge">
                    Currently Studying
                </span>
            </div>
        </div>
        <div class="education-card">
            <div class="edu-icon">💻</div>
            <div>
                <h3>Computer Science</h3>
                <p>
                    Studying programming, data structures,
                    DBMS, web development and database
                    technologies.
                </p>
            </div>
        </div>
    </div>
</section>
<section id="projects" class="section dark">
    <div class="heading">
        <p>MY PROJECTS</p>
        <h2>Featured Projects</h2>
    </div>
    <div class="projects-container">
        <div class="project-card">
            <span>01</span>
            <h3>Simple Calculator</h3>
            <p>
                Developed a C++ calculator supporting
                addition, subtraction, multiplication
                and division.
            </p>
            <div class="tags">
                <b>C++</b>
                <b>Logic</b>
            </div>
        </div>
        <div class="project-card">
            <span>02</span>
            <h3>Tic Tac Toe Game</h3>
            <p>
                Console-based two-player game using
                arrays, functions, loops and
                win-condition logic.
            </p>
            <div class="tags">
                <b>C++</b>
                <b>Arrays</b>
            </div>
        </div>
        <div class="project-card">
            <span>03</span>
            <h3>Student Record Management</h3>
            <p>
                C-based student record management
                system for adding, searching,
                updating and managing records.
            </p>

            <div class="tags">
                <b>C</b>
                <b>Data Structures</b>
            </div>
        </div>
        <div class="project-card">
            <span>04</span>
            <h3>Student Management System</h3>
            <p>
                Web-based student management project
                using HTML, CSS, PHP and MySQL.
            </p>
            <div class="tags">
                <b>HTML</b>
                <b>CSS</b>
                <b>PHP</b>
                <b>MySQL</b>
            </div>
        </div>
        <div class="project-card">
            <span>05</span>
            <h3>Personal Portfolio</h3>
            <p>
                Responsive personal portfolio website
                created using HTML, CSS, JavaScript
                and PHP.
            </p>
            <div class="tags">
                <b>HTML</b>
                <b>CSS</b>
                <b>PHP</b>
</div>
        </div>
    </div>
</section
<section id="resume" class="section">
    <div class="resume-box">
        <div>
            <p>MY RESUME</p>
            <h2>
                Want to know more?
            </h2>
            <p>
                Download my resume to know more about
                my education, skills, internship and projects.
            </p>
        </div>
        <a href="Om Darak.pdf"
           download
           class="btn">
            Download Resume ↓
        </a>
    </div>
</section>
<section id="contact" class="section">
    <div class="heading">
        <p>GET IN TOUCH</p>
        <h2>Contact Me</h2>
</div>
    <div class="contact-container">
        <div class="contact-info">
            <h3>Let's Talk</h3>
            <p>
                If you would like to connect with me
                regarding internships, projects or
                opportunities, feel free to contact me.
            </p>
            <p>
                📧
                <a href="mailto:omdarak97@gmail.com">
                    omdarak97@gmail.com
                </a>
            </p>
            <p>
                📞
                <a href="tel:+918010539521">
                    +91-8010539521
                </a>
            </p>
            <p>
                📍 Maharashtra, India
            </p>
        </div>
        <form action="contact.php"
              method="POST"
              class="contact-form">
            <label>Your Name</label>
            <input type="text"
                   name="name"
                   placeholder="Enter your name"
                   required>
            <label>Your Email</label>
            <input type="email"
                   name="email"
                   placeholder="Enter your email"
                   required>
            <label>Subject</label>
            <input type="text"
                   name="subject"
                   placeholder="Enter subject">
            <label>Message</label>
            <textarea name="message"
                      rows="5"
                      placeholder="Your message..."
                      required></textarea>
            <button type="submit"
                    class="btn">
                Send Message ➤
            </button>
        </form>
    </div>
</section>
<footer>
    <h3>
        OM <span>DARAK</span>
    </h3>
    <p>
        B.C.S. Computer Science Student
    </p>
    <div class="footer-links">
        <a href="#home">Home</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>
    <p>
        © 2026 Om Darak. All Rights Reserved.
    </p>
</footer>
<script src="script.js"></script>
</body>
</html>
#scipte.js
// Mobile menu toggle
const menuBtn = document.getElementById("menu");
const nav = document.querySelector("nav");

if (menuBtn && nav) {
    menuBtn.addEventListener("click", () => {
        nav.classList.toggle("active");
    });

    // Close menu after clicking a link
    nav.querySelectorAll("a").forEach((link) => {
        link.addEventListener("click", () => nav.classList.remove("active"));
    });
}
#my.css
/* ---------- Reset & Variables ---------- */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --bg: #1644dcdd;
    --bg-alt: #111833;
    --card: #161f3d;
    --text: #e8ecf8;
    --muted: #9aa5c8;
    --accent: #38bdf8;
    --accent-2: #818cf8;
    --border: rgba(255, 255, 255, 0.08);
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: "Segoe UI", Roboto, Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

a {
    color: inherit;
    text-decoration: none;
}

img {
    max-width: 100%;
    display: block;
}

/* ---------- Header ---------- */
header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 8%;
    background: rgba(11, 16, 32, 0.9);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--border);
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 1.5rem;
    font-weight: 800;
    letter-spacing: 1px;
}

.logo img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
    object-fit: cover;
}

.logo span,
h1 span,
footer h3 span {
    color: var(--accent);
}

nav {
    display: flex;
    gap: 28px;
}

nav a {
    color: var(--muted);
    font-weight: 500;
    transition: color 0.2s;
}

nav a:hover {
    color: var(--accent);
}

#menu {
    display: none;
    background: none;
    border: none;
    color: var(--text);
    font-size: 1.8rem;
    cursor: pointer;
}

/* ---------- Buttons ---------- */
.btn {
    display: inline-block;
    padding: 12px 28px;
    border-radius: 8px;
    border: 2px solid var(--accent);
    background: var(--accent);
    color: #04121f;
    font-weight: 700;
    font-size: 1rem;
    cursor: pointer;
    transition: transform 0.2s, background 0.2s, color 0.2s;
}

.btn:hover {
    transform: translateY(-2px);
    background: var(--accent-2);
    border-color: var(--accent-2);
}

.btn.outline {
    background: transparent;
    color: var(--accent);
}

.btn.outline:hover {
    background: var(--accent);
    color: #04121f;
}

/* ---------- Hero ---------- */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    padding: 120px 8% 60px;
    background: radial-gradient(circle at 80% 20%, rgba(56, 189, 248, 0.15), transparent 50%), var(--bg);
}

.hero-content {
    max-width: 600px;
}

.small-title {
    color: var(--accent);
    letter-spacing: 3px;
    font-weight: 600;
}

.hero h1 {
    font-size: clamp(2.8rem, 7vw, 5rem);
    line-height: 1.1;
    margin: 8px 0;
}

.hero h2 {
    font-size: 1.5rem;
    font-weight: 500;
    color: var(--muted);
    margin-bottom: 16px;
}

.intro {
    color: var(--muted);
    margin-bottom: 28px;
}

.buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
    margin-bottom: 28px;
}

.social {
    display: flex;
    gap: 22px;
}

.social a {
    color: var(--muted);
    border-bottom: 1px solid transparent;
    transition: color 0.2s, border-color 0.2s;
}

.social a:hover {
    color: var(--accent);
    border-color: var(--accent);
}

.profile {
    position: relative;
    display: flex;
    align-items: center;
    gap: 30px;
}

.profile-circle {
    width: 320px;
    height: 320px;
    border-radius: 50%;
    padding: 6px;
    background: linear-gradient(135deg, var(--accent), var(--accent-2));
    box-shadow: 0 0 60px rgba(56, 189, 248, 0.25);
}

.profile-circle img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
    border: 6px solid var(--bg);
}

.code-text {
    font-size: 1.6rem;
    font-weight: 800;
    line-height: 1.5;
    color: var(--accent-2);
    opacity: 0.85;
}

/* ---------- Sections ---------- */
.section {
    padding: 100px 8%;
}

.section.dark {
    background: var(--bg-alt);
}

.heading {
    text-align: center;
    margin-bottom: 50px;
}

.heading p {
    color: var(--accent);
    letter-spacing: 3px;
    font-weight: 600;
    font-size: 0.9rem;
}

.heading h2 {
    font-size: 2.4rem;
}

/* ---------- About ---------- */
.about-container {
    display: grid;
    grid-template-columns: 1.4fr 1fr 0.8fr;
    gap: 30px;
    align-items: start;
}

.about-text p {
    color: var(--muted);
    margin-bottom: 16px;
}

.about-text .btn {
    margin-top: 8px;
}

.info-box {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 24px;
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.info-box div {
    display: flex;
    flex-direction: column;
}

.info-box b {
    color: var(--accent);
    font-size: 0.85rem;
    letter-spacing: 1px;
    text-transform: uppercase;
}

.info-box span {
    word-break: break-word;
}

.coding-card {
    background: linear-gradient(135deg, var(--accent), var(--accent-2));
    color: #04121f;
    border-radius: 14px;
    padding: 28px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 220px;
}

.coding-card h3 {
    font-size: 1.6rem;
    line-height: 1.3;
}

.coding-card span {
    font-size: 2.2rem;
    font-weight: 800;
    align-self: flex-end;
}

/* ---------- Skills ---------- */
.skills-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
}

.skill {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 24px;
    transition: transform 0.25s, border-color 0.25s;
}

.skill:hover {
    transform: translateY(-5px);
    border-color: var(--accent);
}

.skill-icon {
    width: 54px;
    height: 54px;
    border-radius: 12px;
    background: rgba(56, 189, 248, 0.15);
    color: var(--accent);
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 800;
    margin-bottom: 14px;
}

.skill h3 {
    margin-bottom: 12px;
}

.bar {
    height: 8px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 99px;
    overflow: hidden;
    margin-bottom: 6px;
}

.bar span {
    display: block;
    height: 100%;
    border-radius: 99px;
    background: linear-gradient(90deg, var(--accent), var(--accent-2));
}

.skill small {
    color: var(--muted);
}

/* ---------- Education ---------- */
.education-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 24px;
    max-width: 1000px;
    margin: 0 auto;
}

.education-card {
    display: flex;
    gap: 18px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 26px;
}

.edu-icon {
    font-size: 2rem;
    width: 60px;
    height: 60px;
    flex-shrink: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    background: rgba(129, 140, 248, 0.15);
    border-radius: 12px;
}

.education-card h3 {
    margin-bottom: 6px;
}

.education-card p {
    color: var(--muted);
    font-size: 0.95rem;
}

.badge {
    display: inline-block;
    margin-top: 12px;
    padding: 4px 14px;
    border-radius: 99px;
    background: rgba(56, 189, 248, 0.15);
    color: var(--accent);
    font-size: 0.8rem;
    font-weight: 600;
}

/* ---------- Projects ---------- */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
    gap: 24px;
}

.project-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 28px;
    transition: transform 0.25s, border-color 0.25s;
}

.project-card:hover {
    transform: translateY(-6px);
    border-color: var(--accent);
}

.project-card > span {
    font-size: 2.4rem;
    font-weight: 800;
    color: rgba(56, 189, 248, 0.35);
}

.project-card h3 {
    margin: 6px 0 10px;
}

.project-card p {
    color: var(--muted);
    font-size: 0.95rem;
    margin-bottom: 16px;
}

.tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}

.tags b {
    font-size: 0.78rem;
    font-weight: 600;
    padding: 4px 12px;
    border-radius: 99px;
    background: rgba(129, 140, 248, 0.15);
    color: var(--accent-2);
}

/* ---------- Resume ---------- */
.resume-box {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 24px;
    max-width: 1000px;
    margin: 0 auto;
    padding: 44px;
    border-radius: 18px;
    background: linear-gradient(135deg, rgba(56, 189, 248, 0.15), rgba(129, 140, 248, 0.15));
    border: 1px solid var(--border);
}

.resume-box > div > p:first-child {
    color: var(--accent);
    letter-spacing: 3px;
    font-weight: 600;
    font-size: 0.9rem;
}

.resume-box h2 {
    margin: 4px 0 8px;
    font-size: 2rem;
}

.resume-box p {
    color: var(--muted);
}

/* ---------- Contact ---------- */
.contact-container {
    display: grid;
    grid-template-columns: 1fr 1.2fr;
    gap: 40px;
    max-width: 1000px;
    margin: 0 auto;
}

.contact-info h3 {
    font-size: 1.6rem;
    margin-bottom: 12px;
}

.contact-info p {
    color: var(--muted);
    margin-bottom: 14px;
}

.contact-info a:hover {
    color: var(--accent);
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 8px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 28px;
}

.contact-form label {
    font-size: 0.9rem;
    color: var(--muted);
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 12px 14px;
    margin-bottom: 10px;
    border-radius: 8px;
    border: 1px solid var(--border);
    background: var(--bg);
    color: var(--text);
    font-family: inherit;
    font-size: 1rem;
    outline: none;
    transition: border-color 0.2s;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: var(--accent);
}

.contact-form textarea {
    resize: vertical;
}

.contact-form .btn {
    align-self: flex-start;
}

/* ---------- Footer ---------- */
footer {
    text-align: center;
    padding: 50px 8% 30px;
    background: var(--bg-alt);
    border-top: 1px solid var(--border);
}

footer h3 {
    font-size: 1.6rem;
}

footer p {
    color: var(--muted);
    margin: 6px 0;
}

.footer-links {
    display: flex;
    justify-content: center;
    gap: 24px;
    margin: 18px 0;
}

.footer-links a {
    color: var(--muted);
}

.footer-links a:hover {
    color: var(--accent);
}

/* ---------- Responsive ---------- */
@media (max-width: 992px) {
    .hero {
        flex-direction: column-reverse;
        text-align: center;
        padding-top: 110px;
    }

    .buttons,
    .social {
        justify-content: center;
    }

    .profile {
        flex-direction: column;
    }

    .profile-circle {
        width: 240px;
        height: 240px;
    }

    .code-text br {
        display: none;
    }

    .about-container,
    .contact-container {
        grid-template-columns: 1fr;
    }
}

@media (max-width: 768px) {
    header {
        padding: 14px 6%;
    }

    #menu {
        display: block;
    }

    nav {
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        flex-direction: column;
        gap: 0;
        background: var(--bg);
        border-bottom: 1px solid var(--border);
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease;
    }

    nav.active {
        max-height: 400px;
    }

    nav a {
        padding: 14px 6%;
        border-top: 1px solid var(--border);
    }

    .section {
        padding: 80px 6%;
    }

    .resume-box {
        padding: 28px;
        flex-direction: column;
        text-align: center;
    }
}
