# Portfolio-using-bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gokulnath | Portfolio</title>

  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  >
</head>
<body class="bg-light text-dark">

  <!-- Header -->
  <header class="bg-dark text-white text-center py-5">
    <h1 class="fw-bold">V. Gokulnath</h1>
    <p class="lead">Aspiring Software Developer</p>
  </header>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-secondary sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Portfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- About -->
  <section id="about" class="container py-5">
    <h2 class="text-primary mb-3">About Me</h2>
    <p>
      I am a passionate Computer Engineering student interested in software
      development, problem-solving, and building real-world projects.
      Currently preparing for internships and placements.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills" class="container py-5">
    <h2 class="text-primary mb-4">Skills</h2>

    <div class="d-flex flex-wrap gap-2">
      <span class="badge bg-info text-dark p-2">HTML</span>
      <span class="badge bg-info text-dark p-2">CSS</span>
      <span class="badge bg-info text-dark p-2">Java</span>
      <span class="badge bg-info text-dark p-2">Python</span>
      <span class="badge bg-info text-dark p-2">Data Structures</span>
      <span class="badge bg-info text-dark p-2">Problem Solving</span>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="container py-5">
    <h2 class="text-primary mb-4">Projects</h2>

    <div class="card mb-3 border-start border-4 border-info shadow-sm">
      <div class="card-body">
        <h5 class="card-title">To-Do List Application</h5>
        <p class="card-text">
          Simple task manager built using HTML and CSS.
        </p>
      </div>
    </div>

    <div class="card mb-3 border-start border-4 border-info shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Resume Generator Bot</h5>
        <p class="card-text">
          Automation project created using UiPath.
        </p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="container py-5">
    <h2 class="text-primary mb-3">Contact Me</h2>
    <p><strong>Email:</strong> gokulnath5607@gmail.com</p>
    <p><strong>GitHub:</strong> github.com/Gokulnath-07</p>
    <p><strong>LinkedIn:</strong> linkedin.com/in/gokulnath</p>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">© 2025 V. Gokulnath | All Rights Reserved</p>
  </footer>

  <!-- Bootstrap JS -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
  </script>

</body>
</html>
