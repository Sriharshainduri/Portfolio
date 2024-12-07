# Portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Elegant Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <div class="container">
      <h1 class="logo">Sriharsha Induri</h1>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Header Section -->
  <header>
    <div class="header-content">
      <img src="profile.jpg" alt="Profile Picture" class="profile-img">
      <h1>Hi, I'm Sriharsha</h1>
      <p>A passionate Web Developer</p>
      <a href="#contact" class="cta-button">Get in Touch</a>
    </div>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I'm Sriharsha, a passionate web developer with a deep interest in creating engaging and responsive websites. With a strong foundation in web technologies, I love crafting user-friendly experiences that bring ideas to life online. Currently, I'm enhancing my skills through an internship at Oasis Infobyte, where I'm gaining hands-on experience in both design and development. I’m always eager to learn, grow, and take on new challenges to make a meaningful impact in the field of web development.

    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-container">
      <div class="skill">HTML & CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">React</div>
      <div class="skill">Node.js</div>
      <div class="skill">Responsive Design</div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project">
        <h3>Online hospital management</h3>
        <p>A UI design on Online Hospital management</p>
      </div>
      <div class="project">
        <h3>Chat Application</h3>
        <p>An online chat application using a firebase.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Feel free to reach out through email or connect with me on LinkedIn!</p>
    <p>Email: <a href="mailto:your-email@example.com">sriharshainduri@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/your-profile" target="_blank">sriharsha induri</a></p>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Sriharsha. All Rights Reserved.</p>
  </footer>

</body>
</html>


#Portfolio.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Global Styles */
  body {
    font-family: 'Arial', sans-serif;
    color: #333;
    line-height: 1.6;
  }
  
  /* Navigation Bar */
  nav {
    position: sticky;
    top: 0;
    background-color: #0d0d0d;
    color: white;
    padding: 1rem;
    z-index: 1000;
  }
  
  nav .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .nav-links {
    list-style: none;
  }
  
  .nav-links li {
    display: inline;
    margin: 0 1rem;
  }
  
  .nav-links a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
  }
  
  .nav-links a:hover {
    color: #4CAF50;
  }
  
  /* Header Section */
  header {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('your-header-image.jpg') center/cover;
    height: 100vh;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  
  .profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 1rem;
  }
  
  .cta-button {
    display: inline-block;
    background-color: #4CAF50;
    color: white;
    padding: 0.75rem 1.5rem;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s;
  }
  
  .cta-button:hover {
    background-color: #333;
  }
  
  /* Section Styles */
  section {
    padding: 4rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
  }
  
  #about, #contact {
    background-color: #f9f9f9;
    border-radius: 10px;
    padding: 2rem;
  }
  
  h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  
  /* Skills Section */
  .skills-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
  }
  
  .skill {
    background-color: #4CAF50;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    font-size: 1rem;
    transition: transform 0.3s;
  }
  
  .skill:hover {
    transform: scale(1.1);
  }
  
  /* Projects Section */
  .project-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  
  .project {
    background-color: #fff;
    padding: 1rem;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  
  .project:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
  }
  
  /* Contact Section */
  #contact a {
    color: #4CAF50;
    text-decoration: none;
  }
  
  #contact a:hover {
    text-decoration: underline;
  }
  
  /* Footer Styles */
  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    .nav-links li {
      display: block;
      margin: 0.5rem 0;
    }
  }
  
