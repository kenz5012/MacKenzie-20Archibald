<!-->contact.html-->

<!doctype html>

<html>

<head>

<title>Photography Website Title</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<h1>My Portfolio Website</h1>

</header>

<nav>

<ul>

<li><a href="index.html">Home Page</a></li>

<li><a href="gallery.html">Gallery Page</a></li>

<li><a href="portfolio.html">Portfolio Page</a></li>

<li><a href="hobbies.html">My Hobbies</a></li>

<li><a href="contact.html">Contact Me</a></li>

</ul>

</nav>

<img class="photographer" src="images/camera.png" alt="">

<div class="content">

<h2>How to Contact Me, and I will contact you</h2>

<p>Fill in the form below and press Submit when done. </p>

<div class="container">

<form action="">

<label for="fname">First Name</label>

<input type="text" id="fname" name="firstname" placeholder="Your name..">

<label for="lname">Last Name</label>

<input type="text" id="lname" name="lastname" placeholder="Your last name..">

<label for="regarding">Regarding</label>

<select id="regarding" name="regarding">

<option value="photography">Photography</option>

<option value="videoedit">Video Editing</option>

<option value="graphics">Graphics Design</option>

<option value="general">General Things</option>

</select>

<label for="subject">Subject</label>

<textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

<input type="submit" value="Submit">

</form>

</div>

</div>

</body>

</html>

<!--gallery.html-->

<!doctype html>

<html>

<head>

<title>Photography Website Title</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<h1>My Portfolio Website</h1>

</header>

<nav>

<ul>

<li><a href="index.html">Home Page</a></li>

<li><a href="gallery.html">Gallery Page</a></li>

<li><a href="portfolio.html">Portfolio Page</a></li>

<li><a href="hobbies.html">My Hobbies</a></li>

<li><a href="contact.html">Contact Me</a></li>

</ul>

</nav>

<img class="photographer" src="images/camera.png" alt="">

<div class="content">

<h2>This is my Gallery.</h2>

<div class="photoGallery" style="max-width:80%">

<img class="mySlides" src="images/gallery/beach-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/butterfly-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/castle-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/cat-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/chicken-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/duck-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/landscape-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/lighthouse-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/milkshake-image.jpg" style="width:100%">

<img class="mySlides" src="images/gallery/rabbit-image.jpg" style="width:100%">

<div class="leftButton" onclick="plusDivs(-1)"><img src="images/leftArrow.png" alt="left arrow"></div>

<div class="rightButton" onclick="plusDivs(1)"><img src="images/nextArrow.png" alt="left arrow"></div>

</div>

</div>

<script>

var slideIndex = 1; // creating a variable called slide index

showDivs(slideIndex); // calling the show show divs function with the slide index in it

//this is the plus divs function

function plusDivs(n) {

showDivs(slideIndex += n);

}

// this is the current div function

function currentDiv(n) {

showDivs(slideIndex = n);

}

// this is the show divs functions

function showDivs(n) {

var i; // local variable called i

var x = document.getElementsByClassName("mySlides");

// this is the variable called x

// in this variable we will hold the my slides div

// we are identifying the div using the class element

if (n > x.length) {slideIndex = 1}

// if we have gone through all of the images then we reset back to first one.

if (n < 1) {slideIndex = x.length}

// if we have gone below the number of images we have then we reset back to the first one.

// below is the for loop which will go through x and show only the one present

// it will hide rest of the images from view.

for (i = 0; i < x.length; i++)

{

x[i].style.display = "none"; // we are changing the display style to none

// this will make it invisible from the screen

}

x[slideIndex-1].style.display = "block";  

// this will show only 1 image

}

</script>

</body>

</html>

<!-- hobbies.html-->

<!doctype html>

<html>

<head>

<title>Photography Website Title</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<h1>My Portfolio Website</h1>

</header>

<nav>

<ul>

<li><a href="index.html">Home Page</a></li>

<li><a href="gallery.html">Gallery Page</a></li>

<li><a href="portfolio.html">Portfolio Page</a></li>

<li><a href="hobbies.html">My Hobbies</a></li>

<li><a href="contact.html">Contact Me</a></li>

</ul>

</nav>

<img class="photographer" src="images/camera.png" alt="">

<div class="content">

<h2>My Hobbies and things I like</h2>

<div class="hobbies">

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/P9YNl1urDyE" frameborder="0" allowfullscreen></iframe>

</div>

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/sglxMjjGnYU" frameborder="0" allowfullscreen></iframe>

</div>

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/4mx8EMlUMlw" frameborder="0" allowfullscreen></iframe>

</div>

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/DZcMTnmFbo4" frameborder="0" allowfullscreen></iframe>

</div>

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/2fW4_mPYvJY" frameborder="0" allowfullscreen></iframe>

</div>

<div class="videos">

<iframe width="560" height="315" src="https://www.youtube.com/embed/nFuc_wEL3oQ" frameborder="0" allowfullscreen></iframe>

</div>

</div>

</div>

</body>

</html>

<!--index.html-->

<!doctype html>

<html>

<head>

<title>Photography Website Title</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<h1>My Portfolio Website</h1>

</header>

<nav>

<ul>

<li><a href="index.html">Home Page</a></li>

<li><a href="gallery.html">Gallery Page</a></li>

<li><a href="portfolio.html">Portfolio Page</a></li>

<li><a href="hobbies.html">My Hobbies</a></li>

<li><a href="contact.html">Contact Me</a></li>

</ul>

</nav>

<img class="photographer" src="images/camera.png" alt="">

<div class="content">

<h2>Second heading for the Home Page</h2>

<p>Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info </p>

<p>Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info </p>

<p>Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info </p>

</div>

</body>

</html>

<!-- portfoli.html-->

<!doctype html>

<html>

<head>

<title>Photography Website Title</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<h1>My Portfolio Website</h1>

</header>

<nav>

<ul>

<li><a href="index.html">Home Page</a></li>

<li><a href="gallery.html">Gallery Page</a></li>

<li><a href="portfolio.html">Portfolio Page</a></li>

<li><a href="hobbies.html">My Hobbies</a></li>

<li><a href="contact.html">Contact Me</a></li>

</ul>

</nav>

<img class="photographer" src="images/camera.png" alt="">

<div class="content">

<h2>Stuff I did and Proud Of</h2>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/batman.jpg" alt="" width="150px"></div>

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/redposter.jpg" alt="" width="150px"></div

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/teamwork.jpg" alt="" width="150px"></div>

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/web1.jpg" alt="" width="150px"></div>

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/web2.jpg" alt="" width="150px"></div>

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

<div class="portfolio">

<div class="pImage"><img src="images/portfolio/web3.jpg" alt="" width="150px"></div>

<span class="pInfo">Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info Info</span>

</div>

<div style="clear: both;"></div>

</div>

</body>

</html>

<!--style.css-->

html,body,h1, h2, h3, p, div, li, ul

{

margin: 0px;

padding: 0px;

font-family: Arial;

color: yellow;

letter-spacing: 2px;

text-shadow: -1px 0 white, 0 1px white, 1px 0 white, 0 -1px white;

}

html, body

{

height:100%;

}

html

{

background: url(images/background.jpg) no-repeat center center fixed;

-webkit-background-size: cover;

-moz-background-size: cover;

-o-background-size: cover;

background-size: cover;

}

header

{

width: 100%;

height: 10%;

text-align: center;

}

header h1

{

position: relative;

top: 50%;

transform: translateY(-50%);

}

nav

{

width: 15%;

height: 80%;

float: left;

}

nav ul

{

list-style: none;

}

nav li

{

font-size: 16pt;

display: block;

margin-left: 10px;

padding: 5px;

margin-top: 15px;

width: 80%;

text-align: center;

}

nav a:link, a:visited {

background-color: #000;

color: white;

padding: 14px 25px;

text-align: center;

text-decoration: none;

display: block;

width: 80%;

transition: box-shadow .3s;

}

nav a:hover, a:active {

background-color: #21212c;

box-shadow: 0 0 11px #fffa69;

}

p

{

line-height: 30px;

margin-left: 15px;

margin-right: 15px;

margin-top: 5%;

}

.content

{

padding-top: 10px;

padding-left: 5%;

width: 80%;

height: 80%;

float: left;

}

footer

{

width: 100%;

background: red;

height: 10%;

}

/* Style inputs with type="text", select elements and textareas */

input[type=text], select, textarea {

width: 100%; /* Full width */

padding: 12px; /* Some padding */  

border: 1px solid #ccc; /* Gray border */

border-radius: 4px; /* Rounded borders */

box-sizing: border-box; /* Make sure that padding and width stays in place */

margin-top: 6px; /* Add a top margin */

margin-bottom: 16px; /* Bottom margin */

resize: vertical; /* Allow the user to vertically resize the textarea (not horizontally) */

font-family: Arial;

}

/* Style the submit button with a specific background color etc */

input[type=submit] {

background-color: #000;

color: white;

padding: 12px 20px;

border: none;

border-radius: 4px;

cursor: pointer;

transition: box-shadow .3s;

}

/* When moving the mouse over the submit button, add a darker green color */

input[type=submit]:hover {

background-color: #21212c;

box-shadow: 0 0 11px #fffa69;

}

/* Add a background color and some padding around the form */

.container {

border-radius: 5px;

padding: 20px;

width: 60%;

}

.mySlides

{

height: 700px;

box-shadow: 0 0 11px #fffa69;

}

.leftButton

{

position: absolute;

float: left;

font-size: 20pt;

cursor:pointer

}

.rightButton

{

font-size: 20pt;

clear: both;

float: right;

cursor:pointer

}

.photoGallery

{

margin-top: 20px;

margin-left: auto;

margin-right: auto;

}

.portfolio

{

width: 80%;

clear: both;

margin-top: 15px;

background-image: url("images/bgPort.jpg");

background-attachment: fixed;

height: 250px;

box-shadow: 0 0 5px lightblue;

}

.pImage

{

padding: 10px;

margin-top: 10px;

width: 150px;

float: left;

}

.pInfo

{

clear: both;

position: relative;

top: 40%;

transform: translateY(-40%);

}

.videos

{

margin-top: 15px;

margin-left: 5%;

box-shadow: 0 0 5px pink;

width: 560px;

float: left;

}

.hobbies

{

width: 100%;

}

.photographer

{

position: fixed;

bottom: -10px;

left: 0px;

}
