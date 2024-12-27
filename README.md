# Tejas
Portfilo 
<!DOCTYPE html>

<html lang="en">

<head>

 <meta charset="UTF-8">

 <meta name="viewport" content="width=device-width, initial-scale=1.0">

 <meta http-equiv="X-UA-Compatible" content="ie=edge">

 <title>Your Portfolio</title>

 <link rel="stylesheet" href="EX.15.css">

</head>

<body>

 <header>

 <div class="navbar">

 <div class="logo">SID</div>

 <nav>

 <ul>

 <li><a href="#about">About Me</a></li>

 <li><a href="#skills">Skills</a></li>

 <li><a href="#projects">Projects</a></li>

 <li><a href="#contact">Contact</a></li>

 </ul>

 </nav>

 </div>

 </header>

 <section id="home" class="hero">

 <div class="hero-content">

 <!-- Profile Image Section --> 

 <div class="profile-image">

 <img src="profile.jpg" alt="Your Profile Image">

 </div>

 <h1>Hello, I'm <span> TEJAS BORATE</span></h1>

 <p>Web Developer | Designer | Creator</p>

 </div>

 </section>

 <section id="about" class="section about">

 <h2>About Me</h2>

 <p>I am a passionate web developer with a keen interest in creating beautiful and functional 

websites.</p>
</section>

 <section id="skills" class="section skills">

 <h2>Skills</h2>

 <div class="skill-container">

 <div class="skill">

 <h3>HTML</h3>

 <div class="progress-bar">

 <div class="progress html"></div>

 </div>

 </div>

 <div class="skill">

 <h3>CSS</h3>

 <div class="progress-bar">

 <div class="progress css"></div>

 </div>

 </div>

 <div class="skill">

 <h3>JavaScript</h3>

 <div class="progress-bar">

 <div class="progress js"></div>

 </div>

 </div>

 </div>

 </section>

 <section id="projects" class="section projects">

 <h2>Projects</h2> <br>

 <div class="project-list">

 <div class="project">

 <img src="Project-1.png" alt="Project 1">

 <h3>Project 1</h3>

 <p>Styling Table with css.</p>

 </div>

 <div class="project">

 <img src="Project-2.png" alt="Project 2">

 <h3>Project 2</h3>

 <p>Creating a ID card With CSS</p>

 </div>

 </div>

 </section>

 <section id="contact" class="section contact">

 <h2>Contact</h2>

 <form action="#" method="POST">

 <input type="text" name="name" placeholder="Your Name" required>

 <input type="email" name="email" placeholder="Your Email" required>

 <textarea name="message" placeholder="Your Message" required></textarea>

 <button type="submit">Send Message</button>

 </form>

 </section>
 <footer>

 <p>&copy; 2024 Siddharth Angre |All Rights Reserved</p>

 </footer>

</body>

</html>

CSS:

* {

 margin: 0;

 padding: 0;

 box-sizing: border-box;

 font-family: 'Arial', sans-serif;

 }

 

 body {

 background-color: #f7f7f7;

 color: #333;

 }

 

 a {

 text-decoration: none;

 color: inherit;

 }

 

 header {

 background-color: #333;

 padding: 20px;

 }

 

 .navbar {

 display: flex;

 justify-content: space-between;

 align-items: center;

 }

 

 .navbar .logo {

 font-size: 24px;

 font-weight: bold;

 color: #fff;

 }

 

 nav ul {

 list-style: none;

 display: flex;

 gap: 20px;

 }
nav ul li a {

 color: #fff;

 font-size: 18px;

 transition: color 0.3s;

 }

 

 nav ul li a:hover {

 color: #ff6347;

 }

 

 .hero {

 height: 100vh;

 background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);

 color: white;

 display: flex;

 justify-content: center;

 align-items: center;

 text-align: center;

 flex-direction: column;

 }

 

 .hero-content {

 display: flex;

 flex-direction: column;

 justify-content: center;

 align-items: center;

 }

 

 .profile-image img {

 border-radius: 50%;

 width: 150px; /* Adjust the size of your profile image */

 height: 150px;

 object-fit: cover;

 margin-bottom: 20px;

 }

 

 .hero-content h1 {

 font-size: 3rem;

 margin-bottom: 20px;

 }

 

 .hero-content h1 span {

 color: #ff6347;

 }

 

 .hero-content p {

 font-size: 1.2rem;

 }

 

 .section {

 padding: 50px 0;
 text-align: center;

 }

 

 .about, .skills, .projects, .contact {

 background-color: #fff;

 margin: 20px 0;

 border-radius: 10px;

 box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

 }

 

 .skills .skill-container {

 display: flex;

 justify-content: center;

 gap: 30px;

 }

 

 .skills .skill {

 width: 200px;

 }

 

 .skills h3 {

 margin-bottom: 10px;

 }

 

 .progress-bar {

 width: 100%;

 height: 20px;

 background-color: #ddd;

 border-radius: 10px;

 }

 

 .progress {

 height: 100%;

 border-radius: 10px;

 }

 

 .html {

 width: 90%;

 background-color: #ff6347;

 }

 

 .css {

 width: 80%;

 background-color: #2575fc;

 }

 

 .js {

 width: 20%;

 background-color: #f1c40f;

 }
.projects .project-list {

 display: flex;

 gap: 30px;

 justify-content: center;

 }

 

 .projects .project {

 width: 300px;

 background-color: #f0f0f0;

 border-radius: 10px;

 overflow: hidden;

 text-align: center;

 box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

 }

 

 .projects .project img {

 width: 100%;

 height: 200px;

 object-fit: cover;

 }

 

 .projects .project h3 {

 margin: 15px 0;

 font-size: 1.5rem;

 }

 

 .contact form {

 display: grid;

 gap: 15px;

 max-width: 500px;

 margin: 0 auto;

 }

 

 .contact input, .contact textarea {

 padding: 15px;

 border: 2px solid #ddd;

 border-radius: 10px;

 font-size: 1rem;

 }

 

 .contact button {

 padding: 15px;

 background-color: #2575fc;

 color: #fff;

 border: none;

 border-radius: 10px;

 font-size: 1.1rem;

 cursor: pointer;

 transition: background-color 0.3s;

 }

.contact button:hover {

 background-color: #ff6347;

 }

 

 footer {

 text-align: center;

 background-color: #333;

 color: #fff;

 padding: 20px;

 font-size: 14px;

 }

 

 footer p {

 margin: 0;

 }
 



