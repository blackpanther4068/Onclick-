# Onclick-
<!DOCTYPE html>
<html>
<head>
<title>click on different objects</title>
<h1 style="text-align:center">clicks info</h1>
</head>
<body>
<p style="text-align:center"><small>click on object to know about that particular object</small></p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTateX8N8bbNFuovOOwP8iq2fev4ubba_29Mg&usqp=CAU" usemap=#workmap width=340px height=340px>
<map name="workmap">
<area shape="rect"
coords="0,10,220,310"
onclick="f1()">
<area shape="rect"
coords="220,65,285,220"
onclick="f2()">
<area shape="rect"
coords="290,65,330,195"
onclick="f3()">
<area shape="circle"
coords="295,278,50"
onclick="f4()">
</map>
<script>
function f1(){alert("you clicked on laptop");}
function f2(){alert("you clicked on tablet");}
function f3(){alert("you clicked on phone");}
function f4(){alert("you clicked on cup");} 
</script>
</body>
</html>
