<!DOCTYPE html>
<html lang="en">
<head>

  <title>Bootstrap Theme Simply Me</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1"> 
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"> <!-- link naar de css site -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">  <!--voor de icoontjes onderaan de site--> 
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet"> 
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script> <!--javascript file-->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script> <!--bootstrap.js file-->
  
  <style>
  .navbar {
    margin-bottom: 0; 
	border-radius: 0;
	background-color: #5E4485; <!--de paarse bar bovenaan de site-->
	color: #FFF; <!--wit-->
	padding: 1% 0;
	fot-size: 1.2em:
	border: 0;
  }
  .navbar-brand {
    float: left;
	min-height: 55px;
	padding: 0 15px 5px;
  }
  .navbar-inverse .navbar-nav .active a, .navbar-inverse .navbar-nav .active a:focus,
  .navbar-inverse .navbar-nav .active a:hover, {
    color: #FFF;
	background-color: #5E4485;
	
  }
  
  </style> 
</head>
<body>
	<nav class="navbar navbar-inverse">
		<div class="container-fluid">
			<div class="navbar-header">
				<button type="button" class="navbar-toggle" data-toggle="collapse" 
				data-target="#myNavbar">
                    <span class="icon-bar"></span> 
				</button> <!--button voor de mobiele weergave-->
				<a class="navbar-brand" href="#">ME</a>
			</div>			 
			<div class="collapse navbar-collapse" id="myNavbar">
			    <ul class="nav navbar-nav navbar right">
				    <li class="active"><a href="#">Home</a></li> <!--deze buttons hebben geen class active
					en zijn dus nog niet gemarkeerd als actief of ingedrukt-->
					<li><a href="#">About</a></li>
					<li><a href="#">Services</a></li>
					<li><a href="#">Testemonials</a></li>
					<li><a href="#">Contact</a></li>
					
				</ul>			
			</div>
		</div>
	</nav>
	

</body>
</html>
