# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bootstrap Webpage Example</title>
  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">MySite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#hero">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="py-5 text-center bg-light" id="hero">
    <div class="container">
      <h1 class="display-4">Welcome to MySite</h1>
      <p class="lead">This is a simple and responsive Bootstrap webpage example.</p>
      <a href="#features" class="btn btn-primary btn-lg mt-3">Learn More</a>
    </div>
  </section>

  <!-- Features Section -->
  <section class="py-5" id="features">
    <div class="container">
      <h2 class="mb-4 text-center">Features</h2>
      <div class="row text-center">
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Responsive Design</h5>
              <p class="card-text">Looks great on all devices, from mobile to desktop.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Easy to Use</h5>
              <p class="card-text">Built with Bootstrap components and utilities.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Customizable</h5>
              <p class="card-text">Easily tweak the layout and styling to suit your needs.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="py-5 bg-light" id="about">
    <div class="container">
      <h2 class="mb-4 text-center">About Us</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          <p>
            MySite is a demo web project showcasing how you can create beautiful and functional web layouts using Bootstrap's grid and components. This page is fully responsive and mobile-friendly.
          </p>
        </div>
        <div class="col-md-6">
          <img src="https://via.placeholder.com/500x300" class="img-fluid rounded" alt="About image">
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p class="mb-0">&copy; 2025 MySite. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle (includes Popper) -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
## OUTPUT:
<img width="1581" height="566" alt="Screenshot 2025-10-17 105011" src="https://github.com/user-attachments/assets/a1ab874b-6537-40a0-b764-17ea7f2ecc7a" />
<img width="1816" height="336" alt="Screenshot 2025-10-17 105040" src="https://github.com/user-attachments/assets/d524a79f-e318-4372-bbe0-ad1e6fa39d46" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
