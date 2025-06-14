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
<b>approaches</b> (e.g., ecoinformatics, phylogenetic comparative methods, 
genomics, fieldwork, experiments).

<br><br>

I am currently a <b>Walter Benjamin Postdoctoral Fellow</b> at UCLA, 
kindly funded by the <a href='https://www.dfg.de/en'>German Research Foundation</a>. 
Here, I work with <a href='https://pinterwollmanlab.eeb.ucla.edu/'>Noa Pinter-Wollman</a> 
to investigate how the social behavior of ants responds to changes in temperature.

<br><br>

Prior to this, I was an EMBO Postdoctoral Fellow at <a href='https://tbg.senckenberg.de/hillerlab/'>Michael Hiller's group</a>, 
working on the evolution of torpor across mammals and birds. My PhD was 
on the thermal adaptation of microbes (mainly), under the supervision of
<a href='https://profiles.imperial.ac.uk/s.pawar'>Samraat Pawar</a>, 
<a href='https://www.biology.ox.ac.uk/people/tim-barraclough'>Tim Barraclough</a>, 
and <a href='https://profiles.imperial.ac.uk/c.prentice'>Colin Prentice</a>.

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

<!--
<div class="mySlides fade">
  <img src="images/publications/word_network.png" style="width:80%">
  <div class="text"><font size = '3.5' color = "#000000">Network of semantically related terms from the abstracts of my papers.</font></div>
</div>
-->

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
<!--  <span class="dot" onclick="currentSlide(3)"></span> -->
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
