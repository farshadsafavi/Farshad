---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<style>
img {
  float: left;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
.sidenav {
  height: 100%;
  width: 160px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  padding-top: 20px;
}

.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
}

.sidenav a:hover {
  color: #f1f1f1;
}

.main {
  margin-left: 160px; /* Same as the width of the sidenav */
  font-size: 28px; /* Increased text to enable scrolling */
  padding: 0px 10px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
<div class="sidenav">
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#clients">Clients</a>
  <a href="#contact">Contact</a>
</div>
<div class="clearfix">
<img src="assets/Farshad.jpg" alt="Pineapple" style="width:250px;height:250px;margin-right:15px;">
My name is Farshad Safavi. I have Master of computer engineering from University of Toronto. I earned my bachelor of Electrical Engineering from Carleton University. I am very interested to research on Artificial Inteligence and Machine Learning.<br>
I am a computer engineer who has a great passion about building software products using Artificial Intelligence (AI). I have developed and deployed various large scaled software products. I am currently developing software to architect different deep learning models including convolutional neural networks(CNN) , recurrent neural networks(RNN) and generative adversarial networks(GAN) using Python and PyTorch. I’d love to combine my passion for AI with my software development skills to build smart products of the future.
Skills: Python, Java, C++, OOP, PyTorch. <br>
The main purpose of this page is to introduce you to number of projects I am very interested in and the project I have accomplished in the past. </div>
<div id="mySidenav" class="sidenav">
  <a href="jekyll/update/2020/01/22/welcome-to-jekyll.html" id="about">About</a>
  <a href="jekyll/update/2020/01/22/welcome-to-jekyll.html" id="blog">Blog</a>
  <a href="Projects" id="projects">Projects</a>
  <a href="Projects" id="contact">Contact</a>
</div>





