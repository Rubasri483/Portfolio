# Ex01 Portfolio
## Date: 29/04/2026

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Rubasri</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: #fff;
      padding: 20px;
    }

    h1, h2 {
      text-align: center;
      margin-bottom: 10px;
    }

    p {
      text-align: center;
      line-height: 1.6;
    }

    .container {
      max-width: 900px;
      margin: auto;
    }

    .box {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(12px);
      border-radius: 20px;
      padding: 25px;
      margin: 20px 0;
      box-shadow: 0 8px 25px rgba(0,0,0,0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .box:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(0,0,0,0.5);
    }

    .profile-pic {
      width: 130px;
      height: 130px;
      margin: auto;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 50px;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }

    ul {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 10px;
    }

    ul li {
      list-style: none;
      padding: 8px 15px;
      border-radius: 20px;
      background: rgba(255,255,255,0.15);
      font-size: 14px;
      transition: background 0.3s;
    }

    ul li:hover {
      background: rgba(255,255,255,0.3);
    }

    .project {
      background: rgba(255,255,255,0.07);
      padding: 15px;
      border-radius: 15px;
      margin-top: 15px;
      transition: transform 0.3s;
    }

    .project:hover {
      transform: scale(1.02);
    }

    .project h3 {
      text-align: center;
      margin-bottom: 8px;
    }

    .project p {
      text-align: left;
      font-size: 14px;
    }

    a {
      color: #ffd86b;
      text-decoration: none;
      font-weight: 500;
    }

    a:hover {
      text-decoration: underline;
    }

    footer p {
      font-size: 13px;
      opacity: 0.8;
    }

    @media (max-width: 600px) {
      .box {
        padding: 15px;
      }
    }
  </style>
</head>

<body>
  <div class="container">

    <!-- HEADER -->
    <div class="box">
      <div class="profile-pic">👩‍💻</div>
      <h1>Rubasri Ravishankar</h1>
      <p>Aspiring ML Engineer</p>
      <p> Chennai, India |  B.Tech AIML</p>
    </div>

    <!-- ABOUT -->
    <div class="box">
      <h2>About Me</h2>
      <p>
        I'm Rubasri, an AIML student passionate about building intelligent systems.
        I enjoy solving real-world problems using Machine Learning and constantly
        improving my technical skills.love exploring how technology can solve real-world problems and have worked on projects like sentiment analysis and plant disease detection. I am always eager to learn, improve, and grow as a developer while aiming to build impactful solutions.
      </p>
    </div>

    <!-- SKILLS -->
    <div class="box">
      <h2>Skills</h2>
      <ul>
        <li>Python</li>
        <li>Machine Learning</li>
        <li>HTML & CSS</li>
        <li>NumPy & Pandas</li>
        <li>Scikit-learn</li>
        <li>Git & GitHub</li>
        <li>SQL</li>
      </ul>
    </div>

    <!-- PROJECTS -->
    <div class="box">
      <h2>Projects</h2>

      <div class="project">
        <h3>🌿 Plant Disease Detection</h3>
        <p>Developed a CNN model using TensorFlow to identify plant diseases from leaf images.</p>
      </div>

      <div class="project">
        <h3>💬 Sentiment Analyzer</h3>
        <p>Built an NLP model using Scikit-learn to classify movie reviews as positive or negative.</p>
      </div>

      <div class="project">
        <h3>🌐 Personal Portfolio</h3>
        <p>A responsive personal website designed with modern UI to showcase projects and skills.</p>
      </div>

    </div>

    <!-- EDUCATION -->
    <div class="box">
      <h2>Education</h2>
      <p> B.Tech in Artificial Intelligence and machine learning</p>
      <p> Saveetha Engineering college, Chennai</p>
      <p>2024 – 2028</p>
    </div>

    <!-- CONTACT -->
    <div class="box">
      <h2>Contact</h2>
      <p> <a href="mailto:rubasriravishankar@gmail.com">rubasri@email.com</a></p>
      <p> <a href="#">LinkedIn</a></p>
      <p> <a href="#">GitHub</a></p>
    </div>

    <!-- FOOTER -->
    <div class="box">
      <footer>
        <p>Made with  by Rubasri</p>
      </footer>
    </div>

  </div>
</body>
</html>
```

## OUTPUT

<img width="1349" height="591" alt="image" src="https://github.com/user-attachments/assets/f7eab859-3807-4fea-a1af-4ff3c140d3ba" />

<br>

<img width="1365" height="584" alt="image" src="https://github.com/user-attachments/assets/9027f748-1568-4527-84df-f6a591932cb5" />

<br>

<img width="1342" height="491" alt="image" src="https://github.com/user-attachments/assets/292b75bd-c708-4180-b95b-af59603f3c99" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
