# newone<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
</head>
<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
    }

    .hero {
        background: #007bff;
        color: #fff;
        padding: 50px 20px;
        text-align: center;
    }

    .hero h1 {
        font-size: 3rem;
    }

    .section {
        padding: 40px 20px;
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

    footer a {
        color: #ffc107;
    }
</style>
</head>

<body>
<!-- Hero Section -->
<div class="hero">
    <h1>Jenish</h1>
    <p>Web Developer | Designer</p>
</div>

<!-- About Section -->
<div class="section" id="about">
    <div class="container">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate web developer with experience in creating responsive and user-friendly websites. I love coding and bringing designs to life.</p>
    </div>
</div>

<!-- Skills Section -->
<div class="section bg-light" id="skills">
    <div class="container">
        <h2>Skills</h2>
        <div class="skills">
            <div>
                <label>HTML</label>
                <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">90%</div>
                </div>
            </div>
            <div>
                <label>CSS</label>
                <div class="progress">
                    <div class="progress-bar bg-success" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                </div>
            </div>
            <div>
                <label>JavaScript</label>
                <div class="progress">
                    <div class="progress-bar bg-warning" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">75%</div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Projects Section -->
<div class="section" id="projects">
    <div class="container">
        <h2>Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Project 1</h5>
                        <p class="card-text">A brief description of the project.</p>
                        <a href="#" class="btn btn-primary">View Project</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Project 2</h5>
                        <p class="card-text">A brief description of the project.</p>
                        <a href="#" class="btn btn-primary">View Project</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Project 3</h5>
                        <p class="card-text">A brief description of the project.</p>
                        <a href="#" class="btn btn-primary">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Contact Section -->
<div class="section bg-light" id="contact">
    <div class="container">
        <h2>Contact</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
    </div>
</div>

<!-- Footer -->
<footer>
    <p>&copy; 2025 Jenish. All rights reserved. | <a href="#">Privacy Policy<g/a></p>
</footer>
</body>
</html>
