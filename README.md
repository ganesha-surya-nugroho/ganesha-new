<!doctype html>
<html>
<head>
 <title>Ganesha</title>
 <style>
  body {
    font: 16px/28px arial, sans-serif;
    background-color: lightgray;
 
 
 }
 
 .container {
     width: 960px;
     margin: auto;
     background-color: #fff;
 
 
 }
 
 .header{
     padding: 20px;
 
 }
 
 .header ul li{
     display: inline-block;
     margin-top: 20px;
     margin-right:10px;
     padding: 3px;
 
 }
 
 .header a{
     text-decoration: none;
     color: salmon;
 
 
 }
  
 .header a:hover {
     background-color: lightskyblue;
     color: white;
 }
 
 .hero{
     height: 330px;
     background-image: url(hero.png.jpg);
     background-size: cover;
     background-position: 0-180px;
     border-bottom:  5px solid lightskyblue;
     border-top:  5px solid salmon;
     width: 960px;
     margin: auto;
 }
 
  .content {
      width: 700px;
     padding: 30px
     box-sizing: border-box;
     float: left;
 
  }
 
  .main h2 {
     font-size: 32px;
     font-weight: bold;
     width: 700px;
  }
 
  .main .penulis{
     font-size: 11px
     margin-bottom: -5;
     background-color: #fff;
     width: 700px;
  }
 
  .main .penulis a{
      color: salmon;
      text-decoration: none;
      background-color: #fff;
      width: 700px;
  }
 
  .main p{
     margin-bottom: 20px;
     font-size: 25px;
     width: 700px;
 
  }
   .copyright {
      background-color: #333;
      
  }
 
   .copyright {
        color: #eaeaea;
        text-align-last: center;
   }
  
  /* clearfix */   
  .cf:before,
  .cf:after {
      content: " "; /* 1 */
      display: table; /* 2 */
  }
  
  .cf:after {
      clear: both;
  }
  
  
  .cf {
      *zoom: 1;
  }
  
  /*sidebar*/
   .sidebar{
       float: right;
       float: top;
  
  
  
   }
 </style>
</head>
<body>


    <div class="container">
       <div class="header">
        <h1 class="judul">Ganesha</h1>
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">products</a></li>
          <li><a href="#">services</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </div>
  </div>
  <div class="hero"></div>
  <div class="main cf">
      <h2>Judul Artikel</h2>
      <p class="penulis">ditulis oleh<a
      href="#">ganesha</a>. pada 27 september 2021. </p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
      proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  </p></div>
    
<div class="footer"></div>
<p class="copyright">copyright by ganesha 2021</p>


    </div>
    <div class="main"></div>
    

    <div class="sidebar">
      <h3>Tentang penulis</h3>
      <img src="ganes.png" alt="ganes">
    </div>

</body>
</html>
