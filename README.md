<!DOCTYPE html>
<html>
<head>
<title>TERABYTE</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>
  .para{
    border: 2px solid black;
    width: 500px;
  }
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("pic2.jpeg");
  min-height: 100%;
}

.w3-bar .w3-button {
  padding: 16px;
}
</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">TERABYTE</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="signup.html" class="w3-bar-item w3-button"><i class="fa fa-sign-in"></i>LOGIN</a>
      <a href="#about" class="w3-bar-item w3-button"><i class="fa fa-info-circle"></i>ABOUT</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> TEAM</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i> WORK</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <img src="C:\Users\anush\OneDrive\Desktop\nicepic.jpg" alt="title" width="1400" height="700">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">Start something that matters</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Start something that matters</span><br>
    <span class="w3-large">We at Terabyte are here to design your dream website.</span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Hire us and get started today!</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">ABOUT TERABYTE</h3>
  
    <p class="w3-center w3-large">Key features of our company</p>
    <p id="para" value="">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ex assumenda voluptate excepturi. Commodi eveniet quaerat blanditiis officia soluta sit ut esse debitis sint laborum nemo repudiandae quod, numquam facilis alias iusto repellat molestiae iste ipsum sed tenetur. Sit voluptates qui corporis commodi asperiores nemo accusantium aliquid? Voluptate veniam nulla quibusdam! Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque aut sint fugiat, exercitationem magni placeat repellendus vero corporis aperiam voluptatem iusto libero sit omnis pariatur nemo a totam accusantium? Adipisci.</p>
  
  <button id="btn1" onclick="toggleHide()"> Read More</button>
  <script>
    function toggleHide(){
      let btn=document.getElementById('btn1');
      let para=document.getElementById('para');
      if(para.style.display !='none'){
        para.style.display ='none';
      }
      else{
        para.style.display ='block';
      }
    }
  </script>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-desktop w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Responsive</p>
      <p> WE ARE HERE TO HELP YOU DESIGN THE WEBSITE OF YOUR NEEDS IN A GO.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Passion</p>
      <p>OUR DEVELOPERS ARE SKILLED AND TRAINED TO GIVE THE BEST OUTCOMES.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Design</p>
      <p>TELL US ABOUT YOUR DREAM DESIGN AND WE'LL MAKE IT HAPPEN.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Support</p>
      <p>CONTACT OUR TEAM FOR FURTHER DETAILS AND HELP.</p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>We know design.</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod<br>tempor incididunt ut labore et dolore.</p>
      <p><a href="#work" class="w3-button w3-black"><i class="fa fa-th"> </i> View Our Works</a></p>
    </div>
    <div class="w3-col m6">
      <img class="w3-image w3-round-large" src="titlepic.jpg" alt="Buildings" width="900" height="394">
    </div>
  </div>
</div>

<!-- Team Section -->
<div class="w3-container" style="padding:128px 16px" id="team">
  <h3 class="w3-center">THE TEAM</h3>
  <p class="w3-center w3-large">The ones who started Terabyte</p>
  <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="jakey.jpeg" alt="deep" style="width:60%">
        <div class="w3-container">
          <h3>Jake Peralta</h3>
          <p class="w3-opacity">CEO & Founder</p>
          <p>Topper of trip school. He works efficiently and loves playing video games.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="santiago.jpg" alt="anusha" style="width:60%">
        <div class="w3-container">
          <h3>Amy Santiago</h3>
          <p class="w3-opacity">Art Director</p>
          <p>Key witness of trip school. She assists jake in his endeavours and supervises the overall project</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="boyle.jpg" alt="Mike" style="width:60%">
        <div class="w3-container">
          <h3>Charles Boyle</h3>
          <p class="w3-opacity">Web Designer</p>
          <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="rosa.jpg" alt="Dan" style="width:50%">
        <div class="w3-container">
          <h3>Rosa Diaz</h3>
          <p class="w3-opacity">Designer</p>
          <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
        </div>
      </div>
    </div>
  </div>
</div>
-->
<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">14+</span>
    <br>Partners
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">55+</span>
    <br>Projects Done
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">89+</span>
    <br>Happy Clients
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">150+</span>
    <br>Meetings
  </div>
</div>


<div class="w3-container" style="padding:128px 16px" id="work">
  <h3 class="w3-center">OUR WORK</h3>
  <p class="w3-center w3-large">What we've done for people</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="pic7.png" style="width:100%" height="220px" onclick="onClick(this)" class="w3-hover-opacity" alt="A microphone">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic8.jpg" style="width:100%" height="220px"onclick="onClick(this)" class="w3-hover-opacity" alt="A phone">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic6.webp" style="width:100%"height="220px" onclick="onClick(this)" class="w3-hover-opacity" alt="A drone">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic5.avif" style="width:100%" height="220px"onclick="onClick(this)" class="w3-hover-opacity" alt="Soundbox">
    </div>
  </div>

  <div class="w3-row-padding w3-section">
    <div class="w3-col l3 m6">
      <img src="nicepic.jpg" style="width:100%"height="220px" onclick="onClick(this)" class="w3-hover-opacity" alt="A tablet">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic4.jpg" style="width:100%" height="220px"onclick="onClick(this)" class="w3-hover-opacity" alt="A camera">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic3.webp" style="width:100%"height="220px" onclick="onClick(this)" class="w3-hover-opacity" alt="A typewriter">
    </div>
    <div class="w3-col l3 m6">
      <img src="pic1.jpg" style="width:100%" height="220px" onclick="onClick(this)" class="w3-hover-opacity" alt="A tableturner">
    </div>
  </div>
</div>

<div class="w3-container w3-light-grey w3-padding-64">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Our Skills.</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod<br>
      tempor incididunt ut labore et dolore.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod<br>
      tempor incididunt ut labore et dolore.</p>
    </div>
    <div class="w3-col m6">
      <p class="w3-wide"><i class="fa fa-camera w3-margin-right"></i>Photography</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:90%">90%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Web Design</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:85%">85%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-photo w3-margin-right"></i>Photoshop</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:75%">75%</div>
      </div>
    </div>
  </div>
</div>


<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="pricing">
  <h3>PRICING</h3>
  <p class="w3-large">Choose a pricing plan that fits your needs.</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16"><b>10GB</b> Storage</li>
        <li class="w3-padding-16"><b>10</b> Emails</li>
        <li class="w3-padding-16"><b>10</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">Rs. 5000</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
    <div class="w3-third">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-red w3-xlarge w3-padding-48">Pro</li>
        <li class="w3-padding-16"><b>25GB</b> Storage</li>
        <li class="w3-padding-16"><b>25</b> Emails</li>
        <li class="w3-padding-16"><b>25</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">Rs. 10,000</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Premium</li>
        <li class="w3-padding-16"><b>50GB</b> Storage</li>
        <li class="w3-padding-16"><b>50</b> Emails</li>
        <li class="w3-padding-16"><b>50</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">Rs. 20,000</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT US</h3>
  <p class="w3-center w3-large">Lets get in touch. Send us a message:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> GEC, Farmagudi</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone: +00 151515</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: trippersftw@mail.com</p>
    <br>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-black" id="login" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
        <script>
          let button=document.getElementById('login');
          button.addEventListener('click', function run(){
  
  alert("submitted")
          });
          </script>
      </p>
    </form>
  </div>
</div>

<script>
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>

</body>
</html>

// SIGN-UP PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SIGN-UP PAGE</title>

</head>
<body>
    <div>
        <header>
          <nav class="navbar">
              <ul>
                  <li><a href="#">Home </a></li>
                  <li><a href="#"> About</a></li>
                  <li><a href="#"> Services</a></li>
                  <li><a href="#"> Contact</a></li>
                  <div class="search">
                      <input type="text" name="search" id="search" placeholder="Search this website..">
              
                  </ul>
              </nav>
             
          </header>
          </div>
          <div class="left">
            <!-- <img src="dex logo.jpg" alt=""> -->
            <div class="title">TERABYTE</div>
                        </div>
    <!-- <p>Lorem ipsum dolor sit amet.</p> -->
   <style>

.navbar{
    background-color: rgb(26 21 21);
    border-radius: 2px;
        }
        .navbar li {
            font-size: 21px;
            display: inline-block;
            margin: 13px 20px;
            padding: 6px 6px ;
            float: right;
            /* list-style: none; */
            
        }
        .navbar li a{
            color: blanchedalmond;
            text-decoration: none;
        }
        .navbar li a:hover, .navbar li a.active{
            color: rgb(132, 129, 129);
            text-decoration: underline;
        }
        
        .navbar ul{
            overflow: auto;
           
        }
        .navbar input{
            
            background-color: #0f0e0e;
            border: 2px solid rgb(86, 81, 81);
            border-radius: 8px;
            padding: 3px 17px;
            width: 179px;
        }
        .search{
    background-color: none;
    margin-left: 55px;
    width: -45px;
    position: absolute;
    left: -448px;
    top: 18px;
    display: inline-block;
    text-align: center;
    float: inline-start;
    color: azure;
    padding: 17px 549px;
            color: #c0b4b4;
            float: inline-start;
            color: azure;
            
        }
 body{
    margin: 50 200 200 500;
 }
        .container{
            text-align: center;
    width: 724px;
    /* padding: 10px; */
    border: 3px solid rgb(233 224 224);
    font-weight: bold;
    background-color: #0e0d0d;
    padding: 10px;
    margin-top: 10px;
    margin: 40px 30px;
        }
        h2{
            font-size: 35px;
            color: aliceblue;
            border-bottom: 2px solid #767272;
        }
        p{
            text-align: center;
            font-size: 20px;
            border: 5px solid rgb(124, 120, 104);
            width: 500px ;
            border-radius: 10px;
            padding: 10px;
            margin-left: 140px;
        }
        .btn, #login{
         align-items: center;
            color: white;
    background-color: rgb(43 43 40);
    padding: 9px;
    width: 127px;
    cursor: pointer;
    border: 3px solid rgb(40 36 36);
    border-radius: 3px;
        }
        .btn:hover{
            background-color: rgb(34, 33, 33);
        }
       
        a{
            text-decoration: none;
        }
        a:hover{
            background-color: rgb(61, 59, 59);
        }
        a:active{
            background-color: rgb(77, 75, 75);
        }
        
    .title{
        /* border: 2px solid white; */
        margin: 10px;
        margin-top: -77px;
        width: 500px;
        padding: 20px;
        font-size: 20px;
        color: whitesmoke;

        position: relative;
       animation-name: anu2;
       animation-duration: 3s;
       animation-iteration-count: 1;
       animation-fill-mode: alternate;
       animation-timing-function: ease-in-out;

    }

    @keyframes anu2{
                    0%{
                        top: 0px;
                        left: 0px;
                        right: 250px;
                    }
                    25%{
                        top: 0px;
                        left: 420px;
                    }
                    75%{
                        top: 0px;
                        left: 420px;
                    }
                    100%{
                        top: 0px;
                        left: 0px;
                        right: 250px;
                    }
                }
#name{
    margin-left: 200px;
}
    .form-group input{
        margin: 5px 234px;
        width: 300px;
        text-align: center;
        display: block;
        padding: 6px;
        border: 3px solid rgb(15, 14, 14);
border-radius: 7px;
    }            
    body{
     /* background: url(bgimg2.jpg); */
     background-color: black;
               }
    #para{
        color: white;
        text-align: right;
        margin-left: 800px;
        
    }      
    .pic{
        position: absolute;
        /* width: ; */
        margin-top: 90px;
        margin-left: 800px;
        animation-name: picture;
       animation-duration: 3s;
       animation-iteration-count: 2;
       animation-fill-mode: alternate;
       animation-timing-function:ease;
    }
    @keyframes picture {
                    from{
                        width: 200px;

                    }
                    to{
                        width: 600px;

                    }
                }     
   </style>
<div class="pic" id="image">

    <img src="fff.webp" alt="HERE" style="width:100%">
</div>
<div class="container">
    <h2>SIGN-UP FOR FREE!</h2>
    <!-- <form action="noaction.php"> -->
        <form action="">
        
<div class="form-group">

 <input type="text" name="Name "id="name" placeholder="Enter your Name"><br>

 <input type="text" name="Email "id="name" placeholder="Enter your Email"><br>

  <input type="text" name="Phone "id="name" placeholder="Enter your Phone"><br>

<input type="text" name="Address "id="name" placeholder="Enter your Address"><br>

<input type="text" name="Company "id="name" placeholder="Enter your workplace"><br>

<!-- <a href="" class="btn">Read more</a> -->
<button class="btn">Reset</button> 
<button id="login">Sign in</button>
</div>

<script>
    let button=document.getElementById('login');
    button.addEventListener('click', function run(){

alert("submitted")
    });

 </script>
</div>
<div>
    <!-- <p id="para"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Itaque repellendus dolor vero fugit fugiat perferendis ducimus illo laboriosam deleniti alias saepe expedita ut aut, temporibus quae doloribus earum assumenda quia! Sit distinctio aliquam quasi delectus aliquid, nostrum, autem recusandae numquam enim cumque quas neque vero pariatur at officia unde suscipit.</p>
<button id="btn1" onclick="toggleHide()"> Read More</button> -->
</div>
    </form>
</div>
</body>
</html>


