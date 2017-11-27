<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>

<body>
<nav class = "navbar navbar-default">
<div class = "container-fluid">
<div class = "navbar-header">
<button type = "button" class = "navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
<span class = "icon-bar"></span>
<span class = "icon-bar"></span>
<span class = "icon-bar"></span>

</button>
<a class = "navbar-brand" href="#"> Palomar Valero</a>
</div> <!-- this ends the div for nav -->

<div class = "collapse navbar-collapse" id="myNavbar">
 <ul class="nav navbar-nav">
      <li><a href="index.html">Home</a></li>
      <li class = "active"><a href="car_wash.html">Car Wash</a></li>
      <li><a href="deli.html">Deli</a></li>
      <li><a href="propane.html">Propane</a></li>
	  
    </ul>
	<ul class="nav navbar-nav navbar-right">
</ul>
	  <button class = "btn btn-danger navbar-btn"> Deals</button> <!-- Creates a button -->

  </div>
 </div>
</nav>


<div class ="jumbotron">
<h1 class ="text-center"> Palomar Valero </h1>
<p> some text </p>
</div>

<div class = "container">
<p> This text is outside the jumbotron </p>
</div> <!-- This ends the container div -->
</html>
