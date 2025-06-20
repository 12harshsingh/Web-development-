# Web-development-

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <h1>harsh singh</h1>
    <p>Web Developer | Front-End Enthusiast</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="profile.jpg" alt="My Photo" />
    <p>Hello! I'm harsh, a passionate front-end developer with experience in creating responsive and interactive websites. I enjoy building user-friendly web applications using HTML, CSS, and JavaScript.</p>
  </section>

  
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Responsive Design</li>
    </ul>
  </section>


  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <img src="project1.jpg" alt="Project 1" />
      <h3>Portfolio Website</h3>
      <p>A personal portfolio built with HTML, CSS, and JavaScript.</p>
    </div>
    <div class="project">
      <img src="project2.jpg" alt="Project 2" />
      <h3>To-Do App</h3>
      <p>A simple and clean to-do list application using React.</p>
    </div>
  </section>

  
  <section id="resume">
    <h2>Resume</h2>
    <p><a href="resume.pdf" download>Download My Resume (PDF)</a></p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: harshsingh@example.com</p>
    <p>Phone: +123 456 7890</p>
  </section>

</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 2rem;
  text-align: center;
}

section {
  padding: 2rem;
  margin: 1rem;
  background: #fff;
  border-radius: 5px;
}

h2 {
  border-bottom: 2px solid #333;
  padding-bottom: 0.5rem;
}

#about img {
  width: 150px;
  border-radius: 50%;
  display: block;
  margin-bottom: 1rem;
}

#skills ul {
  list-style-type: none;
  padding: 0;
}

#skills li {
  display: inline-block;
  background: #e0e0e0;
  padding: 0.5rem 1rem;
  margin: 0.5rem;
  border-radius: 3px;
}

.project {
  margin-bottom: 2rem;
}

.project img {
  width: 100%;
  max-width: 400px;
  border-radius: 5px;
}

a {
  color: #0066cc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
📁 Folder Structure
/portfolio/
│
├── index.html
├── style.css
├── profile.jpg
├── project1.jpg
├── project2.jpg
└── resume.pdf
