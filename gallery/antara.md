<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

<title> kim feng photography </title>
<link rel="shortcut icon" type="img/jpeg" href="https://live.staticflickr.com/65535/53860844264_1e7a52a33d_o.jpg"/>

<link href='https://fonts.googleapis.com/css?family=Open Sans:400,400italic,600,600italic|Inconsolata' rel='stylesheet' type='text/css'>
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.6.0/css/font-awesome.min.css">

<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&display=swap" rel="stylesheet">

<style>
.nav {
    display: block;
    font-size: 13px;
    color: #646060;
    font-family: 'Open Sans', serif;
    border-bottom: 1px solid #eee;
    padding-top: 10px;
    padding-bottom: 9px;
    padding-right:20px;
    line-height: 180%;
    text-align: left;
}

.navSub {
    padding-left:20px;
}

.active {
    display: none;
}

#homeTitle {
  position: fixed;
  font-size: 18px;
  font-family: 'Playfair Display', serif;
  color: #b20005;
  text-align: left;
  padding-left:20px;
  padding-top: 10px;
  padding-bottom: 9px;
  padding-right:10px;
}

* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides1 .mySlides2 {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
    height: 100%;
    width: 100%;
}

#container1 {
    position:absolute;
}

#container2 {
    position:absolute;
}

#container3 {
    position:absolute;
}

#container4 {
    position:absolute;
}

#container5 {
    position:absolute;
}

#container6 {
    position:absolute;
}

img {
  max-width: 100%;
  max-height: 70vh;
  width: auto;
  position: relative;
  margin-top: 1%;
  margin-bottom: 1%;
  margin-left: auto;
  margin-right: auto;
  object-fit: contain;
}

.centeredButtons {
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Next & previous buttons */
.prev, .next {
  text-align: center;
  cursor: pointer;
  position: relative;
  width: auto;
  padding: 16px;
  display: inline-block;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* Next & previous buttons */
/*.prev1, .next1, .prev2, .next2, .prev3, .next3, .prev4, .next4, .prev5, .next5 {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}*/

/* Position the "next button" to the right */
/*.next1, .next2, .next3, .next4, .next5 {
  right: 0;
  border-radius: 3px 0 0 3px;
}*/

/* On hover, add a black background color with a little bit see-through */
/* .prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
} */

/* Caption text */
.text {
  font-size: 20px;
  padding: 3px 12px;
  position: absolute;
  width: 100%;
  text-align: center;
  font-family: 'Playfair Display', serif;
}

.title {
  font-size: 25px;
  padding: 3px 12px;
  position: relative;
  width: 100%;
  text-align: center;
  font-family: 'Playfair Display', serif;
  color: #b20005;

}

.subtitle {
  font-size: 17px;
  padding: 3px 12px;
  position: relative;
  width: 100%;
  text-align: center;
  font-family: 'Playfair Display', serif;
}

.bodytext {
  font-size: 15px;
  color: 282828;
  font-weight: 400;
  padding: 3px 20vw;
  position: relative;
  width: 100%;
  text-align: left;
  font-family: 'Open Sans', serif;
  -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    font-smoothing:antialiased;
}

.bodytext-centre {
  font-size: 15px;
  color: 282828;
  font-weight: 400;
  padding: 3px 20vw;
  position: relative;
  width: 100%;
  text-align: center;
  font-family: 'Open Sans', serif;
  -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    font-smoothing:antialiased;
}

.bodytext-skinny{
  font-size: 15px;
  color: 282828;
  font-weight: 400;
  padding: 3px 30vw;
  position: relative;
  width: 100%;
  text-align: left;
  font-family: 'Open Sans', serif;
  -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    font-smoothing:antialiased;
}

div.a {
  text-indent: 50px;
}

/* old bodytext
.bodytext {
  font-size: 15px;
  padding: 3px 12px;
  position: relative;
  width: 100%;
  text-align: center;
  font-family: 'Playfair Display', serif;
}
*/

a:link, a:visited {
  color: #646060;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: #b20005;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: #f5b673;
  background-color: transparent;
  text-decoration: underline;
}

.audio-video {
    text-align: center;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

/* @-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
} */

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 15px}
}

@media only screen and (max-width: 1200px) {
  img {max-height: 30vh; min-height: 30vh;}
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: transparent;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: transparent;
}
</style>
</head>
<body>

<a id="homeTitle" href="https://kimfengphotography.tumblr.com/">kim feng photography</a>

<br>
<br>
 
<div class="nav">
  <a class="navSub" href="https://kimfengphotography.tumblr.com/gallery">art practice</a>
  <a class="navSub" href="https://kimfengphotography.tumblr.com/documentation-work">documentation work</a>
  <a class="navSub" href="https://kimfengphotography.tumblr.com/about">about</a>
</div>

<p class="title"><strong>Antara</strong></p>
<p class="subtitle"><em>2024</em></p>

<!-- slideshow -->
<div class="slideshow-container" id="container1">

<div class="container">

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53708302827_678e2a3f17_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Kampung Bukit Cina, Melaka</div>
        <div class="bodytext-centre">Kodak Vision 3 250D 120
            <br>December 2023
            <br>
            <br>C-type print
            <br>Kodak Endura, W40xH30cm
            <br>May 2024</div>
      </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53709219696_3709ca914f_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Ah Chor (1919–)</div>
    <div class="bodytext-centre">Ilford HP5 120
            <br>December 2023
            <br>
            <br>Silver gelatin print
            <br>Ilford RC Pearl, W40xH30cm
            <br>March 2024</div>
      </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53709648300_11bc58588e_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Sungai Sitiawan Mangrove</div>
        <div class="bodytext-centre">Kodak Vision 3 250D 120
            <br>December 2023
            <br>
            <br>C-type print
            <br>Kodak Endura, W40xH30cm
            <br>May 2024</div>
      </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53709427178_30338fcdea_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Kampung Cina, Sitiawan</div>
    <div class="bodytext-centre">Ilford HP5 120
            <br>December 2023
            <br>
            <br>Silver gelatin print
            <br>Ilford RC Pearl, W40xH30cm
            <br>March 2024</div>
    </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53709648405_24bb7a5195_b.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Kampung Cina, Sitiawan</div>
        <div class="bodytext-centre">Kodak Vision 3 250D 120
            <br>December 2023
            <br>
            <br>C-type print
            <br>Kodak Endura, W40xH30cm
            <br>May 2024</div>
     </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53708302767_e17dd92163_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Ikan Bilis, Sungai Pinang Kecil, Pulau Pangkor</div>
        <div class="bodytext-centre">Ilford HP5 120
            <br>December 2023
            <br>
            <br>Silver gelatin print
            <br>Ilford RC Pearl, W40xH30cm
            <br>March 2024</div>
     </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53803093117_6250295f19_b.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="subtitle">Roomsheet</div>
        <div class="bodytext-centre">Screen print on Hahnemuhle
            <br>Set of 9, W22xH16cm each
            <br>May 2024<br><br><br><br></div>
     </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53756822378_a91945e95a_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
        <div class="subtitle">Darkroom prints</div>
        <div class="bodytext-centre">Installation views<br><br><br><br><br><br></div>
     </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53756947984_8f7bfa126e_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
        <div class="subtitle">Darkroom prints</div>
        <div class="bodytext-centre">Installation views<br><br><br><br><br><br></div>
     </div>

</div>

<br>
<br>
<br>
<br>

<div class="slideshow-container" id="container2">

<div class="container">

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53708306727_68326f22e5_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="subtitle">Cili Kari Rempah</div>
        <div class="bodytext-centre">Kodak Gold 135
            <br>2019
            <br>Scan</div>
     </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53756822408_29b5b35f11_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
        <div class="subtitle">Cili Kari Rempah</div>
        <div class="bodytext-centre">Installation view<br><br><br></div>
     </div>
     
</div>

<br>
<br>
<br>
<br>

<div class="slideshow-container" id="container3">

<div class="container">

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53755713922_308931789a_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="subtitle">Blindboxes</div>
        <div class="bodytext-centre">May 2024
        <br>Set of 8, W28xH28xD13cm each.
        <br><br>Magnetic closure cardboard boxes, flyscreen, cheesecloth, polyester thread, cloth tape, LED tea lights, tissue, assorted ingredients (daun limau purut, serai, daun kesum, udang kering, bawang putih, bawang merah kecil, daun kari, kerisik).</div>
     </div>
     
       <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53756822383_ab64441481_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="subtitle">Blindboxes</div>
        <div class="bodytext-centre">Installation views in the low-light room.
        <br><br>Playing on speakers: 1 minute looping audio of myself talking in Manglish combined with samples of my Mum doing food prep. Script written in collaboration with my Mum, Aunty Joanne, and Farah.</div>
     </div>

       <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53756622841_9a35b3a68b_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="subtitle">Blindboxes</div>
        <div class="bodytext-centre">Installation views in the low-light room.
        <br><br>Playing on speakers: 1 minute looping audio of myself talking in Manglish combined with samples of my Mum doing food prep. Script written in collaboration with my Mum, Aunty Joanne, and Farah.</div>
     </div>

</div>

<script>
let slideIndex = [1,1,1];
let slideId = ["mySlides1", "mySlides2", "mySlides3"]
showSlides(1, 0);
showSlides(1, 1);
showSlides(1, 2);

function plusSlides(n, no) {
  showSlides(slideIndex[no] += n, no);
}

function showSlides(n, no) {
  let i;
  let x = document.getElementsByClassName(slideId[no]);
  if (n > x.length) {slideIndex[no] = 1}    
  if (n < 1) {slideIndex[no] = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex[no]-1].style.display = "block";  
}
</script>

</body>
</html> 