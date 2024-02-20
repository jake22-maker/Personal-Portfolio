# Personal-Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>My Portfolio</title>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio website! I'm passionate about coding and love to create beautiful websites.</p>
        <img src="images/profile.jpg" alt="Profile Picture">
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>This is a description of my first project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>This is a description of my second project.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>


/* Reset some default styles */
body, h1, h2, h3, p, img {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f1f1f1;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 24px;
}

section {
    padding: 20px;
    margin-bottom: 20px;
    background-color: #fff;
}

section h2 {
    font-size: 18px;
    margin-bottom: 10px;
}

section p {
    margin-bottom: 20px;
}

img {
    max-width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer p {
    font-size: 14px;
}
