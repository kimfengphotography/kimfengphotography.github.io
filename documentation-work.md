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
.mySlides1 .mySlides2 .mySlides3 .mySlides4 {display: none}
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
@media only screen and (max-width: 1080px) {
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

<p class="title"><strong>Documentation Work</strong></p>

<!-- slideshow -->

<div class="slideshow-container" id="container1">

<div class="container">

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53929095277_9ce54f167c_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maximilian Harley, <i>Waiting on a kingfisher</i>, 2024
    <br><i>Abstraction</i>, Compendium Gallery, Armadale, VIC</div>
  </div>

  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53930243213_13c0424aa3_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maximilian Harley, <i>Symplegma</i>, 2024
    <br><i>Abstraction</i>, Compendium Gallery, Armadale, VIC</div>
  </div>
 
  <div class="mySlides1 fade">
    <img src="https://live.staticflickr.com/65535/53930450200_c5e352a51c_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,0)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,0)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maximilian Harley, <i>Untitled (... eyes like ripening fruit)</i>, 2024
    <br><i>Abstraction</i>, Compendium Gallery, Armadale, VIC</div>
  </div>

</div>


<br>
<br>
<br>
<br>



<div class="slideshow-container" id="container2">

<div class="container">

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53930000815_c5a6bf226d_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53929549881_6580c8752d_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53929549866_89adae2abf_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53930000595_da80e1590e_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53928647922_3ece17cff1_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53929893289_4ca6f8866a_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53929893259_ae9709c955_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

  <div class="mySlides2 fade">
    <img src="https://live.staticflickr.com/65535/53930000905_2b5c7c7e87_k.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,1)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, 2024
    <br><i>I Confide In Your Texture</i>, Oddany Gallery, Collingwood, VIC</div>
  </div>

</div>


<br>
<br>
<br>
<br>


<div class="slideshow-container" id="container3">

<div class="container">

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388758_2e7eab3335_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860557150_edc083bdb6_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388683_8b8b754243_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860557120_70666c44df_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388748_cbd50c3c84_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388708_f0c5dc593d_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860510819_ba1f9703af_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388718_feb4ce248b_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre"><i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel<br><br><br></div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860139601_48054ed68e_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Genevieve Elliot, <i>ThoughtFormsLeather</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860557170_1781cb01de_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Genevieve Elliot, <i>ThoughtFormsLeather</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53859246222_d6ff352e3c_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Genevieve Elliot, <i>ThoughtFormsLeather</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860388753_5aa72dea2c_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Genevieve Elliot, <i>ThoughtFormsLeather</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>
  
  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53859246127_c6794d86f9_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maddison Wandel, <i>a calling back</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860139501_9842eae6c0_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maddison Wandel, <i>a calling back</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

  <div class="mySlides3 fade">
    <img src="https://live.staticflickr.com/65535/53860557100_039b7e00aa_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,2)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,2)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Maddison Wandel, <i>a calling back</i>, 2024<br><br>
        Shown at <i>Forest Falls Behind</i>, Green Floor Gallery, Fitzroy, VIC<br><br>
        Curators: Maddison Wandel and Lily Fforde<br><br>
        Exhibiting artists: Maddison Wandel, Lily Fforde, Ruth Höflich, Genevieve Elliot, and Ishika Kinzel</div>
  </div>

</div>


<br>
<br>
<br>
<br>




<div class="slideshow-container" id="container4">

<div class="container">

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860579215_a0536cabbf_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Sean Monaghan, <i>Raw Wood, Uncut Silk</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860576485_84b27f529b_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Sean Monaghan, <i>Raw Wood, Uncut Silk</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860579295_52bdc68812_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Sean Monaghan, <i>Raw Wood, Uncut Silk</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860161616_a0536cabbf_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Sean Monaghan, installation of <i>Armed With Many Warnings</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53859268812_486e4c8ba6_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Simone Lee, <i>Untitled</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
      <img src="https://live.staticflickr.com/65535/53859268897_e6e9d90c7e_o.jpg" style="width:100%">
      <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Keiran Molaeb, <i>We All Share The Same Sky</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860161701_3af777aaf5_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Keiran Molaeb, <i>We All Share The Same Sky</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860161571_0c540aaf25_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Trinh Dang, <i>I’m Feeling in Bien Hoa</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860532884_c805754429_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Trinh Dang, <i>shhhh, đi ngủ</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860579155_fa6f63df84_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Trinh Dang, <i>I’m Feeling in Bien Hoa</i>, 2024</div>
  </div>

  <div class="mySlides4 fade">
    <img src="https://live.staticflickr.com/65535/53860532879_bea2e01433_o.jpg" style="width:100%">
    <div class="centeredButtons">
        <a class="prev" onclick="plusSlides(-1,3)">&#10094;</a>
        <a class="next" onclick="plusSlides(1,3)">&#10095;</a>
    </div>
    <div class="bodytext-centre">Tess Rogers, <i>Hamish</i> (left) and <i>Teeth</i> (right),2024</div>
  </div>

</div>


<br>


<script>
let slideIndex = [1,1,1,1];
let slideId = ["mySlides1", "mySlides2", "mySlides3", "mySlides4"]
showSlides(1, 0);
showSlides(1, 1);
showSlides(1, 2);
showSlides(1, 3);

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