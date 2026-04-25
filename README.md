# Ex01 Portfolio
## Date: 25-04-2026

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
## index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- HOME -->
<section id="home">
    <div class="home-container">
        <img src="profile.jpg" class="profile-img">

        <h1>Madhu Priya R</h1>
        <p class="tagline">Aspiring Web Developer</p>

        <p class="intro">
            I create clean and responsive websites using HTML, CSS and JavaScript.
        </p>
    </div>
</section>

<!-- ABOUT -->
<section id="about">
    <h2>About Me</h2>
    <p>
        I am a B.E (CSE) student passionate about creating interactive, responsive websites 
        and learning the latest web technologies. I enjoy solving problems and bringing 
        ideas to life through clean code and creative design.
    </p>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>Skills</h2>
    <div class="skills">
        <div class="skill-box">HTML5</div>
        <div class="skill-box">CSS</div>
        <div class="skill-box">C</div>
        <div class="skill-box">Python</div>
        <div class="skill-box">Git & GitHub</div>
    </div>
</section>

<!-- PROJECTS -->
<section id="projects">
    <h2>Projects</h2>

    <div class="project-box">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio to showcase my skills and projects.</p>
    </div>

    <div class="project-box">
        <h3>AJIO App</h3>
        <p>An e-commerce fashion store web application.</p>
    </div>

    <div class="project-box">
        <h3>Restaurant Website</h3>
        <p>An online food ordering & table booking platform.</p>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Me</h2>

    <div class="contact-box">
        <p>Email: <a href="#">madhu@email.com</a></p>
        <p>Phone: +91 98765 12345</p>
        <p>Location: Chennai</p>
        <p>GitHub: <a href="#">View Projects</a></p>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Madhu Priya R</p>
</footer>

</body>
</html>
```
## style.css

```
body {
    margin: 0;
    font-family: Arial;
}

/* HOME */
#home {
    height: 100vh;
    background: linear-gradient(135deg, #ff7e5f, #feb47b);
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
    margin-bottom: 15px;
}

.tagline {
    font-size: 18px;
}

.intro {
    max-width: 400px;
    margin: auto;
}

/* ABOUT */
#about {
    padding: 40px;
    text-align: center;
    background: #f4f4f4;
}

/* SKILLS */
#skills {
    padding: 40px;
    text-align: center;
    background: #ffffff;
}

.skills {
    margin-top: 20px;
}

.skill-box {
    display: inline-block;
    padding: 10px 15px;
    margin: 5px;
    background: #ff7e5f;
    color: white;
    border-radius: 20px;
    transition: 0.3s;
}

.skill-box:hover {
    background: #333;
}

/* PROJECTS */
#projects {
    padding: 40px;
    text-align: center;
    background: #f4f4f4;
}

.project-box {
    background: #fff;
    padding: 15px;
    margin: 10px;
    display: inline-block;
    width: 220px;
    border-radius: 10px;
    box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

/* CONTACT */
#contact {
    padding: 40px;
    text-align: center;
    background: #ffffff;
}

.contact-box {
    background: #fdf1ec;
    padding: 20px;
    margin: auto;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.contact-box a {
    color: #ff7e5f;
    text-decoration: none;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
}
```

## OUTPUT

<img width="1852" height="862" alt="image" src="https://github.com/user-attachments/assets/92742cdd-3443-40e3-b0a8-4786cb2bd0eb" />



<img width="1830" height="849" alt="image" src="https://github.com/user-attachments/assets/0b1137bd-c9e4-4dbd-81a9-3543f32c520e" />




<img width="1885" height="566" alt="image" src="https://github.com/user-attachments/assets/d607b478-29ea-4cfc-bbe4-f3032eea9a2b" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
