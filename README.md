<!doctype html>
<html>
<head>
<title>types of selectors</title>
<style>
*{
margin:0;
padding:0;
}
div{
width:450px;
height:400px;
background-color:black;
margin:auto;
border:1px solid #C7D1D1;
}
ul li{
color:white;
list-style-type:none;
display:inline;
padding:21.8px;
line-height:45px;

}
ul li:hover{
background-color:#011094;
height:40px;
}

ul{
border:1px solid #C7D1D1;
background-color:blue;
width:450px;
height:53px;
}


.u2{
display:none;
position:absolute;
top:55px;
left:260px;
z-index:1;
background-color:red;
width:100px;
height:230px;
width:60px;
height:130px;
overflow:hidden;
}
.u2 li{
float:none;
padding:5px;
margin:0;
width:30px;
height:30px;
} 
u2 li a:hover{
display:block;
}

</style>
</head>
<body>
<div>


<ul>
<li>Home</li>

<li>Games</li>

<ul class="u2">
<li><a>1</a></li>
<li><a>1</a></li>
<li><a>1</a></li>
</ul>


<li>Scores</li>
<li>About</li>
<li>Contact</li>
</ul>


</div>
</body>
</html>
