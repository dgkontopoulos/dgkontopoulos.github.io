---
permalink: /
title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify;">

<font size = "3.5">
Hello there! My name is Dimitrios - Georgios Kontopoulos and I am 
an <b>integrative biologist</b>, focusing on how various biological 
systems respond to environmental changes.

<br><br>
My research spans <b>levels of biological organization</b> (from molecules to ecosystems), 
<b>taxonomic groups</b> (from microbes to birds and mammals), 
<b>timescales</b> (from seconds to millions of years), and 
<b>methodological approaches</b> (e.g., ecoinformatics, phylogenetic comparative methods, 
comparative genomics, machine learning).

<br><br>

I am currently a <b>postdoctoral fellow</b> at the 
<a href="https://tbg.senckenberg.de/hillerlab/">Hiller group of LOEWE-TBG</a>, 
investigating the genomic, physiological, and ecological drivers of 
dormancy across birds and mammals. Prior to this, I did a PhD at 
Imperial College London (primarily supervised by <a href="https://pawarlab.org">Samraat Pawar</a>), in 
which I mainly examined how microbial growth rate responds to changes in 
temperature across species and environments.

<br><br>
For more information, click on the tabs at the top of this page.
</font>
</div>

<br>

<div class="slideshow-container">

<center>

<div class="mySlides fade">
  <img src="images/publications/wordcloud.png" style="width:80%">
  <div class="text"><font size = '3.5' color = "#000000">Word cloud based on the abstracts of my papers.</font></div>
</div>

<div class="mySlides fade">
  <img src="images/publications/word_network.png" style="width:80%">
  <div class="text"><font size = '3.5' color = "#000000">Network of semantically related terms from the abstracts of my papers.</font></div>
</div>

<div class="mySlides fade">
  <img src="images/Volos.jpg" style="width:80%">
  <div class="text"><font size = "3.5" style = "text-shadow:1px 1px #000000"><b>A gorgeous panoramic photo of 
Volos, Greece, my hometown.</b></font><br><br><font size = "2.5" style = "text-shadow:1px 1px #000000">By Tsints (https://bit.ly/2iOtksL), CC BY-SA 3.0.</font></div>
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
