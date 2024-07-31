<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhannad Aldossary - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }
        .skills, .projects, .contact {
            margin-bottom: 2em;
        }
        h2 {
            color: #4CAF50;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 0.5em;
        }
        .skills ul, .projects ul {
            list-style: none;
            padding: 0;
        }
        .skills li, .projects li {
            background: white;
            margin-bottom: 0.5em;
            padding: 1em;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .projects a {
            color: #4CAF50;
            text-decoration: none;
        }
        .contact a {
            color: #4CAF50;
            text-decoration: none;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact form button {
            padding: 0.5em 1em;
            background: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <img src="https://via.placeholder.com/150" alt="Muhannad Aldossary">
    <h1>Muhannad Aldossary</h1>
    <p>Full-Stack Developer Creating Scalable Web Solutions</p>
</header>

<div class="container">
    <section class="introduction">
        <h2>Introduction</h2>
        <p>Hello! I'm Muhannad Aldossary, a Computer Science graduate working at GOSI. I work on various projects on the side, such as developing apps, websites, and AI projects.</p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li><strong>Front-End:</strong> HTML, CSS, JavaScript, React, Python, Java</li>
            <li><strong>Back-End:</strong> Node.js, Express, Ruby on Rails</li>
            <li><strong>Frameworks:</strong> Flutter, Flask</li>
            <li><strong>Databases:</strong> MongoDB, MySQL</li>
            <li><strong>Tools:</strong> Git</li>
        </ul>
    </section>

    <section class="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <strong>Video Understanding Website for Educational Content</strong><br>
                Technologies: Flask<br>
                <a href="https://youtu.be/gsb86T1NCck" target="_blank">Live Demo</a> | <a href="https://github.com/wingmoe21/tech_innovators" target="_blank">GitHub Repo</a>
            </li>
            <li>
                <strong>Koala Journey</strong><br>
                Designing the front end for a startup, using Adobe XD and React Native.<br>
                <a href="path_to_file/Koala Journey- Mock Screens.xd" target="_blank">Design Mockup</a>
            </li>
        </ul>
    </section>

    <section class="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:maldossary16@gmail.com">maldossary16@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/muhannad-aldossary-0b9a43135/" target="_blank">Muhannad Aldossary</a></p>
        <p>GitHub: <a href="https://github.com/wingmoe21" target="_blank">wingmoe21</a></p>
        <p>Call or WhatsApp: +966505600703</p>
        <form>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</div>

</body>
</html>
