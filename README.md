# Project Responsive Web Design using Bootstrap
## Date:30.05.2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>RCB Clone</title>

  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet"/>

  <style>
    body {
      font-family: Arial, sans-serif;
    }

    /* Hero Section */
    .hero {
      height: 80vh;
      background: url("rcb_bg.png");
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .hero h1 {
      font-size: 4rem;
      font-weight: bold;
    }

    .hero p {
      font-size: 1.5rem;
    }

    footer a {
      text-decoration: none;
    }

    .card-img-top {
      height: 200px;
      object-fit: cover;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="logo.png" height="40" alt="RCB Logo" />
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Team</a></li>
          <li class="nav-item"><a class="nav-link" href="#">News</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Schedule</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Videos</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div>
      <h1>Play Bold</h1>
      <p>Welcome to the Official RCB Website</p>
      <a href="#" class="btn btn-danger">Explore Now</a>
    </div>
  </section>

  <!-- News Section -->
  <section class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4 text-center">Latest News</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="Screenshot 2025-05-30 092557.png" class="card-img-top" alt="News 1">
            <div class="card-body">
              <h5 class="card-title">RCB Wins Again!</h5>
              <p class="card-text">A thrilling match against their rivals leads to another victory.</p>
              <a href="#" class="btn btn-outline-danger">Read More</a>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="Screenshot 2025-05-30 092651.png" class="card-img-top" alt="News 2">
            <div class="card-body">
              <h5 class="card-title">Player Spotlight</h5>
              <p class="card-text">A look into the amazing performance of our star player.</p>
              <a href="#" class="btn btn-outline-danger">Read More</a>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="Screenshot 2025-05-30 092658.png" class="card-img-top" alt="News 3">
            <div class="card-body">
              <h5 class="card-title">Behind the Scenes</h5>
              <p class="card-text">Exclusive training sessions and team bonding moments.</p>
              <a href="#" class="btn btn-outline-danger">Read More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Royal Challengers Bangalore. All Rights Reserved.</p>
    <div>
      <a href="#" class="text-white me-2">Facebook</a> |
      <a href="#" class="text-white ms-2">Instagram</a>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // JS Interactions (if needed)
    console.log("RCB Clone Website Loaded!");
  </script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-05-30 094104.png>)

![alt text](<Screenshot 2025-05-30 094056.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
