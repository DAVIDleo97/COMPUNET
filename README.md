<!DOCTYPE html>
<html>
<head>
</head>

<body>
	<h1>Sentencias</h1>

	<p id="resultado1"></p>
	<p id="mensaje"></p>

</body>

<script>

//SENTENCIAS

var u = 8 - 4;
var p = 3 * u;
document.getElementById("resultado1").innerHTML = p;

//SENTENCIAS AGURPADAS EN BLOQUE

function mifuncion(argument){

	var hola = "I love js.";
	document.getElementById("mensaje").innerHTML = hola;

}

mifuncion();

</script>
</html>
