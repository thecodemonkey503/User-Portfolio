<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chaitanya Vishwakarma | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Home Section -->
    <header id="home">
        <div class="hero">
            <img src="Chaitanya.png" alt="Profile Photo" class="profile-img">
            <h1>Hi, I'm <span>Chaitanya Vishwakarma</span></h1>
            <h2>B.Tech 1st Year | CSE (AI & ML) | KIET</h2>
            <p class="tagline">Aspiring AI Engineer • Tech Enthusiast</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I'm Chaitanya Vishwakarma, a first-year B.Tech student at KIET Ghaziabad, specializing in
            CSE (AI & ML). I’m passionate about technology, programming, and building creative digital projects.
            I enjoy learning new tech stacks, problem-solving, and exploring AI/ML concepts. My goals include
            becoming a skilled developer and contributing to impactful projects.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills-container">
            <div class="skill">C Programming</div>
            <div class="skill">Python</div>
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">AI/ML Basics</div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>Basic Calculator Website</h3>
                <p>A simple calculator website built using HTML, CSS, and JavaScript.</p>
                <button>View Project</button>
            </div>

            <div class="project-card">
                <h3>Personal Portfolio</h3>
                <p>My first portfolio project created using pure HTML and CSS.</p>
                <button>View Project</button>
            </div>

            <div class="project-card">
                <h3>AI/ML Learning Notes</h3>
                <p>Organized notes and mini projects based on ML basics.</p>
                <button>View Project</button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:chaitanya@example.com">chaitanya@example.com</a></p>
        <p>GitHub: <a href="#">github.com/chaitanya</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/chaitanya</a></p>
    </section>

    <footer>
        <p>© 2025 Chaitanya Vishwakarma. All rights reserved.</p>
    </footer>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f5f7fa;
    color: #222;
    line-height: 1.6;
}

/* Header / Home */
header {
    background: #0d47a1;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
    margin-bottom: 20px;
}

.tagline {
    font-size: 1.2rem;
    margin-top: 10px;
    opacity: 0.9;
}

/* Section Styling */
section {
    padding: 60px 20px;
    max-width: 900px;
    margin: auto;
}

h2 {
    text-align: center;
    margin-bottom: 30px;
    color: #0d47a1;
}

/* Skills Section */
.skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    justify-content: center;
}

.skill {
    background: #e3f2fd;
    padding: 12px 20px;
    border-radius: 8px;
    font-size: 1rem;
    border: 1px solid #90caf9;
}

/* Projects Section */
.project-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.project-card {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
}

.project-card h3 {
    margin-bottom: 10px;
    color: #0d47a1;
}

.project-card button {
    margin-top: 10px;
    padding: 10px 15px;
    border: none;
    background: #0d47a1;
    color: white;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

.project-card button:hover {
    background: #1565c0;
}

/* Contact Section */
#contact a {
    color: #0d47a1;
    text-decoration: none;
    font-weight: bold;
}

#contact a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #0d47a1;
    color: white;
    margin-top: 40px;
}


My Personal Portfolio Website

This is my personal portfolio website created using HTML and CSS. I made this project as part of the Web Design Workshop (WDW) assignment for B.Tech 1st Year – CSE (AI & ML) at KIET Ghaziabad.

The main purpose of this website is to introduce myself, showcase my skills, highlight a few basic projects, and provide my contact details. The entire website is designed by me using simple, clean, and easy-to-read HTML and CSS.

Project Structure: portfolio/ │── index.html │── style.css │── images/ │ └── Chaitanya.png │── index.txt (README)

What I Have Included:

Home Section

My name, course, branch, and college

A short tagline about me

My profile photo

About Section A short description about who I am, my interests, and my goals in the tech field.

Skills Section The skills I currently know:

C Programming

Python

HTML

CSS

Basics of AI/ML

Projects Section Some basic projects I have worked on:

Calculator Website

Personal Portfolio

AI/ML Notes

Contact Section Includes my:

Email

GitHub

LinkedIn

Technologies Used:

HTML5

CSS3

Flexbox & Grid for layout

Simple system fonts

How to Run This Project: Just open the index.html file in any browser. No installation or server setup is required.

Deployment (Optional): This project can be deployed on:

Vercel

GitHub Pages

Netlify

Assignment Requirements Completed:

All 5 sections included

Website made with only HTML & CSS

Clean and simple UI

Screenshots and PPT created

README file written

Ready to submit

About Me: Chaitanya Vishwakarma B.Tech CSE (AI & ML), KIET Ghaziabad Aspiring AI Engineer | Tech Enthusiast
