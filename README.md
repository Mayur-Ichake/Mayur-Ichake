<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mayur Ichake Portfolio</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<!-- Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
  body {font-family: 'Roboto', sans-serif; margin:0; padding:0; background:#f5f5f5; color:#333;}
  header {background:#1f1f1f; color:white; padding:60px 20px; text-align:center;}
  header h1 {font-size:2.5em; margin:0;}
  header h3 {font-weight:400; font-size:1.3em; margin-top:10px;}
  .typewriter {display:inline-block; border-right:2px solid #fff; padding-right:5px; animation:blink 0.7s infinite;}
  @keyframes blink{0%,50%,100%{border-color:#fff}25%,75%{border-color:transparent}}
  
  section {padding:60px 20px;}
  h2 {text-align:center; margin-bottom:40px; font-size:2em;}
  
  /* Skills */
  .skills {display:flex; flex-wrap:wrap; justify-content:center; gap:20px;}
  .skill {background:white; padding:20px; width:200px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1); text-align:center; transition:transform 0.3s;}
  .skill:hover {transform:translateY(-10px);}
  .skill i {font-size:2em; margin-bottom:10px; color:#ff6f61;}
  .progress {height:10px; background:#eee; border-radius:5px; margin-top:10px;}
  .progress-bar {height:10px; background:#ff6f61; border-radius:5px; width:0%; animation:loadProgress 2s forwards;}
  @keyframes loadProgress {from{width:0%} to{width: var(--width)}}
  
  /* Projects */
  .projects {display:flex; flex-wrap:wrap; justify-content:center; gap:20px;}
  .project-card {background:white; width:250px; padding:20px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1); transition:transform 0.3s; text-align:center;}
  .project-card:hover {transform:translateY(-10px);}
  .project-card img {width:100%; border-radius:10px;}
  .project-card h4 {margin:15px 0 10px;}
  
  /* Buttons */
  .buttons {text-align:center; margin-top:30px;}
  .buttons a {display:inline-block; margin:0 10px; padding:10px 20px; border-radius:30px; background:#ff6f61; color:white; text-decoration:none; transition:0.3s;}
  .buttons a:hover {background:#e85c50;}
  
  /* Footer */
  footer {background:#1f1f1f; color:white; text-align:center; padding:30px 20px;}
  
  /* Animations */
  .fade-in {opacity:0; transform:translateY(30px); animation:fadeIn 1s forwards;}
  .fade-in:nth-child(1){animation-delay:0.2s;}
  .fade-in:nth-child(2){animation-delay:0.4s;}
  .fade-in:nth-child(3){animation-delay:0.6s;}
  .fade-in:nth-child(4){animation-delay:0.8s;}
  @keyframes fadeIn {to{opacity:1; transform:translateY(0);}}
</style>
</head>
<body>

<header>
  <h1>Hi 👋, I'm Mayur Ichake</h1>
  <h3>Final Year ENTC Student | <span class="typewriter">Python & AI/ML Enthusiast</span></h3>
</header>

<section id="skills">
  <h2>💻 Skills</h2>
  <div class="skills">
    <div class="skill fade-in">
      <i class="fab fa-python"></i>
      <h4>Python</h4>
      <div class="progress"><div class="progress-bar" style="--width:90%"></div></div>
    </div>
    <div class="skill fade-in">
      <i class="fas fa-database"></i>
      <h4>Pandas</h4>
      <div class="progress"><div class="progress-bar" style="--width:85%"></div></div>
    </div>
    <div class="skill fade-in">
      <i class="fas fa-project-diagram"></i>
      <h4>AI/ML</h4>
      <div class="progress"><div class="progress-bar" style="--width:75%"></div></div>
    </div>
    <div class="skill fade-in">
      <i class="fas fa-robot"></i>
      <h4>Robotics</h4>
      <div class="progress"><div class="progress-bar" style="--width:70%"></div></div>
    </div>
  </div>
</section>

<section id="projects">
  <h2>📂 Projects</h2>
  <div class="projects">
    <div class="project-card fade-in">
      <img src="https://via.placeholder.com/250x150.png?text=Core+Python" alt="Core Python">
      <h4>Core Python</h4>
      <p>Beginner-friendly scripts and exercises to strengthen Python fundamentals.</p>
    </div>
    <div class="project-card fade-in">
      <img src="https://via.placeholder.com/250x150.png?text=Pandas" alt="Pandas Projects">
      <h4>Pandas Projects</h4>
      <p>Data cleaning, analysis, and visualization using Pandas.</p>
    </div>
    <div class="project-card fade-in">
      <img src="https://via.placeholder.com/250x150.png?text=Robotics" alt="Robotic Arm">
      <h4>Robotic Arm</h4>
      <p>Tomato cutting robotic arm using ESP32-CAM & Arduino.</p>
    </div>
    <div class="project-card fade-in">
      <img src="https://via.placeholder.com/250x150.png?text=Edge+AI" alt="Edge AI">
      <h4>Edge AI</h4>
      <p>Human activity recognition & animal intrusion alert system.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>📫 Contact Me</h2>
  <div class="buttons">
    <a href="https://github.com/Mayur-Ichake" target="_blank"><i class="fab fa-github"></i> GitHub</a>
    <a href="https://www.linkedin.com/in/mayur-ichake" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
    <a href="mailto:mayur@example.com"><i class="fas fa-envelope"></i> Email</a>
  </div>
</section>

<footer>
  <p>Made with ❤️ by Mayur Ichake | Python & AI/ML Enthusiast</p>
</footer>

</body>
</html>
