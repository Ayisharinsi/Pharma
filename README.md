# Project Responsive Web Design using Bootstrap
## Date:06/05/24

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Company</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pharmaceutical Company</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Products
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Medicines</a>
              <a class="dropdown-item" href="#">Vaccines</a>
              <a class="dropdown-item" href="#">Supplements</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Content Sections -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <h2>Welcome to Our Pharmaceutical Company</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod velit sit amet justo sodales, ut interdum nunc posuere. Donec et leo a justo vulputate vehicula.</p>
      </div>
      <div class="col-md-6">
        <img src="aysh/pharapp/static/pharmacy.avif" alt="Pharmaceutical Company" height="300" width="'400">
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-md-4">
        <h3>Our Products</h3>
        <p>Explore our range of high-quality pharmaceutical products.Our pharmacy offers a diverse selection of medicines to address various health concerns.</p>
        <a href="#" class="btn btn-primary">View Products</a>
      </div>
      <div class="col-md-4">
        <h3>Responsibility</h3>
        <p>Dispensing medications accurately and safely, including interpreting prescriptions and providing dosage instructions.
         </p>
        <a href="#" class="btn btn-primary">Read more</a>
      </div>
      <div class="col-md-4">
        <h3>Contact Us</h3>
        <p>Get in touch with us for any inquiries or feedback.</p>
        <a href="#" class="btn btn-primary">Contact Us</a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 Pharmaceutical Company. BY AYISHA RINSI K(212223040022).</p>
    </div>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](project.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
