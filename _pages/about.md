---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify;">

<font size = "3.5">
Hello there! My name is Dimitrios - Georgios Kontopoulos and I am 
an <b>evolutionary biologist</b>, mainly focusing on how temperature 
changes influence biological systems.

<br><br>
I started my studies with a BSc in Molecular Biology and Genetics from the 
<a href="http://mbg.duth.gr/index.php/en/">Democritus University of 
Thrace</a>, followed by an MRes in Biodiversity Informatics and 
Genomics from Imperial College London. I then 
pursued a PhD degree at Imperial College London (primarily 
supervised by <a href="http://pawarlab.org">Samraat Pawar</a>), in 
which I examined likely constraints on thermal adaptation, 
mainly across microbial species.
<br><br>
I am currently an <b>EMBO postdoctoral fellow</b> at the 
<a href="https://tbg.senckenberg.de/hillerlab/">Hiller group of LOEWE-TBG</a>, 
investigating the genomic, physiological, and ecological drivers of 
dormancy across birds and mammals.
<br><br>
For more information, click on the tabs at the top of this page.
</font>
</div>

<br>

<div class="slideshow-container">

<center>

<div class="mySlides fade">
  <img src="images/Volos.jpg" style="width:80%">
  <div class="text"><font size = "3.5" style = "text-shadow:1px 1px #000000"><b>A gorgeous panoramic photo of 
Volos, Greece, my hometown.</b></font><br><br><font size = "2.5" style = "text-shadow:1px 1px #000000">By Tsints (http://bit.ly/2iOtksL), CC BY-SA 3.0.</font></div>
</div>

<div class="mySlides fade">
  <img src="images/publications/wordcloud.png" style="width:80%">
  <div class="text"><font size = '3.5' color = "#000000">Word cloud based on the abstracts of my papers.</font></div>
</div>

<div class="mySlides fade">
  <img src="images/publications/word_network.png" style="width:80%">
  <div class="text"><font size = '3.5' color = "#000000">Network of semantically related terms from the abstracts of my papers.</font></div>
</div>
</center>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
