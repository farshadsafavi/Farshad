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
#mySidenav a {
  position: absolute;
  left: -80px;
  transition: 0.3s;
  padding: 15px;
  width: 100px;
  text-decoration: none;
  font-size: 20px;
  color: white;
  border-radius: 0 5px 5px 0;
}

#mySidenav a:hover {
  left: 0;
}

#about {
  top: 60px;
  background-color: #4CAF50;
}

#blog {
  top: 120px;
  background-color: #2196F3;
}

#projects {
  top: 180px;
  background-color: #f44336;
}

#contact {
  top: 240px;
  background-color: #555
}
</style>
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





