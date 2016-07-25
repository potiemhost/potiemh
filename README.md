# potiemh
<!DOCTYPE html>
<html>
<head>
<style>
.button1 {
    position: relative;
    background-color:rgb(100,200,500);
    border: none;
    font-size: 28px;
    color: #FFFFFF;
    padding: 20px;
    width: 200px;
    text-align: center;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    text-decoration: none;
   overflow: hidden;
   vertical-align:middle;
    cursor: pointer;
    
    
}

.button1:after {
    content: "";
    background: #FFFFFF;
    display: block;
    position: absolute;
    padding-top: 300%;
    padding-left: 350%;
    margin-left: -20px!important;
    margin-top: -120%;
    opacity: 0;
    
    transition: all 0.8s
}

.button1:active:after {
    padding: 0;
    margin: 0;
    opacity: 1;
    transition: 0s
}
</style>
</head>

<head>
<style>
.button {
  border-radius: 4px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '»';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
body
{ font-family:Arial;
    }
</style>
</head>
<head>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #000033;
}

li {
    float: left;
}

li a, .dropbtn {
    display: inline-block;
    color:#ccccff;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
    background-color: #330000;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display:none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 200px;
    box-shadow: 10px 10px 16px 0px rgba(0,0,20,0.2);
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: grey}

.dropdown:hover .dropdown-content {
    display: block;
}
</style>
</head>
<body>

<ul>
  
  
  
  
    
  <li class="dropdown">
  
    <a href="#" class="dropbtn">
    <div class="container" onclick="myFunction(this)">
  <div class="bar1"></div>
  <div class="bar2"></div>
  <div class="bar3"></div>
</div></a>

<script>
function myFunction(x) {
    x.classList.toggle("change");
}
</script>
    <div class="dropdown-content">
      <a href="#">Books</a>
      <a href="">Characters</a>
      <a href="">Cast & Crew</a>
      <a href="#">Scenes</a>
    </div>
  </li>
<li><a class="active" href="#home">Game of Thrones</a></li>
</ul>
</head>
<head>
<style>
.container {
    display: inline-block;
    cursor: pointer;
}

.bar1, .bar2, .bar3 {
    width: 35px;
    height: 5px;
    background-color: #ddccff;
    margin: 6px 0;
    transition: 0.4s;
}

.change .bar1 {
    -webkit-transform: rotate(-45deg) translate(-9px, 6px) ;
    transform: rotate(-45deg) translate(-9px, 6px) ;
}

.change .bar2 {opacity: 0;}

.change .bar3 {
    -webkit-transform: rotate(45deg) translate(-8px, -8px) ;
    transform: rotate(45deg) translate(-8px, -8px) ;
}



body, html {
    height: 200%;
}

.parallax {
    /* The image used */
    background-image: url('http://mspoweruser.com/wp-content/uploads/2016/07/game-thrones-season-6.jpg');

    /* Full height */
    height: 30%;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}


</style>
</head>

<head>
  <link rel="stylesheet" href="http://mGoaxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
</head>

<body>


<div class="parallax"></div>

<div style="height:1000px;background-color:#000033;font-size:30px">






<div class="container">



<h1 style="color:#ffffcc" align="center" >Winter is Coming</h1>
<p align="center">
<button class="button" style=margin-lef:auto,mrgin-right:auto,display:block><span>Winterfell</span></button>
</p>
<p align="center">
<input type="image" src="http://img.cinemablend.com/cb/1/1/5/4/0/8/a1154086d8a1f5b453bbc9fd840e6910b22e82e9c9ffa848ec1d8d301799fe30c.jpg"  alt="Iron Throne" onclick="window.location.href='http://esquireuk.cdnds.net/16/08/980x735/cersei-lannister-game-of-thrones-43.jpg'" width=500px   class="img-responsive"> 
</p>
</div>
</div>

<div class="parallax"></div>

</body>
</html>
