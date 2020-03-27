<!DOCTYPE html>
<html>
<meta charset="utf-8">
<link rel="stylesheet" type="text/css" href="S5.css">
<head>
<title>S5 Css Practice</title>
</head>
<body>
<div id="container">
<div id="orangebox"></div>
<div id="yellowbox"></div>
<div id="wrapper">			
<align><div id="bluebox"></div>	
<ul>				
<li><div id="purplebox1"></div></li>
<li><div id="purplebox2"></div></li>
<li><div id="purplebox3"></div></li>
</ul>	
</align>
</div>
<center> <div id="greenbox"></div> </center>
</div>
</body>
</html>


css:

#container{
width: 1200px;
margin: 0px auto;}

#orangebox{
width: 1200px;
height:300px;
background: orange;
position: relative;}

#yellowbox{
width: 450px;
height: 230px;
background: yellow;
position: absolute;
right:20px;
top:15px;
margin-right: 260px;
margin-top: 30px;

}
#wrapper{width: 1200px;}

#bluebox{
width:550px;
height: 550px;
background: blue;
margin-top: 50px;
margin-right: 15px;
display: inline-block;}

li{width: 500px;
height: 500px;
position: absolute;
top: 309px;
right:29px;
margin-right: 300px;
list-style-type: none;}

ul{display: inline-block;}

#purplebox1{
width:590px;
height: 150px;
margin-top: 50px;
background: purple;
display: inline-block;
}


#purplebox2{
width: 590px;
height: 150px;
position: absolute;
top: 200px;
margin-top: 50px;
background: purple;
display: inline-block;
}

#purplebox3{
width: 590px;
height: 150px;
position: absolute;
top: 400px;
margin-top: 50px;
background: purple;
display: inline-block;
}

#greenbox{
width: 600px;
height: 400px;
margin-top: 50px;
position: relative;
background: green;
}
