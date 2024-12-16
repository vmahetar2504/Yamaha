# Yamaha
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yamaha</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .brand-carousel .carousel-item {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .brand-carousel img {
        max-width: 10%;
        height: auto;
        padding: 10px;
    } .contact-header {
            text-align: center;
            margin-bottom: 2rem;
        }
        .form-container {
            background-color: #f8f9fa;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .contact-details li {
            list-style-type: none;
        }
        .form-container input,
        .form-container textarea {
            border-radius: 6px;
        }
        .footer {
            background-color: #343a40;
            color: #ffffff;
            padding: 1.5rem 0;
            text-align: center;
        }
        .footer p {
            margin: 0;
            font-size: 0.9rem;
        }
        .footer .btn {
            background-color: #ffcc00;
            color: #343a40;
            border: none;
            border-radius: 20px;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .footer .btn:hover {
            background-color: #e6b800;
        }
         /* Additional styling */
         .navbar-brand {
            font-size: 1.8rem;
            font-weight: bold;
            color: red !important;
        }
        .navbar-nav .nav-link {
            color: red !important;
            font-weight: 500;
            transition: color 0.3s;
        }
        .navbar-nav .nav-link:hover {
            color: #ff4d4d !important;
        }
        .btn-custom {
            background-color: red;
            color: white;
            border: none;
            transition: background-color 0.3s;
        }
        .btn-custom:hover {
            background-color: #cc0000;
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.2);
        }
        .section-title {
            color: #0d6efd;
            text-transform: uppercase;
            font-weight: bold;
        }
</style>
</head>
<body>
<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
        <a class="navbar-brand" href="#home">YAMAHA</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#team">Our Team</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#products">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contactus">Contact Us</a>
                </li>
            </ul>
            <div class="d-flex ms-3">
                <a href="https://yamaha-login.netlify.app/" class="btn btn-custom me-2">Log in</a>
                <a href="https://yamaha-registration.netlify.app/" class="btn btn-custom">Sign Up</a>
            </div>
        </div>
    </div>
</nav>
  
  <!--new-->
  <div class="container my-5"  href="#home">
    <!-- About Section Heading -->
    <div class="text-center mb-4">
      <h1 id="about" class="display-4 fw-bold">Home</h1>
    </div>
    <!-- Image and Content Section -->
    <div class="row align-items-center">
      <!-- Image Section -->
      <div class="col-lg-6 mb-4 mb-lg-0">
        <img src=https://i.postimg.cc/ryRj6CYp/1.png class="img-fluid rounded shadow" alt="Yamaha Image">
      </div>
      <!-- Text Content -->
      <div class="col-lg-6">
        <p class="lead">
          Yamaha Motor made its initial foray into India in 1985 as a joint venture. In August 2001, it became a
          100% subsidiary of Yamaha Motor Co., Ltd., Japan (YMC). In 2008, Mitsui & Co. Ltd. entered into an
          agreement with YMC to become a joint investor in India Yamaha Motor Private Limited (IYM).
        </p>
      </div>
    </div>
  </div>
  <!--new-->
  <div class="container my-5">
      <div class="text-center mb-4">
        <h1 id="about" class="display-4 fw-bold">About</h1>
      </div>
      <div class="container mt-5">
        <div class="row gy-4">
            <!-- Vision Section -->
            <div class="col-lg-4 col-md-6 d-flex">
                <div class="card p-4 shadow-sm w-100">
                    <div class="card-body">
                        <h2 class="section-title">Vision</h2>
                        <p class="text-muted">
                            Our vision is to be the premier online destination for Yamaha motorcycle enthusiasts worldwide, providing comprehensive information, resources, and a vibrant community hub.
                        </p>
                    </div>
                </div>
            </div>
            <!-- Mission Section -->
            <div class="col-lg-4 col-md-6 d-flex">
                <div class="card p-4 shadow-sm w-100">
                    <div class="card-body">
                        <h2 class="section-title">Mission</h2>
                        <p class="text-muted">
                            Our mission is to empower Yamaha bike enthusiasts by delivering accurate, up-to-date information, insightful reviews, and engaging content. We aim to foster a community where riders can connect, learn, and share their passion for Yamaha motorcycles.
                        </p>
                    </div>
                </div>
            </div>
            <!-- Goals Section -->
            <div class="col-lg-4 col-md-12 d-flex">
                <div class="card p-4 shadow-sm w-100">
                    <div class="card-body">
                        <h2 class="section-title">Goals</h2>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item border-0 px-0">
                                <strong>1. Educational Excellence:</strong> Provide detailed guides, reviews, and comparisons to educate Yamaha bike enthusiasts on models, maintenance, and riding techniques.
                            </li>
                            <li class="list-group-item border-0 px-0">
                                <strong>2. Community Engagement:</strong> Build a robust online community where Yamaha riders can exchange knowledge, experiences, and tips.
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
<!--new-->
  <div class="container my-5">
    <!-- Our Team Heading -->
    <div class="text-center mb-4">
        <h1 id="team" class="display-4 fw-bold">Our Team</h1>
    </div>
    <!-- Team Members Section -->
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-4">
        <!-- Team Member Card 1 -->
        <div class="col">
            <div class="card h-100 shadow-sm">
                <img src=https://i.postimg.cc/tTWLgQCr/2.png class="card-img-top" alt="Motofumi Shitara">
                <div class="card-body">
                    <h5 class="card-title">Motofumi Shitara</h5>
                    <p class="card-text"><strong>Post:</strong> Chairman of India</p>
                    <p class="card-text"><strong>Degree:</strong> B.Tech</p>
                </div>
            </div>
        </div>
        <!-- Team Member Card 2 -->
        <div class="col">
            <div class="card h-100 shadow-sm">
                <img src=https://i.postimg.cc/2yxM4QWh/3.jpg class="card-img-top" alt="Hiroaki Fujita">
                <div class="card-body">
                    <h5 class="card-title">Hiroaki Fujita</h5>
                    <p class="card-text"><strong>Post:</strong> Managing Director of India</p>
                    <p class="card-text"><strong>Degree:</strong> M.Tech</p>
                </div>
            </div>
        </div>
        <!-- Team Member Card 3 -->
        <div class="col">
            <div class="card h-100 shadow-sm">
                <img src=https://i.postimg.cc/3Nhz4Sk3/4.jpg class="card-img-top" alt="Genichi Kawakami">
                <div class="card-body">
                    <h5 class="card-title">Genichi Kawakami</h5>
                    <p class="card-text"><strong>Post:</strong> President</p>
                    <p class="card-text"><strong>Degree:</strong> BCA</p>
                </div>
            </div>
        </div>
        <!-- Team Member Card 4 -->
        <div class="col">
            <div class="card h-100 shadow-sm">
                <img src=https://i.postimg.cc/NG83qcnF/5.jpg class="card-img-top" alt="Hiroyuki Yanagi">
                <div class="card-body">
                    <h5 class="card-title">Hiroyuki Yanagi</h5>
                    <p class="card-text"><strong>Post:</strong> Representative Director</p>
                    <p class="card-text"><strong>Degree:</strong> MCA</p>
                </div>
            </div>
        </div>
    </div>
</div>
<!--new-->
<div class="container my-5">
  <!-- Products Section Heading -->
  <div class="text-center mb-4">
      <h1 id="products" class="display-4 fw-bold">Our Products</h1>
  </div>
  <!-- Products Grid -->
  <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <!-- Product Card 1 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/C14pNpTR/6.jpg class="card-img-top" alt="Yamaha MT15 V2">
              <div class="card-body">
                  <h5 class="card-title">Yamaha MT15 V2</h5>
                  <p class="card-text"><del>MRP: ₹1.74 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.68 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 2 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/7ZSs7My6/7.png class="card-img-top" alt="Yamaha R15 V4">
              <div class="card-body">
                  <h5 class="card-title">Yamaha R15 V4</h5>
                  <p class="card-text"><del>MRP: ₹1.82 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.98 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 3 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/MHjbwq6T/8.jpg class="card-img-top" alt="Yamaha R15S">
              <div class="card-body">
                  <h5 class="card-title">Yamaha R15S</h5>
                  <p class="card-text"><del>MRP: ₹1.66 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.48 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 4 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/JhkktPw6/9.webp class="card-img-top" alt="Yamaha FZS-FI V3">
              <div class="card-body">
                  <h5 class="card-title">Yamaha FZS-FI V3</h5>
                  <p class="card-text"><del>MRP: ₹1.23 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.22 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 5 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/yYGx9cyw/10.jpg class="card-img-top" alt="Yamaha FZS-FI V4">
              <div class="card-body">
                  <h5 class="card-title">Yamaha FZS-FI V4</h5>
                  <p class="card-text"><del>MRP: ₹1.39 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.30 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 6 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/N0pW971X/11.jpg class="card-img-top" alt="Yamaha MT 03">
              <div class="card-body">
                  <h5 class="card-title">Yamaha MT 03</h5>
                  <p class="card-text"><del>MRP: ₹4.23 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹4.04 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 7 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/mrnWpyts/12.jpg class="card-img-top" alt="Yamaha R3">
              <div class="card-body">
                  <h5 class="card-title">Yamaha R3</h5>
                  <p class="card-text"><del>MRP: ₹4.70 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹4.64 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
      <!-- Product Card 8 -->
      <div class="col">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/Jn3KH1w2/13.jpg class="card-img-top" alt="Yamaha FZ 25">
              <div class="card-body">
                  <h5 class="card-title">Yamaha FZ 25</h5>
                  <p class="card-text"><del>MRP: ₹1.23 Lakh</del></p>
                  <p class="card-text text-success">Price: ₹1.20 Lakh</p>
                  <button class="btn btn-primary">Buy Now</button>
              </div>
          </div>
      </div>
  </div>
</div>
<!--new-->
<div class="container py-5">
  <!-- Gallery Header -->
  <div class="text-center mb-4">
      <h1 class="display-4 fw-bold">Gallery</h1>
      <p class="lead text-muted">Discover highlights from Yamaha's world of innovation, events, and top models.</p>
  </div>
  <!-- Responsive Gallery Grid -->
  <div class="row g-4">
      <!-- Image 1 -->
      <div class="col-12 col-sm-6 col-md-4">
          <div class="card h-100 shadow-sm">
              <a href="#imageModal1" data-bs-toggle="modal">
                  <img src=https://i.postimg.cc/NGp73CQm/14.jpg class="card-img-top img-fluid" alt="Gallery Image 1">
              </a>
          </div>
      </div>
      <!-- Image 2 -->
      <div class="col-12 col-sm-6 col-md-4">
          <div class="card h-100 shadow-sm">
              <a href="#imageModal2" data-bs-toggle="modal">
                  <img src=https://i.postimg.cc/NG9mnsPq/15.jpg class="card-img-top img-fluid" alt="Gallery Image 2">
              </a>
          </div>
      </div>
      <!-- Image 3 -->
      <div class="col-12 col-sm-6 col-md-4">
          <div class="card h-100 shadow-sm">
              <a href="#imageModal3" data-bs-toggle="modal">
                  <img src=https://i.postimg.cc/vHvBqCMw/16.jpg class="card-img-top img-fluid" alt="Gallery Image 3">
              </a>
          </div>
      </div>
      <!-- Image 4 -->
      <div class="col-12 col-sm-6 col-md-4">
          <div class="card h-100 shadow-sm">
              <a href="#imageModal4" data-bs-toggle="modal">
                  <img src=https://i.postimg.cc/W4Gfgmg8/17.jpg class="card-img-top img-fluid" alt="Gallery Image 4">
              </a>
          </div>
      </div>
      <!-- Image 5 -->
      <div class="col-12 col-sm-6 col-md-4">
          <div class="card h-100 shadow-sm">
              <a href="#imageModal5" data-bs-toggle="modal">
                  <img src=https://i.postimg.cc/bYCBYzQw/18.jpg class="card-img-top img-fluid" alt="Gallery Image 5">
              </a>
          </div>
      </div>
  </div>
</div>
<!-- Modal Template for Images -->
<div class="modal fade" id="imageModal1" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
          <img src="E:/pictures/14.jpg" class="img-fluid" alt="Gallery Image 1">
      </div>
  </div>
</div>
<div class="modal fade" id="imageModal2" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
          <img src="E:/pictures/15.jpg" class="img-fluid" alt="Gallery Image 2">
      </div>
  </div>
</div>
<div class="modal fade" id="imageModal3" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
          <img src="E:/pictures/16.jpg" class="img-fluid" alt="Gallery Image 3">
      </div>
  </div>
</div>
<div class="modal fade" id="imageModal4" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
          <img src="E:/pictures/17.jpg" class="img-fluid" alt="Gallery Image 4">
      </div>
  </div>
</div>
<div class="modal fade" id="imageModal5" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
          <img src="E:/pictures/18.jpg" class="img-fluid" alt="Gallery Image 5">
      </div>
  </div>
</div>
<!--new-->
<div class="container py-5">
  <!-- Reviews Header -->
  <div class="text-center mb-4">
      <h1 class="display-4 fw-bold">Customer Reviews</h1>
      <p class="lead text-muted">Hear what our customers have to say about their Yamaha experience.</p>
  </div>
  <!-- Responsive Review Cards -->
  <div class="row g-4">
      <!-- Review 1 -->
      <div class="col-12 col-sm-6 col-lg-4">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/LsJzTpJN/19.jpg class="card-img-top img-fluid" alt="Customer 1 Review">
              <div class="card-body">
                  <h5 class="card-title">Chauhan Chirag</h5>
                  <p class="card-text">
                      Yamaha offers a wide range of motorcycles catering to different riding styles and preferences. From entry-level bikes like the Yamaha YZF-R3 to high-end models like the Yamaha YZF-R1M, there's something for every type of rider.
                  </p>
              </div>
              <div class="card-footer text-muted">
                  <small>Submitted on: November 1, 2024</small>
              </div>
          </div>
      </div>
      <!-- Review 2 -->
      <div class="col-12 col-sm-6 col-lg-4">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/SN9JQxw6/20.jpg class="card-img-top img-fluid" alt="Customer 2 Review">
              <div class="card-body">
                  <h5 class="card-title">Rathod Krunal</h5>
                  <p class="card-text">
                      Yamaha motorcycles are known for their reliable performance and innovative design. For commuting or adventure, bikes like the Yamaha MT series provide comfort and versatility. Yamaha bikes are praised for their durability, powerful engines, and advanced technology.
                  </p>
              </div>
              <div class="card-footer text-muted">
                  <small>Submitted on: October 25, 2024</small>
              </div>
          </div>
      </div>
      <!-- Review 3 -->
      <div class="col-12 col-sm-6 col-lg-4">
          <div class="card h-100 shadow-sm">
              <img src=https://i.postimg.cc/TYQ3QN5s/21.jpg class="card-img-top img-fluid" alt="Customer 3 Review">
              <div class="card-body">
                  <h5 class="card-title">Mahetar Arman</h5>
                  <p class="card-text">
                      Yamaha bikes are known for their strong performance across different categories. Whether you're looking at their sport bikes like the YZF-R series or their adventure bikes like the Super Ténéré, Yamaha typically delivers good power, handling, and acceleration.
                  </p>
              </div>
              <div class="card-footer text-muted">
                  <small>Submitted on: October 15, 2024</small>
              </div>
          </div>
      </div>
      <!-- Additional Content -->
      <div class="col-12 mt-4">
          <div class="alert alert-info text-center" role="alert">
              <h5>Share Your Experience!</h5>
              <p>We value your feedback. Let us know what you think about Yamaha products!</p>
              <button class="btn btn-primary">Submit Your Review</button>
          </div>
      </div>
  </div>
</div>
<!--new-->
<div class="container py-5">
  <!-- Section Header -->
  <div class="text-center mb-4">
      <h1 class="display-5 fw-bold">Our Brands</h1>
      <p class="lead text-muted">Explore our wide range of trusted brands bringing you the best in performance and quality.</p>
  </div>
  <!-- Bootstrap Carousel -->
  <marquee behavior direction="left">
  <div id="brandCarousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner brand-carousel">
          <!-- Slide 1 -->
          <div class="carousel-item active">
              <div class="d-flex justify-content-center">
                  <img src=https://i.postimg.cc/HxmqqHf9/22.jpg class="img-fluid rounded mx-2" alt="Brand 1">
                  <img src=https://i.postimg.cc/fRwBQyLL/23.png class="img-fluid rounded mx-2" alt="Brand 2">
                  <img src=https://i.postimg.cc/d1KhgksN/24.png class="img-fluid rounded mx-2" alt="Brand 3">
                  <img src=https://i.postimg.cc/YCHqrKKj/25.jpg class="img-fluid rounded mx-2" alt="Brand 4">
                  <img src=https://i.postimg.cc/x83pLzCw/26.png class="img-fluid rounded mx-2" alt="Brand 5">
                  <img src=https://i.postimg.cc/zvTv7JYZ/27.png class="img-fluid rounded mx-2" alt="Brand 6">
              </div>
          </div>
          <!-- Slide 2 -->
          <div class="carousel-item">
              <div class="d-flex justify-content-center">
                 
              </div>
          </div>
      </div>
      </marquee>
      <!-- Carousel Controls -->
      <button class="carousel-control-prev" type="button" data-bs-target="#brandCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#brandCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
      </button>
  </div>
  <!-- Additional Content -->
  <div class="mt-5 text-center">
      <p>We are proud to collaborate with these industry-leading brands, providing products that consistently set the standard for quality and innovation. Check out more about each brand below:</p>
      <button class="btn btn-primary">Explore Our Brands</button>
  </div>
</div>
<!--new-->
<div class="container py-5">
  <!-- Section Header -->
  <div class="contact-header">
      <h1 id="contactus">Contact Us</h1>
      <p class="text-muted">We’d love to hear from you! Get in touch with us through any of our offices or drop a message below.</p>
  </div>
  <!-- Contact Information -->
  <div class="row mb-4">
      <div class="col-md-4">
          <div class="form-container">
              <h4>Head Office:</h4>
              <p class="contact-details">
                  <li>Address: 85-88, Harivilla Bunglow, Nr. Silver Star Mall, Gota Road, Ahmedabad - 382481</li>
              </p>
          </div>
      </div>
      <div class="col-md-4">
          <div class="form-container">
              <h4>Branch 1:</h4>
              <p class="contact-details">
                  <li>Address: Desai Nagar, Opp. Chitra Petrol Pump, Bhavnagar, Gujarat, 364003</li>
              </p>
          </div>
      </div>
      <div class="col-md-4">
          <div class="form-container">
              <h4>Branch 2:</h4>
              <p class="contact-details">
                  <li>Address: Plot No. 8/4, Udhyognagar, Viththalwadi, Bhavnagar, Gujarat, 364001</li>
              </p>
          </div>
      </div>
  </div>
  <!-- Contact Form -->
  <div class="row">
      <div class="col-lg-8 mx-auto">
          <div class="form-container">
              <form>
                  <div class="mb-3">
                      <label for="name" class="form-label">Enter Your Name:</label>
                      <input type="text" class="form-control" id="name" name="name" placeholder="Your name.." required>
                  </div>
                  <div class="mb-3">
                      <label for="phone" class="form-label">Contact No:</label>
                      <input type="tel" class="form-control" id="phone" name="phone" placeholder="Your phone number.." required>
                  </div>
                  <div class="mb-3">
                      <label for="email" class="form-label">Email ID:</label>
                      <input type="email" class="form-control" id="email" name="email" placeholder="Your email.." required>
                  </div>
                  <div class="mb-3">
                      <label for="message" class="form-label">Message:</label>
                      <textarea class="form-control" id="message" name="message" rows="4" placeholder="Write something.." required></textarea>
                  </div>
                  <div class="text-center">
                      <button type="submit" class="btn btn-primary">Send</button>
                  </div>
              </form>
          </div>
      </div>
  </div>
</div>
<!--new-->
 <!-- Footer Section -->
 <div class="footer">
  <div class="container">
      <p>@ All Rights Reserved By YAMAHA | Design & Developed by Mahetar Vahid</p>
  </div>
</div>
<!-- JavaScript -->
<script>
      alert("Yamaha webpage designed & developed by V.J.Mahetar!");
</script>
  <!-- Bootstrap JS (Optional, for collapsible nav) -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
