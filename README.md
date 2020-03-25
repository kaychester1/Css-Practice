# Css Practice
 Practice S5
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="BMP.css">
	<title>Box Model Practice </title>
</head>
<body>	

	<div id="wrapper">
		<div id="orange"></div>
		<div id="black"></div>
		
			<div id="blue"></div>
				<ul>
					<li>	<div id="purple1"></div> 	</li>
					<li>	<div id="purple2"></div> 	</li>
					<li>	<div id="purple3"></div>	</li>
			</ul>
	<center>
		<div id="lastbox"></div>
	</center>
	

	</div>	
</body>
</html>

#wrapper{
	width: 1200px;
	margin: 50px auto;
}
#orange{
	height: 300px;
	width: 1200px;
	background: orange;
position: relative;
}
#black{
	height: 250px;
	width: 400px;
	background: black;
	position: absolute;
	right: 20px;
	top:20px;
		margin: 50px auto;
	

	right: 20px;
	top:20px;
}
#blue{
	height: 550px;
	width: 390px;
	display: inline-block;
	margin: auto;
	background: blue;
}
#purple1, #purple2, #purple3{
	height: 150px;
	width: 590px;
	display: inline-block;
	background: purple;

}


#lastbox{
	height: 400px;
	width: 600px;
	margin: 0 auto;
	background:green;
}
