index.html
html
<!DOCTYPE html>
<html lang="en">
<head>
    <!Document Metadata>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        / Optional inline style for a simple layout/
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header, nav, footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            margin-top: 10px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <!Header Section>
    <header>
        <h1>Welcome to My Portfolio</h1>
    </header>

    <!Navigation Bar>
    <nav>
        <!Links for Navigation>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!Main Content Section>
    <main>
        <!About Section>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I am a web development enthusiast passionate about creating stunning and functional websites.</p>
        </section>

        <!Projects Section>
        <section id="projects">
            <h2>Projects</h2>
            <p>Take a look at some of the projects I have worked on:</p>
            <ul>
                <li>Project 1: Portfolio Website</li>
                <li>Project 2: E-commerce Site</li>
                <li>Project 3: Blogging Platform</li>
            </ul>
        </section>
    </main>

    <!Footer Section>
    <footer>
        <p>Contact Me: <a href="mbalutomaureen@gmail.com">mbalutomaureen@gmail.com</a></p>
        <p>© 2025 Maureen Mbaluto. All rights reserved.</p>
    </footer>
</body>
</html>
