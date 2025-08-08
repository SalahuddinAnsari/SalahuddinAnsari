<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Salahuddin Ansari - Portfolio</title>
<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background-color: #0a0a0a;
        color: #fff;
        scroll-behavior: smooth;
    }
    header {
        text-align: center;
        padding: 50px 20px;
        background: linear-gradient(135deg, #6a00ff, #9a4dff);
    }
    header img {
        width: 150px;
        border-radius: 50%;
        border: 4px solid #9a4dff;
        transition: transform 0.3s ease;
    }
    header img:hover {
        transform: scale(1.05);
    }
    h1 {
        margin-top: 20px;
        font-size: 2.5rem;
    }
    h2 {
        color: #9a4dff;
    }
    nav {
        text-align: center;
        margin: 20px 0;
    }
    nav a {
        margin: 0 15px;
        text-decoration: none;
        color: #fff;
        font-weight: bold;
        transition: color 0.3s ease;
    }
    nav a:hover {
        color: #9a4dff;
    }
    section {
        max-width: 900px;
        margin: auto;
        padding: 40px 20px;
        opacity: 0;
        transform: translateY(30px);
        transition: opacity 1s ease, transform 1s ease;
    }
    section.visible {
        opacity: 1;
        transform: translateY(0);
    }
    .skills span {
        display: inline-block;
        margin: 10px;
        padding: 10px 20px;
        background: #1a1a1a;
        border: 1px solid #9a4dff;
        border-radius: 20px;
        transition: background 0.3s ease;
    }
    .skills span:hover {
        background: #9a4dff;
        color: #0a0a0a;
    }
    footer {
        text-align: center;
        padding: 20px;
        background: #1a1a1a;
    }
    button {
        padding: 10px 20px;
        background: #9a4dff;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        color: #fff;
        transition: background 0.3s ease;
    }
    button:hover {
        background: #6a00ff;
    }
</style>
</head>
<body>

<header>
    <img src="your-photo.jpg" alt="Salahuddin Ansari">
    <h1>Salahuddin Ansari</h1>
    <h2>Web Developer & UI Designer | Data Analyst | Electrical Engineer</h2>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Me</h2>
    <p>I am an Electrical Engineer, graduated from Aliah University, New Town. 
    An enthusiastic learner skilled in Microsoft Office, Advanced Excel, HTML, CSS, Java, SQL, Python, Power BI, and UX/UI Design. 
    I am keenly interested in data analysis and creative web development.</p>
</section>

<section id="skills" class="skills">
