<html lang="en">
<head>
    <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
<style>
    body {
        line-height: 1.6; 
        background-color: rgb(0, 0, 0);
    }

    .hero {
      background-color: rgb(0, 0, 0);
      text-align: center;
       /* display: flex; */
      justify-content: center;
      align-items: center;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(245, 242, 242, 0.1);
        color: #fafafa;
        padding: 40px 20px;
    }

    .hero h1 {
        font-size: 3rem;
        font-family: Times New Roman;
        font-size: 55px;
        font-style: inherit;
    }
    .hero p{
        font-family: Archivo;
        font-style: inherit;
    }

    .section {
        padding: 40px 20px;
        border-radius: 100px;
    }

    .skills .progress {
        margin-bottom: 15px;
    }

    footer {
        background: #343a40;
        color: #fff;
        padding: 10px 20px;
        text-align: center;
    }
    .p1{
         color: #fff;
         font-family: Archivo;  
        font-style: inherit;
    }
    .p3{
        color: white;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    footer a {
        color: #ffc107;
    }
    .p2{
        width: 200px;
      height: 200px;
      border-radius: 80%;
      overflow: hidden;
      position: relative;
      animation: blink-photo-shadow 1.5s infinite alternate;
      align-items: center;
      justify-content: center;
      display: flex;
      text-align: center;
    }
    .p2 img{
        .inner-photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: flex;
      align-items: center;
      font-size: 5px;
      position: relative;
      display: flex; 
      justify-content: center; 
      
    }
    }
    .skills{
        /* background-color: black; */
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    .s1{
      color: #fff;
    }
    .form-container {
      max-width: 400px;
      margin: auto;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }
    .form-container input, .form-container textarea, .form-container button {
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }
    .form-container button {
      background-color: #00ff2a;
      color: white;
      border: none;
    }
    .form-container button:hover {
      background-color: orangered green pink;
    }
    .form-container h2,label{
         color: #ddd;
    }
    .clickbox{
        width: 150px;
      height: 50px;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
      font-size: 18px;
      font-weight: bold;
      text-decoration: none;
      background: linear-gradient(135deg, #33ff00, #bbff00, orangered);
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
      transition: all 0.3s ease;
    }
    .clickbox:hover{
        background: linear-gradient(135deg, #ff002b, #ec9625);
      transform: scale(1.1);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
    }
    @keyframes blink-photo-shadow {
        0% {
        box-shadow: 0 0 20px 3px #4000f1;
      }
      25% {
        box-shadow: 0 0 20px 3px #ff0000;
      }
      50% {
        box-shadow: 0 0 20px 3px #00ff0d;
      }
      75% {
        box-shadow: 0 0 20px 3px #ff00b3;
      }
      100% {
        box-shadow: 0 0 20px 3px #ff9900;
      }

    }
</style>
</head>

<body>
<!-- Hero Section -->
<div class="hero">
    <div class="p2">
        <img src="IMG_20230727_203753 (1).jpg" alt="My photo" width="200" height="200">
    </div>
    <h1>Jenish</h1>
    <p>Web Developer | Designer</p>
</div>

<!-- About Section -->
<div class="section" id="about">
    <div class="container">
        <h2 class="p1">About Me</h2>
        <p class="p3">Hello! I'm Passionate UI/UX Designer with a B.Sc. in Computer Science (First Class, 6.9 CGPA). Successfully completed a UI/UX Design course at Emax Education with a 95% grade. Experienced in creating intuitive designs for applications, including food ordering and taxi apps, using tools like Figma. Skilled in HTML5, CSS, JavaScript, jQuery, and Bootstrap. Dedicated to delivering seamless user experiences through innovative design solutions.</p>
    </div>
</div>

<!-- Skills Section -->
<div class="skills">
    <div class="container">
        <h2 class="s1">Skills</h2>
        <div class="skills">
            <div>
                <label class="s1">HTML5</label>
                <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">90%</div>
                </div>
            </div>
            <div>
                <label class="s1">CSS</label>
                <div class="progress">
                    <div class="progress-bar bg-success" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                </div>
            </div>
            <div>
                <label class="s1">JavaScript</label>
                <div class="progress">
                    <div class="progress-bar bg-success" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                </div>
            </div>
            <div>
                <label class="s1">Bootstrap</label>
                <div class="progress">
                    <div class="progress-bar bg-success" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                </div>
            </div>
            <div>
                <label class="s1">jquery</label>
                <div class="progress">
                    <div class="progress-bar bg-success" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Projects Section -->
<div class="section" id="projects">
    <div class="container">
        <h2 class="s1">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">figma taxie app</h5>
                        <p class="card-text">The taxi app design in Figma is a user-friendly, modern, and visually appealing interface tailored for seamless ride-booking experiences. It follows a clean and intuitive layout with a focus on usability, accessibility, and functionality. Here's a breakdown of its key components:</p>
                        <a href="#" class="clickbox" >View Project</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">My website</h5>
                        <p class="card-text">This website is designed to showcase my skills and expertise as a UI/UX designer</p>
                        <a href="#" class="clickbox" >View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Contact Section -->

<div class="form-container">
    <h2>Contact Me</h2>
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Your Name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" placeholder="Your Message" required></textarea>

      <button class="clickbox">Send</button>
    </form>
  </div>



<!-- Footer -->
<footer>
    <p>&copy; 2025 Jenish. All rights reserved.
</footer>
</body>
</html>
