# longmonga
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
     <style>        
     .d-flex{
            color: white;
        }
        .d-flex>a{
            padding-right: 40px;
        }
        b{
            color: white;
            margin-left: 40px 20px;
            padding: auto;
        }
        .container-fluid>.navbar-brand{
            margin-left: 40px;
        }
        a:hover>b{
          background-color: green;
        }
      * {
          box-sizing: border-box;
          margin: 0;
          padding: 0;
      }
      .hinh{
          width: 90%;
          height: 500px;
          margin: 10px;
      }
      h4{
          color: gray;
          text-align: center;
          font-weight: normal;
      }
      .card {
          text-align: center;
          margin-top: 30px;
      }
      .h-100 {
          padding: 0;
          margin: 0;
          position: absolute;
          bottom: 45%;
      }
      .card-text {
          color: gray;
      }
      h6 {
          color: black ;
      }
      .btn{
          margin-top: 30px;
          background-color: green;
      }
      .card-img{
        height: 300px;
      }
      h1{
        color: white;
        margin-top: 100px;
      }
      h1>.card-title{
        font-size: 50px;
        font-weight: bold;
      }
      .container{
        margin-top: 20px;

      }
      .text-reset{
        margin-top: 30px;
      }
      h2{
        font-size: 40px;
        text-align: center;
      }
      .text-uppercase>.card-text{
        color: black;
      }
      .row2{
        --bs-gutter-x: 1.5rem;
        --bs-gutter-y: 0;
        display: flex;
        margin-top: calc(var(--bs-gutter-y) * -1);
        margin-right: calc(var(--bs-gutter-x) * -.5);
        margin-left: calc(var(--bs-gutter-x) * -.5);
      }
      .trang1{
        margin-top: 20px;
      }
      .hidde:hover{
        background-color: green;
      }
      
  </style>
</head>
<body>
    <nav class="navbar navbar-light bg-success">
        <div class="container-fluid">
             <b>HELP <i class="fa-solid fa-phone-rotary"></i> +1-202-555-0151</b>
          <form class="d-flex">
            <a>MY ACCOUNT</a>
            <a>SIGN IN</a>    
             <a>CREATE ACCOUNT</a>
          </form>
        </div>
      </nav>
        </div>
        <nav class="navbar navbar-expand-lg navbar-light " style="background-color: rgb(3, 184, 3);">
            <div class="container-fluid">       
              <a class="navbar-brand" href="#" style="color: white;font-weight: bold;">TSHOP</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item boderr">
                    <a class="nav-link active hidde  " aria-current="page" href="#"> <b>HOME</b></a>
                  </li>
                  <li class="nav-item dropdown ">
                    <a class=" nav-link dropdown-toggle hidde" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     <b>SHOP</b> 
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle hidde" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      <b>PAGES</b> 
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>

                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle hidde" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                   <b>   NEW PRODUCTS </b>
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link disabled hidde" href="#" tabindex="-1" aria-disabled="true">
                        <b>ALL LINK PAGE</b> </a>
                  </li>
                </ul>
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                   <b> <i class="fa-solid fa-cart-shopping"></i>  CART($210.00) </b> </a>
                    <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true"><b><i class="fa-solid fa-magnifying-glass"></i></b> </a>           
        </div>
        </div>
    </nav>
    <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
          <img src="11.jpg" 
           class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="12.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="13.jpg" class="d-block w-100"  alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>


    <div class="container">
      <h2>NEW ARRIVALS</h2>
      <div class="row">
          <div class="col-12 col-sm-6 col-md-4 col-lg-3 image">
              <div class="card">
                  <div class="bg-image hover-zoom ripple" data-mdb-ripple-color="light">
                      <img src="68.png" class="hinh" />
                      <a href="#!">
                          <div class="mask">
                              <div class="d-flex justify-content-start align-items-end h-100">
                                  <h5>
                                      <span class="badge bg-success ">NEW</span>
                                      <span class="badge bg-danger ">15% OFF</span>
                                  </h5>
                              </div>
                          </div>
                          <div class="hover-overlay">
                              <div class="mask" style="background-color:
                                      rgba(251, 251, 251, 0.15);"></div>
                          </div>
                      </a>
                  </div>
                  <div class="card-body">
        <h5 class="card-title">CONSECTETUER ADIPISCING</h5>
                      <p class="card-text">Some quick example text to
                          build on the card title and make up the bulk of
                          the card's content.</p>
                      <p class="text-reset">
                      <p>XXL/XL/S</p>
                      </p>
                      <h6 class="mb-3"><strong class="text-danger">$25</strong></h6>
                      <a href="#" class="btn btn-primary"><i class="fa-solid fa-cart-shopping"></i> Add to card</a>
                  </div>
              </div>
          </div>

          <div class="col-12 col-sm-6 col-md-4 col-lg-3 image">
              <div class="card">
                  <div class="bg-image hover-zoom ripple" data-mdb-ripple-color="light">
                      <img src="66.png" class="hinh" />
                      <a href="#!">
                          <div class="mask">
                              <div class="d-flex justify-content-start align-items-end h-100">
                                  <h5>
                                      <span class="badge bg-success sale">15% OFF</span>
                                  </h5>
                              </div>
                          </div>
                          <div class="hover-overlay">
                              <div class="mask" style="background-color:
                                      rgba(251, 251, 251, 0.15);"></div>
                          </div>
                      </a>
                  </div>
                  <div class="card-body">
                      <h5 class="card-title">LUPTATUM ZZRIL DELENIT</h5>
                      <p class="card-text">Some quick example text to
                          build on the card title and make up the bulk of
                          the card's content.</p>
                      <p class="text-reset">
                      <p>XXL/XL/S</p>
                      </p>
                      <h6 class="mb-3"><strong class="text-danger">$25</strong></h6>
                      <a href="#" class="btn btn-primary"><i class="fa-solid fa-cart-shopping"></i> Add to card</a>
                  </div>
              </div>
          </div>

          <div class="col-12 col-sm-6 col-md-4 col-lg-3 image">
              <div class="card">
                  <div class="bg-image hover-zoom ripple" data-mdb-ripple-color="light">
                      <img src="69.png" class="hinh" />
                      <a href="#!">
                          <div class="mask">
                              <div class="d-flex justify-content-start
                                      align-items-end h-100">
                                  <h5>
                                      <span class="badge bg-danger sale">NEW</span>
                                  </h5>
                              </div>
                          </div>
                          <div class="hover-overlay">
                              <div class="mask" style="background-color:
                                      rgba(251, 251, 251, 0.15);"></div>
                          </div>
                      </a>
                  </div>
                  <div class="card-body">
                      <h5 class="card-title">ELEIFEND OPTION</h5>
                      <p class="card-text">Some quick example text to
                          build on the card title and make up the bulk of
                          the card's content.</p>
                      <p class="text-reset">
                      <p>XXL/XL/M/S</p>
                      </p>
                      <h6 class="mb-3"><strong class="text-danger">$25</strong></h6>
                      <a href="#" class="btn btn-primary"><i class="fa-solid fa-cart-shopping"></i> Add to card</a>
                  </div>
              </div>
          </div>

          <div class="col-12 col-sm-6 col-md-4 col-lg-3 image">
              <div class="card">
                  <div class="bg-image hover-zoom ripple" data-mdb-ripple-color="light">
                      <img src="67.jpg" class="hinh" />
                      <a href="#!">
                          <div class="hover-overlay">
                              <div class="mask" style="background-color:
                                      rgba(251, 251, 251, 0.15);"></div>
                          </div>
                      </a>
                  </div>
                  <div class="card-body">
                      <h5 class="card-title">MUTATIONEM</h5>
                      <p class="card-text">Some quick example text to
                          build on the card title and make up the bulk of
                          the card's content.</p>
                      <p class="text-reset">
                      <p>XXL/XL/S</p>
                      </p>
                      <h6 class="mb-3"><strong class="text-danger">$25</strong></h6>
                      <a href="#" class="btn btn-primary"><i class="fa-solid fa-cart-shopping"></i> Add to card</a>
                  </div>
              </div>
          </div>
      </div>
    </div>


      <div class="card bg-dark text-white">
        <img src="https://tse1.mm.bing.net/th?id=OIP.ZwkozLciGl9AWrdw4JLMtgHaE8&pid=Api&P=0" class="card-img" alt="...">
        <div class="card-img-overlay">
          <h1 class="card-title"> TRUSTED SELLER 500+</h1>
          <p class="card-text"><b> Lorem ipsum, dolor sit amet consectetur</b></p>
        </div>
      </div>


       <!-- Footer -->
<footer class="text-center text-lg-start bg-light text-muted">
  <!-- Section: Social media -->
  <section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom">
    <!-- Left -->

    <!-- Right -->
  </section>
  <!-- Section: Social media -->

  <!-- Section: Links  -->
  <section class="">
    <div class="container text-center text-md-start mt-5 bg-light">
      <!-- Grid row -->
      <div class="row2 mt-3">
        <!-- Grid column -->
        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
          <!-- Content -->
          <h6 class="text-uppercase fw-bold mb-4">
            SUPPORT <hr>
          </h6>
          <p>Lorem ipsum dolor sit amet, consectetur</p>
            <br>
            <h5 style="color: black;">+1-202-555-0151 </h5>
            <br>
          <p><i class="fas fa-envelope me-3"></i>help@yourweb.com</p>
          
        </div>
        <!-- Grid column -->

        <!-- Grid column -->
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">
           SHOP <hr>
          </h6>
          <p>
           Men's
          </p>
          <p>
          Women's
          </p>
          <p>
          Kids'
          </p>
          <p>
            Shoes
          </p>
          <p>
            Gift card
          </p>
        </div>
        <!-- Grid column -->

        <!-- Grid column -->
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">
          INFORMATION <hr>
          </h6>
          <p>
            Question?
          </p>
          <p>
           Order Status
          </p>
          <p>
            Sizing charts
          </p>
          <p>
            Return policy
          </p>
          <p>
            Contact Us
          </p>
        </div>
        <!-- Grid column -->

        <!-- Grid column -->
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">MY ACCOUNT <hr></h6>
          
          <p>My account</p>
          <p>My address</p>
          <p>Wish list</p>
          <p>Order list</p>
          <p>Order Status</p>
        </div>
        <!-- Grid column -->
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">STAY IN TOUCH<hr></h6>
          <form class="row g-3">
            <div class="col-auto ">
              <label for="inputPassword2" class="visually-hidden ">Email</label>
              <input type="password" class="form-control "style="text-align:center;"  placeholder="Email">
            </div>
            <div class="col-auto ">
              <label for="inputPassword2" class="visually-hidden ">SUBCRIBE</label>
              <input type="password" class="form-control  "style="text-align:center;" placeholder="SUBCRIBE">
            </div>
          </form>
          <div class="trang1">
            <a href="" class="me-4 text-reset">
                <i class="fa-brands fa-facebook" ></i>
            </a>
            <a href="" class="me-4 text-reset">
                <i class="fa-brands fa-twitter" ></i>
            </a>
            <a href="" class="me-4 text-reset">
                <i class="fa-brands fa-chrome"></i>
            </a>
            <a href="" class="me-4 text-reset">
                <i class="fa-brands fa-chrome" ></i>
            </a>
            <a href="" class="me-4 text-reset">
                <i class="fa-brands fa-linkedin"></i>
            </a>
          </div>
        </div>
      </div>
      <!-- Grid row -->
    </div>
  </section>
  <!-- Section: Links  -->
</footer>
<!-- Footer -->
  <!-- Copyright -->
  <br>
  <div class="">  
    <div class="text-lg-start p-4 text-muted" style="background-color: rgb(201, 197, 197);"  >
    © 2021 Copyright:
    <a class="text-reset fw-bold" href="https://mdbootstrap.com/">MDBootstrap.com</a>
  </div>
  <!-- Copyright -->
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bai 2 Lab 7</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
        integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body{
            background-color: #eee;
        }
        
        .header>.navbar {
            height: 20px;
            font-size: x-small;
            font-weight: bold;
            color: white;
        }

        .header>.bg {
            background: rgb(78, 233, 78);
        }

        .header>.navbar-light>.navbar-nav>.nav-link {
            color: white;
        }

    
        .navbarMenu>.navbar-light>.navbar-brand,
        .navbar-light>.navbar-nav>.nav-link.active,
        .navbar-light>.navbar-nav>.show>.nav-link,
        .btn {
            color: white;
            font-size: medium;
        }

        .navbarMenu>.navbar {
            min-height: 50px;
        }

        .navbarMenu>.d-flex {
            display: flex;

        }

        .navbarMenu>.d-flex>.fa-sharp {
            padding: 10px 10px 0 0;
        }

        #carouselExampleControlsNoTouching {
            width: 100%;
        }

        .carousel-item>img {
            width: 100%;
            height: 500px;
        }

      

        .nav2 {
            margin: 20px;
            background-color: white;
        }

        .nav2>.nav {
            border: 2px solid rgb(165, 165, 165);
            border-radius: 10px;
        }

        .nav2>.nav>li>a {
            color: black;
            padding: 10px 10px;
        }

        .shp {
            margin: 30px;
            display: flex;
            justify-content: space-between;
        }


        @media screen and (max-width: 640px) {
            .shp>i {
                font-size: x-small !important;
            }

        }

        
        .content>.btn {
            margin: 0 0 20px 0;
            width: 100%;
        }


       

        .footer>.btn-outline-light {
            color: black;
            border-color: black;
        }

        .footer>.btn {
            font-size: small;
            border-radius: 50%;
        }

        .footer>.mb-4 button {
            border-radius: 10px;
            width: 100%;
            margin: 20px 0;
        }

        .footer>.w-100 {
            width: 5% !important;
            height: 5%;
            padding: 5px;
            border-radius: 10px;
        }

        
        .footerend>p {
            padding: 10px 0 0 20px;
        }

        .footerend {
            width: 100%;
            height: auto;
            display: flex;
            justify-content: space-between;
        }
        .text-reset{
            text-decoration: none;
        }
    </style>
</head>

<body>
    <div class="header">

        <!-- Navbar -->
        <nav class="navbar navbar-expand-lg navbar-light bg">
            <!-- Container wrapper -->
            <div class="container-fluid">

                <!-- Collapsible wrapper -->
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <!-- Left links -->
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Help</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">
                                <i class="fa-solid fa-phone-volume"></i>
                                1234567890
                            </a>
                        </li>
                    </ul>
                    <!-- Left links -->
                </div>
                <!-- Collapsible wrapper -->

                <!-- Right elements -->
                <div class="d-lg-flex d-none align-items-center">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link" href="#">My Acount</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Sign In</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Create Account</a>
                        </li>
                    </ul>
                </div>
            </div>
            <!-- Right elements -->
    </div>
    </nav>
    </div>

    <div class="navbarMenu bg-success">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid">
                <a style="font-size:xx-large; font-weight: bold;" class="navbar-brand" href="#">TSSHOP</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">HOME</a>
                        </li>
                        <li class="nav-item">
                            <div class="dropdown">
                                <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1"
                                    data-bs-toggle="dropdown" aria-expanded="false">
                                    NEW PRODUCTS
                                </button>
                                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another
                                            action</a></li>
                                    <li><a class="dropdown-item" href="#">Something
                                            else here</a></li>
                                </ul>
                            </div>
                        </li>
                        <li class="nav-item dropdown">
                            <div class="dropdown">
                                <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1"
                                    data-bs-toggle="dropdown" aria-expanded="false">
                                    SHOP
                                </button>
                                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another
                                            action</a></li>
                                    <li><a class="dropdown-item" href="#">Something
                                            else here</a></li>
                                </ul>
                            </div>
                            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another
                                        action</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something
                                        else here</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <div class="dropdown">
                                <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1"
                                    data-bs-toggle="dropdown" aria-expanded="false">
                                    PAGES
                                </button>
                                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another
                                            action</a></li>
                                    <li><a class="dropdown-item" href="#">Something
                                            else here</a></li>
                                </ul>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">ALL PAGE LINK</a>
                        </li>
                    </ul>
                    <form class="d-flex">
                        <i class="fa-sharp fa-light fa-cart-shopping fa-2xl"
                            style="font-size:medium; color: #eee;">Card(12345688)</i>
                        <i class="fa-solid fa-magnifying-glass" style="font-size: medium; color: #eee;"></i>
                    </form>
                </div>
            </div>
        </nav>
    </div>

    <div class="nav2">
        <ul class="nav">
            <li class="nav-item">
                <a class="nav-link" href="#">Home /</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Category / </a>
            </li>
            <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Cart</a>
            </li>

        </ul>


    </div>

    <!-- nav -->

    <div class="shp">
        <i class="fa-solid fa-cart-shopping fa-2xl" style="color: #000000; font-size: large;"> Cart Shopping</i>
        <i class="fa-solid fa-less-than fa-2xl" style="color: #00060f; font-size: medium;"> BACK TO SHOPPING</i>
    </div>

    <!-- content  -->
    <div class="content">
        <section class="h-100 h-custom" style="background-color: #eee;">
            <div class="container py-5 h-100">
                <div class="row d-flex justify-content-center align-items-center h-100">
                    <div class="col">
                        <div class="card">
                            <div class="card-body p-4">

                                <div class="row">

                                    <div class="col-lg-7">
                                        <h5 class="mb-3"><a href="#!" class="text-body"></h5>
                                        <hr>

                                        <div class="d-flex justify-content-between align-items-center mb-4">
                                            <div>
                                                <p class="mb-1" style="padding-top:40px; font-size: small;">PRODUCTS</p>

                                            </div>
                                            <div>
                                                <p class="mb-1"
                                                    style="padding-top:38px; font-size: small; padding-right: 200px;">
                                                    DETAILS</p>
                                            </div>

                                            <div>
                                                <p class="mb-0"><span class="text-muted">Sort by:</span> <a href="#!"
                                                        class="text-body">price <i
                                                            class="fas fa-angle-down mt-1"></i></a></p>
                                                <div>
                                                    <p class="mb-1" style="font-size: small;">TOTAL</p>
                                                </div>
                                            </div>
                                        </div>

                                        <div class="card mb-3">
                                            <div class="card-body">
                                                <div class="d-flex justify-content-between">
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div>
                                                            <img src="11pr.jpg"
                                                                class="img-fluid rounded-3" alt="Shopping item"
                                                                style="width: 65px;">
                                                        </div>
                                                        <div class="ms-3">
                                                            <h5>Iphone 11 pro</h5>
                                                            <p class="small mb-0">256GB, Navy Blue</p>
                                                        </div>
                                                    </div>
                                                    <div class="d-flex flex-row align-items-center">

                                                        <div style="width: 50px;">
                                                            <h5 class="fw-normal mb-0">2</h5>
                                                        </div>
                                                        <div style="width: 80px;">
                                                            <h5 class="mb-0">$900</h5>
                                                        </div>
                                                        <a href="#!" style="color: #cecece;"><i
                                                                class="fas fa-trash-alt"></i></a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div class="card mb-3">
                                            <div class="card-body">
                                                <div class="d-flex justify-content-between">
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div>
                                                            <img src="sam.jpg"
                                                                class="img-fluid rounded-3" alt="Shopping item"
                                                                style="width: 65px;">
                                                        </div>
                                                        <div class="ms-3">
                                                            <h5>Samsung galaxy Note 10 </h5>
                                                            <p class="small mb-0">256GB, Navy Blue</p>
                                                        </div>
                                                    </div>
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div style="width: 50px;">
                                                            <h5 class="fw-normal mb-0">2</h5>
                                                        </div>
                                                        <div style="width: 80px;">
                                                            <h5 class="mb-0">$900</h5>
                                                        </div>
                                                        <a href="#!" style="color: #cecece;"><i
                                                                class="fas fa-trash-alt"></i></a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div class="card mb-3">
                                            <div class="card-body">
                                                <div class="d-flex justify-content-between">
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div>
                                                            <img src="can.jpg"
                                                                class="img-fluid rounded-3" alt="Shopping item"
                                                                style="width: 65px;">
                                                        </div>
                                                        <div class="ms-3">
                                                            <h5>Canon EOS M50</h5>
                                                            <p class="small mb-0">Onyx Black</p>
                                                        </div>
                                                    </div>
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div style="width: 50px;">
                                                            <h5 class="fw-normal mb-0">1</h5>
                                                        </div>
                                                        <div style="width: 80px;">
                                                            <h5 class="mb-0">$1199</h5>
                                                        </div>
                                                        <a href="#!" style="color: #cecece;"><i
                                                                class="fas fa-trash-alt"></i></a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div class="card mb-3 mb-lg-0">
                                            <div class="card-body">
                                                <div class="d-flex justify-content-between">
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div>
                                                            <img src="mac.jpg"
                                                                class="img-fluid rounded-3" alt="Shopping item"
                                                                style="width: 65px;">
                                                        </div>
                                                        <div class="ms-3">
                                                            <h5>MacBook Pro</h5>
                                                            <p class="small mb-0">1TB, Graphite</p>
                                                        </div>
                                                    </div>
                                                    <div class="d-flex flex-row align-items-center">
                                                        <div style="width: 50px;">
                                                            <h5 class="fw-normal mb-0">1</h5>
                                                        </div>
                                                        <div style="width: 80px;">
                                                            <h5 class="mb-0">$1799</h5>
                                                        </div>
                                                        <a href="#!" style="color: #cecece;"><i
                                                                class="fas fa-trash-alt"></i></a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                    </div>
                                    <div class="col-lg-5">

                                        <button type="button" class="btn btn-success">Proceedd To Checkout -></button>

                                        <div class="card text-dark rounded-3">
                                            <div class="card-body">



                                                <div class="d-flex justify-content-between">
                                                    <p class="mb-2">Subtotal</p>
                                                    <p class="mb-2">$4798.00</p>
                                                </div>

                                                <hr class="my-4">

                                                <div class="d-flex justify-content-between">
                                                    <p class="mb-2">Shipping</p>
                                                    <p class="mb-2">$20.00</p>
                                                </div>

                                                <hr class="my-4">

                                                <div class="d-flex justify-content-between mb-4">
                                                    <p class="mb-2">Total(Incl. taxes)</p>
                                                    <p class="mb-2">$4818.00</p>
                                                </div>

                                                <hr class="my-4">

                                                <div class="btn-group">
                                                    <input class="btn active"
                                                        style="border: 2px solid gray; width: 100%;" type="search"
                                                        class="form-control rounded" placeholder="Coupon code"
                                                        aria-label="Search" aria-describedby="search-addon" />
                                                    <button type="button" style="border: 2px solid gray; width: 30%;"
                                                        class="btn btn-primary">Apply!</button>

                                                </div>

                                            </div>
                                        </div>

                                    </div>

                                </div>
                                <div style="padding: 20px 50px 60px 0;">
                                    <button style="width:15%; margin-right: 300px; font-size: xx-small;" type="button"
                                        class="btn btn-secondary">
                                        <i class="fas fa-long-arrow-alt-left me-2"></i> Continue shopping</a>
                                    </button>
                                    <button style="width:15%; font-size: xx-small;" type="button"
                                        class="btn btn-secondary">
                                        <i class="fa-solid fa-rotate-right"> Update Cart</i>
                                    </button>
                                </div>

                            </div>

                        </div>
                    </div>
                </div>
            </div>
    </div>
    </section>
    </div>

    <!-- Footer -->
    <div class="footer">
        <footer class="text-center text-lg-start bg-light text-muted">
            <!-- Section: Links  -->
            <section class="ND">
                <div class="container text-center text-md-start mt-5">
                    <!-- Grid row -->
                    <div class="row mt-md-3 col-lg-12">
                        <!-- Grid column -->
                        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4
                      col-2">
                            <!-- Content -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                <i class="fas fa-gem me-3"></i>
                                Support
                                <hr>
                            </h6>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                            </p>
                            <div class="contact">
                                <i class="fa-solid fa-phone"></i>
                                <p class="contact-text">0339119229</p>
                            </div>
                            <div class="contact">
                                <i class="fa-sharp fa-regular fa-envelope"></i>
                                <p class="contact-text">sontung1994@gmail.com</p>
                            </div>
                        </div>
                        <!-- Grid column -->

                        <!-- Grid column -->
                        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4
                      col-2">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                Products
                                <hr>
                            </h6>
                            <p>
                                <a href="#!" class="text-reset">Angular</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">React</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Vue</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Laravel</a>
                            </p>
                        </div>
                        <!-- Grid column -->

                        <!-- Grid column -->
                        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4
                      col-2">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                Useful links
                                <hr>
                            </h6>
                            <p>
                                <a href="#!" class="text-reset">Pricing</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Settings</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Orders</a>
                            </p>
                            <p>
                                <a href="#!" class="text-reset">Help</a>
                            </p>
                        </div>
                        <!-- Grid column -->

                        <!-- Grid column -->
                        <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0
                      mb-4 col-2">
                            <!-- Links -->
                            <h6 class="text-uppercase fw-bold mb-4">
                                STAY IN TOUCH
                                <hr>
                            </h6>
                            <form>
                                <div class="form-group">
                                    <input type="email" class="form-control" id="exampleInputEmail1"
                                        aria-describedby="emailHelp" placeholder="Enter email">
                                </div>
                                <button type="submit" class="btn btn-primary
                              bg-success"><b style="display: flex; flex-wrap:wrap;">Subscribe</b> </button>
                            </form>
                            <section class="mb-4">
                                <!-- Facebook -->
                                <a class="btn btn-outline-light btn-floating
                              m-1" href="#!" role="button"><i class="fab
                                  fa-facebook-f"></i></a>

                                <!-- Twitter -->
                                <a class="btn btn-outline-light btn-floating
                              m-1" href="#!" role="button"><i class="fab
                                  fa-twitter"></i></a>

                                <!-- Google -->
                                <a class="btn btn-outline-light btn-floating
                              m-1" href="#!" role="button"><i class="fab
                                  fa-google"></i></a>

                                <!-- Instagram -->
                                <a class="btn btn-outline-light btn-floating
                              m-1" href="#!" role="button"><i class="fab
                                  fa-instagram"></i></a>

                            </section>
                        </div>
                        <!-- Grid column -->

                    </div>
                    <!-- Grid row -->
                </div>
            </section>
            <!-- Section: Links  -->
        </footer>
        <!-- Footer -->
    </div>

    <div class="footerend" style="background-color: #caced1;">
        <p>© 2020 Author</p>
        <div>
            
        </div>
    </div>

</body>

</html>
