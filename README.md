<html>
<head>
<title> Website layout with image gallery</title>
</head>
<style>
*{
   box-sizing:border-box;
}
body
{
   margin:0;
   background:gray;
}
nav{
     background:#594848;
     width:100%;
     overflow:auto;
}
ul{
     margin:0;
     padding:0;
     list-style:none;
}
li{
     float:left;
}
nav a{
       width:120px;
       display:block;
       text-decoration:none;
       text-align:center;
       background:#594848;
       font-size:17px;
       color:white;
       padding:20px 10px;
       font-family:Arial;
}
nav a:hover{
      background:skyblue;
      color:black;
}
.container{
      max-width:1200px;
      margin:auto;
      background:#f2f2f2;
      overflow:auto;
}
.gallery{
     margin:5px;
     border:1px solid #ccc;
     float:left;
     width:390px;
}
.gallery img{
     width:100%;
     height:auto;
}
.desc{
    padding:15px;
    text-align:center;
}
footer{
   padding:10px;
   font-size:17px;
   font-weight:bold;
   text-align:center;
   background:#594848;
   color:white;
   font-family:Arial;
   letter-spacing:1px;
}
</style>
<body>
<nav>
     <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Downloads</a></li>
        <li><a href="#">Gallery</a></li>
        <li><a href="#">Contact</a></li>
     </ul>
</nav>
<div class="container">

    <div class="gallery">
    <img src="cat.jpg">
    <div class="desc">Cats are very friendly animals as they can be kept as domestic pets.</div>
    </div>

    <div class="gallery">
    <img src="bird.jpg">
    <div class="desc">Birds are one unique part of the nature bio-diversity.</div>
    </div>

    <div class="gallery">
    <img src="dog.jpg">
    <div class="desc">Dogs are known to be a human's best friend.</div>
    </div>

    <div class="gallery">
    <img src="fish.jpg">
    <div class="desc">Fishes are aquatic creatures that are non-harmful and swim peacefully.</div>
    </div>

    <div class="gallery">
    <img src="fox.jpg">
    <div class="desc">Foxes are wild predators,which are known to be smart and cunning.</div>
    </div>

    <div class="gallery">
    <img src="owl.jpg">
    <div class="desc">Owls are night creatures that stay active only in the dark.</div>
    </div>
</div>
<footer>
All Rights are reserved in Web Master
</footer>
</body>
</html>
