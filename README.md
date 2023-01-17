# tindog
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;900&family=Ubuntu:wght@300;400;700&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="css/styles.css">
</head>

<body>

  <section id="title">
    <div class="container-fluid">
    <!-- Nav Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" href="">Tindog</a>
       <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
          <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#pricing">Pricing</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
          </li>
      </ul>
   </div>
  </nav>



    <!-- Title -->
     <div class="row">
      <div class="col-lg-6 col-md-12">
        <h1 class="big-heading" >Meet new and interesting dogs nearby. </h1>
        <button type="button" class="btn btn-dark btn-lg download-button"><i class="bi bi-apple"></i> Download</button>
        <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="bi bi-google-play"></i> Download</button>
      </div>
     
    <div class="col-lg-6 image-container">
      <img class="title-image"src="images/iphone6.png" alt="iphone-mockup">
    </div>
  </div>

  </section>


  <!-- Features -->

  <section id="features">

    <div class="row"> 

    <div class="feature-box col-lg-4"> 
      <i class="icon bi bi-check-circle-fill fs-1"></i>
      <h3 class="feature-title">Easy to use.</h3>
      <p>So easy to use, even your dog could do it.</p>
    </div>
  
    <div class="feature-box col-lg-4"> 
      <i class="icon bi bi-bullseye fs-1"></i>
    <h3 class="feature-title">Elite Clientele</h3>
    <p>We have all the dogs, the greatest dogs.</p>
    </div>
    
    <div class="feature-box col-lg-4"> 
      <i class="icon bi bi-heart-fill fs-1"></i>
    <h3 class="feature-title">Guaranteed to work.</h3>
    <p>Find the love of your dog's life or your money back.</p>
    </div>
  </div>
    

  </section>


  <!-- Testimonials -->

  <section id="testimonials">
    
    <div id="carouselExample" class="carousel slide" data-ride="false;">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
    <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
    <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
    <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
    <em>Beverly, Illinois</em>
        </div>
        
      </div>
      <button class="carousel-control-prev" href="#testimontial-carousel" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" href="#testimontial-carousel"  type="button" data-bs-target="#carouselExample" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-4">

    <div class="pricing-col">
    <div class="card">
      <div class="card-header">
        <h3>Chihuahua</h3>
      </div>
       <div class="card-body">
        <h2 class="price-text">Free</h2>
        <p>5 Matches Per Day</p>
        <p>10 Messages Per Day</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
      </div>
  </div>
</div>

  <div class="pricing-col">
  <div class="card">
    <div class="card-header">
      <h3>Labrador</h3>
    </div>
     <div class="card-body">
      <h2 class="price-text">$49 / mo</h2>
      <p>Unlimited Matches</p>
      <p>Unlimited Messages</p>
      <p>Unlimited App Usage</p>
      <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
    </div>
</div>
</div>

<div class="pricing-col"> 
<div class="card">
  <div class="card-header">
    <h3>Mastiff</h3>
  </div>
   <div class="card-body">
    <h2 class="price-text">$99 / mo</h2>
    <p>Pirority Listing</p>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>

  </div>
</div>
</div>

</div>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button type="button" class="btn btn-dark btn-lg download-button"><i class="bi bi-apple"></i> Download</button>
    <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="bi bi-google-play"></i> Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <i class="social-icon bi bi-twitter"></i>
    <i class="social-icon bi bi-facebook"></i>
    <i class="social-icon bi bi-instagram"></i>
    <i class="social-icon bi bi-envelope-fill"></i>
    <p>© Copyright TinDog</p>

  </footer>


</body>

</html>
