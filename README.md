<!doctype html>
<!DOCTYPE html>
<html>
<head> <meta charset="utf 8">
	<title>Photo Gallery</title>
	<style>
h1 {
color: white;
background-color: red;
border: 5px solid green;
padding: 10px;
text-align: center;
text-shadow: 2px 2px blue;
font-family: Arial, helvetica, sans-serif;
}
a:hover{
	color: hotpink;
}

 * {
  box-sizing: border-box;
}

.img-container {
  float: left;
  width: 33.33%;
  height: 30%
  padding: 5px;
}

ul{
	list-style-type: none;
	overflow: hidden;
	background-color: white;
}
li{
	float: left;
}
li a{
	display: inline-block;
	color: white;
	text-align: center;
	padding: 14px 16px;
}
li a:hover{
	background-color: green;
}
.active{
	background-color: red;
}
p{
	color: orange;
}

	
	</style>


</head>
<body style="background: black">
	<h1>WELCOME TO MY PHOTO GALLERY</h1>
	<p><a href="https://www.facebook.com/simi.das.5477" target="_blank" color="white">Click on it for visiting my facebook page</a></p>
<ul>
  	<li><a href="file:///E:/sublime%20editor/website/website.html" class="active">Home</a></li>
  	<li><a href="https://passiontowrite25.blogspot.com/" target="_blank">My Blog</a></li>
  	<li><a href="file:///E:/sublime%20editor/rough%20practice/multimedia.html" target="_blank">Contact</a></li>
  	<li><a href="file:///E:/sublime%20editor/rough%20practice/simi.html" target="_blank">About me!</a></li>
  </ul>

  <div class="img-container">
  <p>This picture is taken inside my college campus.</p>
  <a href="https://www.facebook.com/simi.das.5477" target="_blank">
  <img src="D:/SIMI/mypic.jpg" alt="Italy" style="width:50%" class="img-container"></a>
 </div>
  <div class="img-container">
  	<p>This picture is taken on induction function of RCMSIT.</p>
  	<a href="https://www.linkedin.com/in/simi-das-19241452/">
  <img src="D:/SIMI/Casual pics/2019-01-20-14-20-07-735.jpg" alt="Forest" style="width:68%" class="img-container"></a>
  </div>
  <div class="img-container">
  	<p>This picture is taken during the installation ceremony of RCGK.</p>
  	<a href="https://www.instagram.com/?hl=en">
  <img src="D:/SIMI/Installation/PicsArt_09-14-05.59.49.jpg" alt="Mountains" style="width:45%" class="img-container"></a>
  </div>
<div class="img-container">
	<p>This picture is taken in Ecopark.</p>
	<a href="https://passiontowrite25.blogspot.com/" target="_blank">
  <img src="D:/SIMI/Eco Park/2019-01-30-15-44-18-168.jpg" alt="Mountains" style="width:45%" class="img-container"></a>
  </div>

	
	

</body>
</html>
