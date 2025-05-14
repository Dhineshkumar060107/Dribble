# Project Responsive Web Design using Bootstrap
## Date:14/05/2025

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
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home - DK Pharmaceutical Company</title>
  
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body style="background-color: rgb(247, 248, 247);">
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#"> DK Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active"><a class="nav-link" href="web.html">HOME</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">ABOUT</a></li>
        <li class="nav-item"><a class="nav-link" href="product.html">PRODUCTS</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">CONTACT</a></li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#">LOGIN</a></li>
        <li class="nav-item"><a class="nav-link" href="#">REGISTER</a></li>
      </ul>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to DK Pharmaceutical Company</h1>
        <p>Welcome to Pharmaceutical Company, your trusted source for high-quality pharmaceutical products...</p>
        <p>We offer a wide range of prescription and over-the-counter medications to meet your healthcare needs...</p>
        <p>In addition to medications, we also carry a variety of healthcare products and accessories...</p>
        <p>Thank you for choosing us. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="pharm.jpg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2025 DK Pharmaceutical Company. All rights reserved. BY DhineshKumar.L (212224230066)</p>
  </footer>

  <!-- Scripts -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ABOUT DK Pharmaceutical Company</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body background="image/a.jpg" style="background-repeat: no-repeat; background-size: cover;">
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">DK Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item"><a class="nav-link" href="home.html">HOME</a></li>
        <li class="nav-item active"><a class="nav-link" href="about.html">ABOUT</a></li>
        <li class="nav-item"><a class="nav-link" href="product.html">PRODUCTS</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">CONTACT</a></li>
      </ul>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container mt-5">
    <h1>ABOUT DK Pharmaceutical Company</h1>
    <div id="vision">
      <h2>Vision</h2>
      <p>To be a leading provider of innovative healthcare solutions that improve quality of life globally.</p>
    </div>
    <div id="mission">
      <h2>Mission</h2>
      <p>To develop and deliver safe, effective, and affordable medications that meet healthcare needs.</p>
    </div>
    <div id="values">
      <h2>Values</h2>
      <ul>
        <li>→ Quality</li>
        <li>→ Integrity</li>
        <li>→ Innovation</li>
        <li>→ Customer Focus</li>
        <li>→ Teamwork</li>
      </ul>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-2 mt-2">
    <p>&copy; 2025 DK Pharmaceutical Company. All rights reserved. BY DhineshKumar.L (212224230066)</p>
  </footer>

  <!-- Scripts -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Products - Pharmaceutical Company</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body background="a.png" style="background-repeat: no-repeat; background-size: cover;">
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">DK Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item"><a class="nav-link" href="home.html">HOME</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">ABOUT</a></li>
        <li class="nav-item active"><a class="nav-link" href="product.html">PRODUCTS</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">CONTACT</a></li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#">LOGIN</a></li>
        <li class="nav-item"><a class="nav-link" href="#">REGISTER</a></li>
      </ul>
    </div>
  </nav>

  <!-- Products -->
  <div class="container mt-5">
    <h1>OUR PRODUCTS</h1>
    <div class="card-deck">
      <div class="card">
        <img src="pharm1.jpg" class="card-img-top" alt="Product 1">
        <div class="card-body">
          <h5 class="card-title">PRODUCT 1</h5>
          <p class="card-text">Generic pharmaceuticals and medical consumables.</p>
          <a href="#" class="btn btn-primary">Buy Now</a>
        </div>
      </div>
      <div class="card">
        <img src="pharm2.jpeg" class="card-img-top" alt="Product 2">
        <div class="card-body">
          <h5 class="card-title">PRODUCT 2</h5>
          <p class="card-text">Thiamine, Benztrophine, Pyridoxine Tablets.</p>
          <a href="#" class="btn btn-primary">Buy Now</a>
        </div>
      </div>
      <div class="card">
        <img src="pharm3.webp" class="card-img-top" alt="Product 3">
        <div class="card-body">
          <h5 class="card-title">PRODUCT 3</h5>
          <p class="card-text">Terbinafine Tablets.</p>
          <a href="#" class="btn btn-primary">Buy Now</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-2 mt-2">
    <p>&copy; 2025 DK Pharmaceutical Company. All rights reserved. BY DhineshKumar.L (212224230066)</p>
  </footer>

  <!-- Scripts -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Us - DK Pharmaceutical Company</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">DK Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item"><a class="nav-link" href="home.html">HOME</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">ABOUT</a></li>
        <li class="nav-item"><a class="nav-link" href="product.html">PRODUCTS</a></li>
        <li class="nav-item active"><a class="nav-link" href="contact.html">CONTACT</a></li>
      </ul>
    </div>
  </nav>

  <!-- Contact Form -->
  <div class="container mt-5">
    <h1>CONTACT US</h1>
    <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
    <form>
      <div class="form-group">
        <label for="name">YOUR NAME</label>
        <input type="text" class="form-control" id="name" placeholder="Enter your name" />
      </div>
      <div class="form-group">
        <label for="email">YOUR EMAIL</label>
        <input type="email" class="form-control" id="email" placeholder="Enter your email" />
      </div>
      <div class="form-group">
        <label for="message">MESSAGE</label>
        <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-2 mt-4">
    <p>&copy; 2025 DK Pharmaceutical Company. All rights reserved. BY DhineshKumar.L (212224230066)</p>
  </footer>

  <!-- Scripts -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```



## OUTPUT:

![alt text](<Screenshot 2025-05-14 200336.png>)
![alt text](<Screenshot 2025-05-14 200351.png>)
![alt text](<Screenshot 2025-05-14 200405.png>)
![alt text](<Screenshot 2025-05-14 200418.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
