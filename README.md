# Portfolio-using-bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gokulnath | Software Developer</title>

  <!-- Bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
    }

    .section-title {
      font-weight: 700;
      position: relative;
      display: inline-block;
    }

    .section-title::after {
      content: "";
      display: block;
      width: 60%;
      height: 4px;
      background: #0dcaf0;
      margin-top: 8px;
    }

    .badge-custom {
      font-size: 0.9rem;
      padding: 10px 15px;
      border-radius: 50px;
      background-color: #e3f2fd;
      color: #000;
    }

    .project-card {
      transition: 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }

    footer {
      background-color: #111;
    }

    .btn-custom {
      background-color: #0dcaf0;
      color: #000;
      font-weight: 600;
    }

    .btn-custom:hover {
      background-color: #0bb6d4;
    }
  </style>
</head>

<body>

  <header class="text-white text-center py-5">
    <div class="container">
      <h1 class="fw-bold display-4">V. Gokulnath</h1>
      <p class="lead">Pre-Final Year B.Tech IT Student | Aspiring Software Developer</p>
      <a href="#contact" class="btn btn-custom mt-3">Contact Me</a>
    </div>
  </header>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">My Portfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#internship">Internship</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section id="about" class="container py-5">
    <h2 class="section-title text-primary">About Me</h2>
    <p class="mt-3">
      Motivated B.Tech IT student with strong foundation in Java, Data Structures, 
      and Software Development. Passionate about problem-solving, automation, 
      robotics, and building real-world applications. Currently seeking internship 
      and entry-level opportunities to grow professionally.
    </p>
  </section>

  <section id="education" class="bg-light py-5">
    <div class="container">
      <h2 class="section-title text-primary">Education</h2>
      <div class="mt-4">
        <h5>B.Tech - Information Technology</h5>
        <p>K.S. Rangasamy College of Technology (Anna University)<br>
        CGPA: 7.83/10 | 2023 – 2027</p>

        <h5>12th Standard</h5>
        <p>Vishweshvaraiyah Matric Hr. Sec School<br>
        Percentage: 78%</p>
      </div>
    </div>
  </section>

  <section id="skills" class="container py-5">
    <h2 class="section-title text-primary">Technical Skills</h2>

    <div class="d-flex flex-wrap gap-3 mt-4">
      <span class="badge-custom">Java</span>
      <span class="badge-custom">C</span>
      <span class="badge-custom">C#</span>
      <span class="badge-custom">Data Structures</span>
      <span class="badge-custom">HTML & CSS</span>
      <span class="badge-custom">UiPath RPA</span>
      <span class="badge-custom">Automation</span>
      <span class="badge-custom">Embedded Systems</span>
      <span class="badge-custom">Problem Solving</span>
    </div>
  </section>

  <section id="internship" class="bg-light py-5">
    <div class="container">
      <h2 class="section-title text-primary">Internship</h2>
      <div class="mt-4">
        <h5>IT Intern – Bornfire Innovations Pvt Ltd</h5>
        <p>
          Completed 15-day internship assisting in IT operations, gaining exposure to 
          Web Development and corporate workflow practices. Recognized for consistency 
          and dedication.
        </p>
<a href="C:\Users\User\Downloads\intern.jpg" 
   style="text-decoration: none; 
          padding: 8px 15px; 
          border-radius: 10px; 
          background-color: #4CAF50; 
          color: white;
          display: inline-block;
          target: _self">
   Certification
</a>      </div>
    </div>
    
  </section>

  <section id="projects" class="container py-5">
    <h2 class="section-title text-primary">Projects</h2>

    <div class="row mt-4">

      <div class="col-md-6 mb-4">
        <div class="card project-card shadow-sm">
          <div class="card-body">
            <h5 class="card-title">TYDRON – Autonomous Floor Cleaning Robot</h5>
            <p>
              Designed and built an intelligent robot with obstacle avoidance 
              and autonomous navigation. Finalist at National Level Hackathon 
              (SRM IST Chennai).
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-6 mb-4">
        <div class="card project-card shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Resume Generator Bot – UiPath</h5>
            <p>
              Developed RPA bot to automate resume creation by extracting 
              and processing user data into formatted templates.
            </p>
          </div>
        </div>
      </div>

    </div>
  </section>

  <section id="contact" class="bg-dark text-white py-5">
    <div class="container">
      <h2 class="section-title text-info">Contact Me</h2>
      <p class="mt-4">
        📧 Email: gokulnath5607@gmail.com <br>
        📞 Phone: +91 90422 15607 <br>
        💻 GitHub: github.com/Gokulnath-07 <br>
        🔗 LinkedIn: linkedin.com/in/gokulnath
      </p>
    </div>
  </section>

  <footer class="text-white text-center py-3">
    <p class="mb-0">© 2026 V. Gokulnath | Designed with Bootstrap 5</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

  
