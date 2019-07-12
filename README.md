# Orion-s-Website
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
<link rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" type="text/css" href="orionstyle.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
<script type="text/javascript"src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
<script src="https://unpkg.com/@barba/core"></script>
<script type="text/javascript"src="barba.js"></script>

<title>Orion Studios Africa</title>
</head>

<body>

<!--Welcome Section-->

<!--SVG Logo animation-->
<!-- <div class="container">
<div class="col-lg-8-align-self-center">
  <div class="circle1"></div>
  <div class="circle2"></div>
</div>
</div> -->
<img src="Grande orion.svg">

<div class="welcome-section">
  <ul class="fly-in-text hidden">
    <li>O</li>
    <li>R</li>
    <li>I</li>
    <li>O</li>
    <li>N</li>
  </ul>
</div>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type="text/javascript">
            
    $(function() {
                
    setTimeout(function() {
    $('.fly-in-text').removeClass('hidden');
    }, 500);
    })();          
            
</script> 

<script src="barba.min.js"></script>
<!--End of Welcome Section-->

<!--Navigation-->
<header style="margin:0px;display:flex;vertical-align:center;">   

<!--Orion Logo-->
<div class="Orion-Logo">
   <img src="../img/Orion Card.svg" style="margin-left: 20px">
</div>

<!-- Sidebar Menu -->
<div class="container fluid">
<div class="justify-content-center">
<div class="d-flex flex-row-reverse">
  
  <div id="mySidenav" class="sidenav">


  <a href="javascript:void(0)" class="closebtn  " onmouseout="closeNav()">&times;</a>
    <a href= "#portfolio active">PORTFOLIO</a></li>
    <a href="#projects">PROJECTS</a></li>
    <a href="#packages">PACKAGES</li>
    <a href="#contact">CONTACT</a></li>
    <a href="#about">ABOUT</a></li>
  </div>

<span style="float:left;font-size:20px;cursor:pointer;" onmouseover ="openNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>
</header>
<!--End of Navigation-->

<!-- !PAGE CONTENT! -->
<!--Portfolio Section Begins-->

<!-- Grid Gallery Layout-->
<div class="container-fluid">
<div class="row">
<div class="gallery" id="gallery">

  <div>
    <img class="img-fluid" src="../img/Amina/PORTRAITS/IMG_8545.jpg" alt="Card image cap">
  </div>

  <div>
    <img class="img-fluid" src="../img/Stella Kareo/IMG_5693.jpg">
  </div>

  <div>
    <img class="img-fluid" src="../img/Njeri Macharia/IMG_6768-Recovered.jpg" alt="Card image cap">
  </div>
  
  <div>
    <img class="img-fluid" src="../img/Stella Kareo/IMG_5775.jpg" alt="Card image cap">
  </div>

  <div>
    <img class="img-fluid" src="../img/Njeri Macharia/IMG_6779.jpg" alt="Card image cap">
  </div>

  <div>
    <img class="img-fluid" src="../img/Labdi/VIN_0429.jpg" alt="Card image cap">
  </div>

  <div>
    <img class="img-fluid" src="../img/Moji/IMG_5080.jpg" alt="Card image cap">
    </div>
 
  <div>
    <img class="img-fluid" src="../img/Noel/IMG_6889.jpg" alt="Card image cap">
  </div>

</div>
<!--Portfolio Section Ends-->


<!-- Footer -->
<!--Orion Socials-->
<footer style="border-style:none;margin:auto;text-align:center;">
  <div class="orionstudiosafrica_social">
    
    <a href="https://www.facebook.com/OrionStudiosAfrica/" target="_blank">
      <span class="fa-stack" style="font-size:15px;color:grey;"></i>
        <i class="fa fa-circle fa-stack-2x"></i>
        <i class="fa fa-facebook fa-stack-1x fa-inverse"></i>
      </span>
    </a>

    <a href="https://www.instagram.com/orionstudiosafrica/?hl=en" target="_blank">
      <span class="fa-stack" style="font-size:15px;color:grey;"></i>
        <i class="fa fa-circle fa-stack-2x"></i>
        <i class="fa fa-instagram fa-stack-1x fa-inverse"></i>
      </span>
    </a>
    
    <a href="#" target="_blank">
      <span class="fa-stack" style="font-size:15px;color:grey;"></i>
        <i class="fa fa-circle fa-stack-2x"></i>
        <i class="fa fa-linkedin fa-stack-1x fa-inverse"></i>
      </span>
    </a>
  </div>
  <p style="font-size:11px;">&copy;Orion Studios Africa,2019</a></p>
</footer>
<!--End of Footer Section-->

<pre>
<main id="barba-wrapper">
    <div class="barba-container" data-namespace="grid">
    </div>
</main>
</pre>
 
<script>

