# My-1st-Portfolio
The portfolio page is a clean, professional HTML document featuring sections for "About Me," "Projects," and "Contact." It includes a responsive design, a navigation bar, and links to your email and LinkedIn profile.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #0073e6;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: white;
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 1rem;
        }
        .section-title {
            color: #0073e6;
            margin-top: 1rem;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .project {
            border: 1px solid #ddd;
             border-radius: 5px;
            padding: 1rem;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #f4f4f4;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <p>Welcome to my professional portfolio page</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
 <div class="container">
        <section id="about">
            <h2 class="section-title">About Me</h2>
            <p>I am a recent graduate in Computer Systems Engineering with hands-on experience in frontend development, basic AI concepts, and general computer operations. My professional journey includes internships, teaching, and customer service roles.</p>
        </section>

        <section id="projects">
            <h2 class="section-title">Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>WhatsApp Clone</h3>
                    <p>A frontend design project replicating the user interface of WhatsApp, showcasing responsive and interactive design skills.</p>
                </div>
                <div class="project">
                    <h3>School Management System</h3>
                    <p>Developed an API using Python and designed the frontend for a comprehensive system to manage school operations.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2 class="section-title">Contact</h2>
            <p>Feel free to reach out for collaboration or opportunities:</p>
            <ul>
                <li>Email: pkdevelop@gmail.com</li>
                <li>Phone: 923478309474</li>
               <li>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
 
