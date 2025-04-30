# MDAP-EX_01-Portfolio
## Date: 25/04/2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My CSE Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <header class="hero">
      <img src="profile.jpg" alt="My Profile" class="profile-pic" />
      <h1>Your Name</h1>
      <p>CSE Student | Web Developer | Tech Enthusiast</p>
      <nav class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#certifications">Certifications</a>
        <a href="#achievements">Achievements</a>
        <a href="#internships">Internships</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>I am a Computer Science student passionate about building scalable web apps and solving real-world problems.</p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p><strong>B.Tech in Computer Science and Engineering</strong></p>
      <p>XYZ College of Engineering, 2022 - 2026</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>C, C++, Python, JavaScript</li>
        <li>HTML, CSS, React</li>
        <li>Git, GitHub, MySQL, MongoDB</li>
      </ul>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>Portfolio Website (React)</li>
        <li>Student Result System (C++)</li>
        <li>ASD Detection Model (Python)</li>
      </ul>
    </section>

    <section id="certifications">
      <h2>Certifications</h2>
      <ul>
        <li>Python for Everybody – Coursera</li>
        <li>Frontend Development – Great Learning</li>
        <li>Git & GitHub – Udemy</li>
      </ul>
    </section>

    <section id="achievements">
      <h2>Achievements</h2>
      <ul>
        <li>Top 10 in college coding contests</li>
        <li>300+ problems on LeetCode</li>
        <li>Winner of CodeHack 2024</li>
      </ul>
    </section>

    <section id="internships">
      <h2>Internships</h2>
      <ul>
        <li>Web Dev Intern at ABC Co.</li>
        <li>Python & Data Science Training</li>
      </ul>
    </section>

    <section id="resume">
      <h2>Resume</h2>
      <p><a href="resume.pdf" download>Download My Resume</a></p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: your.email@example.com</p>
      <p>GitHub: <a href="#">github.com/yourusername</a></p>
    </section>

    <footer>
      <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>

```
CSS CODE:
```
body {
    font-family: Arial, sans-serif;
    background: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
  }
  
  .container {
    max-width: 900px;
    margin: auto;
    padding: 2rem;
  }
  
  .hero {
    text-align: center;
    background: #0077b6;
    color: white;
    padding: 2rem;
    border-radius: 10px;
  }
  
  .profile-pic {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    border: 3px solid white;
    margin-bottom: 1rem;
  }
  
  .navbar {
    margin-top: 1rem;
  }
  
  .navbar a {
    color: white;
    margin: 0 0.5rem;
    text-decoration: none;
    font-weight: bold;
  }
  
  h2 {
    color: #0077b6;
    margin-top: 2rem;
  }
  
  ul {
    list-style-type: square;
    padding-left: 1.5rem;
  }
  
  a {
    color: #0077b6;
    text-decoration: none;
  }
  
  footer {
    text-align: center;
    margin-top: 2rem;
    color: #777;
  }

```



## OUTPUT
![image](https://github.com/user-attachments/assets/a34519ee-af4b-4a0b-abd0-045942d39b44)
![image](https://github.com/user-attachments/assets/b9f0e712-646a-4610-81a3-977919ba9e39)
![image](https://github.com/user-attachments/assets/2d5b3f54-6451-4ec2-b995-74a1aac132e1)





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
