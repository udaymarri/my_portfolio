# my_portfolio
Created my personal portfolio website showcasing my projects and skills
<!DOCTYPE html>
<html>
<head>
        <title>M.UDAY RAJA SEKHAR REDDY - Portfolio</title>
    <style>

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

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            text-align: center;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin-top: 10px;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        .section {
            padding: 40px 0;
            margin-bottom: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        ul {
            list-style-type: none;
            padding-left: 0;
            text-align: center;
        }

        ul li {
            font-size: 1.2rem;
            margin: 5px 0;
        }

        .project-item {
            background-color: #f9f9f9;
            padding: 20px;
            margin: 10px 0;
            border-radius: 8px;
            text-align: center;
        }

        .project-item a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #0073e6;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .project-item a:hover {
            background-color: #005bb5;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            .project-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>M.UDAY RAJA SEKHAR REDDY</h1>
            <nav>
                <ul>
                    <li><a href="bio">About Me</a></li>
                    <li><a href="skill">Skills</a></li>
                    <li><a href="pro">Projects</a></li>
                    <li><a href="Dail">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="bio" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hi, I'm uday raja sekhar reddy, a passionate web developer with experience in front-end and back-end technologies. I love building innovative web applications and solving problems with code.</p>
        </div>
    </section>

    <section id="skills" class="section">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React.js, Node.js</li>
                <li>Python, Django</li>
                <li>Git, GitHub</li>
                <li>Responsive Design</li>
            </ul>
        </div>
    </section>

    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-item">
                <h3>Project 1: Portfolio Website</h3>
                <p>This is my personal portfolio website where I showcase my work and skills. Built with HTML, CSS, and JavaScript.</p>
                <a href="Pro">View Project</a>
            </div>
            <div class="project-item">
                <h3>Project 2: Web App</h3>
                <p>A web application built using React and Node.js. It allows users to track tasks and manage projects.</p>
                <a href="pro">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact</h2>
            <p align="center">You can reach me via email at <a href="mailto:uday.marri57@gmail.com"> uday.marri57@gmail.com</a></p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 uday raja sekhar reddy. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
