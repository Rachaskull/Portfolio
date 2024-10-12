/portfolio
   ├── index.html
   ├── style.css
   └── /images
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <div class="welcome-text">
            <h1>Welcome to My Portfolio</h1>
            <p>Computer Science Enthusiast | Automation Advocate | Club Leader</p>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I’m [Your Name], a B.Tech student majoring in Computer Science and Engineering at GLA University...</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>C</li>
            <li>Python</li>
            <li>Java</li>
            <li>MySQL</li>
            <li>Automation</li>
            <li>Problem Solving</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-item">
            <h3>Automation Project 1</h3>
            <p>Description of the project...</p>
        </div>
        <div class="project-item">
            <h3>Python Project</h3>
            <p>Description of the project...</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></p>
    </section>

    <footer>
        <p>© 2024 [Your Name]. All Rights Reserved.</p>
    </footer>
</body>
</html>
/* Reset default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    padding: 10px 0;
    color: white;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 50px;
    text-align: center;
}

#welcome-text h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

#welcome-text p {
    font-size: 1.2em;
    color: #666;
}

#about, #skills, #projects, #contact {
    background-color: white;
    margin-bottom: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

ul {
    list-style-type: none;
}

.project-item {
    margin: 20px 0;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

a {
    color: #00aaff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
