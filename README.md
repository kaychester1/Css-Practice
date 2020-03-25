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
		<div id="displayinline">
						
						<div id="blue"></div>

		</div>
						<ul>
								<li>	<div id="purple1"></div> 	</li>
								<li>	<div id="red"></div> 	</li>
								<li>	<div id="pink"></div>	</li>
						</ul>

		
	<center>
		<div id="lastbox"></div>
	</center>
	

	</div>

		
	
</body>
</html>

css:
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
	top:75px;
	bottom: 70px;
	right: 150px;
}
#displayinline{
	display: inline-block;

}
#blue{
	width: 550px;
	height: 390px;
	background: blue;
	position: relative;
	top: 40px;
	
	
}
ul{

}
#purple1{
	height: 110px;
	width: 610px;
	display: inline-block;
	background: purple;
	 position: absolute;
	 top: 390px;
	 left: 700px;

}
li{ list-style-type: none; }

#red{
	height: 110px;
	width: 610px;
	position: absolute;
	 top: 530px;
	 left: 700px;
	 background: purple;

	

}
#pink{
	height: 110px;
	width: 610px;
	 position: absolute;
	 top: 670px;
	 left: 700px;
	background: purple;

}
#lastbox{
	height: 300px;
	width: 600px;
	margin: 0 auto;
margin-top: 70px;
	background:green;
}
