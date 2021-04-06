<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sadia's kitchen</title>

    <!--Boostrap cdn-->
   <link rel="stylesheet" href="/css/bootstrap.min.css">

   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
   <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
   
   
   <!--Font awsome cdn-->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



   <style>
         .carousel-inner img{
             width: 100%;
             height:50%;
         }

         h2{
             text-align:center;
         }
  
        .about-us{
            text-align:justify;
        }

        .footer{
            position:relative;
            left:0;
            bottom:0;
            width:100%;
            background-color:black;
            color:white;
            text-align:center;

        }


        .media-button .btn{
            border:none;
            border-radius:none;
            cursor:pointer;
            font-size:32px;
            padding:5px;
            margin:10px;
            width:50px;
            background-color:white;
            
        }

        .btn:hover{
            background-color:cornflowerblue;
        }

       </style>

</head>

   <body>
       <nav class="navbar  bg-dark navbar-dark">
           <!--Brand-->

           <a class="navbar-brand" href="#"><img src="chef-512.webp" alt="logo" style="width:100px">Sadia's Kitchen</a>


           <!--Toggler/collapsible Button-->

          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#colnav">
            <span class="navbar-toggler-icon"></span>
          </button>

          <!--Navbar-link-->
           <div class="collapse navbar-collapse" id="colnav">
               <ul class="navbar-nav">
                   <li class="nav-item"><a class="nav-link" href="#">About Us</a></li>
                   <li class="nav-item"><a class="nav-link" href="#">Contact Us</a></li>
                   <li class="nav-item"><a class="nav-link" href="#">Report Here</a></li>  
                   </ul>
                </div>

    </nav>

     <!--Carousel-->
     <div id="demo" class="carousel slide" data-ride="carousel">

        <!-- Indicators -->
        <ul class="carousel-indicators">
            <li data-target="#demo" data-slide to="0" class="active"></li>
            <li data-target="#demo" data-slide to="1" ></li>
            <li data-target="#demo" data-slide to="2" ></li>

        </ul>

        <!--The slideshow-->
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="img-fluid" src="sandra-seitamaa-OFJGlG3sKik-unsplash.jpg" alt="look" width="1100px" height="500px">
                <div class="carousel-caption">
                 <h3 style="color:yellow">Sadia's Kitchen</h3>
                 <p>Welcome to our page</p>
                </div>
            </div>

            <div class="carousel-item">
                <img class="img-fluid" src="jay-wennington-N_Y88TWmGwA-unsplash.jpg" alt="f1" width="1100px" height="500px">
                <div class="carousel-caption">
                     <p style="color:black">I hope you will like our service</p>
                   </div>
            
            
            </div>

            <div class="carousel-item">
                <img class="img-fluid" src="jakub-kapusnak-4f4YZfDMLeU-unsplash.jpg" alt="f2" width="1100px" height="500px">
                <div class="carousel-caption">
                    <p style="color:yellowgreen">If you face any problem then give us the feedback</p>
                   </div>
            
            
            
            </div>
        
        </div>


     <!--Left and right controls-->

     <a class="carousel-control-prev" href="#demo" data-slide="prev"><span class="carousel-control-prev-icon "></span></a>
     
     <a class="carousel-control-next" href="#demo" data-slide="next"><span class="carousel-control-next-icon "></span></a>



        </div>

    <!--About us-->
    <div class="text mt-3">
          <h2>About Us</h2>
           <p class="mt-3 about-us">Dolor eos dolor amet sadipscing erat. Eos dolores stet diam vero duo sit takimata kasd rebum, clita sed takimata at duo eirmod amet sit sit sadipscing. Lorem dolores kasd clita erat est justo, sit
             sadipscing tempor kasd gubergren ut justo, erat et lorem nonumy et eirmod. Amet aliquyam est ut.</p>

        </div>


    <!--Card creating-->

  <div class="card-deck">

    <div class="card" style="width:400px">
        <img class="card-img-top" src="french frie.jpg" alt="card image" height="500px">
        
        <div class="card-body">
            <h4 class="card-title">Fresns Fries</h4>
            <button class="btn btn-primary">Order now</button>
        </div>
     </div>

     <div class="card" style="width:400px">
        <img class="card-img-top" src="falooda.jpg" alt="card image" height="500px">
        
        <div class="card-body">
            <h4 class="card-title">Falooda</h4>
            <button class="btn btn-primary">Order now</button>
        </div>
    </div>

     <div class="card" style="width:400px">
        <img class="card-img-top" src="biriyani pic.jpg" alt="card image" height="500px">
        
        <div class="card-body">
            <h4 class="card-title">Biriyani</h4>
            <button class="btn btn-primary">Order now</button>
        </div>
     </div>

     <div class="card" style="width:400px">
        <img class="card-img-top" src="cake.png" alt="card image" height="500px">
        
        <div class="card-body">
            <h4 class="card-title">Cake</h4>
            <button class="btn btn-primary">Order now</button>
        </div>
    </div>

</div>

    <!--location setting-->
    
      <div class="jumbotron">
          <div class="row">
              <div class="col-8">
                  Khulna
                  <div class="row">
                      <div class="col-6"><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3677.92681067358!2d89.5676798!3d22.8051757!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39ff8fe0bbffe219%3A0x94fbf41153244f65!2sTootpara%20Central%20Rd%2C%20Khulna!5e0!3m2!1sen!2sbd!4v1617719376850!5m2!1sen!2sbd" width="600px" height="400px" style="border:0;" allowfullscreen="" loading="lazy"></iframe></div>
                     
                    
                  </div>
              </div>
            <div class="col-sm-4 mt-3">
                <h3 style="text-align:center" style="color:blueviolet" >Contact details</h3><br><br>
                <h2 style="text-align:center">Sadia's Kitchen</h2>
                <p style="text-align:center">143 London Avenue , Hadith park , Khulna</p><br><br>

                <h2 style="text-align:center">Phone:</h2>
                <p style="text-align:center">+880199*******</p><br><br>
                
             
                <h2 style="text-align:center">Openning hours</h2>
                <p style="text-align:center">Tue-Sun:5PM to 11PM</p>
                <p style="text-align:center">Inc. Bank Holidays</p>
            </div>
          
          </div>
    </div>

    <!--Footer-->

    <div class="footer">

        <span>&copy;</span>All right reserved by Sadia's Kitchen

        <div class="media-button">
            <button class="btn" onclick="window.open('https://www.youtube.com/channel/UCTarr_yrhUuPpzNrUu7h2vg')" class="request-callback"><i class="fa fa-youtube-play" aria-hidden="true" style="color:red;"></i></button>
            <button class="btn" onclick="window.open('https://www.facebook.com/mdrayhan.enrayhan')" class="request-callback"><i class="fa fa-facebook-official" aria-hidden="true" style="color:blue"></i></button>
            <button class="btn" onclick="window.open('https://github.com/Rayhan740')" class="request-callback"><i class="fa fa-github" aria-hidden="true"></i></button>
            <button class="btn" onclick="window.open('https://twitter.com/SakibulRayhan')" class="request-callback"><i class="fa fa-twitter-square" aria-hidden="true" style="color:#1DA1F2"></i></button>
            <button class="btn" onclick="window.open('https://wa.me/<+8801646835425>')" class="request-callback"><i class="fa fa-whatsapp" aria-hidden="true" style="color:	#25D366"></i></button>
                     
           </div>













        </div>
    



   </body>




</html>
© 2021 GitHub, Inc.
