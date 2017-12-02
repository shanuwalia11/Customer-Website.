# Customer-Website.
A customer Website using the language of HTML, CSS and JavaScript.
Here, i'm gonna showing the code of Customer Website using the language of HTML, CSS and JavaScript.

Home page of customer website

<!DOCTYPE html>
<html>
<head>
<title> Customer Website</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

/* style of countdown */
​p {
  text-align: center;
  font-size: 60px;
}
/* style of animated icon */
#div1 {
  font-size:100px;
}
/* Set a style for all buttons */
button  {
        background-color: #3D66F6;
        color: yellow;
        padding: 15px 21px;
        margin: 20px 0;
        cursor: pointer;
        }


/* Style of SideBar */
body { 
      font-family: "Lato", sans-serif;
	  transition: background-color .5s;
	 }

.sidenav {
          height: 100%;
		  width: 0;
		  position: fixed;
		  z-index: 1;
		  top: 0;
		  left: 0;
		  background-color: #BDB76B;
		  overflow-x: hidden;
		  transition: 0.5s;
		  padding-top: 60px;
}

.sidenav a {
            padding: 10px 10px 10px 36px;
			text-decoration: none;
			font-size: 35px;
			color: red;
			display: block;
			transition: 0.3s;
			}
.sidenav a:hover {
                  color: blue;
				  }
.sidenav .closebtn {
                     position: absolute;
					 top: 0;
					 right: 34px;
					 font-size:70px;
					 margin-left: 60px;
					 }
#main {
       transition: margin-left .6s;
	   padding: 20px;
	  }
@media screen and (max-height: 450px) {
                                        .sidenav {
										          padding-top: 20px;
												  }
										.sidenav a { 
										            font-size: 20px;
													}
									   }

/* Style of Social Media Icons */
.fa { 
      text-decoration: none;
	  padding: 20px;
	  width: 80px;
	  font-size: 30px;
	  text-align: center;
	  margin: 6px 3px;
	  border-radius: 38%;
	 }

.fa:hover {
            opacity: 0.7;
		  }
/* Facebook */
.fa-facebook {
              background: #3B5998;
              color:white;
			  float: right;
              }			  
/* YouTube */
.fa-youtube { 
              background: #bb0000;
			  color: white;
			  float:right;
			 }
/* Instagram */
.fa-instagram {
               background: #125688;
			   color: white;
			   float: right;
			   }
/* Whatsapp */
.fa-whatsapp { 
                background: #34af23;
                color: white;
                float: right;
               }
/* Google */			   
.fa-google {
            background: #dd4b39;
            color: white;
			float: right;
           }	
/* Instagram */		   
.fa-linkedin {
              background: #007bb5;
              color: white;
			  float: right;
              }
			  
/* wechat */
.fa-wechat { 
             background: #34af23;
             color: white;
             float: right;
            }			 
			  
/* Android */
.fa-android {
              background: #a4c639;
              color: white;
			  float: right;
            }

/* Style of Search */

.button {
         background-color: red;
		 padding:10px 20px;
		 text-decoration:none;
		 display: inline-block;
		 font-size: 16px;
		 margin: 4px 2px;
		 cursor: pointer;
		 border-radius: 25px;
		 box-shadow: 0 9px #999;
		 width:5%;
		 
		 }
		 
input[type=text]  {
                   width: 82%;
				   box-sizing: border-box;
				   border: 4px solid red;
				   border-radius: 25px;
				   font-size: 16px;
				   background-color: white;
				   background-image: url('searchicon.png');
				   background-repeat: no-repeat;
				   padding: 12px 20px 12px 40px;
				   -webkit-transition: width 0.2s ease-in-out;
				   transition: width 0.2s ease-in-out;
				   }
input[type=search]:focus {
                       width: 75%;
                       }					   
.button:hover { 
               background-color: MediumSeaGreen
               }
.button:active {
			     background-color: yellow;
				 box-shadow: 0 10px blue;
				 transform: translateY(5px);
				}

body { 
       background-image: url(" Rough-Grey-Tilable-Pattern-For-Website-Background.jpg");
	  }
body { 
      margin: 0;
	  }
/* Style the header */
.header { 
         background-color: slateblue;
		 padding: 1px;
         text-align: center;
         }
		 
/* Style of Navigation Bar */
ul  { 
     list-style-type: none;
	 background-color: #4B0082;
	 padding: 0px;
	 margin: 0px;
	 overflow: hidden;
	 }
/* write flows Horizontally */
li   {
      float: left;
	  }
li a {
      text-decoration: none;
	  padding: 16px 108px;
	  display: block;
	  color: #FFD700;
	  }
li a:hover {
            background-color: red;
			}
	 
/* Style of Dropdown List */

li a, .dropbtn  { 
                 display: inline-block;
				 }
li a:hover, .dropdown:hover .dropbtn {
                                       background- color: red;
                                      }
li.dropdown { 
             display: inline-block;
             }
.dropdown-content { 
                   display: none;
                   position: absolute;
                   background-color: #DAA520;
				   min-width: 297px;
				   box-shadow: 3px 8px 16px 3px rgb(60, 60, 60);
				   z-index: 1;
				   }
.dropdown-content a {
                     color: black;
                     padding: 16px 65px;
                     text-decoration: none;
                     display: block;
                     text-align: left;
                     }					 
.dropdown-content a:hover { 
                           background-color: slateblue;
                           }
.dropdown:hover .dropdown-content { 
                                   display: block;
                                  }	
/* Style of pagination */

.pagination { 
             display:inline-block;
             }
.pagination a {
               text-decoration:none;
			   padding:12px 20px;
			   margin:1px;
			   color:black;
			   float:left;
			   transition:background-color .3s;
			   border: 3px solid black;
			   font-size: 26px;
			   }
			   
.pagination a.active {
                      background-color: red;
					  color:white;
					  border: 3px solid red;
					  }
 
.pagination a:hover:not(.active) {
                                 background-color:blue;
								 }
								 
/* Style of Footer */
.footer {
         border: 10px solid #191970;
         padding: 15px;
         text-align:center;
         }		 
		 
/* style of text shadow */
h1 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}
h2 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}

/* Style of column */

* { 
    box-sizing: border-box;
   }
 
/* Create three unequal column that floats next to each other */ 
.column {
          float: left;
		  padding: 10px;
		 }
/* left and right column */
.column.side {
               width:12%;
              }			   

/* Column middle */
.column.middle {
                 width: 75%;
				}

/* Clear floats after the column */

.row:after {
            content: "";
			display: table;
			clear:both;
			}
/* Responsive layout - makes the three column stack on top of each other instead of next to each other */
@media (max-width: 600px)  {
                           .column.side, .column.middle { 
                                                          width: 100%;
                                                         }
                           }														 


						   
						   
						   
						   
</style>		 
</head>

<body>
<!-- Header Content --> 
<div class="header">
<img src="logo.png" style ="float:left;width:150px;height:75px;">
    <h1>
<form action="http://www.google.com/search" class="navbar-form navbar-left" method="get" name="searchform" target="_blank">
    <input name="sitesearch" type="hidden" value="">
    <input autocomplete="on" class="form-controls search"  id="myInput" onsearch="myFunction()" name="search" placeholder="Explore..." required="required" type="text">
	<button class="button" type="submit">GO</button>
	<!-- On search event --> 
<p id="demo"></p>

<script>
function myFunction() {
   var x = document.getElementById("myInput");
   document.getElementById("demo").innerHTML = "You are searching for: " + x.value;
}
</script>

	
</form>    
</h1> 
</div>


<!-- Navigation Bar -->
<ul> 
    <li><a class="active" href="HOME.html"><b><i><font size="5">HOME</font></i></b></a></li>
	<li><a href="MAP.html"><b><i><font size="5">MAP</font></i></b></a></li>
	<li><a href="about.html"><b><i><font size="5">ABOUT</font></i></b></a></li>
	<li><a href="CONTACT.html"><b><i><font size="5">CONTACT</font></i></b></a></li>
<!-- Dropdown List --> 
    <li class="dropdown">
	<a href="javascript:void(0)" class="dropbtn"><b><i><font size="5">MORE</font></i></b></a>
	<div class="dropdown-content">
	   <a href="HOME.html"> <b><i><font size="5">SITE 1</font></i></b></a>
	   <a href="about.html"><b><i><font size="5"> SITE 2</font></i></b></a>
	   <a href="CONTACT.html"><b><i> <font size="5">SITE 3</font></i></b></a>
	   <a href="MAP.html"><b><i> <font size="5">SITE 4</font></i></b></a>
	</div>
	</li>
</ul>

<!-- Add Icons -->
<a href="https://www.youtube.com/results?search_query=oil+and+gas+pipeline+" class="fa fa-youtube"></a>
<a href="https://www.instagram.com/?hl=en " class="fa fa-instagram"></a>

<a href=" https://www.google.co.in/?gfe_rd=cr&dcr=0&ei=9uoJWqnqOIry8AfWiIHwAQ" class="fa fa-google"></a>
<a href=" https://in.linkedin.com/" class="fa fa-linkedin"></a>
<a href=" https://www.android.com/" class="fa fa-android"></a>
<a href=" https://web.whatsapp.com/" class="fa fa-whatsapp"></a>
<a href="https://en-gb.facebook.com/?stype=lo&jlou=AfcY7CBqBvVNSGl05SzX9CHSwDAsUOy4A5SBB1oJ0qszb3gGo9glkRhFEpenor9kj_QqlGaPTNM-ZPfRZC8llSVFywe-Bl9r6QmpBLhQ6t2m5w&smuh=25246&lh=Ac8OQ-tZi715rj0Rs" class="fa fa-facebook"></a>
<a href=" https://web.wechat.com/" class="fa fa-wechat"></a>
<!-- on click event --> 
<button onclick="myFunction()"><b><i>CLICK ME</i></b></button>

<p id="demo"></p>
<script>
function myFunction() {
    document.getElementById("demo").innerHTML = "Welcome to my world";
}
</script>

<!-- animation icon -->
<div id="div1" float="right" class="fa"></div>

<script>
function hand() {
  var a;
  a = document.getElementById("div1");
  a.innerHTML = "&#xf25a;";
  setTimeout(function () {
      a.innerHTML = "&#xf256;";
    }, 500);
  setTimeout(function () {
      a.innerHTML = "&#xf259;";
    }, 1000);
  setTimeout(function () {
      a.innerHTML = "&#xf256;";
    }, 1500);
}
hand();
setInterval(hand, 2000);
</script>

<br><br><br><br>
<!-- Style of Side Bar -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
	<br><br>
	<a href="MAP.html"><b><i>Hyderabad</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vijayawada</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vizag</i></b></a>
</div>

<div id="main">
   <span style="font-size:30px;cursor:pointer;color:blue" onclick="openNav()"><b>&#9783 &#9892;</b><b><i><font color="red">CLICK ME</font></i></b></span>
</div>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "rgba(1,0,5,0.4)";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>

<!-- countdown -->
<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 1, 2018 15:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

    // Get todays date and time
    var now = new Date().getTime();
    
    // Find the distance between now an the count down date
    var distance = countDownDate - now;
    
    // Time calculations for days, hours, minutes and seconds
    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    // Output the result in an element with id="demo"
    document.getElementById("demo").innerHTML = days + "d " + hours + "h "
    + minutes + "m " + seconds + "s ";
    
    // If the count down is over, write some text 
    if (distance < 0) {
        clearInterval(x);
        document.getElementById("demo").innerHTML = "EXPIRED";
    }
}, 1000);
</script>


<!-- Introduction -->
<h1 style="text-align:center; color:blue; font-family:verdana; font-size:300%" ><em>INTRODUCTION</em></h1>
<!-- Slidebar Images -->
<div class="w3-content w3-display-container">

<div class="w3-display-container mySlides">
    <img src="Pipeline-Feature.jpg" style="width:980px;height:500px;">
	<div class="w3-display-bottomleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>

<div class="w3-display-container mySlides">
    <img src="pipeline.jpg" style="width:980px;height:500px;">
	<div class="w3-display-topleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>

<div class="w3-display-container mySlides">
    <img src="05_china_-_300.jpg" style="width:980px;height:500px;" >
	<div class="w3-display-bottomleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>

<div class="w3-display-container mySlides">
    <img src="0801-03-18-e1334779453664.jpg" style="width:980px;height:500px;">
	<div class="w3-display-bottomleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>

<div class="w3-display-container mySlides">
    <img src="AAEAAQAAAAAAAAJ7AAAAJGUyMTE5NWE4LWY1NTktNDc1Ni1hYTk2LTMxYThmZDViNzdhMA.jpg" style="width:980px;height:500px;">
	<div class="w3-display-bottomleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>

<div class="w3-display-container mySlides">
    <img src="gas-pipelines-Sleipner-Photo-Kjetil-Alsvik-Statoil.jpg" style="width:980px;height:500px;">
	<div class="w3-display-bottomleft w3-large w3-container w3-paddin-16 w3-red">
<h2><b><i>OIL AND GAS PIPELINE</i></b></h2>
    </div>
</div>
<button class="w3-button w3-display-left w3-red" onclick="plusDivs(-1)"><b><i>CLICK ME</i></b> &#10094;</button>
<button class="w3-button w3-display-right w3-red" onclick="plusDivs(1)"><b><i>CLICK ME</i></b> &#10095;</button>
</div>

<script>
var slideIndex=1;
showDivs(slideIndex);

function plusDivs(n) {
                       showDivs(slideIndex +=n);
                     }		  

function showDivs(n){
                      var i;
                      var x=document.getElementsByClassName("mySlides");	
                      if(n>x.length) {
                                      slideIndex=1
                                      }	
                       if (n<1) {
                                 slideIndex=x.length
                                 }
                       for (i=0; i<x.length; i++) {
                                                    x[i].style.display="none";
                                                   }													
                       x[slideIndex-1].style.display="block";
					  }
</script>

<!-- Paragraph Section -->
<!-- style for arrange in column -->
<div class="row">
  <div class="column side">
    <h2>Side</h2>
	</div>
  <div class="column middle">	
	

<!-- change the color of text on mouse down event -->
	<p id="p1" onmousedown="mouseDown()" onmouseup="mouseUp()">
<b><i> India consists of a vast network of inter and intrastate pipelines that serve a 
vital role in transporting water, hazardous liquids and raw materials. There is an 
estimated 2.6 million miles of pipelines in the nation and it delivers trillions of 
cubic feet of natural gas and hundreds of billions of tons of liquid petroleum products
each year. Because the pipeline network fuels the nation's daily functions and livelihoods 
by delivering resources used for energy purposes, it's crucial to shed light on this 
transportation system. This article briefly discusses oil and gas pipelines, what they are, 
why they exist, their potential health and environmental impacts, proposed projects and who 
oversees them.</i></b></p>
<!-- onmousedown event -->
<script>
function mouseDown() {
    document.getElementById("p1").style.color = "red";
}

function mouseUp() {
    document.getElementById("p1").style.color = "black";
}
</script>

<br>
<h2 style="font-family:verdana; font-size:250%; color:blue;"><em> What are pipelines and what are they used for?</em></h2>

<b><i>The pipeline network in India is a transportation system used to move goods and 
materials. Pipelines transport a variety of products such as sewage and water. However, 
the most common products transported are for energy purposes which include natural gas,
biofuels and liquid petroleum. Pipelines exist throughout the country and they vary 
by the goods transported, the size of the pipes and the material used to make pipes.</i></b></p>

<p><b><i>While some pipelines are built above ground, the majority of pipelines in India 
are buried underground. Because oil and gas pipelines are well concealed from the public,
most individuals are unaware of the existence of the vast network of pipelines.</i></b></p>

<h2 style="font-family:verdana; font-size:250%; color:blue;"><em>Types of Oil and Gas Pipelines</em></h2>
<p><b><i>There are two main categories of pipelines used to transport energy products: <br>
1. Petroleum Pipelines <br>
2. Natural Gas Pipelines <br>
</i></b></p>

<h4 style="font-family:verdana; font-size:150%; color:red;"><b><i>Petroleum Pipelines</i></b></h4>
<p><b><i>It transport crude oil or natural gas liquids and there are three main types of 
petroleum pipelines involved in this process: gathering system, crude oil pipeline system 
and refined products pipelines systems. The gathering pipeline systems gather the crude 
oil or natural gas liquid from the production wells. It's then transported with crude
oil pipeline system to a refinery. Once the petroleum is refined into products such as
gasoline or kerosene, it's transported via the refined products pipeline systems to 
storage or distribution stations.</i></b></p>
<h4 style="font-family:verdana; color:red; font-size:150%;"><em><b><i>Natural Gas Pipelines</i></b></em></h4>
<p><b><i>It transport natural gas from stationary facilities such as gas wells or import/
export facilities and deliver to a variety of locations such as homes or directly to other
export facilities. This process also involves three different types of pipelines: gathering
systems, transmission systems and distribution systems. Similar to the petroleum gathering 
systems, the natural gas gathering pipeline system gathers the raw material from production
wells. IT's then transported with large lines of transmission pipelines what move natural 
gas from facilities to ports, refiners and cities across the country. Lastly, the 
distribution systems consist of a network that distributes the product to homes and 
businesses. The two types of distribution systems are the main distribution line which 
are larger lines that move products close to cities and the service distribution lines 
which are smaller lines that connect main lines into homes and businesses.</i></b></p>



<br>
  </div>
 <!-- Style for arrange in column --> 
  <div class="column side">
    <h2>Side</h2>
  </div>
</div>
<!-- Pagination -->
<div class="pagination">
    <a href="#" ><b><i>&laquo;</i></b></a>
	<a href="home.html" class="active"><b><i>1</i></b></a>
	<a href="map.html"><b><i>2</i></b></a>
	<a href="about.html"><b><i>3</i></b></a>
	<a href="contact.html"><b><i>4</i></b></a>
	<a href="about.html"><b><i>5</i></b></a>
	<a href="home.html"><b><i>6</i></b></a>
	<a href="#"><b><i>&raquo;</i></b></a>
</div>

<!-- Style of Footer -->
<div class="footer">
    <h4 style="color:red;"> <b><i>Copyright</i></b></h4>
	  <h4 style="color:blue; font-family:verdana;"><b><i>[ABOUT][CONTACT]</i></b></h4>
</div>

<!-- Create three different column -->

    
  
  
  



</body>
</html>


About page of customer website

<!DOCTYPE html>
<html>
<head>
<title> Customer Website</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
/* style of rolling wheel */
#container {
  position: absolute;
  left: 80%;
  height: 120px;
  width: 120px;
  border-radius: 50%;
  background: #272727;
}
.circle1 {
  position: relative;
  top: 0px;
  width: 0px;
  height: 0px;
  border-right: 60px solid transparent;
  border-top: 60px solid #1ba7f2;
  border-left: 60px solid transparent;
  border-bottom: 60px solid transparent;
  border-top-left-radius: 60px;
  border-top-right-radius: 60px;
  -moz-transform:rotate(320deg);
  -webkit-transform:rotate(320deg);
  -o-transform:rotate(320deg);
  -ms-transform:rotate(320deg);
  animation: spin1 0.5s infinite linear;
  -webkit-animation: spin1 0.5s infinite linear;
  
}
.circle2 {
  position: absolute;
  top: 0px;
  width: 0px;
  height: 0px;
  border-right: 60px solid transparent;
  border-top: 60px solid #1ba7f2;
  border-left: 60px solid transparent;
  border-bottom: 60px solid transparent;
  border-top-left-radius: 60px;
  border-top-right-radius: 60px;
  -moz-transform:rotate(80deg);
  -webkit-transform:rotate(80deg);
  -o-transform:rotate(80deg);
  -ms-transform:rotate(80deg);
  animation: spin2 0.5s infinite linear;
  -webkit-animation: spin2 0.5s infinite linear;
}
.circle3 {
  position: absolute;
  top: 0px;
  width: 0px;
  height: 0px;
  border-right: 60px solid transparent;
  border-top: 60px solid #1ba7f2;
  border-left: 60px solid transparent;
  border-bottom: 60px solid transparent;
  border-top-left-radius: 60px;
  border-top-right-radius: 60px;
  -moz-transform:rotate(200deg);
  -webkit-transform:rotate(200deg);
  -o-transform:rotate(200deg);
  -ms-transform:rotate(200deg);
  animation: spin3 0.5s infinite linear;
  -webkit-animation: spin3 0.5s infinite linear;
}
/* animations */

@keyframes spin1 {
  0% {
  -moz-transform:rotate(320deg);
  -webkit-transform:rotate(320deg);
  -o-transform:rotate(320deg);
  -ms-transform:rotate(320deg);
  }
  100% {
  -moz-transform:rotate(680deg);
  -webkit-transform:rotate(680deg);
  -o-transform:rotate(680deg);
  -ms-transform:rotate(680deg); 
  }
}
@-webkit-keyframes spin1 {
  0% {
  -moz-transform:rotate(320deg);
  -webkit-transform:rotate(320deg);
  -o-transform:rotate(320deg);
  -ms-transform:rotate(320deg);
  }
  100% {
  -moz-transform:rotate(680deg);
  -webkit-transform:rotate(680deg);
  -o-transform:rotate(680deg);
  -ms-transform:rotate(680deg); 
  }
}
@keyframes spin2 {
  0% {
  -moz-transform:rotate(80deg);
  -webkit-transform:rotate(80deg);
  -o-transform:rotate(80deg);
  -ms-transform:rotate(80deg);
  }
  100% {
  -moz-transform:rotate(440deg);
  -webkit-transform:rotate(440deg);
  -o-transform:rotate(440deg);
  -ms-transform:rotate(440deg); 
  }
}
@-webkit-keyframes spin2 {
  0% {
  -moz-transform:rotate(80deg);
  -webkit-transform:rotate(80deg);
  -o-transform:rotate(80deg);
  -ms-transform:rotate(80deg);
  }
  100% {
  -moz-transform:rotate(440deg);
  -webkit-transform:rotate(440deg);
  -o-transform:rotate(440deg);
  -ms-transform:rotate(440deg); 
  }
}
@keyframes spin3 {
  0% {
  -moz-transform:rotate(200deg);
  -webkit-transform:rotate(200deg);
  -o-transform:rotate(200deg);
  -ms-transform:rotate(200deg);
  }
  100% {
  -moz-transform:rotate(560deg);
  -webkit-transform:rotate(560deg);
  -o-transform:rotate(560deg);
  -ms-transform:rotate(560deg); 
  }
}
@-webkit-keyframes spin3 {
  0% {
  -moz-transform:rotate(200deg);
  -webkit-transform:rotate(200deg);
  -o-transform:rotate(200deg);
  -ms-transform:rotate(200deg);
  }
  100% {
  -moz-transform:rotate(560deg);
  -webkit-transform:rotate(560deg);
  -o-transform:rotate(560deg);
  -ms-transform:rotate(560deg); 
  }
}

/* Style of SideBar */
body { 
      font-family: "Lato", sans-serif;
	  transition: background-color .5s;
	 }

.sidenav {
          height: 100%;
		  width: 0;
		  position: fixed;
		  z-index: 1;
		  top: 0;
		  left: 0;
		  background-color: #BDB76B;
		  overflow-x: hidden;
		  transition: 0.5s;
		  padding-top: 60px;
}

.sidenav a {
            padding: 10px 10px 10px 36px;
			text-decoration: none;
			font-size: 35px;
			color: red;
			display: block;
			transition: 0.3s;
			}
.sidenav a:hover {
                  color: blue;
				  }
.sidenav .closebtn {
                     position: absolute;
					 top: 0;
					 right: 34px;
					 font-size:44px;
					 margin-left: 60px;
					 }
#main {
       transition: margin-left .6s;
	   padding: 20px;
	  }
@media screen and (max-height: 450px) {
                                        .sidenav {
										          padding-top: 20px;
												  }
										.sidenav a { 
										            font-size: 20px;
													}
									   }

/* Style of Social Media Icons */
.fa { 
      text-decoration: none;
	  padding: 20px;
	  width: 80px;
	  font-size: 30px;
	  text-align: center;
	  margin: 6px 3px;
	  border-radius: 38%;
	 }

.fa:hover {
            opacity: 0.7;
		  }
/* Facebook */
.fa-facebook {
              background: #3B5998;
              color:white;
			  float: right;
              }			  
/* YouTube */
.fa-youtube { 
              background: #bb0000;
			  color: white;
			  float:right;
			 }
/* Instagram */
.fa-instagram {
               background: #125688;
			   color: white;
			   float: right;
			   }
/* Whatsapp */
.fa-whatsapp { 
                background: #34af23;
                color: white;
                float: right;
               }
/* Google */			   
.fa-google {
            background: #dd4b39;
            color: white;
			float: right;
           }	
/* Instagram */		   
.fa-linkedin {
              background: #007bb5;
              color: white;
			  float: right;
              }
			  
/* wechat */
.fa-wechat { 
             background: #34af23;
             color: white;
             float: right;
            }			 
			  
/* Android */
.fa-android {
              background: #a4c639;
              color: white;
			  float: right;
            }

/* Style of Search */

.button {
         background-color: red;
		 padding:10px 20px;
		 text-decoration:none;
		 display: inline-block;
		 font-size: 16px;
		 margin: 4px 2px;
		 cursor: pointer;
		 border-radius: 25px;
		 box-shadow: 0 9px #999;
		 }
		 
input[type=text]  {
                   width: 82%;
				   box-sizing: border-box;
				   border: 4px solid red;
				   border-radius: 25px;
				   font-size: 16px;
				   background-color: white;
				   background-image: url('searchicon.png');
				   background-repeat: no-repeat;
				   padding: 12px 20px 12px 40px;
				   -webkit-transition: width 0.2s ease-in-out;
				   transition: width 0.2s ease-in-out;
				   }
input[type=text]:focus {
                       width: 75%;
                       }					   
.button:hover { 
               background-color: MediumSeaGreen
               }
.button:active {
			     background-color: yellow;
				 box-shadow: 0 10px blue;
				 transform: translateY(5px);
				}

body { 
       background-image: url(" Rough-Grey-Tilable-Pattern-For-Website-Background.jpg");
	  }
body { 
      margin: 0;
	  }
/* Style the header */
.header { 
         background-color: slateblue;
		 padding: 1px;
         text-align: center;
         }
		 
/* Style of Navigation Bar */
ul  { 
     list-style-type: none;
	 background-color: #4B0082;
	 padding: 0px;
	 margin: 0px;
	 overflow: hidden;
	 }
/* write flows Horizontally */
li   {
      float: left;
	  }
li a {
      text-decoration: none;
	  padding: 16px 108px;
	  display: block;
	  color: #FFD700;
	  }
li a:hover {
            background-color: red;
			}
	 
/* Style of Dropdown List */

li a, .dropbtn  { 
                 display: inline-block;
				 }
li a:hover, .dropdown:hover .dropbtn {
                                       background- color: red;
                                      }
li.dropdown { 
             display: inline-block;
             }
.dropdown-content { 
                   display: none;
                   position: absolute;
                   background-color: #DAA520;
				   min-width: 297px;
				   box-shadow: 3px 8px 16px 3px rgb(60, 60, 60);
				   z-index: 1;
				   }
.dropdown-content a {
                     color: black;
                     padding: 16px 65px;
                     text-decoration: none;
                     display: block;
                     text-align: left;
                     }					 
.dropdown-content a:hover { 
                           background-color: slateblue;
                           }
.dropdown:hover .dropdown-content { 
                                   display: block;
                                  }		

/* Style of pagination */

.pagination { 
             display:inline-block;
             }
.pagination a {
               text-decoration:none;
			   padding:12px 20px;
			   margin:1px;
			   color:black;
			   float:left;
			   transition:background-color .3s;
			   border: 3px solid black;
			   font-size: 26px;
			   }
			   
.pagination a.active {
                      background-color: red;
					  color:white;
					  border: 3px solid red;
					  }
 
.pagination a:hover:not(.active) {
                                 background-color:blue;
								 }
								 
/* Style of Footer */
.footer {
         border: 10px solid #191970;
         padding: 15px;
         text-align:center;
         }		 
		 
/* style of text shadow */
h1 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}
h4 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}								  
</style>		 
</head>

<body>
<!-- Header Content --> 
<div class="header">
<img src="logo.png" style ="float:left;width:150px;height:75px;">
    <h1>
<form action="http://www.google.com/search" class="navbar-form navbar-left" method="get" name="searchform" target="_blank">
    <input name="sitesearch" type="hidden" value="">
   <input autocomplete="on" class="form-controls search"  id="myInput" onsearch="myFunction()" name="search" placeholder="Explore..." required="required" type="text">
	<button class="button" type="submit">GO</button>
	<!-- On search event --> 
<p id="demo"></p>

<script>
function myFunction() {
   var x = document.getElementById("myInput");
   document.getElementById("demo").innerHTML = "You are searching for: " + x.value;
}
</script>
</form>     
</h1> 
</div>
<!-- Navigation Bar -->
<ul> 
    <li><a class="active" href="HOME.html"><b><i><font size="5">HOME</font></i></b></a></li>
	<li><a href="MAP.html"><b><i><font size="5">MAP</font></i></b></a></li>
	<li><a href="about.html"><b><i><font size="5">ABOUT</font></i></b></a></li>
	<li><a href="CONTACT.html"><b><i><font size="5">CONTACT</font></i></b></a></li>
<!-- Dropdown List --> 
    <li class="dropdown">
	<a href="javascript:void(0)" class="dropbtn"><b><i><font size="5">MORE</font></i></b></a>
	<div class="dropdown-content">
	   <a href="HOME.html"> <b><i><font size="5">SITE 1</font></i></b></a>
	   <a href="about.html"><b><i><font size="5"> SITE 2</font></i></b></a>
	   <a href="CONTACT.html"><b><i> <font size="5">SITE 3</font></i></b></a>
	   <a href="MAP.html"><b><i> <font size="5">SITE 4</font></i></b></a>
	</div>
	</li>
</ul>

<!-- Add Icons -->

<a href="https://www.youtube.com/results?search_query=oil+and+gas+pipeline+" class="fa fa-youtube"></a>
<a href="https://www.instagram.com/?hl=en " class="fa fa-instagram"></a>

<a href=" https://www.google.co.in/?gfe_rd=cr&dcr=0&ei=9uoJWqnqOIry8AfWiIHwAQ" class="fa fa-google"></a>
<a href=" https://in.linkedin.com/" class="fa fa-linkedin"></a>
<a href=" https://www.android.com/" class="fa fa-android"></a>
<a href=" https://web.whatsapp.com/" class="fa fa-whatsapp"></a>
<a href="https://en-gb.facebook.com/?stype=lo&jlou=AfcY7CBqBvVNSGl05SzX9CHSwDAsUOy4A5SBB1oJ0qszb3gGo9glkRhFEpenor9kj_QqlGaPTNM-ZPfRZC8llSVFywe-Bl9r6QmpBLhQ6t2m5w&smuh=25246&lh=Ac8OQ-tZi715rj0Rs" class="fa fa-facebook"></a>
<a href=" https://web.wechat.com/" class="fa fa-wechat"></a>

<br><br><br><br>
<!-- Style of Side Bar -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
	<a href="MAP.html"><b><i>Hyderabad</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vijayawada</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vizag</i></b></a>
</div>

<div id="main">
  <span style="font-size:30px;cursor:pointer;color:blue" onclick="openNav()"><b>&#9783 &#9892;</b><b><i><font color="red">CLICK ME</font></i></b></span>
</div>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "rgba(1,0,5,0.4)";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>
<!-- Add rolling wheel -->
<div id="container">
  <div class="circle1">
  </div>
  <div class="circle2">
  </div>
  <div class="circle3">
  </div>
</div>


<!-- About -->
<h1 style="font-family:verdana; font-size:300%; color:blue; text-align:center;"><em><b>ABOUT<b></em></h1>
<h4 style="font-family:verdana; font-size:200%; color: red;"><em><b>PROFILE</b></em></h4>
<p><b><i>The story of ACE traces and symbolises the development and growth of the Indian 
petroleum industry. From the discovery of crude oil in the far east of India at Digboi, 
Assam in 1889 to its present status as a fully integrated upstream petroleum company, ACE
has come far, crossing many milestones.</i></b></p>
<p><b><i>On February 18, 1959, ACE was incorporated to expand and develop the newly 
discovered oil fields of Naharkatiya and Moran in the Indian North East. In 1961, it 
became a joint venture company between the Indian Government and Burmah ACE,UK.</i></b></p>
<p><b><i> In 1981, ACE became a wholly-owned Government of India enterprise. Today, ACE is 
a premier Indian National Oil company engaged in the business of exploration, development
and production of crude oil and natural gas, transportation of crude oil and production
of LPG. ACE also provides various E & p related services and holds 26% equity in 
Numaligarh Refinery Limited.</i></b></p>

<p><b><i>ACE has over 1 lakh sq km of PEL/ML areas for its exploration and production 
activities, most of it in the Indian North East, which accounts for its entire crude oil
production and majority of gas production. Rajasthan is the other producting area of ACE,
contributing 10% of its total gas production.</i></b></p>

<p style="font-family:verdana; font-size:200%; color:red;"><em><b>VISION</b></em></p>
<p style="font-family:verdana; font-size:160%; color:blue;"><em><b>Core Purpose</b></em></p>
<p><b><i>> ACE is the fastest growing Energy Company with highest profitability.</i></b></p>
<p><b><i> > ACE delights the customers with quality products and services at competitive
prices.</i></b></p>
<p><b><i>> ACE is fully committed to safety, health and environment.</i></b></p>
<p><b><i>ACE is a responsible corporate citizen deeply committed to socio-economic 
development in its areas of operations.</i></b></p>

<!-- Pagination -->
<div class="pagination">
    <a href="#" ><b><i>&laquo;</i></b></a>
	<a href="home.html" class="active"><b><i>1</i></b></a>
	<a href="map.html"><b><i>2</i></b></a>
	<a href="about.html"><b><i>3</i></b></a>
	<a href="contact.html"><b><i>4</i></b></a>
	<a href="about.html"><b><i>5</i></b></a>
	<a href="home.html"><b><i>6</i></b></a>
	<a href="#"><b><i>&raquo;</i></b></a>
</div>

<!-- Style of Footer -->
<div class="footer">
    <h4 style="color:red;"> <b><i>Copyright</i></b></h4>
	  <h4 style="color:blue; font-family:verdana;"><b><i>[ABOUT][CONTACT]</i></b></h4>
</div>
</body>
</html>


Map page of customer website

<!DOCTYPE html>
<html>
<head>
<title> Customer Website</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="viewport" content="initial-scale=1.0, user-scalable=no">
<meta charset="utf-8">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

		 
input[type=text]  {
                   width: 20%;
				   box-sizing: border-box;
				   border: 4px solid red;
				   border-radius: 25px;
				   font-size: 16px;
				   background-color: white;
				   background-image: url('searchicon.png');
				   background-repeat: no-repeat;
				   padding: 12px 20px 12px 40px;
				   -webkit-transition: width 0.2s ease-in-out;
				   transition: width 0.2s ease-in-out;
				   }
input[type=text]:focus {
                       width: 25%;
                       }

h2 { 
    text-align: center;
	}
#right-panel {
              font-family: 'Roboto','sans-serif';
              line-height: 35px;
              padding-left: 15px;
             }

#right-panel select, #right-panel input {
                                         font-size: 17px;
                                         }

#right-panel select {
                     width: 100%;
                    }

#right-panel i {
                font-size: 12px;
               }
html, body {
             height: 100%;
             margin: 0;
             padding: 0;
           }
#map {
        height: 75%;
        float: right;
        width: 75%;
        height: 75%;
     }
#right-panel {
              margin: 20px;
              border-width: 2px;
              width: 20%;
              height: 400px;
              float: left;
              text-align: left;
              padding-top: 0;
             }
#directions-panel {
                   margin-top: 10px;
                   background-color:#F5CBA7;
                   padding: 30px;
                   overflow: scroll;
                   height: 180px;
                  }


/* Style of SideBar */
body { 
      font-family: "Lato", sans-serif;
	  transition: background-color .5s;
	 }

.sidenav {
          height: 100%;
		  width: 0;
		  position: fixed;
		  z-index: 1;
		  top: 0;
		  left: 0;
		  background-color: #BDB76B;
		  overflow-x: hidden;
		  transition: 0.5s;
		  padding-top: 60px;
}

.sidenav a {
            padding: 10px 10px 10px 36px;
			text-decoration: none;
			font-size: 35px;
			color: red;
			display: block;
			transition: 0.3s;
			}
.sidenav a:hover {
                  color: blue;
				  }
.sidenav .closebtn {
                     position: absolute;
					 top: 0;
					 right: 34px;
					 font-size:70px;
					 margin-left: 60px;
					 }
#main {
       transition: margin-left .6s;
	   padding: 20px;
	  }
@media screen and (max-height: 450px) {
                                        .sidenav {
										          padding-top: 20px;
												  }
										.sidenav a { 
										            font-size: 20px;
													}
									   }


/* Style of Social Media Icons */
.fa { 
      text-decoration: none;
	  padding: 20px;
	  width: 80px;
	  font-size: 30px;
	  text-align: center;
	  margin: 6px 3px;
	  border-radius: 38%;
	 }

.fa:hover {
            opacity: 0.7;
		  }
/* Facebook */
.fa-facebook {
              background: #3B5998;
              color:white;
			  float: right;
              }			  
/* YouTube */
.fa-youtube { 
              background: #bb0000;
			  color: white;
			  float:right;
			 }
/* Instagram */
.fa-instagram {
               background: #125688;
			   color: white;
			   float: right;
			   }
/* Whatsapp */
.fa-whatsapp { 
                background: #34af23;
                color: white;
                float: right;
               }
/* Google */			   
.fa-google {
            background: #dd4b39;
            color: white;
			float: right;
           }	
/* Instagram */		   
.fa-linkedin {
              background: #007bb5;
              color: white;
			  float: right;
              }
			  
/* wechat */
.fa-wechat { 
             background: #34af23;
             color: white;
             float: right;
            }			 
			  
/* Android */
.fa-android {
              background: #a4c639;
              color: white;
			  float: right;
            }

/* Style of Search */

.button1 {
         background-color: red;
		 padding:10px 20px;
		 text-decoration:none;
		 display: inline-block;
		 font-size: 16px;
		 margin: 4px 2px;
		 cursor: pointer;
		 border-radius: 25px;
		 box-shadow: 0 9px #999;
		 }
		 
input[type=text1]  {
                   width: 82%;
				   box-sizing: border-box;
				   border: 4px solid red;
				   border-radius: 25px;
				   font-size: 16px;
				   background-color: white;
				   background-image: url('searchicon.png');
				   background-repeat: no-repeat;
				   padding: 12px 20px 12px 40px;
				   -webkit-transition: width 0.2s ease-in-out;
				   transition: width 0.2s ease-in-out;
				   }
input[type=text1]:focus {
                       width: 75%;
                       }					   
.button:hover { 
               background-color: MediumSeaGreen
               }
.button:active {
			     background-color: yellow;
				 box-shadow: 0 10px blue;
				 transform: translateY(5px);
				}

body { 
       background-image: url(" Rough-Grey-Tilable-Pattern-For-Website-Background.jpg");
	  }
body { 
      margin: 0;
	  }
/* Style the header */
.header { 
         background-color: slateblue;
		 padding: 1px;
         text-align: center;
         }
		 
/* Style of Navigation Bar */
ul  { 
     list-style-type: none;
	 background-color: #4B0082;
	 padding: 0px;
	 margin: 0px;
	 overflow: hidden;
	 }
/* write flows Horizontally */
li   {
      float: left;
	  }
li a {
      text-decoration: none;
	  padding: 16px 108px;
	  display: block;
	  color: #FFD700;
	  }
li a:hover {
            background-color: red;
			}
	 
/* Style of Dropdown List */

li a, .dropbtn  { 
                 display: inline-block;
				 }
li a:hover, .dropdown:hover .dropbtn {
                                       background- color: red;
                                      }
li.dropdown { 
             display: inline-block;
             }
.dropdown-content { 
                   display: none;
                   position: absolute;
                   background-color: #DAA520;
				   min-width: 297px;
				   box-shadow: 3px 8px 16px 3px rgb(60, 60, 60);
				   z-index: 1;
				   }
.dropdown-content a {
                     color: black;
                     padding: 16px 65px;
                     text-decoration: none;
                     display: block;
                     text-align: left;
                     }					 
.dropdown-content a:hover { 
                           background-color: slateblue;
                           }
.dropdown:hover .dropdown-content { 
                                   display: block;
                                  }		

/* Style of pagination */

.pagination { 
             display:inline-block;
             }
.pagination a {
               text-decoration:none;
			   padding:12px 20px;
			   margin:1px;
			   color:black;
			   float:left;
			   transition:background-color .3s;
			   border: 3px solid black;
			   font-size: 26px;
			   }
			   
.pagination a.active {
                      background-color: red;
					  color:white;
					  border: 3px solid red;
					  }
 
.pagination a:hover:not(.active) {
                                 background-color:blue;
								 }
								  
/* Style of Footer */
.footer {
         border: 10px solid #191970;
         padding: 15px;
         text-align:center;
         }		 
		 
/* style of text shadow */
h1 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}

   
</style>		 
</head>

<body>
<!-- Header Content --> 
<div class="header">
<img src="logo.png" style ="float:left;width:150px;height:75px;">
    <h1>
<form action="http://www.google.com/search" class="navbar-form navbar-left" method="get" name="searchform" target="_blank">
    <input name="sitesearch" type="hidden" value="">
    <input autocomplete="on" class="form-controls search"  id="myInput" onsearch="myFunction()" name="search" placeholder="Explore..." required="required" type="text1">
	<button class="button1" type="submit">GO</button>
	<!-- On search event --> 
<p id="demo"></p>

<script>
function myFunction() {
   var x = document.getElementById("myInput");
   document.getElementById("demo").innerHTML = "You are searching for: " + x.value;
}
</script>
</form>   
</h1> 
</div>


<!-- Navigation Bar -->
<ul> 
    <li><a class="active" href="HOME.html"><b><i><font size="5">HOME</font></i></b></a></li>
	<li><a href="MAP.html"><b><i><font size="5">MAP</font></i></b></a></li>
	<li><a href="about.html"><b><i><font size="5">ABOUT</font></i></b></a></li>
	<li><a href="CONTACT.html"><b><i><font size="5">CONTACT</font></i></b></a></li>
<!-- Dropdown List --> 
    <li class="dropdown">
	<a href="javascript:void(0)" class="dropbtn"><b><i><font size="5">MORE</font></i></b></a>
	<div class="dropdown-content">
	   <a href="HOME.html"> <b><i><font size="5">SITE 1</font></i></b></a>
	   <a href="about.html"><b><i><font size="5"> SITE 2</font></i></b></a>
	   <a href="CONTACT.html"><b><i> <font size="5">SITE 3</font></i></b></a>
	   <a href="MAP.html"><b><i> <font size="5">SITE 4</font></i></b></a>
	</div>
	</li>
</ul>
<!-- Add Icons -->

<a href="https://www.youtube.com/results?search_query=oil+and+gas+pipeline+" class="fa fa-youtube"></a>
<a href="https://www.instagram.com/?hl=en " class="fa fa-instagram"></a>

<a href=" https://www.google.co.in/?gfe_rd=cr&dcr=0&ei=9uoJWqnqOIry8AfWiIHwAQ" class="fa fa-google"></a>
<a href=" https://in.linkedin.com/" class="fa fa-linkedin"></a>
<a href=" https://www.android.com/" class="fa fa-android"></a>
<a href=" https://web.whatsapp.com/" class="fa fa-whatsapp"></a>
<a href="https://en-gb.facebook.com/?stype=lo&jlou=AfcY7CBqBvVNSGl05SzX9CHSwDAsUOy4A5SBB1oJ0qszb3gGo9glkRhFEpenor9kj_QqlGaPTNM-ZPfRZC8llSVFywe-Bl9r6QmpBLhQ6t2m5w&smuh=25246&lh=Ac8OQ-tZi715rj0Rs" class="fa fa-facebook"></a>
<a href=" https://web.wechat.com/" class="fa fa-wechat"></a>

<br><br><br><br><br>
<!-- Style of Side Bar -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
	<br><br>
	<a href="MAP.html"><b><i>Hyderabad</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vijayawada</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vizag</i></b></a>
</div>

<div id="main">
  <span style="font-size:30px;cursor:pointer;color:blue" onclick="openNav()"><b>&#9783 &#9892;</b><b><i><font color="red">CLICK ME</font></i></b></span>
</div>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "rgba(1,0,5,0.4)";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>



<h1 style="text-align:center; color:blue; font-family:verdana; font-size:300%" ><em><b>MAP</b></em></h1>
<div id="map" style="width:100%;height:500px"></div>

<script>
function myMap() {
  var Hyderabad = new google.maps.LatLng(17.387140,78.491684);
  var Vijayawada = new google.maps.LatLng(16.515099,80.632095);
  var Vizag = new google.maps.LatLng(17.6868159,83.2184815);

  var mapCanvas = document.getElementById("map");
  var mapOptions = {center: Vijayawada, zoom: 7};
  var map = new google.maps.Map(mapCanvas,mapOptions);
    

  var flightPath = new google.maps.Polyline({
    path: [Hyderabad, Vijayawada, Vizag],
    strokeColor: "#0000FF",
    strokeOpacity: 0.8,
    strokeWeight: 5

  });
   var marker = new google.maps.Marker({
          position: Hyderabad,
          map: map
        });
		var infowindow = new google.maps.InfoWindow({
    content: "Hyderabad Latitude:17.387140 , Longitude: 78.491684"
  });
  infowindow.open(map,marker);

		var marker = new google.maps.Marker({
          position: Vijayawada,
          map: map
        });
		var infowindow = new google.maps.InfoWindow({
    content: "Vijayawada Latitude: 16.515099, Longitude: 80.632095"
  });
  infowindow.open(map,marker);
		var marker = new google.maps.Marker({
          position: Vizag,
          map: map
        });
		var infowindow = new google.maps.InfoWindow({
    content: "Vizag Latitude:17.6868159 , Longitude: 83.2184815"
  });
  infowindow.open(map,marker);
  flightPath.setMap(map);
}
</script>


<!-- code of calculations-->
<h2><font size="10" color="red"><a href="calculations.html"><b>Calculations<b></a></font></h2>
<div id="map"></div>
    <div id="right-panel">
    <div>
    <h3><font size="5"><b>START:</b></font></h3>
    <select id="start">
	 <option value="Hyderabad">Hyderabad</option>
      <option value="Vijayawaada">Vijayawaada</option>
      <option value="Vishakhapatnam">Vishakhapatnam</option>
     
    </select>
    <br>
	<h3><b>WAYPOINTS:</b> </h3><br>
    <h4><i>(Ctrl+Click or Cmd+Click for multiple selection)</i></h4> <br>
    <select multiple id="waypoints">
      <option value="Dwaraka Tirumala">Dwaraka Tirumala</option>
      <option value="Eluru">Eluru</option>
    </select>
    <br>
    <h3><b>END:</b></h3>
    <select id="end">
      <option value="Vijayawaada">Vijayawaada</option>
      <option value="Vishakhapatnam">Vishakhapatnam</option>
      <option value="Hyderabad">Hyderabad</option>
    </select>
    <br>
	<input type="submit" id="submit">
    </div>
    <div id="directions-panel"></div>
    </div>
	<script>
      function initMap() {
        var directionsService = new google.maps.DirectionsService;
        var directionsDisplay = new google.maps.DirectionsRenderer;
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 7,
          center: {lat: 16.5062, lng: 80.6480}
        });
          
        directionsDisplay.setMap(map);

        document.getElementById('submit').addEventListener('click', function() {
          calculateAndDisplayRoute(directionsService, directionsDisplay);
        });
      }

      function calculateAndDisplayRoute(directionsService, directionsDisplay) {
        var waypts = [];
        var checkboxArray = document.getElementById('waypoints');
        for (var i = 0; i < checkboxArray.length; i++) {
          if (checkboxArray.options[i].selected) {
            waypts.push({
              location: checkboxArray[i].value,
              stopover: true
            });
          }
        }

        directionsService.route({
          origin: document.getElementById('start').value,
          destination: document.getElementById('end').value,
          waypoints: waypts,
          optimizeWaypoints: true,
          travelMode: 'DRIVING'
        }, function(response, status) {
          if (status === 'OK') {
            directionsDisplay.setDirections(response);
            var route = response.routes[0];
            var summaryPanel = document.getElementById('directions-panel');
            summaryPanel.innerHTML = '';
            // For each route, display summary information.
            for (var i = 0; i < route.legs.length; i++) {
              var routeSegment = i + 1;
              summaryPanel.innerHTML += '<b>Route Segment: ' + routeSegment +
                  '</b><br>';
              summaryPanel.innerHTML += route.legs[i].start_address + ' to ';
              summaryPanel.innerHTML += route.legs[i].end_address + '<br>';
              summaryPanel.innerHTML += route.legs[i].distance.text + '<br><br>';
            }
          } else {
            window.alert('Directions request failed due to ' + status);
          }
        });
      }
	  
    </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAiE1ZCpEycxbll9qBp_zMo6Us-n941Heg&callback=initMap">
    </script>
	
	<script language="javascript">
                function multiplyNumbers()
                {
                        var a = 12.56;
                        var b = parseInt(document.getElementById("value2").value);
                        var c = parseInt(document.getElementById("value3").value);
                        var ansD = document.getElementById("answer");
                        ansD.value = 12.56*b;
                    var ansE = document.getElementById("answer1");
                        ansE.value = 12.56*b/c;  

                    
                }
</script>
<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p> <font size="5" color="black" align="center">Enter two number between two distances=</p> 
<input type="text" id="value2" name="value2" value="0"/>
 <p>Volume of Pipeline between selected points = <input type="text" id="answer" name="answer" value=""/> 
Cubic Kilometers.</p>
<br>
<font size="5" color="black" align="center">Enter the number of robots=</p1> 
<input type="text" id="value3" name="value3" value="2"/>
<input type="button" name="Sumbit" value="Here we go" 
onclick="javascript:multiplyNumbers()"/><br><br>
<p>Number of hours required= <input type="text" id="answer1" name="answer1" value=""/> 
Cubic Kilometers.</p>
<br>
<br><br><br>
<!-- Pagination -->
<div class="pagination">
    <a href="#" ><b><i>&laquo;</i></b></a>
	<a href="home.html" class="active"><b><i>1</i></b></a>
	<a href="map.html"><b><i>2</i></b></a>
	<a href="about.html"><b><i>3</i></b></a>
	<a href="contact.html"><b><i>4</i></b></a>
	<a href="about.html"><b><i>5</i></b></a>
	<a href="home.html"><b><i>6</i></b></a>
	<a href="#"><b><i>&raquo;</i></b></a>
</div>


<!-- Style of Footer -->
<div class="footer">
    <h4 style="color:red;"> <b><i>Copyright</i></b></h4>
	  <h4 style="color:blue; font-family:verdana;"><b><i>[ABOUT][CONTACT]</i></b></h4>
</div>
</body>
</html>


Contact page of customer website

<!DOCTYPE html>
<html>
<head>
<title> Customer Website</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
/* style of loader */
.loader {
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid blue;
  border-right: 16px solid green;
  border-bottom: 16px solid red;
  border-left: 16px solid pink;
  width: 120px;
  height: 120px;
  -webkit-animation: spin 2s linear infinite;
  animation: spin 2s linear infinite;
}

@-webkit-keyframes spin {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* style of form */
body {
    font-family: Arial;
}

* {
    box-sizing: border-box;
}

/* Style inputs */
input[type=sf], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #45a049;
}

/* Style the container/contact section */
.container {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 10px;
}

/* Create two columns that float next to eachother */
.column {
    float: left;
    width: 50%;
    margin-top: 6px;
    padding: 20px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media (max-width: 600px) {
    .column, input[type=submit] {
        width: 100%;
        margin-top: 0;
    }
}

#div1 {
  font-size:80px;
}

/* style of Login Form      Full-width input fields */
input[type=login], input[type=password] {
                                        width: 100%;
                                        padding: 15px 25px;
                                        margin: 8px 0px;
                                        display: inline-block;
                                        border: 5px solid #ccc;
                                        box-sizing: border-box;
                                        }
/* Set a style for all buttons */
button  {
        background-color: green;
        color: white;
        padding: 15px 21px;
        margin: 10px 0;
        border: none;
        cursor: pointer;
		
        }

button:hover {
              opacity: 0.9;
              }
/* Extra styles for the cancel button */
.cancelbtn {
            width: auto;
            padding: 15px 21px;
            background-color: red;
            }

/* Center the image and position the close button */
.imgcontainer {
               text-align: center;
               margin: 24px 0 12px 0;
               position: relative;
              }

img.avatar {
            width: 60%;
            border-radius: 60%;
            }

.container {
            padding: 16px;
           }

span.psw {
          float: right;
          padding-top: 16px;
          }

/* The Modal (background) */
.modal {
        display: none; /* Hidden by default */
        position: fixed; /* Stay in place */
        z-index: 1; /* Sit on top */
        left: 0;
        top: 0;
        width: 100%; /* Full width */
        height: 100%; /* Full height */
        overflow: auto; /* Enable scroll if needed */
        background-color: rgb(0,0,0); /* Fallback color */
        background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
        padding-top: 60px;
        }

/* Modal Content/Box */
.modal-content {
                background-color: #7DCEA0;
                margin: 10% auto 20% auto; /* 5% from the top, 15% from the bottom and centered */
                border: 5px solid #888;
                width: 80%; /* Could be more or less, depending on screen size */
                }

/* The Close Button (x) */
.close {
        position: absolute;
        right: 35px;
        top: 0;
        color: red;
        font-size: 45px;
        font-weight: bold;
        }

.close:hover,
.close:focus {
              color: red;
              cursor: pointer;
              }

/* Add Zoom Animation */
.animate {
          -webkit-animation: animatezoom 0.8s;
          animation: animatezoom 0.8s
          }

@-webkit-keyframes animatezoom {
                                from {-webkit-transform: scale(0)} 
                                to {-webkit-transform: scale(1)}
                                }
    
@keyframes animatezoom {
                        from {transform: scale(0)} 
                        to {transform: scale(1)}
                        }

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
                                      span.psw {
                                                  display: block;
                                                  float: none;
                                                }
.cancelbtn {
            width: 100%;
    }
}

/* Style of SideBar */
body { 
      font-family: "Lato", sans-serif;
	  transition: background-color .5s;
	 }

.sidenav {
          height: 100%;
		  width: 0;
		  position: fixed;
		  z-index: 1;
		  top: 0;
		  left: 0;
		  background-color: #BDB76B;
		  overflow-x: hidden;
		  transition: 0.5s;
		  padding-top: 60px;
}

.sidenav a {
            padding: 10px 10px 10px 36px;
			text-decoration: none;
			font-size: 35px;
			color: red;
			display: block;
			transition: 0.3s;
			}
.sidenav a:hover {
                  color: blue;
				  }
.sidenav .closebtn {
                     position: absolute;
					 top: 0;
					 right: 34px;
					 font-size:70px;
					 margin-left: 60px;
					 }
#main {
       transition: margin-left .6s;
	   padding: 20px;
	  }
@media screen and (max-height: 450px) {
                                        .sidenav {
										          padding-top: 20px;
												  }
										.sidenav a { 
										            font-size: 20px;
													}
									   }


/* Style of Social Media Icons */
.fa { 
      text-decoration: none;
	  padding: 20px;
	  width: 80px;
	  font-size: 30px;
	  text-align: center;
	  margin: 6px 3px;
	  border-radius: 38%;
	 }

.fa:hover {
            opacity: 0.7;
		  }
/* Facebook */
.fa-facebook {
              background: #3B5998;
              color:white;
			  float: right;
              }			  
/* YouTube */
.fa-youtube { 
              background: #bb0000;
			  color: white;
			  float:right;
			 }
/* Instagram */
.fa-instagram {
               background: #125688;
			   color: white;
			   float: right;
			   }
/* Whatsapp */
.fa-whatsapp { 
                background: #34af23;
                color: white;
                float: right;
               }
/* Google */			   
.fa-google {
            background: #dd4b39;
            color: white;
			float: right;
           }	
/* Instagram */		   
.fa-linkedin {
              background: #007bb5;
              color: white;
			  float: right;
              }
			  
/* wechat */
.fa-wechat { 
             background: #34af23;
             color: white;
             float: right;
            }			 
			  
/* Android */
.fa-android {
              background: #a4c639;
              color: white;
			  float: right;
            }

/* Style of Search */

.button {
         background-color: red;
		 padding:10px 20px;
		 text-decoration:none;
		 display: inline-block;
		 font-size: 16px;
		 margin: 4px 2px;
		 cursor: pointer;
		 border-radius: 25px;
		 box-shadow: 0 9px #999;
		 }
		 
input[type=text]  {
                   width: 82%;
				   box-sizing: border-box;
				   border: 4px solid red;
				   border-radius: 25px;
				   font-size: 16px;
				   background-color: white;
				   background-image: url('searchicon.png');
				   background-repeat: no-repeat;
				   padding: 12px 20px 12px 40px;
				   -webkit-transition: width 0.2s ease-in-out;
				   transition: width 0.2s ease-in-out;
				   }
input[type=text]:focus {
                       width: 75%;
                       }					   
.button:hover { 
               background-color: MediumSeaGreen
               }
.button:active {
			     background-color: yellow;
				 box-shadow: 0 10px blue;
				 transform: translateY(5px);
				}

body { 
       background-image: url(" Rough-Grey-Tilable-Pattern-For-Website-Background.jpg");
	  }
body { 
      margin: 0;
	  }
/* Style the header */
.header { 
         background-color: slateblue;
		 padding: 1px;
         text-align: center;
         }
		 
/* Style of Navigation Bar */
ul  { 
     list-style-type: none;
	 background-color: #4B0082;
	 padding: 0px;
	 margin: 0px;
	 overflow: hidden;
	 }
/* write flows Horizontally */
li   {
      float: left;
	  }
li a {
      text-decoration: none;
	  padding: 16px 108px;
	  display: block;
	  color: #FFD700;
	  }
li a:hover {
            background-color: red;
			}
	 
/* Style of Dropdown List */

li a, .dropbtn  { 
                 display: inline-block;
				 }
li a:hover, .dropdown:hover .dropbtn {
                                       background- color: red;
                                      }
li.dropdown { 
             display: inline-block;
             }
.dropdown-content { 
                   display: none;
                   position: absolute;
                   background-color: #DAA520;
				   min-width: 297px;
				   box-shadow: 3px 8px 16px 3px rgb(60, 60, 60);
				   z-index: 1;
				   }
.dropdown-content a {
                     color: black;
                     padding: 16px 65px;
                     text-decoration: none;
                     display: block;
                     text-align: left;
                     }					 
.dropdown-content a:hover { 
                           background-color: slateblue;
                           }
.dropdown:hover .dropdown-content { 
                                   display: block;
                                  }		

								  /* Style of pagination */

.pagination { 
             display:inline-block;
             }
.pagination a {
               text-decoration:none;
			   padding:12px 20px;
			   margin:1px;
			   color:black;
			   float:left;
			   transition:background-color .3s;
			   border: 3px solid black;
			   font-size: 26px;
			   }
			   
.pagination a.active {
                      background-color: red;
					  color:white;
					  border: 3px solid red;
					  }
 
.pagination a:hover:not(.active) {
                                 background-color:blue;
								 }
								  

/* Style of Footer */
.footer {
         border: 10px solid #191970;
         padding: 15px;
         text-align:center;
         }		 
		 
/* style of text shadow */
h1 {
    text-shadow: 0 0 5px red, 0 0 7px red;
	}

/* Color of link */
a {
   color: blue;
   }
   
</style>		 
</head>

<body>
<!-- Header Content --> 
<div class="header">
<img src="logo.png" style ="float:left;width:150px;height:75px;">
    <h1>
<form action="http://www.google.com/search" class="navbar-form navbar-left" method="get" name="searchform" target="_blank">
    <input name="sitesearch" type="hidden" value="">
    <input autocomplete="on" class="form-controls search" name="q" type="text" id="myInput" placeholder="Explore..." required="required">
	<button class="button" type="submit">GO</button>
	<!-- On search event --> 
<p id="demo"></p>

<script>
function myFunction() {
   var x = document.getElementById("myInput");
   document.getElementById("demo").innerHTML = "You are searching for: " + x.value;
}
</script>	
</form>     
</h1> 
</div>
<!-- Navigation Bar -->
<ul> 
    <li><a class="active" href="HOME.html"><b><i><font size="5">HOME</font></i></b></a></li>
	<li><a href="MAP.html"><b><i><font size="5">MAP</font></i></b></a></li>
	<li><a href="about.html"><b><i><font size="5">ABOUT</font></i></b></a></li>
	<li><a href="CONTACT.html"><b><i><font size="5">CONTACT</font></i></b></a></li>
<!-- Dropdown List --> 
    <li class="dropdown">
	<a href="javascript:void(0)" class="dropbtn"><b><i><font size="5">MORE</font></i></b></a>
	<div class="dropdown-content">
	    <a href="HOME.html"> <b><i><font size="5">SITE 1</font></i></b></a>
	   <a href="about.html"><b><i><font size="5"> SITE 2</font></i></b></a>
	   <a href="CONTACT.html"><b><i> <font size="5">SITE 3</font></i></b></a>
	   <a href="MAP.html"><b><i> <font size="5">SITE 4</font></i></b></a>
	</div>
	</li>
</ul>
<!-- Add Icons -->

<a href="https://www.youtube.com/results?search_query=oil+and+gas+pipeline+" class="fa fa-youtube"></a>
<a href="https://www.instagram.com/?hl=en " class="fa fa-instagram"></a>

<a href=" https://www.google.co.in/?gfe_rd=cr&dcr=0&ei=9uoJWqnqOIry8AfWiIHwAQ" class="fa fa-google"></a>
<a href=" https://in.linkedin.com/" class="fa fa-linkedin"></a>
<a href=" https://www.android.com/" class="fa fa-android"></a>
<a href=" https://web.whatsapp.com/" class="fa fa-whatsapp"></a>
<a href="https://en-gb.facebook.com/?stype=lo&jlou=AfcY7CBqBvVNSGl05SzX9CHSwDAsUOy4A5SBB1oJ0qszb3gGo9glkRhFEpenor9kj_QqlGaPTNM-ZPfRZC8llSVFywe-Bl9r6QmpBLhQ6t2m5w&smuh=25246&lh=Ac8OQ-tZi715rj0Rs" class="fa fa-facebook"></a>
<a href=" https://web.wechat.com/" class="fa fa-wechat"></a>

<br><br><br><br>
<!-- Style of Side Bar -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
	<br><br>
	<a href="MAP.html"><b><i>Hyderabad</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vijayawada</i></b></a><br><br><br><br>
    <a href="MAP.html"><b><i>Vizag</i></b></a>
</div>

<div id="main">
    <span style="font-size:30px;cursor:pointer;color:blue" onclick="openNav()"><b>&#9783 &#9892;</b><b><i><font color="red">CLICK ME</font></i></b></span>
</div>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "rgba(1,0,5,0.4)";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>
<! -- add loader -->
<div class="loader"></div>

<!-- Add Login Form -->
<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button>

<div id="id01" class="modal">
  
  <form class="modal-content animate" action="/action_page.php">
    <div class="imgcontainer">
      <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
      <img src="avatar1_big@2x.png" alt="Avatar" class="avatar">
    </div>

    <div class="container">
      <label><b><i>Username</i></b></label><br>
      <input type="login" placeholder="Enter Username"  name="username" required><br>
	  
      <label><b><i>Password</i></b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
        
      <button type="submit" ><b>Login</b></button>
	  <button type="reset" > <font color="red" size="4"><b><i>Reset</i></b></font></style></button>
	  <script>
function myFunction() {
    alert("The form was reset");
}
</script>
<br>
      

               <input type="checkbox" checked="checked">	  <b><i> Remember me </i></b>
    </div>

    <div class="container" style="background-color:#f1f1f1">
      <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn"><b>Cancel</b></button>
      <span class="psw"><b><i>Forgot</i></b> <a href="#">password?</a></span>
    </div>
  </form>
</div>



<script>
// Get the modal
var modal = document.getElementById('id01');

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>
<!-- Animated icons -->
<div id="div1" class="fa"></div>

<script>
function hand() {
  var a;
  a = document.getElementById("div1");
  a.innerHTML = "&#xf25a;";
  setTimeout(function () {
      a.innerHTML = "&#xf256;";
    }, 500);
  setTimeout(function () {
      a.innerHTML = "&#xf259;";
    }, 1000);
  setTimeout(function () {
      a.innerHTML = "&#xf256;";
    }, 1500);
}
hand();
setInterval(hand, 2000);
</script>

<h1 style="font-family:verdana; color:blue; font-size:300%; text-align:center;"><em><b>CONTACT</b></em></h1>
<p><b><i>Email Address: <a href="default.asp" target="_blank">shanu.walia.111@gmail.com</a></i></b></p>
<p><b><i>Mobile No. : +91 78760-34007</i></b></p>
<p><b><i>Address: MMU, Mullana, Haryana, India.</i></b></p>

<!-- add submit form -->
<div class="container">
 
  <div class="row">
    <div class="column">
      <div id="map" style="width:100%;height:500px"></div>
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="fname">First Name</label>
        <input type="sf" id="fname" name="firstname" placeholder="Your name..">
        <label for="lname">Last Name</label>
        <input type="sf" id="lname" name="lastname" placeholder="Your last name..">
        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="australia">Australia</option>
          <option value="india">India</option>
          <option value="usa">USA</option>
		  <option value="canada">Canada</option>
		  <option value="newzealand">Newzealand</option>
		  <option value="myanmar">Myanmar</option>
		  <option value="russia">Russia</option>
		  <option value="thailand">Thailand</option>
		  <option value="singapore">Singapore</option>
        </select>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</div>

<script>
// Initialize google maps
function myMap() {
  var myCenter = new google.maps.LatLng(51.508742,-0.120850);
  var mapCanvas = document.getElementById("map");
  var mapOptions = {center: myCenter, zoom: 12};
  var map = new google.maps.Map(mapCanvas, mapOptions);
  var marker = new google.maps.Marker({position:myCenter});
  marker.setMap(map);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBv4nchG4TnY8uUk22mByskFhxfgse48Lo&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->
<br><br><br><br><br><br><br><br><br><br><br><br><br>

<!-- Pagination -->
<div class="pagination">
    <a href="#" ><b><i>&laquo;</i></b></a>
	<a href="home.html" class="active"><b><i>1</i></b></a>
	<a href="map.html"><b><i>2</i></b></a>
	<a href="about.html"><b><i>3</i></b></a>
	<a href="contact.html"><b><i>4</i></b></a>
	<a href="about.html"><b><i>5</i></b></a>
	<a href="home.html"><b><i>6</i></b></a>
	<a href="#"><b><i>&raquo;</i></b></a>
</div>

<!-- Style of Footer -->
<div class="footer">
    <h4 style="color:red;"> <b><i>Copyright</i></b></h4>
	  <h4 style="color:blue; font-family:verdana;"><b><i>[ABOUT][CONTACT]</i></b></h4>
</div>
</body>
</html>


